# Configuração de Rotas e Sub-Rotas em React

## Objetivo
O objetivo dessa atividade foi criar uma aplicação React com duas rotas principais (Home e About) e sub-rotas para cada uma dessas páginas usando o `react-router-dom`.

## Passos

### 1. Configuração do Projeto
Criei um novo projeto React e instalei o pacote `react-router-dom` para gerenciar as rotas.

### 2. Criação dos Componentes
Criei dois componentes simples:
- **Home**: exibe o título "Página Inicial".
- **About**: exibe o título "Sobre".

### 3. Configuração das Rotas
No `App.js`, configurei duas rotas principais:
- Uma para a página inicial (`/`) que exibe o componente **Home**.
- Outra para a página "Sobre" (`/about`) que exibe o componente **About**.

### 4. Adição de Sub-rotas
Adicionei sub-rotas dentro das páginas **Home** e **About**:
- Na **Home**, criei sub-rotas para "Seção 1" e "Seção 2".
- Na **About**, criei sub-rotas para "História" e "Equipe".

### 5. Teste da Aplicação
Após rodar o comando `npm start`, a navegação entre as páginas principais estava funcionando, mas as sub-rotas não foram exibidas corretamente.

