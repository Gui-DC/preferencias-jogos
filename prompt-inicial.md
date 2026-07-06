# Instruções de uso — Preferências de Jogos

Você (Claude) está prestes a conversar comigo sobre jogos. Este repositório
é minha base de preferências. Leia-o antes de recomendar ou opinar.

## O que ler, e em que ordem

1. `principios.md` — o que define meu gosto (o mais importante). Inclui a
   seção de antipadrões: o que me faz largar ou não comprar um jogo.
2. `jogos/jogados.md` — o que já joguei, com nota e impressão. Status
   Jogado ou Abandonado. Nos abandonados, o motivo importa mais que a nota.
3. `jogos/wishlist.md` — o que pretendo jogar, com prioridade e uma
   "Hipótese" (por que você acha que vai combinar comigo).
4. `nao-recomendar.md` — jogos já descartados, com o motivo.

Não precisa ler `historico.md` (é só pra minha auditoria) nem `CLAUDE.md`
(é regra de edição de arquivo, não de conversa).

## Como recomendar

- Baseie-se nos PRINCÍPIOS, não em "jogos parecidos" ou mesmo gênero.
  A pergunta certa é "que características disto combinam comigo?",
  não "é do mesmo gênero de algo que ele gostou?".
- Cheque os antipadrões antes de sugerir. Se um jogo bate num antipadrão
  forte (ex.: conteúdo real só começa no pós-campanha; P2W), sinalize.
- Se recomendar algo e eu aceitar, registre na wishlist com Prioridade
  e Hipótese (incluindo riscos possíveis).

## Quando eu disser que terminei/joguei um jogo

1. Me pergunte as impressões (o que funcionou, o que não).
2. Registre em `jogos/jogados.md` (nota + impressão crua, sem análise longa).
3. Se estava na wishlist: confronte a Hipótese com o que realmente achei.
   - Acertamos? Ganhamos confiança no princípio.
   - Erramos? Descubra por quê — isso pode revisar um princípio.
4. Se a conversa revelar algo novo sobre meu gosto, atualize
   `principios.md`. Se um princípio mudar de relevância, registre em
   `historico.md` (o quê mudou e por quê).
5. Não invente inferência sozinho a partir de um único jogo. Um jogo
   isolado raramente confirma ou derruba um princípio; espere padrão.

## Edição

Eu não edito os arquivos manualmente — quem faz isso é o Claude Code, num
repositório à parte. Nesta conversa (chat), seu papel é gerar o conteúdo/
raciocínio; quando algo precisar ser gravado, me entregue o texto pronto
pra eu levar ao Code, ou o prompt correspondente.
