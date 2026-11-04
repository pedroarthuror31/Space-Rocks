# Space Rocks

**Space Rocks** é um jogo arcade 2D de combate espacial desenvolvido com a **Godot Engine 4** e a linguagem **GDScript**.

O jogador controla uma nave espacial e precisa enfrentar asteroides e naves inimigas, utilizando habilidades de movimentação, disparo e defesa para sobreviver.

O projeto foi desenvolvido como parte do aprendizado em desenvolvimento de jogos, explorando conceitos de programação, física 2D, interfaces gráficas, efeitos visuais e gerenciamento de cenas.

## Sobre o jogo

Inspirado nos clássicos jogos arcade espaciais, Space Rocks oferece uma experiência de ação em que o jogador precisa desviar de obstáculos, enfrentar inimigos e sobreviver aos desafios apresentados durante a partida.

A jogabilidade envolve movimentação livre pelo espaço, disparos de projéteis, gerenciamento de vida e utilização de mecanismos defensivos.

Conforme o jogador avança, novos desafios são apresentados por meio do sistema de progressão.

## Funcionalidades

O jogo conta com os seguintes recursos:

- **Movimentação espacial:** sistema de aceleração e rotação da nave.
- **Sistema de disparos:** criação e movimentação de projéteis.
- **Asteroides:** obstáculos espaciais que representam ameaças ao jogador.
- **Naves inimigas:** adversários que aumentam a dificuldade das partidas.
- **Sistema de vida:** gerenciamento dos pontos de vida da nave.
- **Escudo de proteção:** mecanismo defensivo para auxiliar na sobrevivência.
- **Sistema de progressão:** gerenciamento de níveis e desafios.
- **Efeitos visuais:** explosões, partículas e efeitos de movimentação.
- **Efeitos sonoros:** sons de disparos, explosões e outras interações.
- **Música de fundo:** acompanhamento musical durante a partida.
- **Interface gráfica (HUD):** apresentação de informações relevantes ao jogador.
- **Menu principal:** opções para iniciar o jogo, consultar os controles e sair.
- **Tela de controles:** apresentação dos comandos utilizados durante a partida.

## Controles

| Tecla | Ação |
|---|---|
| `W` | Acelerar a nave |
| `A` | Girar para a esquerda |
| `D` | Girar para a direita |
| `Espaço` | Disparar |
| `P` | Pausar ou continuar a partida |

### Como jogar

1. Execute o jogo e selecione **PLAY** no menu principal.
2. Inicie a partida pela interface do jogo.
3. Utilize `W` para acelerar e `A` e `D` para controlar a direção da nave.
4. Pressione `Espaço` para disparar contra os inimigos.
5. Desvie dos asteroides e dos ataques adversários.
6. Utilize a movimentação e os recursos defensivos disponíveis para sobreviver.

Os comandos também podem ser consultados na opção **CONTROLS** do menu principal.

## Tecnologias utilizadas

| Tecnologia | Utilização |
|---|---|
| **Godot Engine 4.7.1** | Motor de desenvolvimento do jogo |
| **GDScript** | Programação da lógica e das funcionalidades |
| **Sistema de cenas e nós** | Organização dos componentes do jogo |
| **Física 2D** | Movimentação, colisões e interações |
| **Sistema de sinais** | Comunicação entre objetos e eventos |
| **Sistema de partículas** | Efeitos visuais de movimento e explosões |
| **Git e GitHub** | Versionamento e compartilhamento do código-fonte |

## Estrutura do projeto

```text
Space-Rocks/
├── assets/         # Imagens, sons, fontes e outros recursos
├── bullet/         # Projéteis
├── enemy/          # Inimigos
├── explosion/      # Efeitos de explosão
├── hud/            # Interface gráfica
├── menu/           # Menu principal
├── player/         # Nave do jogador
├── rock/           # Asteroides
├── main.gd         # Lógica principal
├── main.tscn       # Cena principal da partida
└── project.godot   # Configuração do projeto
```

## Como executar o projeto

### Requisitos

- Godot Engine 4.7.1 ou versão compatível.
- Computador capaz de executar projetos 2D desenvolvidos na Godot.

### 1. Baixar o projeto

Na página do repositório, clique em **Code → Download ZIP** e extraia os arquivos.

Alternativamente, clone o repositório utilizando o Git:

```bash
git clone https://github.com/pedroarthuror31/Space-Rocks.git
```

### 2. Importar o projeto na Godot

1. Abra o gerenciador de projetos da Godot.
2. Clique em **Importar**.
3. Localize a pasta do projeto.
4. Selecione o arquivo `project.godot`.
5. Confirme a importação e abra o projeto.

### 3. Executar o jogo

Com o projeto aberto na Godot, pressione `F5` para executar a cena principal configurada.

O jogo deverá iniciar pelo menu principal, permitindo acessar as opções **PLAY**, **CONTROLS** e **EXIT**.

## Desenvolvimento e aprendizado

O projeto foi desenvolvido com base nos estudos do livro *Godot 4 Game Development Projects — Second Edition*, com implementações e personalizações adicionais.

Durante o desenvolvimento, foram trabalhados conceitos como:

- Programação orientada a eventos.
- Organização de projetos por cenas e nós.
- Movimentação e física em jogos 2D.
- Detecção e tratamento de colisões.
- Instanciação e gerenciamento de objetos.
- Utilização de sinais para comunicação entre componentes.
- Desenvolvimento de interfaces gráficas.
- Integração de recursos gráficos e sonoros.

Além das funcionalidades do jogo, foram desenvolvidas personalizações na interface, incluindo um menu principal com identidade visual espacial.
