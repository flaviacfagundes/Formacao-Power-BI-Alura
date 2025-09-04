
# O QUE É?

Segundo a Microsoft, o PowerBI é um **conjunto de soluções de serviços de softwares e aplicativos** que trabalham juntos para **transformar fontes de dados não relacionadas** em insights coerentes, que sejam visualmente imersivos e também interativos.

B.I. é uma sigla para o termo "Business Intelligence", do inglês. Podemos traduzi-lo como "Inteligência de Negócios".

# FLUXO DE TRABALHO

O processo de funcionamento do Power BI segue em **obter**, **transformar**, e por fim o **carregar** os dados para a base que será utilizada para construir os relatórios e dashboards.

- **Fontes de Dados**: são os locais de onde é possível extrair os dados que serão utilizados na construção dos relatórios e dashboards.

Após a obtenção dos dados, devido a uma **alta disponibilidade de padrões** e **formatos diferentes** para cada conjunto de dados, é necessário fazer o pré-processamento e transformá-los antes de poder manipulá-los diretamente.

- **Transformação e Carregamento**: essa é a fase de pré-processamento ou transformação dos dados antes do carregamento para a base utilizada nos relatórios e dashboards.

# IMPORTAÇÃO DE DADOS

O primeiro passo para a construção de um dashboard no Power BI é a importação de dados de diferentes fontes. O Power BI suporta uma ampla variedade de formatos de arquivos, como CSV, Excel, TXT, além de conexões com bancos de dados e serviços na nuvem.

Durante o processo de importação, o Power BI oferece uma **pré-visualização dos dados** e permite a configuração de opções como o **decodificador de caracteres** e o **delimitador de colunas**.

# TRANSFORMAÇÃO DE DADOS COM POWER QUERY

Após a importação dos dados, é comum que seja necessário realizar transformações para adequá-los às necessidades da análise. O Power BI oferece o **Power Query**, um editor de **consultas** que permite a **limpeza**, **transformação** e **modelagem** dos dados de forma visual e intuitiva.

# CONSTRUÇÃO DE CARTÕES

Uma vez que os dados foram importados e transformados, é possível criar visualizações para responder a perguntas de negócios e gerar *insights*. O Power BI oferece uma variedade de visuais, como gráficos de barras, gráficos de pizza, tabelas e cartões.

# RECURSO DE QUALIDADE DA COLUNA

O recurso de Qualidade da Coluna no Power BI rotula os valores em linhas em cinco categorias, fornecendo informações sobre a qualidade dos dados em cada coluna:

- **Válido (verde)**: indica que os valores na coluna estão corretos e dentro dos critérios definidos.
- **Erro (vermelho)**: sinaliza a presença de erros na coluna, indicando que os valores não estão de acordo com as regras ou critérios estabelecidos.
- **Vazio (cinza escuro)**: representa valores ausentes ou nulos na coluna, indicando que não há dados presentes.
- **Desconhecido (verde pontilhado)**: indica a presença de erros em uma coluna, resultando em uma qualidade de dados desconhecida para os demais valores.
- **Erro inesperado (vermelho pontilhado)**: identifica a ocorrência de erros inesperados na coluna, que não se enquadram nas categorias anteriores.

# MEDIDAS

No Power BI, medidas são elementos essenciais para realizar cálculos e análises sobre os dados. Elas podem ser classificadas em medidas implícitas e medidas explícitas.

- **Medidas implícitas** são calculadas automaticamente pelo Power BI com base nos dados presentes na tabela. Elas são úteis para realizar operações básicas, como soma, média, contagem, mínimo e máximo. O Power BI identifica automaticamente os campos numéricos na tabela e cria medidas implícitas correspondentes. Essas medidas são atualizadas dinamicamente à medida que os dados são modificados ou filtrados.

- **Medidas explícitas** são cálculos personalizados criados manualmente pelo usuário. Elas são criadas utilizando a linguagem de fórmulas **DAX** (*Data Analysis Expressions*) e permitem realizar cálculos mais complexos e específicos às necessidades do usuário. Com as medidas explícitas, é possível realizar operações matemáticas avançadas, combinar campos de diferentes tabelas, aplicar filtros condicionais e criar métricas personalizadas.

# REFERENCIA A HIERARQUIA

- **Seta apontada para cima (drill up)**: este botão aumenta um nível na hierarquia, mas para cima. 
- **Seta apontada para baixo (drill down)**: esse botão serve para detalhar os campos. 
- **Seta dupla apontada para baixo (próximo nível da hierarquia)**: essa opção faz o caminho inverso do Drill up, ou seja, quando clicamos nela os dados são filtrados pela hierarquia que vem abaixo.
- **Seta dupla em formato de garfo (expandir todo o campo um nível na hierarquia)**: essa opção só funciona quando estamos na hierarquia do topo. Como a seta dupla apontada para baixo, a seta dupla em formato de garfo também aciona as hierarquias abaixo da selecionada. Mas, ao invés de descer um nível todo, ela expande o nível com o próximo abaixo, de modo a incluir a filtragem do nível atual e a filtragem do nível abaixo.

