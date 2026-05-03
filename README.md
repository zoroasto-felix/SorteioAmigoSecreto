# 🌌✨ Sorteio Cósmico de Amigos ✨🌌

> Uma transmissão futurista para descobrir seu amigo secreto em uma edição Cyberpunk imersiva.

![Cyberpunk Style](https://img.shields.io/badge/Estilo-Cyberpunk-%23ff0099)
![Status Online](https://img.shields.io/badge/Status-Online-darkgreen)
![MIT License](https://img.shields.io/badge/Licença-MIT-yellow)

---

## 🧠 Visão Geral do Sistema

Esta é uma **aplicação web interativa** projetada para realizar sorteios de *Amigo Secreto* com uma estética **Cyberpunk** vibrante e imersiva. Através de uma interface futurista, você pode adicionar participantes, realizar sorteios de forma individual e, ao final, revelar todos os pares de "quem tirou quem", tudo acompanhado por **efeitos visuais e uma experiência temática completa**.

---

## 🚀 Funcionalidades da Transmissão

### ✅ Conexão de Participantes (Adicionar/Remover)

* **Campo "Nome do Ser"**: Interface intuitiva para digitar os nomes dos participantes.
* **Validação Inteligente**: Impede entradas vazias e nomes duplicadas na lista de cadastros.
* **Controle de Estado**: Bloqueia a adição de novos participantes após o início do sorteio.
* **Remoção Dinâmica**: Permite remover participantes da lista *antes* do sorteio iniciar, facilitando correções.

### 📋 Lista Dinâmica de Cadastros

* **Atualização em Tempo Real**: A lista de participantes é atualizada instantaneamente a cada adição ou remoção.
* **Marcação Visual**: Participantes já sorteados individualmente recebem uma marcação visual sutil (`drawn-out`) na lista, indicando que já foram "processados".

### 🎲 Simulação de Sorteio Cósmico

* **Requisito Mínimo**: Exige um mínimo de 3 participantes para iniciar a simulação do sorteio.
* **Sorteio Individual**: Ao clicar em "Iniciar Sorteio", um participante é selecionado aleatoriamente entre os que ainda não foram sorteados, e seu nome aparece em destaque no painel de transmissão com animações neon.
* **Fluxo Contínuo**: Permite continuar sorteando um participante por vez até que todos sejam processados.
* **Revelação Completa**: Após todos os participantes serem sorteados individualmente, um botão "Revelar Todos os Pares" surge, exibindo a lista completa de "Quem deu para quem" (`Doador -> Recebedor`).

### 🧩 Gerenciamento de Estado de Transmissão

* **Mensagens Adaptativas**: O sistema fornece feedback dinâmico sobre o estado atual:
    * "Aguardando mais participantes para iniciar a simulação." (menos de 3)
    * "Clique em 'Iniciar Sorteio' para iniciar a transmissão!" (3 ou mais, antes de iniciar)
    * Contagem dos "seres aguardando sua vez" (durante o sorteio).
    * "Transmissão concluída!" (quando todos são sorteados).
* **Controles Inteligentes**: Os botões "Adicionar", "Iniciar Sorteio" e "Reiniciar Sistema" ativam/desativam-se automaticamente conforme o contexto do jogo.
* **Notificações de Alerta**: Feedback visual para erros (nomes vazios, duplicados) e mensagens de sucesso (sistema reiniciado).

### 🔄 Reinício de Sistema Seguro

* **Modal de Confirmação**: Uma janela modal solicita confirmação antes de reiniciar o jogo, prevenindo ações acidentais.
* **Reset Completo**: Limpa todos os dados, redefine estados e prepara a aplicação para uma nova rodada de sorteios futuristas.

---

## 🛠️ Tecnologias de Conectividade

| Linguagem             | Finalidade                                                  |
| :-------------------- | :---------------------------------------------------------- |
| **HTML5** | Estrutura semântica e organização da interface.             |
| **CSS3** | Estilização Cyberpunk, responsividade e animações neon.     |
| **JavaScript (ES6+)** | Lógica central do sorteio, manipulação do DOM, controle de estado e interatividade. |

---

## 💡 Protocolo de Uso

1.  **Acesse o Sistema**: Simplesmente abra o arquivo `index.html` em seu navegador. Nenhuma instalação adicional é necessária.
2.  **Conecte Participantes**:
    * Digite o nome do ser no campo.
    * Clique em “Adicionar Participante” ou pressione `Enter`.
3.  **Inicie a Transmissão**:
    * Com 3 ou mais participantes, clique em “Iniciar Sorteio” para revelar o próximo nome.
    * Continue clicando até todos serem sorteados individualmente.
4.  **Revele os Pares**:
    * Após o último sorteio individual, clique em "Revelar Todos os Pares" para ver o resultado completo.
5.  **Reinicie o Sistema**:
    * Clique em “Reiniciar Sistema” para limpar tudo e começar uma nova rodada futurista.

---

### 🗂️ Estrutura do Projeto

```markdown
.
├── assets/
│   ├── futuristic-friends-background.jpg   # Imagem de fundo temática principal
│   ├── play-game.png                       # Ícone do botão "Iniciar Sorteio"
│   ├── reload-game.png                     # Ícone do botão "Reiniciar Sistema"
│   ├── close-icon.png                      # Ícone para remover participantes
│   ├── waiting-data.gif                    # Animação de espera na área de resultado
│   └── arrow-right-futuristic.png          # Ícone de seta para os pares sorteados
├── futuristic-app.js                       # Lógica principal da aplicação (JavaScript)
├── futuristic-style.css                    # Estilo visual Cyberpunk e animações (CSS)
└── index.html                              # Estrutura principal da página (HTML)
└── README.md                               # Este arquivo de documentação
📊 Diagrama de Conexão do Projeto
Snippet de código

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
🎨 Estética de Transmissão Cyberpunk
🎨 Paleta de Cores Neon
Fundo Escuro: Tons de preto e azul profundo (#0a0a14, rgba(12, 18, 33, 0.8)).

Acentos Vibrantes:

Ciano Elétrico: #00ccff (principal neon, para títulos, bordas e destaque).

Magenta Vibrante: #ff00ff (secundário neon, para títulos e botões de sorteio).

Amarelo Ácido: #ffcc00 (para avisos e botão de reinício).

Vermelho de Erro: #ff3366 (para notificações e alertas).

🅰️ Tipografia Futurista
'Orbitron', monospace: Usada para títulos principais, botões e nomes de destaque, evocando um visual tecnológico e de tela.

'Rajdhani', sans-serif: Aplicada ao corpo do texto e labels, oferecendo legibilidade com um toque moderno.

✨ Efeitos Visuais Dinâmicos
Painéis Translúcidos: Fundos com transparência e backdrop-filter: blur() para um efeito de vidro digital.

Brilhos Neon Intenso: box-shadow e text-shadow pulsantes e estáticos que emanam das bordas dos painéis, textos e botões.

Animações de Interatividade: Transições suaves ao passar o mouse, efeitos de pulso em elementos ativos e animações de texto (como o "Sorteio" piscando).

Ícones Estilizados: Gráficos com filtros de cor para combinar perfeitamente com a paleta neon.

📱 Responsividade Multiplataforma
A interface foi projetada para se adaptar e funcionar perfeitamente em diversos tamanhos de tela, desde monitores de desktop até dispositivos móveis, garantindo uma experiência consistente.

📄 Licença de Código Aberto
Este projeto está licenciado sob a MIT License. Sinta-se livre para usar, modificar e compartilhar.