
# POWER QUERY

## Aba "Consultas"

- **Função**: Lista todas as fontes de dados (consultas) que foram conectadas ao Power Query.
- **Detalhes Técnicos**: Cada consulta representa uma conexão a uma fonte de dados externa (Excel, CSV, banco de dados, etc.). Ao selecionar uma consulta, você visualiza os dados extraídos dessa fonte na área central do editor.
- **Uso**: Permite navegar entre diferentes fontes de dados e gerenciar as conexões.

## Área Central (Exposição dos Dados)

- **Função**: Exibe os dados da consulta selecionada em formato de tabela.
- **Detalhes Técnicos**: Apresenta os dados em linhas e colunas, permitindo visualizar os valores, tipos de dados e estrutura da tabela.
- **Uso**: Permite inspecionar os dados, identificar problemas (erros, valores ausentes) e planejar as transformações necessárias.

## Aba "Config. Consulta"

- **Função**: Exibe as etapas de transformação aplicadas à consulta selecionada.
- **Detalhes Técnicos**: Cada etapa representa uma operação realizada nos dados (filtragem, ordenação, transformação de colunas, etc.). As etapas são aplicadas sequencialmente, e você pode modificar, remover ou adicionar novas etapas.
- **Uso**: Permite rastrear e controlar o processo de transformação dos dados, garantindo a reprodutibilidade e a correção das operações.

## Guia "Página Inicial"

- **Função**: Oferece as ferramentas básicas para conectar a fontes de dados, inserir dados manualmente e gerenciar as configurações de conexão.

`Nova Fonte`: Inicia o processo de conexão a uma nova fonte de dados.
**Detalhes Técnicos**: Abre uma janela com uma lista de tipos de fontes de dados suportados (Excel, CSV, SQL Server, etc.). Ao selecionar um tipo, o Power Query solicita as informações necessárias para estabelecer a conexão (caminho do arquivo, credenciais de acesso, etc.).

`Inserir Dados`: Permite criar uma tabela manualmente, inserindo os dados diretamente no Power Query.
**Detalhes Técnicos**: Abre uma janela com uma grade onde você pode digitar os valores das células. É útil para criar tabelas de lookup ou dados de teste.

`Configurações da fonte de dados`: Permite gerenciar as configurações de conexão das fontes de dados existentes.
**Detalhes Técnicos**: Abre uma janela com informações sobre o tipo de fonte de dados, o caminho do arquivo ou servidor, as credenciais de acesso, etc. Permite modificar essas configurações ou alterar as credenciais.

`Atualizar Visualização`: Atualiza os dados exibidos na área central com as informações mais recentes da fonte de dados.
**Detalhes Técnicos**: Executa novamente a consulta na fonte de dados e atualiza a tabela com os novos valores. É útil quando a fonte de dados é atualizada com frequência.

## Guia "Transformar" e "Adicionar Coluna"

- **Função**: Oferecem uma variedade de ferramentas para transformar e enriquecer os dados.
- **Detalhes Técnicos**: Incluem opções para: 

    - *Transformar colunas existentes*: alterar o tipo de dados, renomear, remover, substituir valores, dividir colunas, etc.
    - *Adicionar novas colunas*: Criar colunas calculadas com base em fórmulas, extrair informações de outras colunas, adicionar colunas condicionais, etc.

## Guia "Exibição"

- **Função**: Permite personalizar a visualização dos dados e ativar ferramentas de análise.

`Barra de Fórmulas`: Exibe a fórmula em linguagem M da etapa selecionada na aba "Config. Consulta".
**Detalhes Técnicos**: A linguagem M é a linguagem de programação usada pelo Power Query para expressar as transformações de dados. A barra de fórmulas permite visualizar e editar o código M das etapas.

`Qualidade da coluna`: Exibe informações sobre a qualidade dos dados em cada coluna (válidos, erros, vazios).
**Detalhes Técnicos**: Calcula a porcentagem de valores válidos, erros e vazios em cada coluna. Permite identificar colunas com problemas de qualidade de dados.

`Distribuição de colunas`: Exibe informações sobre a distribuição dos valores em cada coluna (distintos, exclusivos).

---
