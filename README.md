# 🚀 PWEB Ranqueado v2.1: Ultra Premium AI Framework (Edição Expandida e Auditada)

O **PWEB Ranqueado** é um framework de engenharia de prompt multi-agente para a era do SEO tradicional, GEO (*Generative Engine Optimization*) e AEO (*Answer Engine Optimization* — citação em respostas de IA), com UX/CRO integrado.

Simula o fluxo de trabalho de uma agência de elite dentro do **Claude Projects**, com **13 agentes especialistas** (9 fixos + 4 condicionais) coordenados por um orquestrador central.

> **Sobre esta versão:** a v2.1 amplia a base original de 7 agentes/3 fases para 13 agentes/5 fases, e passou por uma auditoria sênior focada em eliminar redundância entre agentes, melhorar usabilidade e fechar lacunas do fluxo (triagem inicial, loop de refinamento, rubrica de auditoria objetiva).

---

## 🛠️ Como Instalar e Usar no Claude

Requer acesso ao recurso de **Projects** do Claude.

1. No painel do Claude, clique em **Projects** → **Create Project**. Nome sugerido: `PWEB Ranqueado`.
2. Em **Project Instructions**, cole o conteúdo de [`system_instructions.md`](system_instructions.md) — é o roteador enxuto do sistema.
3. Na aba **Files**, faça upload de:
   - [`agentes_detalhados.md`](agentes_detalhados.md) — perfil completo dos 13 agentes, metodologia e rubrica de auditoria;
   - [`knowledge_anchor.md`](knowledge_anchor.md) — regras de roteamento de dados.
4. *(Opcional)* Ainda em **Files**, suba exports do seu site (Semrush, GA4, GSC, backlinks, GBP, YouTube Analytics) para dar contexto real aos agentes.

> Por que dois arquivos separados em vez de um só gigante? A própria documentação da Anthropic recomenda manter as Instruções do Projeto concisas e mover contexto extenso para arquivos — instruções muito longas diluem a atenção do modelo. Por isso o roteador ficou enxuto e o detalhamento foi para a base de conhecimento.

---

## 🤖 A Matriz de Agentes (13)

**Núcleo fixo (sempre ativo):** PipelineDirector, TechSEO, UXArchitect, GeoContent, HumanEditor, OffPagePR, LinkArchitect, DataStrategist, AIVisibility, MatrixAuditor.

**Módulos condicionais (ativados na Fase 0 conforme o projeto):** LocalGEO, VideoGEO, ContentOps.

Perfis completos: ver `agentes_detalhados.md`.

---

## 🔄 Pipeline de Execução em 5 Fases

0. **Triagem** — o `PipelineDirector` faz até 3 perguntas para decidir quais módulos condicionais ativar.
1. **Diagnóstico e Inteligência** — DataStrategist + TechSEO + UXArchitect + módulos aplicáveis.
2. **Arquitetura, Produção e Copywriting** — GeoContent + HumanEditor + VideoGEO (se ativo).
3. **Autoridade e Validação em IA** — OffPagePR + LinkArchitect + AIVisibility, em entrega consolidada.
4. **Auditoria Crítica e Loop de Refinamento** — MatrixAuditor aplica rubrica 0-10; nota < 8 volta ao agente responsável (máx. 2 rodadas).

> 💡 Templates de comandos para disparar cada fase estão em [`prompts_fases_agentes.md`](prompts_fases_agentes.md). Para entregáveis específicos de agência (diagnóstico de crise, migração, briefs, relatórios executivos etc.), ver [`prompts_avancados_profissionais.md`](prompts_avancados_profissionais.md).

---

## 🧠 Otimização do Fluxo (Base de Conhecimento Própria)

O `knowledge_anchor.md` ancora as atribuições de dados brutos e impede sobreposição entre agentes (ex.: um export de backlinks nunca é processado por dois agentes ao mesmo tempo). Arquivos de módulos condicionais só são usados se o módulo correspondente foi ativado na Fase 0.

---

## 📜 Conformidade Algorítmica

Calibrado seguindo as documentações oficiais de: Google Search Essentials, Google AI Overviews, Google Business Profile, YouTube Creator Guidelines, Bing Webmaster Guidelines, GPTBot/SearchGPT, ClaudeBot, PerplexityBot, AppleBot e Meta AI.

---

## 🟩 Contribuição

Sugestões bem-vindas: novos módulos condicionais, novos checklists de UX/SEO, novos contextos inteligentes, melhorias de documentação, correções de bugs.

---

## 🤝 Apoio ao projeto

```
Pix: doacoes@produtoraweb.com
Cripto: 0xEd46dADa43cb7b4e4D753D631B4E99002530D780
```

## 🛡️ Aviso legal

Use com responsabilidade, revise os prompts antes de enviar e valide alterações importantes antes de publicar qualquer projeto.

## 📄 Licença

Distribuído sob **GNU General Public License v3.0 (GPL-3.0)**. Consulte `LICENSE`.

---

Desenvolvido por ProdutoraWeb.com. 🚀
