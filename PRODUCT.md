# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Casal e círculo próximo (família, amigos) que abrem a página no celular ou na TV para ver e compartilhar a selfie espacial. Contexto: orgulho, curiosidade e “isso é real?”.

## Product Purpose

Apresentação HTML de uma única foto oficial Space Selfie (Lucas + namorada no SAT GUS), com narrativa do projeto Mark Rober / CrunchLabs, explicação prática do funcionamento e provas visuais de autenticidade (não é IA). Sucesso: o visitante entende o processo e confia que a imagem veio do espaço.

## Positioning

Uma página pessoal que transforma a entrega oficial de uma Space Selfie em um relato verificável da missão. A prova central é o material real recebido do SAT GUS, contextualizado por fontes e hardware reais — não por imagens geradas ou uma simulação apresentada como captura de órbita.

## Operating Context

Uma página estática em português, consultada e compartilhada principalmente em celular ou TV. A experiência percorre a missão, o processo de envio, a linha do tempo pessoal, a foto final e referências externas; inclui uma visualização 3D controlada por rolagem para explicar o hardware.

## Capabilities and Constraints

- Implementação em HTML estático, sem autenticação, formulário ou backend.
- O modelo interativo usa Three.js, GSAP e WebGL; pessoas com `prefers-reduced-motion` não recebem a animação 3D.
- O conteúdo deve permanecer em português, factual e claramente separado de material promocional de terceiros.
- A página não representa CrunchLabs, Mark Rober, Tyvak, Redwire, Google ou SpaceX; as marcas citadas pertencem aos respectivos titulares.

## Brand Commitments

Tom cósmico, íntimo e verificável: documentação de missão com o carinho de um álbum de casal. A foto oficial, o display CrunchLabs/Google Pixel, o SAT GUS e a curvatura da Terra são evidências a preservar, sem exageros ou alegações inventadas.

## Evidence on Hand

- `assets/nossa-selfie-espacial.jpg`: foto oficial recebida, com a selfie exibida no SAT GUS e a Terra ao fundo.
- `assets/sat-gus-tyvak.jpg` e `assets/sat-gus-patch.png`: referências visuais do satélite e da missão.
- `assets/earth-orbit.mp4`, `assets/earth-from-space.jpg` e `assets/earth-blue-marble.jpg`: imagens de apoio da Terra; a proveniência do vídeo está em `assets/CREDITS-VIDEO.md` (NASA/GSFC, domínio público).
- Os links no site para Space Selfie/CrunchLabs, Tyvak, Redwire, Mark Rober e N2YO são as referências externas de apoio. Não há depoimentos, métricas ou certificações próprias a inventar.

## Product Principles

1. A foto real do SAT GUS é a prova central; o restante explica e autentica.
2. O hardware e o processo devem permanecer compreensíveis: display, câmera, órbita e entrega da imagem.
3. Fatos verificáveis e links oficiais têm prioridade sobre hype ou enfeites sem substância.
4. A experiência precisa continuar compreensível e compartilhável em uma tela pequena, sem perder a legibilidade da selfie.

## Accessibility & Inclusion

WCAG AA alvo; contraste alto em fundo escuro; `prefers-reduced-motion`; textos em português; alt text descritivo nas imagens.
