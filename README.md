# Pesquisa Cognitiva do Azure
As pesquisas tradicionais são baseadas em sintaxe, como quantas aparições uma palavra tem em um documento, mas agora com todas as novas capacidades de pesquisa semântica você pode obter o resultado mais relevante baseado na intenção, não apenas palavras-chave, além de achar até mesmo respostas específicas, ajudando a entregar o melhor resultado possível. <br>
O Azure Cognitive Search é a plataforma de mineração de conhecimento por IA do Azure, ele permite localizar informações específicas de forma eficiente em grandes volumes de informação, pois estratura os trados para consultas ágeis.

## Mineração de Conhecimento
As empresas póssuem muitos dados e estes dados são muitas vezes guardados como documentos, pdfs, notas manuscritas, etc. <br>
A mineração encontra insights nesses dados, o que ajuda a recuperar a informação de forma mais rápida.
### Ingestão de dados
Importação de dados para um sistema com o objetivo de torná-los disponíveis para processamento, análise ou amazenamento.
- Azure Blob Storage Containers: armazena grandes quantidades de dados não estruturados (documentos, imagens, vídeos...), ideal para ingestão de grandes arquivos;
- Azure Data Lake Storage Gen2: combina recursos de Azure Blob Storage com um sistema de arquivos hierárquico, é otimizado para big data analytics, sendo altamente escalável;
- Azure Table Storage: BD NoSQL baseado em chave/atributo, ideal para armazenar dados estruturados com grandes volumes e necessidade de acesso rápido.

### Enriquecimento e índice de IA
Aplicação da IA aos dados para torná-los mais úteis e pesquisáveis.
- Permite uma compreensão profunda: A IA identifica padrão, significados e contextos nos dados, facilitando insights avançados;
- Indexação: cria índices com base nos dados enriquecidos, permitindo buscas enficientes, inclusive com linguagem natural.

### Explorar
Utilização dos dados enriquecidos e indexados para gerar valor real.
- Pesquisa realizada em índice: busca por palavras ou expressões, trazendo resultados baseados nos dados processados e enriquecidos;
- Dentro de aplicativos: a pesquisa pode ser embutida em aplicações web, móveis ou sistemas internos, fornecendo experiências ricas aos usuários finais;
- Crie visualizações de dados: os dados podem ser usados em dashboards, gráficos e relatórios interativos.

## Enriquecimento de IA
Processo que torna o conteúdo mais útil para fins de pesquisa. O conteúdo enriquecido é criado por conjuntos de habilidades como:
- Reconhecer entidades no texto;
- Traduzir o texto;
- Avaliar o sentimento.
