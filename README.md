# 📱 Apple Store UI - Seleção Dinâmica de Produtos

Este projeto é uma réplica funcional da interface de visualização do iPhone 13 Pro. O foco principal foi a implementação de uma galeria interativa onde o usuário pode alternar entre as diferentes cores do aparelho, com atualizações em tempo real no DOM e efeitos de transição.

## 🚀 Tecnologias Utilizadas
* **HTML5:** Estrutura semântica para navegação (navbar), cabeçalho duplo e área de exibição de produto.
* **CSS3:**
    * **Flexbox:** Organização dos itens da navbar e dos seletores de cores.
    * **Design Responsivo:** Media Queries para adaptar a interface, escondendo menus secundários em dispositivos móveis.
    * **Pseudo-classes & Estados:** Estilização de elementos selecionados com `outline` e efeitos de hover.
* **JavaScript (ES6+):**
    * **Manipulação Dinâmica de Atributos:** Alteração do `src` das imagens com base no ID do elemento clicado.
    * **Lógica de Seleção:** Algoritmo para remover a classe `selected` de todos os itens e aplicar apenas ao alvo do clique.
    * **Animações Temporizadas:** Uso de `setTimeout` para criar uma transição de opacidade (`changing`) durante a troca de fotos.

## 🧠 Lógica de ADS Aplicada:
* **Interatividade em Tempo Real:** O código monitora os eventos de clique e responde instantaneamente alterando a interface sem recarregar a página.
* **UX (User Experience):** Feedback visual através de cores selecionadas e transições de imagem, melhorando a fluidez da navegação.
* **Modularidade:** Uso de Template Literals para construir caminhos de arquivos de forma dinâmica.

## ⚙️ Como visualizar
1. Clone este repositório.
2. Abra o arquivo `index.html` no seu navegador.

---
Projeto desenvolvido para praticar manipulação de eventos e lógica de interface no curso de ADS. 💻🔥
