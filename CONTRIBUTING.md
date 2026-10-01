# Como contribuir

Este guia ajuda a equipe a trabalhar de forma clara e revisável. Pergunte ao grupo quando uma decisão de escopo, narrativa ou representação ainda estiver aberta.

## Fluxo de trabalho

1. Atualize sua cópia local a partir de `develop`.
2. Crie uma branch curta para uma tarefa combinada.
3. Faça mudanças pequenas e relacionadas à tarefa.
4. Abra um Pull request para `develop` e explique o que mudou.
5. Peça revisão de pelo menos uma pessoa da equipe antes de integrar.

`main` deve conter versões estáveis para demonstração. `develop` reúne trabalho em andamento que já passou por revisão.

## Nomes de branches

Use `<tipo>/<assunto-curto>`:

- `docs/guia-renpy`
- `feature/dialogo-inicial`
- `feature/sistema-escolhas`
- `feature/minigame-ritmo`
- `fix/erro-no-menu`

Crie branches a partir de `develop`. Não crie uma branch permanente por integrante; uma branch deve representar uma tarefa.

## Commits

Escreva mensagens curtas no imperativo ou descrevendo a mudança:

- `docs: explica como iniciar o projeto`
- `feat: adiciona escolha no diálogo inicial`
- `fix: corrige retorno do minigame`

## Pull requests

Inclua:

- objetivo e resumo da mudança;
- como outra pessoa pode revisar ou testar;
- imagens ou gravações apenas quando úteis e sem dados privados;
- origem e licença para cada asset externo adicionado.

Não integre mudanças que incluam credenciais, tokens, arquivos pessoais, assets sem autorização ou conteúdo gerado por IA em desacordo com o acordo do projeto.
