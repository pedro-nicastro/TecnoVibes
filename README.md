# TecnoVibes

Landing page responsiva sobre tecnologia, criatividade e colaboração. O projeto foi feito com HTML e CSS, sem dependências de frameworks.

## Prévia

A página apresenta a TecnoVibes em uma experiência de rolagem única, com navegação por seções, destaques, galeria, planos e formulário de contato.

## Recursos

- Layout adaptável para desktop e dispositivos móveis.
- Navegação por âncoras e menu compacto em telas menores.
- Galeria com imagens locais e carregamento sob demanda.
- Formulário de contato preparado para abrir o aplicativo de e-mail.
- Estados de foco visíveis, link para pular ao conteúdo e suporte à preferência por movimento reduzido.

## Como visualizar

Não é necessário instalar dependências. Abra `index.html` diretamente no navegador ou inicie um servidor HTTP local na raiz do projeto. Por exemplo, se você tiver o Python instalado:

```bash
python -m http.server 8000
```

Depois, acesse `http://localhost:8000`.

## Estrutura

```text
TecnoVibes/
├── assets/
│   ├── css/
│   │   └── style.css
│   └── img/
│       ├── tecnovibes-logo.svg
│       └── favicon.svg
└── index.html
```

## Personalização

- Edite o conteúdo e os links das seções em `index.html`.
- Ajuste cores, tipografia e comportamento responsivo em `assets/css/style.css`.
- Substitua as imagens dentro de `assets/img/` mantendo os nomes usados no HTML, ou atualize os caminhos correspondentes.
- A marca principal e o ícone da aba do navegador ficam em `assets/img/tecnovibes-logo.svg` e `assets/img/favicon.svg`.
- Atualize o endereço `contato@tecnovibes.com` no formulário para o e-mail real do projeto.
- As fontes DM Sans e Manrope são carregadas pelo Google Fonts; se não houver conexão, o navegador usa uma fonte sans-serif alternativa.

## Tecnologias

- HTML5
- CSS3
- Google Fonts

## Créditos

Projeto de Pedro Nicastro. As imagens e ilustrações ficam na pasta `assets/img/`.
