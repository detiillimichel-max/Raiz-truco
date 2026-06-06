# 🃏 Raiz-truco

Truco Paulista , feito em HTML, CSS e JavaScript puro. Jogue contra o computador com regras oficiais, manilhas com desempate por naipe e sistema de truco.

**Repositório:** `detiillimichel-max / Raiz-truco`

---

## 🎮 Como Jogar

1. Abra o `index.html` no navegador ou acesse via GitHub Pages
2. Clique em uma das suas 3 cartas para selecionar
3. Clique em **Jogar**
4. Quem vence a rodada começa a próxima
5. Primeiro a fazer 12 pontos vence a partida

### Controles
- **Jogar**: Joga a carta selecionada
- **Truco!**: Pede truco na 1ª rodada
- **Aceitar / Correr**: Responde ao truco do adversário
- **Nova Partida**: Zera o placar e reinicia

---

## 📜 Regras Implementadas

### Baralho e Distribuição
- Baralho de 40 cartas. Naipes: ♥ ♦ ♠ ♣
- Ordem de força base: **4 < 5 < 6 < 7 < Q < J < K < A < 2 < 3**
- 3 cartas para cada jogador + 1 Vira
- A carta seguinte à Vira vira Manilha

### Manilhas
- As 4 cartas do valor da manilha são as mais fortes do jogo
- Desempate entre manilhas por naipe:
  **Paus ♣ > Copas ♥ > Espadas ♠ > Ouros ♦**
- Manilhas são marcadas com ⭐ no jogo

**Exemplo:** Vira = 6 ♠ → Manilha = 7. Logo 7♣ é a carta mais forte.

### Vitória da Mão
Mão é melhor de 3 rodadas:
1. 2 rodadas vencidas = ganha a mão
2. **Vantagem da primeira:** quem vence a 1ª rodada leva a mão se a 2ª empatar
3. 1ª rodada empata → quem vencer a 2ª leva a mão
4. Cada um venceu uma → 3ª rodada decide. Empate na 3ª = mão empatada, ninguém pontua

### Pontuação do Truco
- Mão normal = 1 ponto
- Truco aceito = 3 pontos
- Seis = 6 pontos
- Nove = 9 pontos
- Doze = 12 pontos

O computador aceita truco com 60% de chance. Se correr, quem pediu ganha os pontos.

### Início das Rodadas
- A mão é alternada: uma você começa, na próxima o computador começa
- Dentro da mão, quem vence a rodada começa a próxima

---

## 📁 Estrutura do Projeto
# Raiz-truco
