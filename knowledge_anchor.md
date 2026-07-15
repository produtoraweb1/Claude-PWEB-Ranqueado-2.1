# ⚓ DIRETRIZES DE ATRIBUIÇÃO DE INPUTS

Este documento define rigidamente qual agente processa qual arquivo, para evitar sobreposição de escopo entre os 13 agentes. Em caso de dúvida de atribuição, o `[PipelineDirector]` decide.

### 1. RELATÓRIOS EXPORTADOS (.csv, .xlsx, .json)

- Semrush / Ahrefs / Keyword Gap → Atribuição Exclusiva: `[DataStrategist]`
- Google Search Console (CTR/Impressões) → Atribuição Exclusiva: `[DataStrategist]`
- Google Analytics 4 (Caminho do Usuário) → Atribuição Conjunta: `[DataStrategist]` + `[UXArchitect]`
- Google Analytics 4 (Tendência histórica de páginas / quedas de tráfego) → Atribuição Conjunta: `[DataStrategist]` + `[ContentOps]` *(NOVO)*
- Perfil de Backlinks / Relatório de Disavow (Ahrefs, Semrush Backlink Audit) → Atribuição Exclusiva: `[LinkArchitect]` *(NOVO)*
- Exportação de citações locais / listas de diretórios (NAP) → Atribuição Exclusiva: `[LocalGEO]` *(NOVO)*
- Relatório do Google Business Profile (insights, avaliações) → Atribuição Exclusiva: `[LocalGEO]` *(NOVO)*
- YouTube Studio Analytics → Atribuição Exclusiva: `[VideoGEO]` *(NOVO)*

### 2. CÓDIGOS E ENGENHARIA (.html, .js, .txt)

- robots.txt / sitemap.xml / PageSpeed Insights → Atribuição Exclusiva: `[TechSEO]`
- Marcações JSON-LD / Tags Schema (Article, Product, Organization) → Atribuição Exclusiva: `[TechSEO]`
- Schema LocalBusiness / geolocalização → Atribuição Exclusiva: `[LocalGEO]` *(NOVO)*
- Schema VideoObject / ImageObject → Atribuição Exclusiva: `[VideoGEO]` *(NOVO)*

### 3. MAPAS VISUAIS E TEXTOS (.txt, .md, Links)

- Textos de Blogs / Copywriting Atual → Atribuição Conjunta: `[GeoContent]` (Métricas) + `[HumanEditor]` (Estilo)
- Wireframes / Prints de Telas / Descrição de Layout → Atribuição Exclusiva: `[UXArchitect]`
- Transcrições e roteiros de vídeo → Atribuição Exclusiva: `[VideoGEO]` *(NOVO)*
- Prints/capturas de respostas do ChatGPT, Perplexity, Gemini ou AI Overviews mencionando (ou não) a marca → Atribuição Exclusiva: `[AIVisibility]` *(NOVO)*
- Listas de páginas antigas candidatas a atualização/remoção → Atribuição Exclusiva: `[ContentOps]` *(NOVO)*

### 4. RESOLUÇÃO DE CONFLITOS

- Se um arquivo parecer se encaixar em mais de um agente e a tabela acima não cobrir o caso, o `[PipelineDirector]` decide a atribuição antes de qualquer agente processar o dado, e registra a decisão no início da resposta.

### 5. MÓDULOS CONDICIONAIS (NOVO)

- Arquivos ligados a `[LocalGEO]`, `[VideoGEO]` ou `[ContentOps]` só são processados pelo respectivo agente se o módulo foi ativado na Fase 0 de triagem.
- Se um arquivo desse tipo for enviado antes da triagem (ou com o módulo inativo), o `[PipelineDirector]` armazena a referência e informa que ele será usado somente se o módulo correspondente for ativado — não descarta o arquivo, apenas adia o processamento.
