# Barbearia TZ (São José da Lapa)

Site feito de graça para um amigo do Xande, para portfólio. O dono ainda não sabe que o site está sendo feito. Três protótipos para escolher; nada foi publicado.

Para ver: abrir o `index.html` de cada pasta no navegador.

| Pasta | Estilo | Fontes |
|---|---|---|
| `1-tradicao/` | A "Tradição" que o Xande gostou, agora em preto, branco e amarelo (sem o verde). Papel claro com moldura dupla, ornamentos e poste de barbeiro | Playfair Display + Work Sans |
| `2-raio/` | O "Raio" repaginado: foto de fundo, quadro de preços preto sobre amarelo, listras da fachada, aba "Agendar" e botão de WhatsApp | Anton + Barlow |
| `3-clube/` | Nova, baseada nos sites de referência do vídeo (La Mafia, Barbearia do Zé, Clube da Barba, Barber Shop NYC): topo com carrossel de fotos, títulos em versalete serifado, cartões de serviço sobre foto, aba lateral "Agendar" | Cinzel + Lato |

As versões "Ébano e Ouro" e "Claro" foram descartadas e estão em `Sites/_arquivo/Barbearia TZ - versoes descartadas/`.

Todos têm: faixa de protótipo, `noindex`, selo "Aberto agora / Fechado agora" pelo horário do AppBarber, tabela de serviços com valor normal e "com o TZ", galeria ou cartões de serviço, apresentação, horários (o dia de hoje fica destacado), endereço com mapa, dúvidas com animação, botões de agendar (AppBarber) e WhatsApp. Fontes hospedadas na própria pasta, sem Google Fonts. Respeitam `prefers-reduced-motion`. Testados em 375px e 1280px, sem rolagem lateral.

## De onde vieram os dados

