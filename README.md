# Gabriel Aguiar | Portfólio

Portfólio pessoal do **Gabriel Aguiar**, Systems Engineer na Minsait (Java, Oracle, SQL e PL/SQL), com apresentação, stack e projetos.

- **Site publicado:** https://imaguiar.com.br/
- **GitHub:** [Raiugami](https://github.com/Raiugami)
- **LinkedIn:** [gabrielaesaguiar](https://www.linkedin.com/in/gabrielaesaguiar/)
- **Instagram:** [@aguiar.py](https://instagram.com/aguiar.py)

## Sobre o projeto

Página única (one-page), com visual escuro e moderno, responsiva. Seções: apresentação, sobre, stack, projetos e contato.

Projetos em destaque: Organização financeira, Relatório de protocolos, Meus dias, testes com Robot Framework e dois sites feitos para clientes:
- Isabella Garcia | Estética: https://isabella.imaguiar.com.br/
- Patrícia Lima | Harmonia das Orelhas: https://patricia.imaguiar.com.br/

## Tecnologias

- HTML5, CSS3 e JavaScript puros em um único arquivo, sem build e sem dependências
- Google Fonts: Inter, Space Grotesk e JetBrains Mono
- Hospedagem: GitHub Pages, com domínio próprio (`CNAME`)

## Estrutura de pastas

```
.
├── index.html   # página única (estilos e scripts embutidos)
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
