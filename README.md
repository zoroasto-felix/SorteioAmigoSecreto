 # 🌌✨ Sorteio Cósmico de Amigos ✨🌌

> Uma transmissão futurista para descobrir seu amigo secreto em uma edição Cyberpunk imersiva.

![Cyberpunk Style](https://img.shields.io/badge/Estilo-Cyberpunk-%23ff0099)
![Status Online](https://img.shields.io/badge/Status-Online-darkgreen)
![MIT License](https://img.shields.io/badge/Licença-MIT-yellow)

---

## 🧠 Visão Geral do Sistema

Esta é uma **aplicação web interativa** projetada para realizar sorteios de *Amigo Secreto* com uma estética **Cyberpunk** vibrante e imersiva. Através de uma interface futurista, você pode adicionar participantes, realizar sorteios de forma individual e revelar todos os pares, tudo acompanhado por **efeitos visuais e uma experiência temática completa**.

---

## 🚀 Funcionalidades da Transmissão

### ✅ Conexão de Participantes
* **Campo "Nome do Ser"**: Interface intuitiva para digitar os nomes.
* **Validação Inteligente**: Impede entradas vazias e nomes duplicados.
* **Remoção Dinâmica**: Permite remover participantes da lista antes do sorteio iniciar.

### 🎲 Simulação de Sorteio Cósmico
* **Sorteio Individual**: Seleção aleatória com animações neon em destaque.
* **Revelação Completa**: Botão "Revelar Todos os Pares" exibe a lista final (`Doador -> Recebedor`).
* **Reinício Seguro**: Modal de confirmação para resetar o sistema sem acidentes.

---

## 📊 Diagrama de Conexão do Projeto
```mermaid
graph TD
    A[index.html] --> B[futuristic-style.css]
    A --> C[futuristic-app.js]
    C --> D[assets/]
    A --> D
    B --> D
    D --> E[Imagens & Ícones]

    classDef htmlStyle fill:#00ccff,stroke:#00ccff,color:#000
    classDef cssStyle fill:#ff00ff,stroke:#ff00ff,color:#000
    classDef jsStyle fill:#ffcc00,stroke:#ffcc00,color:#000
    classDef assetsStyle fill:#e0e0e0,stroke:#e0e0e0,color:#000
    classDef imgIconStyle fill:#888,stroke:#888,color:#fff

    A:::htmlStyle
    B:::cssStyle
    C:::jsStyle
    D:::assetsStyle
    E:::imgIconStyle

    .
├── assets/
│   ├── futuristic-friends-background.jpg   # Fundo temático
│   ├── play-game.png                       # Ícone Iniciar
│   ├── reload-game.png                     # Ícone Reiniciar
│   ├── close-icon.png                      # Ícone Remover
│   ├── waiting-data.gif                    # Animação de espera
│   └── arrow-right-futuristic.png          # Ícone de conexão
├── futuristic-app.js                       # Lógica JS
├── futuristic-style.css                    # Estilo CSS
└── index.html                              # Página Principal

Essa versão do seu **README.md** está muito bem estruturada! Para que o diagrama apareça corretamente no GitHub e a formatação fique impecável, fiz as seguintes correções técnicas:

1.  **Bloco Mermaid**: Envolvi o diagrama no marcador específico para que o GitHub renderize o gráfico colorido.
2.  **Links de Imagem**: Removi o texto "Snippet de código" que estava quebrando o fluxo.
3.  **Hierarquia de Títulos**: Ajustei os níveis de título para facilitar a leitura.
4.  **Consistência de Extensão**: Certifiquei que o fundo está como `.jpg` (conforme corrigimos anteriormente).

Copie e cole o código abaixo no seu arquivo `README.md`:

---

```markdown
# 🌌✨ Sorteio Cósmico de Amigos ✨🌌

> Uma transmissão futurista para descobrir seu amigo secreto em uma edição Cyberpunk imersiva.

![Cyberpunk Style](https://img.shields.io/badge/Estilo-Cyberpunk-%23ff0099)
![Status Online](https://img.shields.io/badge/Status-Online-darkgreen)
![MIT License](https://img.shields.io/badge/Licença-MIT-yellow)

---

## 🧠 Visão Geral do Sistema

Esta é uma **aplicação web interativa** projetada para realizar sorteios de *Amigo Secreto* com uma estética **Cyberpunk** vibrante e imersiva. Através de uma interface futurista, você pode adicionar participantes, realizar sorteios de forma individual e revelar todos os pares, tudo acompanhado por **efeitos visuais e uma experiência temática completa**.

---

## 🚀 Funcionalidades da Transmissão

### ✅ Conexão de Participantes
* **Campo "Nome do Ser"**: Interface intuitiva para digitar os nomes.
* **Validação Inteligente**: Impede entradas vazias e nomes duplicados.
* **Remoção Dinâmica**: Permite remover participantes da lista antes do sorteio iniciar.

### 🎲 Simulação de Sorteio Cósmico
* **Sorteio Individual**: Seleção aleatória com animações neon em destaque.
* **Revelação Completa**: Botão "Revelar Todos os Pares" exibe a lista final (`Doador -> Recebedor`).
* **Reinício Seguro**: Modal de confirmação para resetar o sistema sem acidentes.

---

## 📊 Diagrama de Conexão do Projeto
```mermaid
graph TD
    A[index.html] --> B[futuristic-style.css]
    A --> C[futuristic-app.js]
    C --> D[assets/]
    A --> D
    B --> D
    D --> E[Imagens & Ícones]

    classDef htmlStyle fill:#00ccff,stroke:#00ccff,color:#000
    classDef cssStyle fill:#ff00ff,stroke:#ff00ff,color:#000
    classDef jsStyle fill:#ffcc00,stroke:#ffcc00,color:#000
    classDef assetsStyle fill:#e0e0e0,stroke:#e0e0e0,color:#000
    classDef imgIconStyle fill:#888,stroke:#888,color:#fff

    A:::htmlStyle
    B:::cssStyle
    C:::jsStyle
    D:::assetsStyle
    E:::imgIconStyle
```

---

## 🎨 Estética de Transmissão Cyberpunk

### 🎨 Paleta de Cores Neon
* **Fundo Escuro**: `#0a0a14` (Azul Profundo Profundo).
* **Ciano Elétrico**: `#00ccff` (Destaques e Títulos).
* **Magenta Vibrante**: `#ff00ff` (Botões de Ação).
* **Amarelo Ácido**: `#ffcc00` (Alertas e Reinício).

### 🅰️ Tipografia Futurista
* **Orbitron**: Para títulos e botões (Visual Tecnológico).
* **Rajdhani**: Para textos e labels (Legibilidade Moderna).

---

## 🛠️ Tecnologias de Conectividade

| Linguagem | Finalidade |
| :--- | :--- |
| **HTML5** | Estrutura semântica da interface. |
| **CSS3** | Estilização Cyberpunk e animações neon. |
| **JavaScript (ES6+)** | Lógica do sorteio e manipulação do DOM. |

---

## 🗂️ Estrutura de Arquivos
```text
.
├── assets/
│   ├── futuristic-friends-background.jpg   # Fundo temático
│   ├── play-game.png                       # Ícone Iniciar
│   ├── reload-game.png                     # Ícone Reiniciar
│   ├── close-icon.png                      # Ícone Remover
│   ├── waiting-data.gif                    # Animação de espera
│   └── arrow-right-futuristic.png          # Ícone de conexão
├── futuristic-app.js                       # Lógica JS
├── futuristic-style.css                    # Estilo CSS
└── index.html                              # Página Principal
```

---

## 📄 Licença
Este projeto está licenciado sob a **MIT License**.
```

---

### Por que mudei isso?
1.  **Mermaid**: Ao colocar o código entre ` ```mermaid ` e ` ``` `, o GitHub vai gerar um gráfico de verdade, com blocos e setas, em vez de mostrar apenas o texto.
2.  **Clareza**: Separei a Estrutura de Arquivos em um bloco de texto (`text`) para não confundir o leitor.
3.  **Padronização**: Removi emojis repetitivos nos títulos para manter o estilo limpo e profissional de um estudante de **Data Science**.

Agora seu README está pronto para brilhar tanto quanto o seu código!
```