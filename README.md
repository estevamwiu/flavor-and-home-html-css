# Sabor & Casa

Site de receitas pessoal feito com HTML e CSS puros, sem frameworks nem JavaScript. A página apresenta algumas das receitas favoritas do autor, com foto e uma descrição curta de cada prato.

Acesse online: https://flavor-and-home-html-css.vercel.app/

## Sobre o projeto

O Sabor & Casa nasceu como um exercício de construção de página estática, com foco em estrutura semântica, estilização com CSS e layout responsivo. O conteúdo é simples de propósito: uma página inicial com apresentação e três receitas, uma para cada momento do dia.

## O que tem na página

- Cabeçalho com a navegação (Receitas, Sobre mim e Contato)
- Seção de boas-vindas com o título "Desfrute de minhas receitas favoritas"
- Três cards de receita, cada um com imagem e descrição:
  - Lanche saudável: tigela com frutas frescas, sementes e chia
  - Pequeno almoço para manhãs sem pressa: sanduíche natural com salada fresca
  - Jantar: prato principal com acompanhamentos saudáveis
- Rodapé com direitos autorais e links de Política de Privacidade e Termos de Uso

Os links do menu e do rodapé ainda são placeholders (`#`), então só a página inicial existe por enquanto.

## Tecnologias

- HTML5
- CSS3
- Deploy na Vercel

## Estrutura de pastas

```
.
├── index.html
├── img/
│   ├── lanche-saudavel.jpg
│   ├── almoco-saudavel.jpg
│   └── jantar-saudavel.jpg
└── (arquivo CSS)
```

## Como rodar localmente

Não há dependências nem etapa de build. Basta clonar o repositório e abrir o `index.html` no navegador:

```bash
git clone https://github.com/estevamwiu/flavor-and-home-html-css.git
cd flavor-and-home-html-css
```

Se preferir um servidor local, qualquer um serve, por exemplo a extensão Live Server do VS Code.

## Deploy

O site é publicado na Vercel. Como é um projeto estático, basta importar o repositório na Vercel e fazer o deploy com as configurações padrão. A cada push na branch principal, o site é atualizado automaticamente.


## Autor

William, estudante de Análise e Desenvolvimento de Sistemas na Fatec Itu.

GitHub: [@estevamwiu](https://github.com/estevamwiu)
