# 🎬 MovieCity — Landing Page

## 🎯 Objetivo da atividade

O objetivo desta atividade é desenvolver uma landing page para uma plataforma fictícia de streaming chamada MovieCity, utilizando React, Vite, JavaScript e CSS. A proposta é colocar em prática os conhecimentos de desenvolvimento front-end, trabalhando com a criação de componentes, a organização do código, a estilização de interfaces e a adaptação de páginas para diferentes tamanhos de tela.

Durante o desenvolvimento, são explorados conceitos importantes do React, como a componentização da interface e o uso do hook `useState` para controlar a abertura e o fechamento do menu de navegação em dispositivos móveis. Também são utilizados recursos do CSS, como Flexbox, CSS Grid, media queries e efeitos de transição, para construir uma interface organizada e responsiva.

A página apresenta um cabeçalho com o nome MovieCity, links de navegação, um botão de Login, uma área de apresentação e seis cards com imagens de filmes. Dessa forma, a atividade permite compreender como diferentes elementos podem ser separados em componentes e reunidos para formar uma única aplicação.

## 🛠️ Tecnologias utilizadas

- **React:** utilizado para criar e organizar a interface em componentes reutilizáveis.
- **Vite:** responsável pela criação do ambiente de desenvolvimento e pela execução da aplicação localmente.
- **JavaScript:** utilizado para implementar a lógica dos componentes e controlar as interações da interface.
- **CSS3:** responsável pela aparência da página, pelo posicionamento dos elementos, pelas animações e pela responsividade.
- **ESLint:** utilizado para identificar possíveis problemas e manter a organização do código.

## ✨ Funcionalidades desenvolvidas

- Cabeçalho com a identidade visual da plataforma MovieCity.
- Menu de navegação com as opções Filmes, Categoria, Sobre e Contato.
- Botão de Login na parte superior da página.
- Área principal com um texto de apresentação e um botão Mais.
- Exibição de seis cards com pôsteres de filmes.
- Efeito visual nos cards ao passar o cursor sobre eles.
- Menu hambúrguer para facilitar a navegação em telas menores.
- Layout responsivo para computadores, tablets e celulares.

Os botões e links fazem parte da interface visual e não possuem, necessariamente, funcionalidades completas de autenticação ou navegação para outras páginas.

## 📋 Pré-requisitos

Antes de executar o projeto, é necessário ter instalado no computador:

- **Node.js:** versão 20.19 ou superior, ou 22.12 ou superior.
- **npm:** gerenciador de pacotes instalado junto com o Node.js.
- **Visual Studio Code** ou outro editor de código de sua preferência.
- **Navegador web:** como Google Chrome, Microsoft Edge ou Mozilla Firefox.

Para verificar se o Node.js e o npm estão instalados corretamente, abra o terminal e execute:

```bash
node -v
npm -v
```

Se os comandos retornarem os números das versões instaladas, será possível prosseguir com a execução.

## 🚀 Como baixar e executar o projeto

### 1. Baixar os arquivos

Faça o download do projeto disponibilizado no repositório ou em formato ZIP. Caso tenha baixado um arquivo compactado, extraia seu conteúdo para uma pasta do computador.

### 2. Abrir o projeto

Abra o Visual Studio Code, selecione a opção **Arquivo → Abrir Pasta** e escolha a pasta do projeto MovieCity.

Em seguida, abra o terminal integrado em **Terminal → Novo Terminal**.

Certifique-se de que o terminal está na pasta que contém o arquivo `package.json`.

### 3. Instalar as dependências

No terminal, execute o comando:

```bash
npm install
```

Esse comando instala as bibliotecas e ferramentas necessárias para executar o projeto, conforme as dependências definidas no arquivo `package.json`.

A instalação precisa ser realizada antes da primeira execução e novamente caso o projeto seja baixado em outro computador.

### 4. Executar a aplicação

Após a instalação das dependências, execute:

```bash
npm run dev
```

O Vite iniciará o servidor de desenvolvimento e exibirá um endereço local no terminal, normalmente:

```text
http://localhost:5173
```

### 5. Acessar a página

Copie o endereço informado pelo Vite e abra-o no navegador. A página inicial do MovieCity será exibida e poderá ser visualizada enquanto o servidor estiver em execução.

**Importante:** não feche o terminal durante a utilização da aplicação. Para encerrar o servidor, volte ao terminal e pressione `Ctrl + C`.

## 📁 Organização dos arquivos

O projeto utiliza uma estrutura de pastas que separa os componentes, as imagens e os arquivos responsáveis pela execução da aplicação.

```text
MovieCity/
├── public/
├── src/
│   ├── assets/
│   │   └── imagens dos filmes
│   ├── components/
│   │   ├── Header.jsx
│   │   ├── Main.jsx
│   │   └── Home.jsx
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```

- **Header.jsx:** contém o cabeçalho, os links de navegação, o botão de Login e o menu hambúrguer.
- **Main.jsx:** apresenta o texto principal, o botão Mais e os cards dos filmes.
- **Home.jsx:** reúne os componentes Header e Main, formando a estrutura principal da página.
- **App.jsx:** importa os estilos globais e renderiza o componente Home.
- **index.css:** concentra os estilos visuais, o posicionamento dos elementos e as regras de responsividade.
- **main.jsx:** é o ponto de entrada que renderiza a aplicação React.
- **assets/:** armazena as imagens utilizadas nos cards dos filmes.
- **package.json:** contém as informações do projeto, suas dependências e os comandos disponíveis.

## 📱 Responsividade

Um dos objetivos da atividade é garantir que a interface funcione em diferentes tamanhos de tela.

Em computadores, o conteúdo principal é distribuído em duas colunas, com o texto de apresentação de um lado e os cards dos filmes do outro. Em telas menores, essas colunas são empilhadas verticalmente, o menu tradicional dá lugar ao menu hambúrguer e os cards passam a ser exibidos em duas colunas nos celulares.

Essas adaptações são realizadas com media queries no CSS, permitindo ajustar os espaçamentos, os tamanhos das fontes e as dimensões dos elementos conforme a largura da tela.

Para testar a responsividade, abra as ferramentas de desenvolvedor do navegador com `F12` e ative o modo de visualização para dispositivos móveis com `Ctrl + Shift + M`.

## 🧪 Comandos adicionais

Além do comando utilizado para iniciar a aplicação, o projeto disponibiliza outros comandos:

| Comando | Finalidade |
|---|---|
| `npm run dev` | Inicia o servidor de desenvolvimento. |
| `npm run build` | Gera os arquivos otimizados para produção na pasta `dist/`. |
| `npm run preview` | Permite visualizar localmente a versão de produção gerada. |
| `npm run lint` | Verifica possíveis problemas no código utilizando o ESLint. |

Para conferir se o projeto pode ser preparado para produção, execute:

```bash
npm run lint
npm run build
```

## 📌 Considerações finais

A atividade MovieCity proporciona uma experiência prática de desenvolvimento front-end, permitindo aplicar conceitos de React, JavaScript e CSS na construção de uma página web. O projeto também reforça a importância da componentização, da organização dos arquivos e da responsividade para criar interfaces que se adaptem a diferentes dispositivos.

Além disso, a estrutura desenvolvida pode ser utilizada como base para futuras melhorias, como a inclusão de informações sobre os filmes, a integração com uma API para carregar títulos dinamicamente e a implementação de funcionalidades reais para os botões e links da plataforma.
