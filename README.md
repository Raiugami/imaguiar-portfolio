# Gabriel Aguiar | Portfólio

Portfólio pessoal do **Gabriel Aguiar**, desenvolvedor, apresentando o serviço de criação de sites para profissionais de atendimento e os projetos publicados.

- **Site publicado:** https://imaguiar.com.br/
- **GitHub:** [Raiugami](https://github.com/Raiugami)
- **LinkedIn:** [gabrielaesaguiar](https://www.linkedin.com/in/gabrielaesaguiar/)
- **Instagram:** [@aguiar.py](https://instagram.com/aguiar.py)

## Sobre o projeto

Página única (one-page), com visual escuro e moderno, responsiva. Seções: apresentação, trabalhos publicados, o que está incluso no serviço, como funciona o processo e contato.

Projetos exibidos:
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

No `<script>` do final do `index.html`:

- `WHATSAPP`: número com DDI+DDD, só dígitos (ex.: `"5511999999999"`). Vazio, os botões de orçamento abrem o e-mail.
- `EMAIL`: e-mail de contato.
- `MENSAGEM`: texto pronto do orçamento.

## Como rodar localmente

Abra o `index.html` no navegador, ou use um servidor local:

```bash
python -m http.server 8000
```

Depois acesse http://localhost:8000.

## Publicação

Publicado pelo GitHub Pages a partir da branch `main`, pasta raiz, no domínio `imaguiar.com.br`. O DNS usa registros `A` apontando para o GitHub Pages.
