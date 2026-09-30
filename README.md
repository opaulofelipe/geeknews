# Geek News

Site editorial estático em HTML, CSS e JavaScript, pronto para GitHub Pages.

## Estrutura

- `index.html` — estrutura semântica e conteúdo da home.
- `styles.css` — layout responsivo, tipografia, estados, acessibilidade e animações.
- `script.js` — filtros, busca, menu mobile, matérias em modal e formulário demonstrativo.

## Paleta usada

Extraída da imagem enviada no briefing:

- `#1E104E` — roxo profundo
- `#452E5A` — roxo secundário
- `#FF653F` — coral
- `#FFC85C` — amarelo

## Conteúdo editorial real

As cinco matérias foram redigidas a partir de fontes reais e apontam para a referência original dentro de cada matéria:

- Filmes — Variety: trailer de *The Further Mis-Adventures of Cliff Booth* (22/09/2026).
- Séries — Variety: cancelamento de *Spider-Noir* após uma temporada (05/09/2026).
- Livros — Publishers Weekly: *Bruja’s Nest*, de Brenda LaTorre, entre os lançamentos destacados da semana de 28/09/2026.
- Quadrinhos — DC: lançamento de *DC/Marvel: The Cosmic Kiss Caper & Other Stories* (08/09/2026).
- Games — PlayStation Blog: State of Play de 03/09/2026 com mais de 30 jogos em duas apresentações.

## Imagens

As imagens são carregadas remotamente para manter o projeto leve e evitar redistribuição desnecessária de arquivos:

- Toni Pomar / Unsplash — cinema.
- Shixart1985 / Wikimedia Commons — televisão.
- You Le / Unsplash — biblioteca.
- PhotopiaCZ / Wikimedia Commons — loja de quadrinhos.
- Robert Torres / Unsplash — controle de videogame.

As imagens são ilustrativas; não são fotografias oficiais das obras noticiadas.

## Publicar no GitHub Pages

1. Envie `index.html`, `styles.css`, `script.js` e `README.md` para a raiz do repositório.
2. No GitHub, abra **Settings → Pages**.
3. Em **Build and deployment**, escolha **Deploy from a branch**.
4. Selecione a branch `main` e a pasta `/ (root)`.
5. Salve.

Não há PHP, banco de dados, build step ou dependências de npm.

## UX e acessibilidade

- HTML semântico e link “pular para conteúdo”.
- Foco visível para navegação por teclado.
- Alvos de toque com dimensão confortável.
- `prefers-reduced-motion` respeitado.
- Contraste pensado para WCAG AA.
- Layout responsivo sem reordenar semanticamente o conteúdo.
- Busca e filtros operáveis por teclado.
- Diálogos nativos com foco e tecla Esc do navegador.
