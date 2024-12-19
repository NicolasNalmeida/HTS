## INSTALAÇÃO DO PROJETO
**INSTALANDO SASS**
```sh
  npm install -g node-sass ## (Recomendado instalar globalmente)
```

```sh
  npm install node-sass
```

**EXECUTANDO O SASS**
Para salvar e assistir as alterações do SASS, execute o comando abaixo em um terminal separado:
```sh
node-sass --watch assets/css/sass/theme.min.scss assets/css/theme.min.css --output-style compressed           ## Este comando assistira as mudanças do SASS e minificará o css fianl
```