<div align="center">

# Livon Saúde · Produto & Tecnologia

Engenharia por trás da **Minha Livon**: saúde ocupacional, SST e gestão de pessoas, com IA no centro.

</div>

---

## Mapa da organização

Os repositórios seguem uma convenção de prefixos. Ao criar um novo, use a que se encaixa.

| Prefixo | O que é | Exemplos |
|---|---|---|
| `minhalivon-*` | Produto principal: monólito e frontends | `minhalivon-backend`, `minhalivon-frontend-vue3` |
| `svc-*` | Microserviços satélite, isolados do monólito | `svc-byok`, `svc-sst`, `svc-middleware` |
| `ai-*` | Agentes e soluções de IA | `ai-scribe`, `ai-atestados`, `ai-plano-de-acao` |
| `int-*` | Integrações com sistemas externos | `int-sap-cpi`, `int-n8n-workflows` |
| `tools-*` | Ferramentas internas de engenharia | `tools-atlas-metrics`, `tools-e2e-tests` |
| `nr01-*` | Iniciativas de NR-01 e riscos psicossociais | `nr01-psicossocial` |

## Repositórios em destaque

| Repositório | Descrição |
|---|---|
| [`minhalivon-backend`](https://github.com/Livon-Saude/minhalivon-backend) | Monólito principal: Python 3.10, Django 4.1, Celery e PostgreSQL |
| [`minhalivon-frontend-vue3`](https://github.com/Livon-Saude/minhalivon-frontend-vue3) | Novo frontend da Minha Livon em Vue 3 + Nuxt |
| [`livon-skills`](https://github.com/Livon-Saude/livon-skills) | Marketplace privado de plugins e skills do Claude Code |
| [`svc-byok`](https://github.com/Livon-Saude/svc-byok) | Painel BYOK: cada cliente usa a própria chave de IA e paga o consumo direto ao provedor |
| [`superset`](https://github.com/Livon-Saude/superset) | Apache Superset para dashboards e análise de dados |

## Como trabalhamos

- **Guildas** são donas dos padrões de engenharia: Definition of Ready/Done, fluxo de PR e cadência de release.
- **Decisões viram ADRs** e passam por uma fase piloto antes de virar regra.
- **Branches protegidas:** `base`, `staging` e `master` não aceitam force push nem deleção, e todo PR precisa de aprovação e de conversas resolvidas.
- **Release com gate:** só entra em produção o que é verificado, reversível e observável.
- **IA com governança:** todo uso de IA generativa segue a Política de Uso e Desenvolvimento de IA Generativa da Livon.

## Primeiros passos

1. Peça para entrar no time da sua guilda na organização.
2. Leia o processo de desenvolvimento em [`SDLC`](https://github.com/Livon-Saude/SDLC) e a documentação técnica em [`docs`](https://github.com/Livon-Saude/docs).
3. Instale o Claude Code e adicione o marketplace [`livon-skills`](https://github.com/Livon-Saude/livon-skills).
4. Trabalhe numa branch de feature e abra o PR contra `base`. <!-- confirmar o fluxo base → staging → master -->

## Documentação

| O quê | Onde |
|---|---|
| Documentação técnica | [`docs`](https://github.com/Livon-Saude/docs) |
| Documentação para usuários | [`user-docs`](https://github.com/Livon-Saude/user-docs) |
| Backlog | Jira, projeto `MLK` |
| Política de IA Generativa | <!-- link --> |

## Contatos

| Assunto | Canal |
|---|---|
| Acessos e plataforma | <!-- canal --> |
| Segurança e LGPD | <!-- e-mail/canal --> |

---

<sub>Visível apenas para membros da organização. Nunca versione segredos, credenciais ou dados pessoais de pacientes e colaboradores (LGPD).</sub>
