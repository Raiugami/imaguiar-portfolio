# Gabriel Aguiar | Portfólio

Portfólio pessoal do **Gabriel Aguiar**, Systems Engineer na Minsait (Java, Oracle, SQL e PL/SQL), com apresentação, stack e projetos.

- **Site publicado:** https://imaguiar.com.br/
- **GitHub:** [Raiugami](https://github.com/Raiugami)
- **LinkedIn:** [gabrielaesaguiar](https://www.linkedin.com/in/gabrielaesaguiar/)
- **Instagram:** [@aguiar.py](https://instagram.com/aguiar.py)

## Sobre o projeto

Página única (one-page), com visual escuro e moderno, responsiva. Seções: apresentação, números, sobre, experiência (linha do tempo e formação), stack, inteligência artificial, projetos e contato.

Projetos em destaque: Discordo (app de conversas com voz e vídeo), Organização financeira, Relatório de protocolos, Meus dias e dois sites feitos para clientes, em carrossel:
- Isabella Garcia | Estética: https://isabella.imaguiar.com.br/
- Patrícia Lima | Harmonia das Orelhas: https://patricia.imaguiar.com.br/

## Página /sites

Página de divulgação do serviço de criação de sites (`imaguiar.com.br/sites`), com vídeo de apresentação vertical, os sites criados (Isabella e Patrícia), o que está incluso, como funciona e botão de orçamento pelo WhatsApp. Sem preço, de propósito. O número do WhatsApp fica na constante `WHATSAPP` no final de `sites/index.html`.

## Tecnologias

- HTML5, CSS3 e JavaScript puros em um único arquivo, sem build e sem dependências
- Google Fonts: Inter, Space Grotesk e JetBrains Mono
- Hospedagem: GitHub Pages, com domínio próprio (`CNAME`)

## Estrutura de pastas

```
.
├── index.html   # página única (estilos e scripts embutidos)
├── sites/       # página de divulgação do serviço de sites
│   ├── index.html
│   ├── img/     # mockups dos sites criados (WebP)
│   └── video/   # apresentacao.mp4 (9:16) e poster.jpg
├── CNAME        # domínio imaguiar.com.br
└── README.md
```

## Como personalizar

No `<script>` do final do `index.html`, troque a constante `EMAIL`. Os cards de projeto ficam na seção `#projetos`.

## Como rodar localmente

Abra o `index.html` no navegador, ou use um servidor local:

```bash
python -m http.server 8000
```

Depois acesse http://localhost:8000.

## Publicação

Publicado pelo GitHub Pages a partir da branch `main`, pasta raiz, no domínio `imaguiar.com.br`. O DNS usa registros `A` apontando para o GitHub Pages.
