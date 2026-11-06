# ☆ meu-site

Meu perfil pessoal em uma página só: criativa, interativa e que muda de cor conforme o interesse que a gente escolhe.

Feito com **HTML, CSS e JavaScript puro**, sem frameworks e sem instalar nada.


## ✨ O que tem na página

- **Meus interesses** (Música, Cozinhar, Passeios e Programação): ao escolher um, a página inteira muda de cor e mostra o conteúdo daquele interesse:
  - Música: álbum favorito e link para ouvir.
  - Cozinhar: fotos dos pratos que eu fiz.
  - Passeios: fotos dos lugares que visitei, com legenda.
  - Programação: atalho para a seção de projetos.
- **Sobre mim**.
- **Meus projetos**: cartões com os projetos que desenvolvi, com tecnologias e link para o repositório.
- **Projetos do curso de Git**: as atividades que fiz durante o curso.
- **Vamos conversar**: contatos que se copiam com um toque.
- **Tema claro e escuro** pelo botão ☾ / ☀ no canto da tela.
- Brilhos ao clicar ✦ ♡ e animações suaves.

## 🎨 Cores que se adaptam

Cada interesse tem uma paleta de 4 cores. A partir dela, o script calcula sozinho as cores dos cartões, dos textos e dos botões, para que o texto fique sempre legível. O texto principal mantém contraste mínimo de 7:1 e os demais, de 4,5:1, seguindo as recomendações de acessibilidade (WCAG).

A página também respeita quem prefere menos movimento (`prefers-reduced-motion`) e funciona bem no celular.

## 🛠️ Tecnologias

- HTML5
- CSS3 (variáveis CSS, grid, flexbox e `@property` para a transição do fundo)
- JavaScript (sem bibliotecas)
- Fontes [Fraunces](https://fonts.google.com/specimen/Fraunces) e [Figtree](https://fonts.google.com/specimen/Figtree), pelo Google Fonts

## 📁 Estrutura

```
meu-site/
├── index.html   # estrutura da página e o JavaScript
├── style.css    # todo o visual
├── fotos/       # imagens usadas nos interesses
└── README.md
```

## 🚀 Como rodar

1. Clone o repositório:
   ```bash
   git clone https://github.com/marisxzh/meu-site.git
   ```
2. Abra a pasta e dê dois cliques no `index.html` (ou arraste o arquivo para o navegador).

Não precisa de servidor nem de instalação. Para as fontes aparecerem, é preciso estar conectada à internet. Sem conexão, o navegador usa fontes padrão.

## 🌐 Publicar no GitHub Pages

1. No repositório, vá em **Settings → Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch**.
3. Selecione a branch `main` e a pasta `/ (root)` e salve.
4. Depois de alguns minutos, o site fica em `https://marisxzh.github.io/meu-site/`.

## ✏️ Como personalizar

Tudo fica no `<script>` do `index.html`:

| O que mudar | Onde |
|---|---|
| Cores de cada interesse | lista `paletas` (4 cores por paleta: fundo 1, fundo 2, destaque e destaque 2) |
| Textos, fotos, álbum e links dos interesses | lista `interests` |
| Projetos | lista `projetos` |
| Projetos do curso de Git | lista `projetosGit` |
| E-mail, Instagram e GitHub | lista de contatos, no bloco `/* Contatos */` |
| Palavras que se digitam no topo | lista `words` |

As fotos ficam na pasta `fotos/`. Se uma imagem não for encontrada, a página mostra um emoji no lugar, então nada quebra.

## 👩‍💻 Autora

**Mariana**, estudante de Engenharia de Computação.
GitHub: [@marisxzh](https://github.com/marisxzh)