- **Endereço, horários, serviços, preços, formas de pagamento, nota 5,0 e o texto de propósito:** página do AppBarber (https://sites.appbarber.com.br/barbeariatz), consultada em 08/11/2026.
- **"+200 avaliações de 5 estrelas":** post do Instagram da barbearia (@el___tz).
- **WhatsApp (31) 99813-2953 e Instagram @el___tz:** perfil e AppBarber.

## Fotos

- **Foto real da barbearia (única):** os dois na porta da loja, recorte do vídeo de tela do Xande. O telefone da placa foi coberto com uma tarja (estava cortado e parecia outro número). As demais fotos tiradas do Instagram foram removidas por estarem borradas.
- **Fotos de banco (Unsplash, licença que permite uso comercial), todas marcadas "Imagem ilustrativa" no site.** Cópias em `_fotos-banco/`:
  - `cadeira-tijolo.jpg`: Nathon Oski, https://unsplash.com/photos/EW_rqoSdDes
  - `tesoura.jpg`: Nate Johnston, https://unsplash.com/photos/tgPrIYnW3g4
  - `cliente-cadeira.jpg`: Allef Vinicius, https://unsplash.com/photos/IvQeAVeJULw
  - `secador.jpg`: delfina pan, https://unsplash.com/photos/wJoB8D3hnzc
  - `ferramentas.jpg`: Andrea Donato, https://unsplash.com/photos/MNu0n-3BIKs
  - `cadeira-preta.jpg`: Joshua Lawrence, https://unsplash.com/photos/dU6eE_j2My8
  - `luminarias.jpg`: Jason Leung, https://unsplash.com/photos/2seUdPQNy_I
  - `poltronas.jpg`: autor "T", https://unsplash.com/photos/fa0DqQ91dWU
- Quando o dono mandar fotos próprias (a barbearia, os cortes, a equipe), elas substituem as de banco.

## Pendências para confirmar com o dono

- Se os preços do AppBarber estão atualizados e o que significa "com o TZ" (assumi: atendimento feito pelo próprio TZ, valor maior).
- Domingo e segunda: o app não lista, o site mostra "Fechado". Confirmar.
- Fotos próprias de boa qualidade e autorização para usar as do Instagram.
- Logo em arquivo (o site usa um "TZ" com raio redesenhado em SVG, parecido com o da loja, não o arquivo original).
- Nomes dos barbeiros, se ele quiser mostrar a equipe. Ficaram de fora: "Estamos contratando" (a pedido), curso de barbeiro, promoções do panfleto.
- Assinaturas e pacotes: o app tem, mas não achei os valores; o site só diz que existem.

## Decisões

- 08/11/2026: o clima do negócio (clássico, premium, jovem, uniformizado) fica no design e **não** vira frase no site. Pedido do Xande: escrever isso fica clichê.
- 08/11/2026: três versões seguem a identidade (preto, branco, amarelo do raio). O verde da Tradição saiu porque a identidade dele já é preta.
- 08/11/2026: depois da primeira rodada o Xande descartou duas versões e pediu mais base nos sites de referência e menos "cara de IA": sem slogans de efeito, com fotos reais e de banco, aba lateral de agendar e botão de WhatsApp como nos sites do vídeo.
- 08/11/2026: sem duração dos serviços (os minutos do AppBarber estão inconsistentes).

## Antes de ir para o ar de verdade

1. Escolher a versão e combinar com o dono.
2. Trocar as fotos de banco pelas do dono e confirmar preços, horários e domingo/segunda.
3. Tirar a faixa de protótipo e o `noindex` (meta, `robots.txt` e `_headers`).
4. Publicar: repositório no GitHub + Cloudflare Pages ligado ao Git, como nos outros sites (`barbearia-tz-<versao>-prototipo-xandemartinsc.pages.dev`, um projeto por versão apontando para a pasta dela). Endereço final: https://barbeariatz.com.br/.

## Rodada 3 (08/11/2026): o cliente escolheu o Clube

- O dono gostou mais da versão `3-clube/`. Ajustes feitos só nela, ainda **não enviados** ao GitHub:
  - Card "Cuidados": trocada a foto (aparecia um funcionário que não trabalha lá) por uma de cliente com toalha no rosto, sem ninguém identificável. Foto de banco: https://unsplash.com/photos/vu1KtfyVO1A (`_fotos-banco/toalha-cliente.jpg`). O `secador.jpg` saiu do Clube.
  - Pix incluído nas formas de pagamento (dinheiro, Pix, crédito e débito).
  - Comodidades: Wi-Fi, ar-condicionado e "fácil de estacionar por perto (sem estacionamento próprio)".
  - Botão "Ver no Google Maps" aponta para a página do Google da barbearia: https://share.google/RdSmT7UBtuFVxTPrl
  - Equipe: o texto diz que são três barbeiros, com o Arthur TZ como dono. "Com o TZ" passou a explicar que é o atendimento do Arthur TZ.
- Respostas do Xande que mudaram as pendências: tem corte infantil (falta valor), tem assinatura (falta como funciona), a equipe é o Arthur TZ + dois barbeiros (falta nome). Perguntas para o dono em `PERGUNTAS-PARA-O-DONO.md`.
- As versões 1 e 2 continuam no ar e no repositório como estavam.

## SEO da versão no ar (18/11/2026)

A versão `3-clube/` é a que está em https://barbeariatz.com.br/. Nela foram removidos o `noindex` (meta, cabeçalho `X-Robots-Tag` e `Disallow` do `robots.txt`) e acrescentados canonical, `og:url`, imagem de compartilhamento com endereço completo, JSON-LD `HairSalon` (endereço, telefone, horário, pagamento, sem `aggregateRating`) e sitemap com o domínio real. As versões `1-tradicao/` e `2-raio/` continuam `noindex`, por serem só protótipos. O endereço `pages.dev` da Clube aponta o canonical para o domínio real.

Otimização de imagens e dados estruturados (18/11/2026, ainda sem publicar): fotos da `3-clube/img/` convertidas para WebP (topo em 1400 px; peso total das imagens de 2,4 MB para 1,3 MB; os JPG originais continuam na pasta), JSON-LD ampliado com serviços/preços (iguais aos da página), equipe e ação de agendamento, JSON-LD de perguntas frequentes, e o carrossel deixou de usar `role="tablist"` (acessibilidade 95 para 100).
