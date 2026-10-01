# Primeiros passos com Ren'Py

Este guia é um roteiro de pesquisa. A liderança informou que também está aprendendo a engine; não se espera que todos já saibam programar.

## Roteiro

1. Baixe o Ren'Py no [site oficial](https://www.renpy.org/latest.html).
2. Abra o launcher e crie um projeto de teste.
3. Explore o tutorial oficial: diálogos, narração, rótulos (`label`) e menus (`menu`).
4. Estude imagens, personagens, cenários, variáveis e condições.
5. Faça mudanças pequenas e execute o projeto pelo launcher.
6. Depois, pesquise screens e Python integrado ao Ren'Py para prototipar minigames.

## Exemplo de estudo

```renpy
label start:
    "A personagem pergunta se você quer ajudar."

    menu:
        "O que você responde?"
        "Pergunto como posso ajudar.":
            $ afinidade = 1
            "Você escuta o que ela prefere."
        "Decido sem perguntar.":
            $ afinidade = 0
            "A personagem explica que queria escolher por conta própria."

    return
```

Exemplo didático, não é cena aprovada. Em um projeto real, inicialize as variáveis antes de usá-las.

## Perguntas para a equipe

- Como criar e executar o projeto em cada sistema operacional usado?
- Como organizar scripts e assets na pasta do Ren'Py?
- Como testar todos os caminhos de uma escolha?
- Qual é a menor versão de um minigame que cabe na demo?
- Como registrar autoria, licença e créditos?

## Fontes oficiais

- [Download](https://www.renpy.org/latest.html)
- [Documentação](https://www.renpy.org/doc/html/)
- [Quickstart](https://www.renpy.org/doc/html/quickstart.html)
- [Python no Ren'Py](https://www.renpy.org/doc/html/python.html)
- [Screens](https://www.renpy.org/doc/html/screens.html)
