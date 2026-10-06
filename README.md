# Lulu Chorona vs Madame Trevosa

Jogo de luta em pixel art para 2 jogadores, que roda direto no navegador, no computador ou no celular.

**Jogar agora:** https://anacpgallotta-hue.github.io/lulu-vs-trevosa/

O mesmo link funciona no computador e no celular. A página percebe sozinha qual é o aparelho:

- **No computador**, joga pelo teclado: WASD de um lado e as setas do outro.
- **No celular**, deite a tela. Aparecem 4 botões de cada lado, um lado para cada jogadora.

## Modos de jogo

- **2 jogadores:** as duas pessoas no mesmo teclado ou no mesmo celular.
- **Contra o PC:** você escolhe se quer ser a Lulu ou a Trevosa e a dificuldade:
  - **Fácil:** o PC é lento e quase não desvia.
  - **Médio:** o PC joga direitinho.
  - **Difícil:** o PC é rápido e desvia bastante.

  Na guerra dos cliques, o PC clica cerca de 3 vezes por segundo no fácil, 4,5 no médio e 6 no difícil. Uma pessoa clicando rápido consegue ganhar em todos os níveis.

Vence quem ganhar 2 rounds. Cada round dura 90 segundos.

## Controles

A Madame Trevosa é ruiva, de olhos escuros e vestido roxo. A Lulu Chorona é loira, de olhos azuis e vestido rosa.

### Madame Trevosa (lado esquerdo)

| Teclado | Celular | Golpe | O que faz |
|---|---|---|---|
| `D` | BUNDADA | Bundada | Avança de costas e arremessa quem estiver na frente. |
| `A` | LINGUA PRESA | Língua presa | Gruda na Lulu, puxa e prende ela por um tempo. |
| `S` | GOLPE | Golpe | Voadora. Se o Magrelo estiver na frente, ela nocauteia ele primeiro. |
| `W` | PULO | Pular | Desvia do Biscoito e das lágrimas. |

### Lulu Chorona (lado direito)

| Teclado | Celular | Golpe | O que faz |
|---|---|---|---|
| `←` | MAGRELO | Magrelo, o guarda-costas | Corre até a Trevosa e dá socos. Fica na frente e segura a bundada e a língua. |
| `↓` | SALSICHA | Biscoito, o salsicha | Morde o calcanhar e deixa a Trevosa pulando de dor. |
| `→` | LAGRIMAS TOXICAS | Lágrimas tóxicas | Três lágrimas verdes que envenenam. |
| `↑` | PULO | Pular | Desvia da bundada, da língua e da voadora. |

O painel no alto da tela mostra o nome de cada golpe, a tecla e quanto falta para ele recarregar.

## Super golpe e guerra dos cliques

1. Cada golpe tem uma **barrinha** no painel de cima, que enche um pouco a cada uso.
2. Depois de **6 usos**, o golpe fica **SUPER**: o quadrinho fica dourado e brilhando, a lutadora ganha uma aura dourada e aparece **SUPER PRONTO** em cima da cabeça dela. No celular, o botão desse golpe pisca em dourado com a palavra SUPER.
3. Na próxima vez que você usar esse golpe, a luta fica em câmera lenta e começa a **guerra dos cliques**, que dura 2,5 segundos:
   - no alto da tela aparece quem soltou o super; quem ataca fica com brilho **dourado** e o aviso **ATAQUE!**, e quem defende fica com brilho **azul** e o aviso **DEFENDA!**;
   - em cima da cabeça de cada lutadora aparece a tecla que ela tem que apertar;
   - quem ataca aperta a **tecla do golpe** o mais rápido que puder, e quem defende aperta o **PULO** (`W` ou `↑`);
   - a cada clique aparece o número ao lado da lutadora e ela **cresce**.
4. Se quem ataca clicar mais, a tela pisca e o super **explode**, com bônus de 1,0x até 1,5x no dano, dependendo de quanto ela clicou mais.
5. Se quem defende clicar mais, aparece **DEFENDEU!**, o golpe é cancelado e quem atacou fica tonta.

## Equilíbrio

Os golpes das duas foram testados em centenas de lutas simuladas de PC contra PC:

- Somando os 3 golpes normais de cada uma, o dano por minuto é praticamente igual para as duas.
- No fácil e no médio, cada uma ganha cerca de 50% das lutas.
- Todo dano do jogo é multiplicado por 0,6, então as lutas duram mais (cerca de 1 minuto por round).

### Os supers

Cada golpe tem uma versão super, bem exagerada. Para ficar justo, os 3 supers de cada lutadora somam **90 pontos de força** (antes do bônus da guerra dos cliques e do 0,6 que vale para todo dano).

| Lutadora | Super | O que acontece | Força |
|---|---|---|---|
| Madame Trevosa | **Bunda gigante** | A bunda cresce e ela atropela tudo, até o Magrelo. A Lulu sai voando. | 30 |
| Madame Trevosa | **Voadora super** | Uma voadora bem mais alta. A Lulu voa girando e quica no chão. | 30 |
| Madame Trevosa | **Língua chicote** | A língua gruda na Lulu, levanta e bate ela no chão 3 vezes. | 3 × 10 |
| Lulu Chorona | **Chuva tóxica** | Aparece uma nuvem em cima da Trevosa e caem 10 lágrimas venenosas. | 10 × 3 |
| Lulu Chorona | **Magrelo gordão** | O Magrelo vira um gordão que aguenta 2 golpes antes de cair. | 5 × 6 |
| Lulu Chorona | **5 salsichas doidas** | Cinco salsichas pulando e mordendo, uma atrás da outra. | 5 × 6 |

### Outros comandos (computador)

- `ENTER`: escolher no menu
- `P` ou `ESC`: pausar
- `M`: ligar ou desligar o som

## Dicas para o celular

- Se a tela estiver em pé, o jogo pede para virar o celular.
- No Android, o botão **Tela cheia** deixa o jogo em tela cheia e deitado.
- No iPhone, use **Compartilhar → Adicionar à Tela de Início** no Safari. Assim o jogo abre em tela cheia, como um app.

## Arquivos

- `index.html`: o jogo inteiro (gráficos, sons e controles) num único arquivo, sem nada para instalar.
- `README.md`: este arquivo.
