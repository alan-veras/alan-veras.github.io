# alan-veras.github.io

Landing page pessoal de links. Preto e branco, com um grafo de rede 3D interativo (Three.js) de fundo.

Publicada em <https://alan-veras.github.io>.

## Estrutura

- `index.html` — página inteira (HTML, CSS e a cena 3D, tudo num arquivo só)
- `.nojekyll` — desliga o processamento Jekyll do GitHub Pages

## Rodar localmente

```bash
python3 -m http.server 8000
```

Depois abre <http://localhost:8000>.

## Editar os links

Todos os links ficam dentro do bloco `<nav>` no `index.html`. Cada um é um `<a class="link">` com um ícone SVG inline.
