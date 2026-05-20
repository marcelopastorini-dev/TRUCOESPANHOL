# 🎴 Truco - Jogo Simples em HTML, CSS e JavaScript

Um protótipo de jogo de **Truco com baralho espanhol**, jogado contra uma IA simples.  
Feito para rodar direto no navegador, sem dependências externas.

---

## 🚀 Como jogar
- Abra o arquivo `index.html` no navegador.
- Você recebe **3 cartas** e joga contra a IA.
- Clique em uma carta para jogá-la.
- Use os botões para chamar **Truco, Envido, Flor, Contra Envido ou Contra Flor**.
- O resultado das rodadas e chamadas aparece no log.

---

## 📜 Regras implementadas
- **Truco**: decidido em melhor de 3 rodadas.  
  - Quem vencer 2 rodadas leva o truco (2 pontos).  
- **Envido**: soma de duas cartas do mesmo naipe + 20.  
  - Vencedor leva 2 pontos.  
- **Flor**: três cartas do mesmo naipe.  
  - Vencedor leva 3 pontos.  
- **Contra Envido / Contra Flor**: mesmas regras, mas chamadas diferentes.  

---

## 🃏 Hierarquia oficial das cartas
Do mais forte para o mais fraco:

1. **1 de Espadas (Ás de Espadas)**  
2. **1 de Bastos (Ás de Bastos)**  
3. **7 de Espadas**  
4. **7 de Ouros**  
5. **3 de qualquer naipe**  
6. **2 de qualquer naipe**  
7. **1 de Copas / 1 de Ouros**  
8. **12 (Rei)**  
9. **11 (Cavaleiro)**  
10. **10 (Valete)**  
11. **7 de Copas / 7 de Bastos**  
12. **6**  
13. **5**  
14. **4**

---

## 🎨 Visual
- Cartas estilizadas com símbolos:  
  - ♥ Copas  
  - ♠ Espadas  
  - ♦ Ouros  
  - ♣ Bastos  
- Fundo com textura de mesa de cartas para dar mais imersão.

---

## 📌 Objetivo
Este projeto é um protótipo didático para aprender lógica de jogos, manipulação de DOM e regras do Truco.  
Pode ser expandido para multiplayer, placar persistente e animações.

---

✨ Divirta-se jogando Truco diretamente no navegador!
