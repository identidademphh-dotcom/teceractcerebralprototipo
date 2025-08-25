tesseract-cerebral/
├─ README.md
├─ LICENSE
├─ .gitignore
├─ .env.example               # chaves falsas + instruções
├─ /docs/
│  ├─ lore/
│  │  ├─ 00_manifesto-da-raposa.md
│  │  ├─ atlas-de-eus.md
│  │  └─ simbolos-e-rituais.md
│  └─ guides/
│     ├─ setup-n8n.md
│     ├─ setup-supabase.md
│     └─ arquitetura-agentes.md
├─ /orquestra/
│  ├─ agentes/
│  │  ├─ hermes.json          # “mensageiro” (coleta/entrega)
│  │  ├─ cartografo.json      # mapeia memórias / embeddings
│  │  ├─ narrador.json        # transmutação p/ texto/poesia
│  │  ├─ filosofo.json        # análise/reflexão
│  │  └─ mestre-de-jogo.json  # orquestrador/roteiro
│  ├─ tools/
│  │  ├─ retriever.tool.json
│  │  ├─ supabase.tool.json
│  │  └─ websearch.tool.json
│  └─ pipelines/
│     ├─ retrieval.rag.json   # query → embed → search → resposta
│     └─ automacoes.yml       # tarefas recorrentes
├─ /fluxos_n8n/
│  ├─ lume_all_in_one.json
│  ├─ heartbeat.json
│  └─ hermes_bridge.json
├─ /supabase/
│  ├─ schema.sql              # tabelas + extensão vector
│  ├─ policies.sql            # RLS minimamente segura
│  └─ seeds.sql               # dados simbólicos iniciais
├─ /prompts/
│  ├─ lume-core.md            # “quem é a Lume?”
│  ├─ estilo-narrativo.md
│  └─ prompt-tests.md
├─ /assets/
│  ├─ emblemas/
│  └─ paleta-cores.md
├─ /tests/
│  ├─ rag-smoke.test.md
│  └─ agentes-healthcheck.md
└─ /ci/
   └─ validate-json.yml       # GitHub Actions: lint/validate JSON
