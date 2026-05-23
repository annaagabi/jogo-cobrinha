# 🐍 Snake Game - Vanilla JavaScript

Um jogo da cobrinha (**Snake Game**) totalmente funcional desenvolvido com **HTML, CSS e JavaScript puro (Vanilla JS)**, sem dependências externas, bibliotecas ou frameworks.

O projeto foi criado para rodar diretamente no navegador em um único arquivo `.html`, oferecendo uma experiência moderna, responsiva e pronta para uso.

> Projeto desenvolvido durante a prática do curso **Inteligências Artificiais Generativas Aplicada à Programação – ChatGPT**, do **SENAI**, com foco na aplicação de conceitos de desenvolvimento e utilização de IA como apoio no processo de construção de software.

---

## 📑 Sumário

- [📌 Sobre o Projeto](#-sobre-o-projeto)
- [🎯 Objetivos do Projeto](#-objetivos-do-projeto)
- [✨ Funcionalidades](#-funcionalidades)
- [🛠️ Tecnologias Utilizadas](#️-tecnologias-utilizadas)
- [📂 Estrutura do Projeto](#-estrutura-do-projeto)
- [⚙️ Como Funciona](#️-como-funciona)
- [🎮 Como Jogar](#-como-jogar)
- [🚀 Como Executar o Projeto](#-como-executar-o-projeto)
- [📥 Como Baixar o Projeto](#-como-baixar-o-projeto)
- [🤝 Como Contribuir](#-como-contribuir)
- [📱 Responsividade](#-responsividade)
- [🧠 Conceitos Aplicados](#-conceitos-aplicados)
- [💡 Melhorias Futuras](#-melhorias-futuras)
- [🐛 Reportando Problemas](#-reportando-problemas)
- [📄 Licença](#-licença)
- [👩‍💻 Autora](#-autora)

---

# 📌 Sobre o Projeto

Este projeto consiste no desenvolvimento de um jogo da cobrinha (**Snake**) clássico, implementado utilizando apenas tecnologias nativas do navegador.

A proposta do projeto foi criar uma versão moderna, responsiva e totalmente funcional do clássico jogo Snake, mantendo simplicidade de execução e uma arquitetura organizada.

A aplicação foi desenvolvida com foco em:

- ✅ simplicidade de execução;
- ✅ código organizado e legível;
- ✅ experiência visual moderna;
- ✅ responsividade;
- ✅ ausência de dependências externas;
- ✅ facilidade de manutenção;
- ✅ performance utilizando JavaScript puro.

Todo o projeto está contido em **um único arquivo HTML**, contendo:

- **HTML** → estrutura da interface;
- **CSS** → estilização e responsividade;
- **JavaScript** → regras e lógica do jogo.

---

# 🎯 Objetivos do Projeto

Este projeto teve como principais objetivos:

- praticar lógica de programação;
- aplicar conceitos de desenvolvimento front-end;
- utilizar **Canvas API** para renderização gráfica;
- trabalhar manipulação de eventos do teclado;
- implementar controle de estado do jogo;
- aplicar conceitos de responsividade;
- exercitar boas práticas de organização de código.

Além disso, o projeto foi utilizado como prática do curso **Inteligências Artificiais Generativas Aplicada à Programação – ChatGPT (SENAI)**, explorando a utilização de IA como apoio no desenvolvimento de software.

---

# ✨ Funcionalidades

O jogo possui as seguintes funcionalidades:

### 🎮 Jogabilidade

✅ Controle pelo teclado:

- Setas do teclado (`↑ ↓ ← →`)
- Teclas `W A S D`

✅ Movimentação fluida da cobrinha

✅ Crescimento progressivo ao consumir alimentos

✅ Sistema de pontuação

✅ Aumento progressivo de velocidade

---

### ⚠️ Sistema de Regras

✅ Detecção de colisão com:

- paredes;
- próprio corpo.

✅ Tela de **Game Over**

✅ Reinício da partida

✅ Bloqueio de reversão instantânea de direção (evita bugs de gameplay)

---

### 🎨 Interface

✅ Layout moderno

✅ Design responsivo

✅ Interface amigável

✅ Inicialização automática ao abrir o arquivo

✅ Funciona offline

✅ Sem bibliotecas externas

---

# 🛠️ Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando apenas tecnologias nativas do navegador.

| Tecnologia | Finalidade |
|------------|------------|
| HTML5 | Estrutura da interface |
| CSS3 | Estilização e responsividade |
| JavaScript (ES6+) | Lógica do jogo |
| Canvas API | Renderização gráfica |

### Dependências externas

❌ Nenhuma

O projeto **não utiliza**:

- frameworks;
- bibliotecas externas;
- CDN;
- banco de dados;
- back-end.

---

# 📂 Estrutura do Projeto

O projeto possui estrutura simples:

```plaintext
snake-game/
│
├── index.html
├── README.md
│
└── assets/
    └── preview.png (opcional)
```

### Organização do `index.html`

O projeto foi estruturado em três camadas:

### 1. HTML

Responsável pela estrutura da interface.

### 2. CSS

Responsável por:

- layout;
- responsividade;
- estilização;
- experiência visual.

### 3. JavaScript

Responsável pela lógica do jogo:

- movimentação;
- colisões;
- renderização;
- pontuação;
- velocidade;
- game over.

---

# ⚙️ Como Funciona

O jogo utiliza um sistema baseado em **grid**.

A cobrinha se movimenta em blocos e a cada atualização:

1. uma nova posição da cabeça é criada;
2. o corpo é atualizado;
3. colisões são verificadas;
4. a tela é renderizada novamente.

---

## Sistema de Renderização

A renderização é feita utilizando a **Canvas API**.

O canvas é responsável por desenhar:

- cobrinha;
- alimentos;
- movimentação;
- atualização do estado visual do jogo.

---

## Sistema de Velocidade Progressiva

A velocidade do jogo aumenta conforme a pontuação cresce.

Isso torna a gameplay mais dinâmica e progressivamente desafiadora.

---

## Sistema de Colisão

O jogo detecta colisões com:

### Parede

Quando a cobrinha ultrapassa os limites do grid.

### Corpo da cobrinha

Quando a cabeça ocupa a mesma posição de outra parte do corpo.

Ao ocorrer uma colisão:

- o loop do jogo é interrompido;
- a tela de **Game Over** é exibida;
- a pontuação final é mostrada.

---

# 🎮 Como Jogar

## Objetivo

Coma o máximo de alimentos possível e alcance a maior pontuação sem colidir.

---

## Controles

| Tecla | Ação |
|--------|------|
| ↑ | Mover para cima |
| ↓ | Mover para baixo |
| ← | Mover para esquerda |
| → | Mover para direita |
| W | Mover para cima |
| A | Mover para esquerda |
| S | Mover para baixo |
| D | Mover para direita |

---

## Regras

- Cada alimento aumenta sua pontuação;
- A cobrinha cresce ao comer;
- A velocidade aumenta gradualmente;
- Encostar na parede encerra a partida;
- Colidir com o próprio corpo encerra a partida.

---

# 🚀 Como Executar o Projeto

## Método 1 — Abrindo diretamente no navegador

1. Baixe o projeto;
2. Extraia os arquivos (se necessário);
3. Abra o arquivo:

```plaintext
index.html
```

4. O jogo iniciará automaticamente.

---

## Método 2 — Clonando o repositório

### 1. Clone o projeto

```bash
git clone https://github.com/annaagabi/snake-game.git
```

### 2. Entre na pasta

```bash
cd snake-game
```

### 3. Abra no navegador

Abra o arquivo:

```plaintext
index.html
```

---

## Método 3 — Executando com VS Code

### 1. Abra a pasta do projeto

```bash
code .
```

### 2. Instale a extensão

**Live Server**

### 3. Execute

Clique com o botão direito em:

```plaintext
index.html
```

Depois:

```plaintext
Open with Live Server
```

---

# 📥 Como Baixar o Projeto

### Pelo GitHub

1. Clique no botão **Code**;
2. Clique em **Download ZIP**;
3. Extraia o `.zip`;
4. Abra o arquivo `index.html`.

---

### Pelo Git

```bash
git clone https://github.com/annaagabi/snake-game.git
```

---

# 🤝 Como Contribuir

Contribuições são bem-vindas.

Se quiser melhorar o projeto:

### 1. Faça um fork

Clique em **Fork** no GitHub.

---

### 2. Clone seu fork

```bash
git clone https://github.com/annaagabi/snake-game.git
```

---

### 3. Crie uma branch

```bash
git checkout -b feature/minha-melhoria
```

---

### 4. Faça as alterações

Implemente sua melhoria.

---

### 5. Commit

```bash
git commit -m "feat: adiciona nova funcionalidade"
```

---

### 6. Push

```bash
git push origin feature/minha-melhoria
```

---

### 7. Abra um Pull Request

Descreva claramente:

- o que foi alterado;
- motivo da alteração;
- possíveis impactos.

---

# 📱 Responsividade

O projeto foi desenvolvido para funcionar em:

- 💻 Desktop
- 🖥️ Notebook
- 📱 Mobile
- 📲 Tablet

O canvas se adapta automaticamente ao tamanho da tela.

---

# 🧠 Conceitos Aplicados

Durante o desenvolvimento foram utilizados conceitos como:

- Manipulação do DOM;
- Eventos de teclado;
- Canvas API;
- Estruturas condicionais;
- Arrays e objetos;
- Controle de estado;
- Renderização gráfica;
- Responsividade;
- Game Loop;
- Detecção de colisão;
- Controle de velocidade.

---

# 💡 Melhorias Futuras

Possíveis melhorias do projeto:

- [ ] Sistema de recorde (High Score)
- [ ] Sons e efeitos sonoros
- [ ] Música de fundo
- [ ] Sistema de pause
- [ ] Escolha de dificuldade
- [ ] Obstáculos
- [ ] Modo infinito
- [ ] Controle touch para mobile
- [ ] Ranking local

---

# 🐛 Reportando Problemas

Encontrou algum problema?

Abra uma **Issue** no GitHub informando:

- descrição do erro;
- como reproduzir;
- prints (se possível);
- navegador utilizado.

---

# 📄 Licença

Este projeto está licenciado sob a licença **MIT**.

Você pode:

✅ usar  
✅ modificar  
✅ estudar  
✅ distribuir  

Livremente.

---

# 👩‍💻 Autora

**Anna Gabriela Monteiro da Silva**

Desenvolvido como prática do curso:

**Inteligências Artificiais Generativas Aplicada à Programação – ChatGPT (SENAI)**

GitHub:

```txt
https://github.com/annaagabi
```
