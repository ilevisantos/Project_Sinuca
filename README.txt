# Projeto Sinuca

## Descrição

Este é um jogo de sinuca (bilhar) desenvolvido para navegadores web, criado como parte de um curso de JavaScript no Udemy. O jogo permite jogar com 1 a 4 jogadores, simulando uma mesa de bilhar com física básica, placar, medidor de força e efeitos sonoros.

## Funcionalidades

- **Modos de Jogo**: Suporte para 1 a 4 jogadores
- **Interface Visual**: Mesa de bilhar renderizada em HTML5 Canvas com design elegante
- **Física do Jogo**: Simulação básica de movimento das bolas, colisões e atrito
- **Placar**: Exibição em tempo real dos pontos de cada jogador
- **Medidor de Força**: Controle preciso da força do taco através de um medidor visual
- **Efeitos Sonoros**: Sons para tacadas, colisões, impactos nas bordas e bolas entrando nos buracos
- **Controles Intuitivos**: Aponte com o mouse, segure para carregar força e solte para atirar

## Como Executar

1. Abra o arquivo `projeto_sinuca.html` em qualquer navegador web moderno
2. No menu inicial, selecione o número de jogadores (1-4)
3. Clique em "Iniciar Jogo"
4. Use o mouse para controlar o taco: aponte, segure para carregar força e solte para atirar

## Tecnologias Utilizadas

- **HTML5**: Estrutura da página e Canvas para renderização
- **CSS3**: Estilização da interface e animações
- **JavaScript (ES6+)**: Lógica do jogo, física das bolas e interatividade
- **Web Audio API**: Reprodução de efeitos sonoros

## Estrutura do Projeto

```
Projeto_Sinuca/
├── projeto_sinuca.html    # Arquivo principal do jogo
└── sons/                  # Efeitos sonoros
    ├── billiard ball hit.mp3
    ├── cushion.mp3
    ├── pool ball pocket.mp3
    └── pool cue strike.mp3
```

## Requisitos

- Navegador web moderno com suporte a HTML5 Canvas e Web Audio API
- Recomendado: Chrome, Firefox, Safari ou Edge

## Créditos

Este projeto foi desenvolvido como exercício prático do curso de JavaScript no Udemy.

## Licença

Este projeto é para fins educacionais e de aprendizado.