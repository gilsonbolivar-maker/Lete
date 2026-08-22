# Lete Diedrichs — site

Site institucional de **Lete Diedrichs**: artista plástica, muralista e professora de canto.

Página única, estática, em HTML e CSS puros — sem build, sem dependências, sem JavaScript.

## Estrutura

```
index.html            página completa (estilos inline no <head> da própria página)
assets/img/           fotos usadas nas seções
```

### Seções

| Âncora       | Conteúdo                                        |
| ------------ | ----------------------------------------------- |
| `#sobre`     | Apresentação e as quatro áreas de atuação       |
| `#muralista` | Galeria de murais e arte em parede              |
| `#canto`     | Aulas de canto presenciais                      |
| `#familia`   | Família & arte                                  |
| `#contato`   | Chamada final e redes sociais                   |

## Rodar localmente

Basta abrir o `index.html` no navegador. Para servir por HTTP:

```bash
python3 -m http.server 8000
# http://localhost:8000
```

## Publicar

Qualquer hospedagem de arquivos estáticos serve (GitHub Pages, Netlify, Cloudflare Pages,
Vercel): o diretório raiz do repositório já é a raiz do site, sem etapa de build.

## Detalhes técnicos

- Tipografia: Bricolage Grotesque, Work Sans e Caveat (Google Fonts).
- Paleta "Mural Tropical" em variáveis CSS, com tema claro e escuro automáticos
  (`prefers-color-scheme`) e possibilidade de forçar via `data-theme` no `<html>`.
- Layout responsivo com CSS Grid e Flexbox; respeita `prefers-reduced-motion`.
- Imagens abaixo da dobra usam `loading="lazy"`.

---

Site desenvolvido por [Pixel Nexo](https://www.pixelnexo.com.br).
