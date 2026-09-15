<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/header-dark.png">
  <img src="./assets/header-light.png" alt="Ruan Gomes — Inteligência Artificial aplicada à operação" width="100%">
</picture>

Construo sistemas de IA e automação que tiram trabalho manual da operação — e os mantenho rodando em produção.

Analista de TI Júnior na Diagonal Têxtil, indústria têxtil em Belo Horizonte. Desenvolvo e opero a plataforma interna de IA e automação, cobrindo comercial, financeiro, atendimento, estoque e TI. Comecei em banco de dados, passei por suporte, infraestrutura e ERP, e hoje desenho, implanto e sustento a solução ponta a ponta.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/impacto-dark.png">
  <img src="./assets/impacto-light.png" alt="Régua de cobrança: ~3 min para 5 s por cliente · Fechamento contábil: 17h30/mês de digitação eliminada · Aprovação de pedido: ~15 min para 2 min · Mais de 20 aplicações em produção" width="100%">
</picture>

### O que está por trás desses números

- **Agente de IA com RAG** atendendo suporte N1 no chat corporativo, que abre chamado sozinho quando três tentativas não resolvem — conversa informal de corredor virou chamado registrado e mensurável
- **Régua de cobrança por WhatsApp**, com IA montando a abordagem e boleto anexado no fluxo — passou a cobrir a carteira inteira, não só a inadimplência grande
- **Integração ERP ↔ sistema contábil**, gerando o arquivo no layout exato que o contábil importa — acabou a redigitação lançamento por lançamento
- **PWA de pedidos com aprovação em campo** — o pedido e os indicadores de decisão chegam na mesma tela, no celular

### Stack

**IA** — agentes · LLMs via API (OpenAI, Anthropic, Google) e locais com Ollama · RAG com pgvector · grafos de conhecimento · engenharia de prompt
**Back-end** — Python · APIs REST · PostgreSQL · Supabase (Edge Functions, pg_cron) · n8n
**Operação** — Docker · PM2 · Sentry · Grafana · Zabbix · Linux · VPS
**Em aprofundamento** — LangGraph · LangChain · LangFlow · LangSmith

### Como eu decido o que automatizar

Procuro onde o processo sangra: a tarefa que alguém repete toda semana, o dado que três áreas calculam de três jeitos, a decisão que trava porque a informação mora em outro sistema. Uso LLM onde ela decide melhor que uma regra, e regra determinística onde IA seria desperdício.

### Sobre os repositórios

Os sistemas acima pertencem à empresa onde trabalho — código, schema e regra de negócio não saem de lá. O que fica público aqui são reimplementações dos mesmos padrões, com dados sintéticos, e projetos pessoais.

<p>
  <a href="https://www.linkedin.com/in/ruanpgm/">
    <img src="https://img.shields.io/badge/LinkedIn-ruanpgm-0A0A0C?style=flat-square&logo=linkedin&logoColor=C8CDD6&labelColor=1E242C" alt="LinkedIn">
  </a>
  <img src="https://img.shields.io/badge/Belo%20Horizonte-MG-1E242C?style=flat-square" alt="Belo Horizonte, MG">
</p>
