# Barbearia TZ

Site da Barbearia TZ, em São José da Lapa/MG. Feito sem cobrança, como trabalho de portfólio.

**No ar: https://barbeariatz.com.br/** (versão `3-clube/`)

## O que tem no repositório

| Pasta | Situação | Estilo |
|---|---|---|
| `3-clube/` | **Versão publicada** | Carrossel de fotos no topo, títulos serifados (Cinzel), cartões de serviço, aba lateral "Agendar" |
| `1-tradicao/` | Protótipo descartado | Papel claro com moldura dupla, em preto, branco e amarelo |
| `2-raio/` | Protótipo descartado | Foto de fundo, quadro de preços preto sobre amarelo |

Os protótipos 1 e 2 ficam só como histórico (`noindex`). Cada pasta é um site completo e independente.

## Como funciona

Site estático: HTML, CSS e um pouco de JavaScript, sem framework e sem build. O visitante vê serviços e preços, horários (com selo "Aberto agora / Fechado agora"), endereço com mapa e dúvidas frequentes. Os botões levam ao agendamento (AppBarber) e ao WhatsApp.

## Como foi feito

- **Direção:** escolhi o estilo a partir de sites de barbearia de referência e do que o dono preferiu entre as três versões.
- **Conteúdo:** endereço, horários, serviços e preços vêm da página da barbearia no AppBarber; as avaliações, do Instagram dela.
- **Código:** gerado com apoio do Claude Code, que eu revisei e ajustei. Testado em 375 px (celular) e 1280 px (computador).
- **Técnico:** fontes hospedadas no próprio site (sem Google Fonts), imagens em WebP, dados estruturados `HairSalon` (JSON-LD) para o Google, canonical e sitemap com o domínio real. Publicado no Cloudflare Pages.

## Fotos

Só uma foto é da barbearia. As demais são de banco (Unsplash, licença de uso livre) e aparecem como "Imagem ilustrativa" no site. Autores: Nathon Oski, Nate Johnston, Allef Vinicius, delfina pan, Andrea Donato, Joshua Lawrence, Jason Leung e outros listados em `_fotos-banco/`.

## Pendências

- Trocar as fotos de banco por fotos próprias da barbearia.
- Confirmar valores de corte infantil e assinatura, e os nomes da equipe.
