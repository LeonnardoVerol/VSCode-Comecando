- [Introdução](#introdução)
- [Evolução dos Editores Gráficos](#evolução-dos-editores-gráficos)
- [Powered by Electron](#powered-by-electron)
- [Painel Lateral](#painel-lateral)
- [Command Pallete](#command-pallete)
- [Column Selection](#column-selection)
- [Add Next Occurence](#add-next-occurence)
- [Line Comment](#line-comment)
- [Screencast Mode](#screencast-mode)
- [Split Screen](#split-screen)
- [Terminal Integrado](#terminal-integrado)
- [Snippets & Emmet](#snippets--emmet)
- [Integração Nativa com Git](#integração-nativa-com-git)
	- [Iniciar um repositório](#iniciar-um-repositório)
	- [Sistema de Branch](#sistema-de-branch)
	- [Staging & Status](#staging--status)
	- [Atualizações do Arquivo](#atualizações-do-arquivo)
	- [Histórico de Commits (via Extensão)](#histórico-de-commits-via-extensão)
- [Extensões e Temas](#extensões-e-temas)
- [Live Share (Extensão Oficial)](#live-share-extensão-oficial)
- [Remote Development (Extensão Oficial)](#remote-development-extensão-oficial)
	- [Exemplo SSH](#exemplo-ssh)
- [Debugger & Run](#debugger--run)
- [Indicações & Sugestões](#indicações--sugestões)
	- [Configurações](#configurações)
	- [Extensões Essenciais](#extensões-essenciais)
		- [Bracket Pair Colorizer 2](#bracket-pair-colorizer-2)
		- [indent-rainbow](#indent-rainbow)
		- [Live Share Extension Pack](#live-share-extension-pack)
		- [Remote Development Extension Pack](#remote-development-extension-pack)
		- [Settings Sync](#settings-sync)
		- [Trailing Spaces](#trailing-spaces)
		- [Paste JSON as Code](#paste-json-as-code)
		- [YAML](#yaml)
		- [Better TOML](#better-toml)
		- [Test Explorer UI](#test-explorer-ui)
		- [Path Intellisense](#path-intellisense)
		- [Markdown All in One](#markdown-all-in-one)
		- [DotENV](#dotenv)
		- [EditorConfig for VS Code](#editorconfig-for-vs-code)
		- [GistPad](#gistpad)
		- [Git History](#git-history)
		- [GitLens — Git supercharged](#gitlens--git-supercharged)
		- [gitignore ou .gitignore Generator](#gitignore-ou-gitignore-generator)
		- [colorize](#colorize)
		- [Code Time](#code-time)
	- [Temas](#temas)
		- [Material Icon Theme](#material-icon-theme)
		- [Monokai Night Theme](#monokai-night-theme)
		- [2077 theme](#2077-theme)
		- [Outrun](#outrun)
		- [Shades of Purple](#shades-of-purple)
		- [Night Owl](#night-owl)
		- [One Dark Pro](#one-dark-pro)
		- [Material Theme](#material-theme)
		- [Winter is Coming Theme](#winter-is-coming-theme)
		- [Outras Opções](#outras-opções)

# Introdução

Essa apresentação serve como uma demonstração básica de algumas funcionalidades e do poder do Visual Studio Code.

# Evolução dos Editores Gráficos

Nos últimos anos eu trabalhei com os 3 editores e acredito que os 3, em sequencia, representam uma evolução [dos editores]. Todos são Cross-Platform.

<img src="images/Untitled.png" width="960" height="100%">

<img src="images/Untitled%201.png" width="960" height="100%">

<img src="images/Untitled%202.png" width="960" height="100%">


# Powered by Electron

Uma curiosidade, tanto o Atom quanto o VS Code funcionam por causa do "Electron".

Em termos simples, o Electron permite você transformar uma aplicação Web em Desktop.

![images/Untitled%203.png](images/Untitled%203.png)


Inclusive sendo possível "inspecionar" o editor como se fosse uma página Web

![images/Untitled%204.png](images/Untitled%204.png)


# Painel Lateral

![images/Untitled%205.png](images/Untitled%205.png)


# Command Pallete

O Atalho mais importante do VS Code: `F1` ou `Ctrl + Shift + P` . Com ele, você consegue chamar qualquer funcionalidade do editor. Praticamente não é necessário decorar muitos outros atalhos.

![images/Untitled%206.png](images/Untitled%206.png)

Podemos usar essa interface, inclusive, para converter a "Indentation" ou "reindent" seu código automaticamente. Se for algo que use muito, pode criar atalhos personalizados tambem.

![images/Untitled%207.png](images/Untitled%207.png)

Outra variante do Command Pallete é o `Ctrl + P`. (ou você pode simplesmente remover o caractere `>` do barra de busca do comando original `Ctrl + Shift + P`)

![images/Untitled%208.png](images/Untitled%208.png)

Com ela, é possível irmos pra outro arquivo, outra linha, ou diretamente para uma função.

![images/Untitled%209.png](images/Untitled%209.png)

![images/Untitled%2010.png](images/Untitled%2010.png)


# Column Selection

Usando o `scroll` do mouse é possível fazer uma seleção múltipla verticalmente. Acredite, será útil.

![images/Untitled%2011.png](images/Untitled%2011.png)

Confira a pasta `videos` do repositório para uma pequena demonstração.

# Add Next Occurence

O segundo Atalho mais importante. Usando o atalho `Ctrl + D` é possível "ir marcando" vários matches da seleção.

![images/Untitled%2012.png](images/Untitled%2012.png)


# Line Comment

O terceiro atalho mais importante, `Ctrl + ;` . Rapidamente comente/"descomente" uma linha ou varias linhas de código.


# Screencast Mode

Esse modo fica mostrando as tecladas digitadas, assim como cliques do mouse. Perfeito para dar aula ou criar videos de tutorial.

![images/Untitled%2013.png](images/Untitled%2013.png)


# Split Screen

Além do Icone no canto superior direito, tambem é possivel dividir a tela, conforme desejar, arrastando as abas para o local desejado.

![images/Untitled%2014.png](images/Untitled%2014.png)

![images/Untitled%2015.png](images/Untitled%2015.png)


# Terminal Integrado

Apertando `Ctrl + '` é possível abrir o Terminal Integrado. Se você estiver trabalhando dentro de uma pasta, ele já abre dentro daquele diretório.

![images/Untitled%2016.png](images/Untitled%2016.png)

Também é possível dividir a tela dos terminais

![images/Untitled%2017.png](images/Untitled%2017.png)


# Snippets & Emmet

Snippets são "atalhos" de código. Apenas digitando palavras chaves, temos a opção de autocompletar que já implementa toda a estrutura do que queremos fazer.

O VS Code não possui nativamente snippets de todas as linguagens mas podemos expandir essa funcionalidade instalando extensões específicas de uma linguagem. Também é possível criar seus próprios snippets.

![images/Untitled%2018.png](images/Untitled%2018.png)

![images/Untitled%2019.png](images/Untitled%2019.png)

![images/Untitled%2020.png](images/Untitled%2020.png)

Emmet é uma extensão famosa estilo snippets para tecnologias Web e já vem integrado no Editor.

```html
ul>li*5
```

```html
<ul>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
    <li></li>
</ul>
```


# Integração Nativa com Git

## Iniciar um repositório

![images/Untitled%2021.png](images/Untitled%2021.png)

## Sistema de Branch

![images/Untitled%2022.png](images/Untitled%2022.png)

## Staging & Status

![images/Untitled%2023.png](images/Untitled%2023.png)

![images/Untitled%2024.png](images/Untitled%2024.png)

## Atualizações do Arquivo

![images/Untitled%2025.png](images/Untitled%2025.png)

## Histórico de Commits (via Extensão)

![images/Untitled%2026.png](images/Untitled%2026.png)


# Extensões e Temas

Extensões expandem as funcionalidades do editor, como suporte de sintaxe para diversas linguagens, snippets, temas e outros.

![images/Untitled%2027.png](images/Untitled%2027.png)


# Live Share (Extensão Oficial)

Com o LiveShare é possível colaborar, gratuitamente, o código. Igual a ideia do Google Docs.

Também disponível comunicação via chat e audio.

![images/Untitled%2028.png](images/Untitled%2028.png)

![images/Untitled%2029.png](images/Untitled%2029.png)

O LiveShare pode ser usado também em conjunto com a IDE "Visual Studio 2019"

![images/Untitled%2030.png](images/Untitled%2030.png)

Caso queira permitir acesso remoto ao Debugger

![images/Untitled%2031.png](images/Untitled%2031.png)


# Remote Development (Extensão Oficial)

Você pode acessar ambientes externos via SSH, Container e WSL.

![images/Untitled%2032.png](images/Untitled%2032.png)

## Exemplo SSH

Ativamos servidor SSH em uma máquina Linux e obtemos seu IP

![images/Untitled%2033.png](images/Untitled%2033.png)

Registramos a conexão no VS Code e conectamos.

![images/Untitled%2034.png](images/Untitled%2034.png)

![images/Untitled%2035.png](images/Untitled%2035.png)

Também é possível configurar o acesso com chave de acesso SSH

![images/Untitled%2037.png](images/Untitled%2037.png)

Primeiro geramos as chaves na nossa maquina (Exemplo Windows):

```powershell
ssh-keygen -t rsa -b 4096 -f %USERPROFILE%/.ssh/id_rsa-remote-ssh
```

E depois enviamos a chave publica para a máquina destino (Nesse exemplo, Ubuntu). Nesse exemplo, ela está salva no arquivo `~/.ssh/authorized_keys` .

Acesso feito, agora é possível, com facilidade, editar os arquivos da máquina linux, de dentro do nosso VS Code.

![images/Untitled%2038.png](images/Untitled%2038.png)

![images/Untitled%2039.png](images/Untitled%2039.png)

Podemos também, rodar códigos.

![images/Untitled%2040.png](images/Untitled%2040.png)

> Mais Informações:
> - [https://code.visualstudio.com/docs/remote/ssh](https://code.visualstudio.com/docs/remote/ssh)
> - [https://code.visualstudio.com/blogs/2019/10/03/remote-ssh-tips-and-tricks](https://code.visualstudio.com/blogs/2019/10/03/remote-ssh-tips-and-tricks)
> - [https://code.visualstudio.com/docs/remote/troubleshooting](https://code.visualstudio.com/docs/remote/troubleshooting)
> - [https://dev.to/dre4success/ssh-to-an-ec2-instance-from-vs-code-2707](https://dev.to/dre4success/ssh-to-an-ec2-instance-from-vs-code-2707)
> - [https://medium.com/@christyjacob4/using-vscode-remotely-on-an-ec2-instance-7822c4032cff](https://medium.com/@christyjacob4/using-vscode-remotely-on-an-ec2-instance-7822c4032cff)


# Debugger & Run

Embora o VS Code não seja uma IDE, é possível rodar diversas linguagens e o Debugger. A Maioria das linguagens de forma quase nativa, outras como C/C++, com um pouco de configuração.

![images/Untitled%2041.png](images/Untitled%2041.png)

![images/Untitled%2042.png](images/Untitled%2042.png)


# Indicações & Sugestões

## Configurações

![images/Untitled%2043.png](images/Untitled%2043.png)

Desmarque

![images/Untitled%2044.png](images/Untitled%2044.png)

Configure conforme gosto. Não interfere no código

![images/Untitled%2045.png](images/Untitled%2045.png)

![images/Untitled%2046.png](images/Untitled%2046.png)

![images/Untitled%2047.png](images/Untitled%2047.png)

![images/Untitled%2048.png](images/Untitled%2048.png)

![images/Untitled%2049.png](images/Untitled%2049.png)

![images/Untitled%2050.png](images/Untitled%2050.png)

![images/Untitled%2051.png](images/Untitled%2051.png)

Essa ultima configuração varia bastante de gosto. Quando ativada, ela gera uma "seleção visual" em todas as ocorrências da palavra onde se encontra o cursor. Eu prefiro que o Editor faça isso APENAS se eu tiver selecionado a palavra.

![images/Untitled%2052.png](images/Untitled%2052.png)

## Extensões Essenciais

### [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)

Ajuda a identificar os pares de chaves e parênteses com cores.

![images/Untitled%2053.png](images/Untitled%2053.png)

### [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)

Essa extensão coloriza o recuo na frente do seu texto alternando quatro cores diferentes em cada etapa.

![images/Untitled%2054.png](images/Untitled%2054.png)

### [Live Share Extension Pack](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare-pack)

Este pacote de extensão inclui tudo o que você precisa para começar a colaboração em tempo real, incluindo chat por áudio e texto integrado.

![images/Untitled%2055.png](images/Untitled%2055.png)

### [Remote Development Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)

Permite abrir qualquer pasta em um contêiner, em uma máquina remota ou no Windows Subsystem for Linux (WSL)

![images/Untitled%2056.png](images/Untitled%2056.png)

### [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync)

Permite sincronizar extensões, configurações e outros, entre diferentes instalações do VS Code.

![images/Untitled%2057.png](images/Untitled%2057.png)

OBS: Atualmente em testes, o VSCode está desenvolvendo funcionalidade similar. [https://code.visualstudio.com/docs/editor/settings-sync](https://code.visualstudio.com/docs/editor/settings-sync)

### [Trailing Spaces](https://marketplace.visualstudio.com/items?itemName=shardulm94.trailing-spaces)

Exibe espaços extras ao final da linha.

![images/Untitled%2058.png](images/Untitled%2058.png)

### [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)

Converte JSON em estruturas de dados

![images/Untitled%2059.png](images/Untitled%2059.png)

### [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml)

Suporte para o arquivo de configuração YAML

### [Better TOML](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml)

Suporte para o arquivo de configuração TOML

![images/Untitled%2060.png](images/Untitled%2060.png)

### [Test Explorer UI](https://marketplace.visualstudio.com/items?itemName=hbenl.vscode-test-explorer)

Esta extensão fornece uma interface de usuário extensível para executar seus testes no VS Code. Pode ser usado com qualquer Framework de teste se houver uma extensão correspondente de "Test Adapter".

![images/Untitled%2061.png](images/Untitled%2061.png)

### [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

Auto completa nomes de arquivos

### [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)

Várias funcionalidades interessantes para se trabalhar com Markdown

### [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)

Suporte a syntax de arquivo .env

![images/Untitled%2062.png](images/Untitled%2062.png)

### [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

Ajuda a manter estilos de codificação consistentes para vários desenvolvedores que trabalham no mesmo projeto em vários editores e IDEs.

Os arquivos EditorConfig são facilmente legíveis e funcionam bem com os sistemas de controle de versão. Arquivo exemplo: [https://editorconfig.org/](https://editorconfig.org/)

![images/Untitled%2063.png](images/Untitled%2063.png)

### [GistPad](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gistfs)

Permite gerenciar GistHub Gists dentro do editor. Você pode abrir, criar, excluir, editar, favoritar e clonar.

![images/Untitled%2064.png](images/Untitled%2064.png)

### [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)

![images/Untitled%2065.png](images/Untitled%2065.png)

### [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)

Adiciona Code Lens, Line Blame, Line Hovers, entre outros.

![images/Untitled%2066.png](images/Untitled%2066.png)

![images/Untitled%2067.png](images/Untitled%2067.png)

![images/Untitled%2068.png](images/Untitled%2068.png)

### [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) ou [.gitignore Generator](https://marketplace.visualstudio.com/items?itemName=piotrpalarz.vscode-gitignore-generator)

Permite criar gitignore completos e específicos por linguagem ou frameworks.

Arquivos exemplos disponivel tambem no repositorio oficial do Github: [https://github.com/github/gitignore](https://github.com/github/gitignore)

![images/Untitled%2069.png](images/Untitled%2069.png)

![images/Untitled%2070.png](images/Untitled%2070.png)

### [colorize](https://marketplace.visualstudio.com/items?itemName=kamikillerto.vscode-colorize)

Colore as marcações de Cor em arquivos de estilos, de acordo com a cor especificada.

![images/Untitled%2071.png](images/Untitled%2071.png)

### [Code Time](https://marketplace.visualstudio.com/items?itemName=softwaredotcom.swdc-vscode)

Métricas

![images/Untitled%2072.png](images/Untitled%2072.png)

## Temas

### [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

Ícones para Extensões e Arquivos.

Exemplo:

![images/Untitled%2073.png](images/Untitled%2073.png)

### [Monokai Night Theme](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-monokai-night)

![images/Untitled%2074.png](images/Untitled%2074.png)

### [2077 theme](https://marketplace.visualstudio.com/items?itemName=Endormi.2077-theme)

Cyberpunk 2077 inspired theme

![images/Untitled%2075.png](images/Untitled%2075.png)

### [Outrun](https://marketplace.visualstudio.com/items?itemName=samrapdev.outrun)

![images/Untitled%2076.png](images/Untitled%2076.png)

### [Shades of Purple](https://marketplace.visualstudio.com/items?itemName=ahmadawais.shades-of-purple)

![images/Untitled%2077.png](images/Untitled%2077.png)

### [Night Owl](https://marketplace.visualstudio.com/items?itemName=sdras.night-owl)

![images/Untitled%2078.png](images/Untitled%2078.png)

### [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)

![images/Untitled%2079.png](images/Untitled%2079.png)

### [Material Theme](https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme)

![images/Untitled%2080.png](images/Untitled%2080.png)

### [Winter is Coming Theme](https://marketplace.visualstudio.com/items?itemName=johnpapa.winteriscoming)

![images/Untitled%2081.png](images/Untitled%2081.png)

### Outras Opções

[https://vscodethemes.com/](https://vscodethemes.com/)
