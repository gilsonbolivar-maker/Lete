# Lete Diedrichs — site

Site institucional de **Lete Diedrichs**: artista plástica, muralista e professora de canto.

Página única, estática, em HTML e CSS puros — sem build, sem dependências, sem JavaScript.
O site não faz nenhuma requisição a servidores externos: tudo que ele precisa está aqui dentro.

## Estrutura

```
index.html            página completa (estilos no topo do próprio arquivo)
assets/img/           fotos usadas nas seções
assets/fonts/         tipografia, servida pelo próprio site
```

### Seções

| Âncora        | Conteúdo                                       |
| ------------- | ---------------------------------------------- |
| `#sobre`      | Apresentação e as quatro áreas de atuação      |
| `#muralista`  | Galeria de murais e arte em parede             |
| `#canto`      | Aulas de canto presenciais                     |
| `#familia`    | Família & arte                                 |
| `#pensamento` | Cartão com a frase que a Lete carrega          |
| `#contato`    | Chamada final e redes sociais                  |

## Ver o site

Abra o `index.html` no navegador — não há nada para instalar.
Para ver exatamente como fica publicado, aponte qualquer servidor de arquivos
estáticos para a raiz do repositório.

## Publicar

A raiz do repositório já é a raiz do site. Basta enviar os arquivos para a
hospedagem: não existe etapa de compilação, nem geração de arquivos.

## Detalhes

- **Tipografia:** Bricolage Grotesque nos títulos, Work Sans no texto corrido e
  Caveat nos trechos manuscritos. Os arquivos ficam em `assets/fonts/`.
- **Cores:** paleta "Bossa" em variáveis CSS, definida uma única vez no bloco
  `:root` do `index.html`. Tema claro e escuro automáticos conforme a preferência
  de quem visita, com a possibilidade de forçar um deles pelo atributo
  `data-theme` no `<html>`.
- **Layout** responsivo em grid e flexbox; respeita `prefers-reduced-motion`.
- Imagens abaixo da dobra carregam sob demanda.

---

Site desenvolvido por [Pixel Nexo](https://www.pixelnexo.com.br).
