# clone-tabnews
Fui convencido pelo Teló

# dia 3
```
checar versão do node
    node -v
checar versões disponíveis e instalar a específica via "codename"
    nvm ls
    nvm install lts/hydrogen
aplicar versão padrão do node no ambiente
    nvm alias default lts/hydrogen
criar arquivos para dependências padrão
    criar arquivo ".nvmrc" na raiz 
        # o conteúdo é a apenas o nome da versão do node
    npm init 
        # gera o arquivo package.json onde ficarão as demais dependências
instalar next e react
    npm install next@13.1.6
    npm install react@18.2.0
    npm install react-dom@18.2.0

Comentários extra curso
    Quebrei o repositório com um commit de 400 mil linhas fazendo push da pasta node_modules
    Foi preciso aprender sobre gitignore
    https://www.freecodecamp.org/news/gitignore-file-how-to-ignore-files-and-folders-in-git/
```