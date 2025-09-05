
# FUNCIONALIDADES

## Remover Linhas Superiores

- **Função**: Remove as primeiras linhas de uma tabela.
- **Parâmetros**: Requer o número de linhas a serem removidas.
- **Contexto**: Útil para eliminar cabeçalhos ou linhas de metadados que não fazem parte dos dados principais.

## Usar a Primeira Linha como Cabeçalho

- **Função**: Promove a primeira linha da tabela para se tornar o cabeçalho das colunas.
- **Parâmetros**: Não requer parâmetros adicionais.
- **Contexto**: Essencial quando a primeira linha contém os nomes das colunas, facilitando a identificação e manipulação dos dados.

## Extrair Texto Após o Delimitador

- **Função**: Extrai a parte do texto que está após um delimitador específico em uma coluna de texto.
- **Parâmetros**: Requer o caractere ou string que será utilizado como delimitador.
- **Contexto**: Útil para remover prefixos, sufixos ou separar informações em colunas que utilizam um padrão de delimitadores.

## Conversão para Tabela

**Técnica**: Utilização da função Table.FromValue ou Json.Document para converter os registros JSON em uma estrutura tabular.
**Detalhes**: O Power Query reconhece automaticamente a estrutura JSON e oferece a opção "Na Tabela" na guia "Converter". Essa função interpreta cada linha do JSON como um registro e transforma esses registros em linhas de uma tabela, onde cada campo do registro se torna uma coluna.

## Expansão das Informações

**Técnica**: Aplicação da função Table.ExpandColumn para desdobrar os registros da coluna "Value" em novas colunas.
**Detalhes**: Ao clicar no botão de expansão na coluna "Value", o Power Query gera automaticamente o código M para expandir os registros. Cada campo dentro dos registros é transformado em uma coluna separada. Inicialmente, os dados podem aparecer transpostos, com as informações dispostas horizontalmente em vez de verticalmente.

## Transposição da Tabela

**Técnica**: Uso da função Table.Transpose para inverter as linhas e colunas da tabela.
**Detalhes**: A transposição é essencial para corrigir a orientação dos dados, transformando as linhas em colunas e vice-versa. Isso é feito selecionando todas as colunas (Ctrl+Shift+A) e aplicando a função "Transpor" na guia "Transformar".

## Promoção do Cabeçalho

**Técnica**: Utilização da função Table.PromoteHeaders para elevar a primeira linha da tabela e usá-la como cabeçalho.
**Detalhes**: Após a transposição, a primeira linha contém os nomes das colunas. A função "Usar a Primeira Linha como Cabeçalho" eleva essa linha para o cabeçalho da tabela, facilitando a identificação e manipulação das colunas.

## Formatação da Coluna

**Técnica**: Aplicação das funções Table.ReplaceValue e Text.Proper para formatar a coluna "product_category_name".
**Detalhes**:

- *Substituição de Underlines*: A função Table.ReplaceValue substitui todos os underlines ("_") por espaços em branco. Isso é feito especificando o valor a ser localizado ("_") e o valor de substituição (" ").
- *Capitalização das Palavras*: A função Text.Proper é usada para colocar a primeira letra de cada palavra em maiúscula. Isso melhora a legibilidade e a apresentação dos dados.

