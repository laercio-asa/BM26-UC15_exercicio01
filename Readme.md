# AULA 01

## Extensões VSCode

- Auto Rename Tag
- Live Server
- Material Icon Theme
- Portuguese (Brazil) Language Pack

## Configurações - VSCode

- Arquivo / Salvamento Automático
- Editar / Quebra de Texto (opcional)

## Padrão de nomes de arquivos / pastas WEB

- sempre minusculo
- preferencialmente usar padrão kebak-case
- nunca usar espaço em branco

## Estrutura Básicas de pastas

📁 css

📁 js

📁 img

📄 index.html

🔵 Readme.md



## TAGs HTML

- html — Define o início e o fim do documento HTML. É o elemento que engloba toda a página.
- head — Contém informações e configurações da página que não fazem parte diretamente do conteúdo visual apresentado ao usuário.
- body — Contém todo o conteúdo que será apresentado na página para o usuário.
- header — Representa o cabeçalho de uma página ou de uma determinada seção. Pode conter informações introdutórias, identidade visual e navegação.
- nav — Representa uma área destinada à navegação. É utilizada principalmente para menus e conjuntos de links de navegação. 
- img — Representa uma imagem dentro da página. É um elemento que não possui conteúdo interno e utiliza atributos para indicar a imagem e sua descrição.
- a — Representa um link. É utilizada para permitir a navegação para outra página, arquivo, endereço, seção ou recurso.
- main — Representa o conteúdo principal da página. Deve conter a parte central e mais importante do conteúdo daquele documento.
- section — Representa uma seção temática de conteúdo. Serve para organizar o conteúdo da página em partes relacionadas.
- h1 ... h6 — Representam títulos e subtítulos em diferentes níveis hierárquicos. h1 representa o nível mais alto e h6 o nível mais baixo.
- p — Representa um parágrafo de texto em uma página HTML. É utilizada para organizar textos em blocos de conteúdo, separando um parágrafo de outro.


## Estrutura do Site Criado

```text
HTML
┌─ HEAD → informações da página
│    ├── META → configurações da página
│    ├── TITLE → título da página
└── /HEAD
┌── BODY → conteúdo visível
│    ┌── HEADER → cabeçalho
│    │    ┌── NAV → menu
│    │    │    ├── IMG → imagem
│    │    │    ├── A   → link
│    │    └── /NAV
│    └── /HEADER
│    ┌── MAIN → conteúdo principal
│    │    ┌── SECTION → seção da página
│    │    │    ├── H1 → título
│    │    │    ├── H6 → subtítulo
│    │    │    └── P  → texto
│    │    └── /SECTION
│    └── /MAIN
└── /BODY
/HTML
```