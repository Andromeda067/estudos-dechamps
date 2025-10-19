### estudos dechamps

anotacoes e asformas de fazer as coisas segindo a metodologia do cur .DEV do felepi dechamps

## inicializacao do projeto

npx create-next-app@latest my-next-app

### dia 10

## editor coinfig

1 - baixar a extencao do editor config
2 - abriri um aarquivo .editorconfig

3- configurar aquivo

        root = true

        {*}

        indent_styke = space
        indent_size = 2

## prettier

1 - npm instaall prettier -D

        packge.json (add scripts)
                "lint:Check": "prettier --check .",
                "lint:Fix": "prettier --write ."

2 - intalar a extencao no vs code prettier

configuracoes(VS code )

busca - formatter (Colocar o pretter )

Busca - format on save (ativar )

Buscar - autoSave (Off)
