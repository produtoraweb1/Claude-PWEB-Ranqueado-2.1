# 🎯 PROMPTS AVANÇADOS — PWEB RANQUEADO v2.1 (Uso Profissional)

8 templates para entregáveis específicos de agência — complementam o pipeline padrão de `prompts_fases_agentes.md`. Cole no chat do projeto já configurado (com `system_instructions.md`, `agentes_detalhados.md` e `knowledge_anchor.md` instalados).

---

## 1. 🚨 Diagnóstico de Queda de Tráfego (Crise)
**Quando usar:** queda repentina de tráfego/rankings — possível update de algoritmo, ação manual, problema técnico ou decaimento de conteúdo.
**Agentes:** DataStrategist + TechSEO + ContentOps + GeoContent

```
[PipelineDirector], ative um DIAGNÓSTICO DE CRISE para [site/URL].
Contexto: queda de [X]% em [tráfego/rankings] observada a partir de [data].
[DataStrategist], correlacione a data com updates de algoritmo conhecidos do período.
[TechSEO], descarte causas técnicas (indexação, robots.txt, Core Web Vitals, migração recente).
[ContentOps], verifique decaimento/canibalização nas páginas mais afetadas.
[GeoContent], avalie se o conteúdo perdeu alinhamento com a intenção de busca atual.
Entreguem um diagnóstico único, hierarquizado por probabilidade (mais provável → menos
provável), com plano de ação para as 3 causas mais prováveis.
```

---

## 2. 🔧 Auditoria de Migração de Site
**Quando usar:** antes/depois de troca de domínio, replatform, redesign ou migração HTTP→HTTPS.
**Agentes:** TechSEO + LinkArchitect + DataStrategist + MatrixAuditor

```
[TechSEO], audite o plano de migração de [site antigo] para [site novo/nova estrutura].
Liste riscos de redirecionamento (301), perda de link equity, quebra de schema e
indexação duplicada.
[LinkArchitect], mapeie os backlinks mais valiosos que precisam de redirecionamento
prioritário.
[DataStrategist], defina as métricas de baseline a monitorar nas 4 semanas pós-migração.
[MatrixAuditor], gere um checklist de go/no-go antes do lançamento.
```

---

## 3. ✍️ Brief de Conteúdo Pronto para Redator
**Quando usar:** produção de conteúdo em escala, terceirizando a escrita.
**Agentes:** DataStrategist + GeoContent + AIVisibility

```
[DataStrategist], identifique as lacunas de palavra-chave para o tópico [tema] frente
aos concorrentes [lista de concorrentes].
[GeoContent], estruture um brief completo: título, H2/H3 sugeridos, perguntas a
responder, termos LSI obrigatórios e extensão recomendada.
[AIVisibility], adicione uma seção "formato ideal para citação em IA" com a estrutura de
abertura que maximiza a chance de ser extraída por AI Overviews/ChatGPT.
Entreguem um brief único, pronto para um redator externo executar sem contexto adicional.
```

---

## 4. 📊 Relatório Executivo para Cliente/Diretoria
**Quando usar:** apresentação de resultados para stakeholders não-técnicos.
**Agentes:** DataStrategist + HumanEditor + MatrixAuditor

```
[DataStrategist], resuma os principais resultados do período [mês/trimestre] em
métricas de negócio (tráfego, conversões, receita estimada) — não métricas técnicas.
[HumanEditor], reescreva em linguagem executiva, sem jargão de SEO, com narrativa clara
de causa e efeito.
[MatrixAuditor], revise se cada dado apresentado responde "e daí para o negócio?" — corte
qualquer métrica sem explicação de impacto.
Formato final: 1 página, com 3 destaques e 3 próximos passos.
```

---

## 5. 🏛️ Arquitetura de Cluster de Conteúdo (Pillar Page)
**Quando usar:** planejamento de autoridade tópica para um novo pilar de conteúdo.
**Agentes:** GeoContent + DataStrategist + LinkArchitect

```
[DataStrategist], mapeie os subtemas e perguntas relacionadas ao tópico-pilar
[tema principal] com potencial de busca.
[GeoContent], organize isso em uma arquitetura de pillar page + cluster pages (1 pilar +
[N] artigos de suporte), definindo o escopo de cada peça sem sobreposição de intenção.
[LinkArchitect], defina a estratégia de linkagem interna entre pilar e cluster (âncoras
e direção dos links).
Entreguem um mapa único da arquitetura, com título e escopo de cada página.
```

---

## 6. 🥊 Auditoria Competitiva 360°
**Quando usar:** benchmark completo contra concorrentes diretos.
**Agentes:** DataStrategist + AIVisibility + LinkArchitect + UXArchitect

```
[PipelineDirector], ative uma AUDITORIA COMPETITIVA 360° comparando [meu site] com
[concorrente 1], [concorrente 2] e [concorrente 3].
[DataStrategist]: gaps de palavra-chave e tráfego estimado.
[AIVisibility]: quem é mais citado em ChatGPT/Perplexity/AI Overviews para as principais
consultas do nicho, e por quê.
[LinkArchitect]: comparação de perfil de backlinks e autoridade de domínio.
[UXArchitect]: comparação de usabilidade, velocidade e experiência de conversão.
Entreguem uma tabela comparativa única + as 5 oportunidades onde estou perdendo para
todos os concorrentes ao mesmo tempo (maior prioridade).
```

---

## 7. 🌍 Plano de Expansão Internacional / Multi-idioma
**Quando usar:** entrada em novo país ou idioma.
**Agentes:** TechSEO + GeoContent + LinkArchitect + LocalGEO (se aplicável)

```
[TechSEO], defina a estrutura ideal de URLs/hreflang para expandir [site] para [novo
idioma/país], considerando SEO técnico multi-regional.
[GeoContent], avalie o que precisa ser localizado além da tradução (intenção de busca,
termos LSI, referências culturais).
[LinkArchitect], mapeie oportunidades de autoridade local no novo mercado.
[LocalGEO], se o negócio terá presença física no novo mercado, defina a estratégia de
Google Business Profile local.
Entreguem um plano único de entrada, faseado em 3 etapas (técnica, conteúdo, autoridade).
```

---

## 8. 🗺️ Roadmap de Priorização (Quick Wins → Longo Prazo)
**Quando usar:** transformar qualquer auditoria/diagnóstico já feito nesta conversa em um plano de ação faseado, com prazos — fecha o gap de nenhum prompt anterior entregar um plano de execução, só diagnósticos.
**Agentes:** PipelineDirector + DataStrategist + MatrixAuditor

```
[PipelineDirector], consolide tudo o que foi levantado nesta conversa (ou cole abaixo
os achados de uma auditoria) em um roadmap único, dividido em:
1) Quick Wins (0-30 dias, baixo esforço/alto impacto)
2) Estrutural (30-90 dias)
3) Estratégico (90+ dias)
[DataStrategist], estime o impacto relativo de cada item.
[MatrixAuditor], sinalize qualquer item que dependa de outro ainda não resolvido
(ordem de dependência entre itens).
Entreguem uma tabela única: item | fase | agente responsável | impacto estimado.
```

---

Cada prompt pode ser encerrado com uma chamada ao `[MatrixAuditor]` (rubrica 0-10, ver `agentes_detalhados.md`) antes da entrega final ao cliente.
