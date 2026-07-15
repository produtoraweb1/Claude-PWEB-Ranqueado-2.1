# 🔄 TEMPLATES DE COMANDOS — PWEB RANQUEADO v2.1

Cole estes comandos no chat do seu Claude Project.

---

## Disparar o pipeline completo (5 fases)

```
[PipelineDirector], inicie o pipeline completo para o site [URL/marca].
Objetivo do projeto: [ex: aumentar tráfego orgânico e citações em IA para o nicho X].
Arquivos anexados: [liste os arquivos, se houver].
Comece pela FASE 0 de triagem antes de qualquer outra coisa.
```

---

## Fase 0 — Triagem (sempre primeiro)

```
[PipelineDirector], faça a triagem inicial: pergunte o tipo de negócio,
se já existe conteúdo publicado e se vídeo faz parte da estratégia.
Com base nas respostas, defina quais módulos condicionais (LocalGEO,
VideoGEO, ContentOps) entram no projeto e resuma o plano de fases.
```

---

## Disparar apenas uma fase

```
[PipelineDirector], ative apenas a FASE [1/2/3/4] para o projeto [nome],
considerando os módulos já definidos na triagem: [liste os ativos].
Contexto relevante: [resumo ou arquivos anexados].
```

---

## Comandos para agentes específicos

**[AIVisibility] — Auditoria de citação em IA**
```
[AIVisibility], simule as 10 perguntas mais prováveis que um usuário faria
ao ChatGPT, Perplexity e Google AI Overviews sobre [tópico/nicho].
Avalie se a marca [nome] apareceria como citação e por quê. Recomende
ajustes de formato para aumentar a citabilidade.
```

**[LocalGEO] — Diagnóstico de SEO local** *(só se o módulo estiver ativo)*
```
[LocalGEO], audite a presença local de [nome do negócio] em Google
Business Profile, Apple Maps e Bing Places. Verifique consistência de
NAP e sugira o schema LocalBusiness ideal.
```

**[LinkArchitect] + [OffPagePR] — Autoridade externa consolidada**
```
[LinkArchitect] e [OffPagePR], analisem o perfil de backlinks/menções
anexado e entreguem UMA lista consolidada de oportunidades, marcando
cada item com 💬 (menção) e/ou 🔗 (link), sem duplicar itens entre vocês.
```

**[VideoGEO] — Otimização de vídeo/multimodal** *(só se o módulo estiver ativo)*
```
[VideoGEO], otimize o roteiro/transcrição anexado para SEO no YouTube e
para leitura por IAs multimodais. Sugira título, descrição, capítulos e
schema VideoObject.
```

**[ContentOps] — Auditoria de conteúdo existente** *(só se o módulo estiver ativo)*
```
[ContentOps], analise a lista de URLs/tráfego anexada e classifique cada
página em: manter, atualizar, consolidar (redirect 301) ou remover.
Aponte casos de canibalização de palavras-chave.
```

**[TechSEO] — Auditoria técnica pura**
```
[TechSEO], faça uma auditoria técnica independente de [site/URL]: rastreabilidade para
bots de IA, indexação, Server-Side Rendering, Core Web Vitals e dados estruturados
(JSON-LD) existentes.
Entregue uma lista priorizada de correções, separando "bloqueadores" (impedem
indexação/rastreamento) de "otimizações" (melhoram performance sem bloquear nada).
```

**[UXArchitect] — Teardown de UX/CRO de uma página**
```
[UXArchitect], faça um teardown de UX/CRO da página [URL/print anexado]: hierarquia
visual, escaneabilidade, posicionamento de CTA, responsividade mobile e Core Web
Vitals (INP).
Aponte os 3 maiores pontos de atrito que provavelmente reduzem a conversão, com a
correção sugerida para cada um.
```

**[GeoContent] — Reestruturação Answer-First**
```
[GeoContent], reestruture o texto anexado (ou colado abaixo) no formato Answer-First
Architecture: resposta direta no primeiro parágrafo, seguida de aprofundamento,
maximizando densidade semântica (LSI) sem perder naturalidade.
Não reescreva o estilo — isso é trabalho do [HumanEditor]; foque só na arquitetura.

[texto ou URL aqui]
```

**[HumanEditor] — Humanizar texto gerado por IA**
```
[HumanEditor], revise o texto abaixo e elimine clichês estruturais de IA (frases de
efeito genéricas, transições robóticas, listas onde não cabem), ajustando o ritmo de
leitura e inserindo ao menos uma analogia ou gancho humano.
Mantenha a estrutura de tópicos definida pelo [GeoContent] intacta.

[texto aqui]
```

**[DataStrategist] — Leitura rápida de dados / quick wins**
```
[DataStrategist], leia o export anexado (Search Console, Semrush ou GA4) e extraia
apenas "Quick Wins": páginas próximas do top 3 que precisam de pouco esforço para
subir, e páginas com alto CTR potencial perdido.
Entregue uma lista de até 10 itens, ordenada por impacto estimado.
```

---

## Auditoria final com loop de refinamento

```
[MatrixAuditor], audite a entrega mais recente aplicando a rubrica 0-10
(naturalidade, citabilidade em IA, usabilidade, e os critérios de módulos
ativos). Para qualquer critério abaixo de 8, devolva ao agente responsável
com o motivo específico antes de aprovar a entrega final.
```
