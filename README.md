# 🚀 Trybe Tech Gallery

Bem-vindo ao repositório do projeto "Trybe Tech Gallery"! Este projeto é uma revisão e aprimoramento de um exercício do curso de programação da Trybe, focado na criação de uma galeria de tecnologias com um design responsivo e moderno.

## 🎯 Objetivo do Projeto

O principal objetivo deste projeto é revisitar e solidificar conceitos fundamentais de desenvolvimento web, com ênfase especial em:

-   **Estrutura Semântica HTML5**: Organização do conteúdo da página de forma clara e acessível.
-   **Estilização Avançada com CSS3**: Aplicação de design visual atraente, incluindo sombras, transições e posicionamento de elementos.
-   **Flexbox para Layouts Responsivos**: Utilização das poderosas ferramentas do Flexbox para criar layouts flexíveis que se adaptam a diferentes tamanhos de tela.
-   **Gerenciamento de Pacotes com pnpm**: Migração e uso eficiente do `pnpm` para uma gestão de dependências mais rápida e eficiente.
-   **Configuração e Testes com Cypress**: Preparação do ambiente para execução de testes end-to-end.
-   **Versionamento de Código com Git**: Boas práticas de commits e histórico de alterações.

## ✨ Demonstração

Veja a Trybe Tech Gallery em ação:

![Demonstração da Trybe Tech Gallery](/images/trybetech.gif)
## ✨ Destaques da Implementação

Este projeto foi uma excelente oportunidade para aplicar e reforçar o aprendizado em diversas áreas:

### 🎨 Design e Estilização (`style.css`)

-   **Cabeçalho Moderno**: Um `header-container` fixo, estilizado com `display: flex;` e `justify-content: space-around;` para centralizar e distribuir os elementos (logo, título e botão "SIGN-UP") de forma equilibrada.
-   **Galeria de Cards Responsiva**: A seção `.gallery` é o coração visual do projeto.
    -   **`display: flex;` e `flex-wrap: wrap;`**: Permitem que os cards de tecnologia (`.gallery-card`) se organizem em linhas e automaticamente quebrem para a próxima linha quando o espaço se torna limitado, garantindo uma ótima experiência em qualquer dispositivo.
    -   **`justify-content: center;`**: Mantém as linhas de cards centralizadas horizontalmente.
    -   **`margin: 0 auto;` e `max-width: 1100px;`**: Centralizam o contêiner principal da galeria na página, garantindo um layout agradável em telas maiores.
-   **Cards Interativos (`.gallery-card`)**:
    -   **`box-shadow`**: Adiciona uma sutil micro-sombra aos cards, conferindo um efeito de profundidade e "flutuação".
    -   **`transition` e `:hover`**: Ao passar o mouse sobre os cards, eles exibem um efeito de levantamento e a sombra se intensifica, melhorando a interatividade.
    -   **Posicionamento de Títulos**: Os títulos das tecnologias (`<h4>`) são posicionados com `position: absolute;` dentro dos cards (`position: relative;`), permitindo que fiquem sobre as imagens dos logos, centralizados e com um visual distinto.
-   **Rodapé Separador**: O `footer-container` utiliza `border-top` para criar uma linha sutil acima dos ícones de redes sociais, proporcionando uma separação visual limpa.

### 📦 Gerenciamento de Dependências (pnpm)

-   O projeto foi migrado para utilizar o `pnpm` como gerenciador de pacotes principal, substituindo o `npm`. Esta mudança visa melhorar a performance das instalações de dependências e otimizar o uso do espaço em disco através de sua arquitetura de armazenamento de conteúdo endereçável.


## ⚙️ Como Rodar o Projeto Localmente

Siga os passos abaixo para configurar e executar este projeto em sua máquina:

1.  **Clone o Repositório:**
    ```bash
    git clone <URL_DO_REPOSITORIO_>
    
    ```
    *(Certifique-se de substituir `<URL_DO_REPOSITORIO_>` pela URL real do repositório.)*

2.  **Instale as Dependências:**
    Como o projeto utiliza `pnpm`, use o seguinte comando:
    ```bash
    pnpm install
    ```
    *(Este comando irá instalar todas as dependências listadas no `package.json` e criar o `pnpm-lock.yaml`.)*

3.  **Execute o Projeto:**
    Este projeto é composto apenas por HTML e CSS estático. Para visualizá-lo, você pode simplesmente abrir o arquivo `index.html` em seu navegador web.

    Ou, se você tiver um servidor local simples configurado (como `live-server`), pode executá-lo:
    ```bash
    npx live-server # Se você tiver o live-server instalado globalmente ou localmente
    ```


## 🤝 Contribuição

Contribuições são sempre bem-vindas! Se você tiver sugestões de melhorias, detetar bugs ou quiser adicionar novos recursos, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

---
Made with ❤️ by Everton Balland