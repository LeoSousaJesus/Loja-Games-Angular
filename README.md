# Loja de Games em Angular

![Loja de Games Banner](https://via.placeholder.com/1200x400/000000/FFFFFF?text=Loja+de+Games+Angular)

## Visão Geral

Este projeto é uma aplicação web desenvolvida em Angular para simular uma loja de jogos online. O objetivo é apresentar uma interface de usuário para navegação, visualização de jogos e um sistema de login básico. A aplicação utiliza o framework Angular, Angular Material para componentes de UI e Bootstrap para elementos como o carrossel.

## Funcionalidades

*   **Página Inicial:** Exibição de banners promocionais e uma grade de jogos com cards interativos.
*   **Listagem de Jogos:** Apresentação de jogos com título, descrição e preço.
*   **Navegação:** Menu superior e rodapé para navegação entre as seções.
*   **Login:** Página dedicada para autenticação de usuários.

## Tecnologias Utilizadas

*   **Angular CLI:** Versão 15.0.4
*   **Angular:** Framework para construção da interface de usuário.
*   **Angular Material:** Biblioteca de componentes de UI para Angular, seguindo as diretrizes do Material Design.
*   **Bootstrap:** Framework de CSS para design responsivo e componentes como o carrossel.
*   **TypeScript:** Linguagem de programação.
*   **HTML5 & CSS3:** Para estruturação e estilização.

## Estrutura do Projeto

A estrutura do projeto segue as convenções padrão do Angular CLI. Os principais diretórios e arquivos são:

```
Loja-Games-Angular/
├── src/
│   ├── app/
│   │   ├── app-routing.module.ts
│   │   ├── app.component.html
│   │   ├── app.component.css
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   │   ├── inicio/             # Componente da página inicial
│   │   ├── login/              # Componente da página de login
│   │   ├── menu/               # Componente do menu de navegação
│   │   └── rodape/             # Componente do rodapé
│   ├── assets/               # Imagens e outros recursos estáticos
│   ├── favicon.ico
│   ├── index.html
│   ├── main.ts
│   └── styles.css
├── angular.json
├── package-lock.json
├── package.json
├── README.md
├── tsconfig.json
└── ... outros arquivos de configuração
```

## Componentes Principais

*   **`AppComponent`**: O componente raiz que orquestra os componentes `MenuComponent`, `RouterOutlet` (para carregar as rotas) e `RodapeComponent`.
*   **`InicioComponent`**: Exibe o carrossel de banners e a listagem de jogos com `mat-card`s. Atualmente, os dados dos jogos são estáticos.
*   **`LoginComponent`**: Contém o formulário para autenticação de usuários.
*   **`MenuComponent`**: Barra de navegação superior da aplicação.
*   **`RodapeComponent`**: Rodapé da aplicação.

## Configuração e Execução

Para configurar e executar o projeto localmente, siga os passos abaixo:

### Pré-requisitos

Certifique-se de ter o [Node.js](https://nodejs.org/en/) e o [Angular CLI](https://angular.io/cli) instalados em sua máquina.

```bash
npm install -g @angular/cli
```

### Instalação

1.  **Clone o repositório:**

    ```bash
git clone https://github.com/LeoSousaJesus/Loja-Games-Angular.git
cd Loja-Games-Angular
    ```

2.  **Instale as dependências:**

    ```bash
npm install
    ```

### Execução

Para iniciar o servidor de desenvolvimento:

```bash
ng serve
```

Navegue até `http://localhost:4200/` em seu navegador. A aplicação será recarregada automaticamente se você fizer alterações nos arquivos fonte.

### Build

Para construir o projeto para produção, utilize:

```bash
ng build
```

Os artefatos de construção serão armazenados no diretório `dist/`.

### Testes

*   **Testes Unitários:**

    ```bash
ng test
    ```

    Executa os testes unitários via [Karma](https://karma-runner.github.io).

*   **Testes End-to-End:**

    ```bash
ng e2e
    ```

    Executa os testes end-to-end. Você precisará adicionar um pacote que implemente recursos de teste end-to-end (ex: Cypress, Protractor).

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests com melhorias, correções de bugs ou novas funcionalidades.

## Licença

Este projeto está licenciado sob a [Licença MIT](https://opensource.org/licenses/MIT).
