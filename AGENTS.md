# AGENTS.md — client

Instruções específicas do `client`. As regras gerais (limites, fluxo de trabalho, definição de pronto) estão no [AGENTS.md da raiz](../AGENTS.md) e valem aqui. Este arquivo só acrescenta ou sobrepõe.

## Estado

**Em definição.** Ainda não há stack, código nem comandos. Antes de criar qualquer código aqui:

1. Confirme com o usuário a plataforma e a stack.
2. Registre a escolha num ADR (`docs/decisions/` da raiz, por ser decisão que afeta o monorepo).
3. Atualize este arquivo com stack, comandos e padrões.

## Repositório

- Git próprio: `BrendownFerreira/el-cazador-client`. Commits são feitos dentro de `client/`.
- Configuração: chaves vindas do `.env` da raiz, pelo mesmo mecanismo do `front-back-api` ([env-sync](../docs/deployment/env-sync.md)). O alvo ainda não existe.

## Docs

- Do cliente: [docs/README.md](docs/README.md)
- Gerais (arquitetura, glossário, ADRs): [../docs/README.md](../docs/README.md)

<!-- Ao definir a stack, preencha:
## Stack
## Comandos (instalar, rodar, testar, lint, build)
## Estrutura de pastas
## Padrões de código
-->
