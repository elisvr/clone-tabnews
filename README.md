# clone-tabnews
Fui convencido pelo Teló

# dia 3
```
Checar versão do node
    node -v

Checar versões disponíveis e instalar a específica via "codename"
    nvm ls
    nvm install lts/hydrogen

Aplicar versão padrão do node no ambiente
    nvm alias default lts/hydrogen

Criar arquivos para dependências padrão
    Criar arquivo ".nvmrc" na raiz 
        # o conteúdo é a apenas o nome da versão do node
    npm init 
        # gera o arquivo package.json onde ficarão as demais dependências

Instalar next e react
    npm install next@13.1.6
    npm install react@18.2.0
    npm install react-dom@18.2.0

Comentários extra curso
    Quebrei o repositório com um commit de 400 mil linhas fazendo push da pasta node_modules
    Foi preciso aprender sobre gitignore
    https://www.freecodecamp.org/news/gitignore-file-how-to-ignore-files-and-folders-in-git/
```

# dia 4
```
Protocolos
HTTP = Hypertext Transfer Protocol
    Define como as informações client/server serão trocadas

FTP = File Transfer Protocol

SMTP = Simple Mail Transfer Protocol

TCP = Transmission Control Protocol
    Possui "Error Recovery" para garantir que a informação no destino final está íntegra

UDP = User Datagram Protocol
    Ideal para realizar tráfego de informações constantes como voz e vídeo mesmo que alguns pacotes se percam, evitando assim, travamentos na transmissão devido a ausência de necessidade de checagem dos pacotes como no caso do TCP
    vídeo de comparação entre TCP e UDP em games
    https://www.youtube.com/watch?v=ZEEBsq3eQmg&ab_channel=Yannick%28yandeu%29

IP = Internet Protocol
```
```
Configurando e executando Next
    criar pasta pages/ na raiz
    criar arquivo index.js dentro de pages/
    obs -> todos os arquivos dentro da pasta pages virarão rotas públicas
    ex, arquivo recuperar-senha.js = site.com/recuperar-senha

Dentro do arquivo package.json, na seção scripts
    criar o seguinte comando
        "dev": "next dev"

Executar o comando no terminal com o nome designado no arquivo anterior
    npm run dev

Deixar o ambiente de desenvolvimento com saída pública
    na aba ports
        right click > port visibility > public
    segue print abaixo
    obs -> por padrão o codespaces utiliza a porta 3000
```
![alt text](doc-images/image-1.png)

# dia 5
```
Comandos git
    verificar "imagens"/commits do repositório
        git log --stat
    verificar arquivos em que estão no estágio de modified
        git status
    commitar mudanças
        git add . || git add nome_do_arquivo
        git commit -m 



Estágios dos arquivos
    modified
        todos os arquivos que são modificados durante as sessões de programação
    staged
        arquivos destacados para realização do novo commit, se necessário nem todos os arquivos que foram modificados precisam estar como staged
    commit
        
    untracked
        arquivos que não estão sendo rastreados para os demais estágios
        geralmente são arquivos novos que nunca passaram pelo repositório

```