# Flappy Bird — Clone em JavaScript Puro

Um clone do clássico *Flappy Bird*, construído do zero com **JavaScript puro (Vanilla JS)**, manipulação direta do DOM e CSS puro — sem frameworks, sem bibliotecas de jogo.

## 🎮 Sobre o projeto

Este projeto foi desenvolvido como exercício prático para consolidar conceitos fundamentais de JavaScript e manipulação de DOM: criação dinâmica de elementos, closures, `requestAnimationFrame`/`setInterval` para loops de jogo, detecção de colisão (AABB) e gerenciamento de estado sem nenhuma lib externa.

### Funcionalidades

- Pássaro controlado por teclado (segurar tecla = sobe, soltar = desce por gravidade)
- Geração dinâmica e infinita de pares de barreiras, com abertura sorteada aleatoriamente
- Detecção de colisão entre pássaro e barreiras
- Contador de pontos, incrementado a cada par de barreiras ultrapassado
- Game over ao colidir (loop do jogo é interrompido)

## 🛠️ Tecnologias utilizadas

- **JavaScript** (ES5/ES6, sem frameworks)
- **HTML5**
- **CSS3** (Flexbox para layout das barreiras)


## ▶️ Como rodar localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/flappy-bird.git
   ```
2. Abra o arquivo `index.html` diretamente no navegador, ou sirva a pasta com uma extensão como Live Server (VS Code).

Não há dependências para instalar — é HTML, CSS e JS puros.

## 🧠 Principais conceitos aplicados

- Factory functions (`function` + `this`) para criação de objetos do jogo
- Closures para encapsular estado interno (ex: altura das barreiras, se o pássaro está voando)
- Manipulação dinâmica do DOM (`createElement`, `appendChild`)
- Detecção de colisão via `getBoundingClientRect()`
- Loop de jogo com `setInterval`

## 🚧 Possíveis melhorias futuras

- Migrar o loop de jogo para `requestAnimationFrame`
- Adicionar tela de "Game Over" e opção de reiniciar
- Salvar recorde (high score) em `localStorage`
- Adicionar efeitos sonoros

## 👤 Autor

Desenvolvido por João Vitor

---

Sinta-se à vontade para abrir issues ou sugerir melhorias!
