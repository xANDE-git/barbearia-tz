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
4. Publicar: repositório no GitHub + Cloudflare Pages ligado ao Git, como nos outros sites (`barbearia-tz-<versao>-prototipo-xandedev.pages.dev`, um projeto por versão apontando para a pasta dela).
