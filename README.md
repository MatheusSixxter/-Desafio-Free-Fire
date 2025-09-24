🎮 Mini Free Fire em C

Trabalho para Segundo Período da Faculdade Estácio - Matheus.
Simulação em texto inspirada no Free Fire, feita em linguagem C.
O jogador enfrenta inimigos (bots), pode atacar ou se curar, e vence quando elimina todos.
Se derrotar todos os inimigos, aparece o famoso grito “BOOYAH!”.

🎮 Como funciona

. O jogador começa com 100 de vida e pode causar até 20 de dano.

. Cada inimigo tem vida e força de ataque diferentes.

. Durante a batalha, o jogador pode:

1.Atacar (causando dano aleatório ao inimigo).

2.Curar-se (+15 de vida, limitado a 100).

. Os inimigos também atacam de forma aleatória.

. O jogo termina quando:

. O jogador perde toda a vida → GAME OVER.

. Todos os inimigos são derrotados → BOOYAH!

⚔️ Estrutura do código

.struct Personagem → Representa jogador e inimigos (nome, vida, ataque).

.atacar() → Função que calcula o dano e aplica no alvo.

.main() → Gerencia as batalhas, controle do jogo e interações.

▶️ Como compilar e executar

No terminal (Linux/Mac/WSL):

gcc freefire.c -o freefire
./freefire


No Windows (com MinGW instalado):

gcc freefire.c -o freefire.exe
freefire.exe

📚 Requisitos

Compilador C (GCC, MinGW ou outro compatível).

Console/terminal para rodar o executável.
