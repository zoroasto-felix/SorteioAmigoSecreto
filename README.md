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
* **Campo "Nome do Ser"**: Interface intuitiva para digitar os nomes dos participantes.
* **Validação Inteligente**: Impede entradas vazias e nomes duplicados na lista de cadastros.
* **Remoção Dinâmica**: Permite remover participantes da lista antes do sorteio iniciar.

### 🎲 Simulação de Sorteio Cósmico
* **Sorteio Individual**: Seleção aleatória com animações neon em destaque no painel.
* **Revelação Completa**: Após o último sorteio, exibe a lista completa de "Doador -> Recebedor".
* **Reinício Seguro**: Modal de confirmação para resetar o sistema sem perder dados acidentalmente.

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

Linguagem,Finalidade
HTML5,Estrutura semântica e organização da interface.
CSS3,"Estilização Cyberpunk, responsividade e animações neon."
JavaScript (ES6+),"Lógica do sorteio, manipulação do DOM e controle de estado."

.
├── assets/
│   ├── futuristic-friends-background.jpg   # Fundo temático principal
│   ├── play-game.png                       # Ícone Iniciar Sorteio
│   ├── reload-game.png                     # Ícone Reiniciar Sistema
│   ├── close-icon.png                      # Ícone para remover participantes
│   ├── waiting-data.gif                    # Animação de espera
│   └── arrow-right-futuristic.png          # Seta para os pares sorteados
├── futuristic-app.js                       # Lógica JavaScript
├── futuristic-style.css                    # Estilização CSS
└── index.html                              # Estrutura Principal

📄 Licença
Este projeto está licenciado sob a MIT License.