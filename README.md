# DICIS Game

Visual novel educativa sobre inclusão e combate à invisibilidade social, desenvolvida pela equipe DICIS.

> O repositório está na fase de organização. O conteúdo abaixo registra a reunião de 25/09/2026; itens não decididos estão marcados como pendentes.

## Objetivo

Criar uma experiência narrativa imersiva, humanizada, responsável e informativa para o público jovem. A meta registrada para outubro de 2026 é uma demo jogável; o jogo completo poderá continuar depois.

## Tecnologia

- Engine planejada: [Ren'Py](https://www.renpy.org/), baseada em Python.
- Narrativa: diálogos, cenários, escolhas e consequências.
- Minigames: a equipe ainda pesquisará como integrá-los e quais cabem na demo.

## Comece por aqui

1. Leia [a visão do projeto](docs/PROJETO.md) e [as decisões registradas](docs/DECISOES.md).
2. Siga o [guia inicial de Ren'Py](docs/REN-PY-INICIO.md).
3. Combine tarefas e leia [como contribuir](CONTRIBUTING.md).
4. Quando o projeto for criado pelo launcher Ren'Py, coloque seus arquivos em `game/`.

## Estrutura

| Caminho | Conteúdo |
|---|---|
| `docs/` | Visão, decisões, pesquisa, roteiro e padrões de conteúdo |
| `game/` | Arquivos do projeto Ren'Py, após a criação pela equipe |
| `assets/` | Materiais autorais ou licenciados, com créditos |
| `prototypes/` | Experimentos que ainda não foram integrados |

## Acordos registrados

- Não usar IA generativa na produção de assets do jogo nem templates feitos com essa tecnologia.
- Não adaptar diretamente os personagens do logotipo DICIS; criar personagens e identidade próprios.
- Dar consequências significativas às escolhas narrativas e buscar minigames pertinentes e distintos.
- Registrar a autoria e a licença dos materiais externos.

## Ainda não decidido

Personagens e histórias da demo, direção visual, seleção dos minigames, divisão de tarefas e licença de distribuição. Consulte `docs/DECISOES.md`.

## Autenticação e dados

O escopo atual descreve um jogo local de narrativa e **não especifica contas, login, servidor ou tokens**. Não implemente nem documente um fluxo de autenticação como se já existisse. Se um recurso online for proposto no futuro, registre a necessidade e as decisões de privacidade e segurança antes de implementá-lo. Veja `docs/ARQUITETURA.md`.
