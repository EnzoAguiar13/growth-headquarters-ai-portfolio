# Growth Headquarters AI

**Sede operacional inteligente para coordenar projetos, agentes especializados e processos empresariais.**

O GH é uma plataforma **local-first**, em desenvolvimento, baseada em arquitetura multiagente, ferramentas autorizadas e uma interface corporativa 3D.

Não é um chatbot. Não é uma ferramenta exclusiva de marketing digital ou tráfego pago. Marketing e tráfego são especialidades possíveis — as primeiras salas de uma sede que pode expandir para outras áreas de operação.

## Visão vs. o que existe hoje

A **visão** é uma sede empresarial com departamentos (projetos, pesquisa, comércio, qualidade de dados, relatórios, automação) cada um como agente com permissões e ferramentas próprias.

O **núcleo atual** demonstra esse contrato com três especialidades, PolicyEngine deny-by-default e um Director allowlisted. PostgreSQL 18 está desenhado e ainda **não operacional**. Meta, Google e OAuth permanecem desligados no código.

## Primeiras especialidades (demonstração)

| Agente | Papel | Limite |
| --- | --- | --- |
| spec.07 Product Researcher | Brief sintético do projeto | Não pesquisa a internet |
| spec.10 Catalog Quality | Inspeção estrutural de catálogo | Não altera nem publica produtos |
| spec.11 Traffic Analyst | Métricas de CSV por regras | Não usa LLM; não lê Meta/Google |

## Estado

**Implementado:** React 18, Three.js, FastAPI, PolicyEngine, Director, os três agentes, CSV, ranking determinístico.

**Experimental:** login loopback; Qwen 2.5 7B via llama-server (padrão `fake`).

**Em implantação:** PostgreSQL 18 e RLS.

**Planejado:** novas especialidades, pesquisa web autorizada, Meta/Google/GA4, OAuth, cofre.

Esta página é só a apresentação estática. O código-fonte permanece em repositório privado.
