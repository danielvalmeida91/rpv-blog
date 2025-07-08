# Projeto: Portal Rio Pomba Valley

Este documento descreve as milestones e issues para o desenvolvimento do portal Rio Pomba Valley, utilizando **React com Next.js** para o frontend e **PHP** para o backend.

---

## Milestone 0: Em Construção

**Objetivo:** Estabelecer padrões básicos para o ambiente de desenvolvimento.

* [ ] **Definir o padrão de escrita do código:** Discutir e formalizar as convenções de estilo de código para JavaScript/React e PHP.
* [ ] **Configurar o .editorconfig:** Criar o arquivo `.editorconfig` para garantir consistência de formatação entre diferentes editores de texto.
* [ ] **Configurar o Prettier:** Instalar e configurar o Prettier para formatação automática de código no frontend e, se aplicável, no backend.
* [ ] **Configurar o .prettierignore:** Criar o arquivo `.prettierignore` para excluir arquivos e diretórios da formatação do Prettier.

---

## Milestone 1: Setup do Ambiente e Base do Projeto

**Objetivo:** Criar a estrutura inicial dos projetos (frontend e backend) e garantir que todos consigam rodar o ambiente de desenvolvimento.

* ### Configuração do Ambiente de Desenvolvimento Frontend:
    * [ ] Instalar Node.js e npm/yarn nas máquinas de desenvolvimento.
    * [ ] Criar projeto Next.js: Inicializar o projeto frontend com Next.js.
    * [ ] Configurar ESLint para React/Next.js: Integrar o ESLint para linting de código JavaScript e React.
    * [ ] Adicionar boilerplate de componentes básicos: Criar componentes como `Layout.js`, `Header.js` e `Footer.js` para a estrutura inicial.
* ### Configuração do Ambiente de Desenvolvimento Backend:
    * [ ] Instalar PHP e Composer: Garantir a instalação do PHP e do gerenciador de dependências Composer.
    * [ ] Escolher e configurar um framework PHP: Definir e configurar o framework PHP a ser utilizado (ex: Laravel, Symfony).
    * [ ] Configurar banco de dados: Configurar a conexão com o banco de dados (ex: MySQL/PostgreSQL) e ferramentas de ORM/Query Builder.
* ### Configuração do Git e Fluxo de Trabalho:
    * [ ] Criar repositórios no GitHub: Configurar os repositórios para frontend e backend (pode ser um monorepo ou dois repositórios separados).
    * [ ] Definir e documentar o fluxo de trabalho Git: Estabelecer e documentar as boas práticas de uso do Git (ex: branches, pull requests).
    * [ ] Configurar `.gitignore` para frontend e backend: Adicionar arquivos e diretórios que devem ser ignorados pelo Git em ambos os projetos.

---

## Milestone 2: Estrutura Básica do Conteúdo e Navegação

**Objetivo:** O portal começa a ter suas primeiras páginas e uma navegação funcional.

* [ ] **Definição da Estrutura de Páginas:** Criar o esqueleto das principais páginas do portal (Home, Sobre RPV, Parceiros, Notícias/Eventos, Contato).
* [ ] **Implementação da Navegação Frontend:**
    * [ ] Criar componente de Navbar/Header com links para as páginas principais.
    * [ ] Implementar sistema de rotas no Next.js para navegação entre as páginas.
* [ ] **Configuração Inicial da API (Backend):**
    * [ ] Criar um endpoint de teste (ex: `/api/status`) para verificar a comunicação entre frontend e backend.
    * [ ] Configurar CORS no backend para permitir requisições do frontend.

---

## Milestone 3: Desenvolvimento do Conteúdo Estático e Layout

**Objetivo:** O portal começa a ganhar corpo e design, com as primeiras páginas estilizadas.

* [ ] **Desenvolvimento da Página Inicial (Home):**
    * [ ] Implementar seções principais (ex: banner, introdução ao RPV, destaques).
    * [ ] Estilizar a página com base no design aprovado.
* [ ] **Desenvolvimento da Página "Sobre RPV":** Adicionar informações textuais e imagens sobre a iniciativa do Rio Pomba Valley.
* [ ] **Criação de Componentes Reutilizáveis:** Desenvolver componentes de UI reutilizáveis (ex: botões, cards, seções padronizadas).
* [ ] **Aplicação de Estilos Globais e Tema:** Definir variáveis CSS, fontes e paleta de cores para o tema global do portal.

---

## Milestone 4: Integração com Backend e Conteúdo Dinâmico

**Objetivo:** O portal começa a interagir com o backend para exibir informações dinâmicas.

* ### Desenvolvimento da Funcionalidade de Notícias/Eventos (CRUD simples):
    * [ ] **Backend:** Criar endpoints para listar, criar, editar e excluir notícias/eventos.
    * [ ] **Backend:** Modelar o banco de dados para armazenar notícias/eventos.
    * [ ] **Frontend:** Criar página para listar notícias/eventos.
    * [ ] **Frontend:** Implementar o consumo da API para exibir as notícias/eventos na página.
* ### Desenvolvimento da Funcionalidade de Parceiros:
    * [ ] **Backend:** Criar endpoints para listar parceiros (ex: nome, logotipo, descrição).
    * [ ] **Frontend:** Implementar seção/página para exibir logotipos e informações dos parceiros.

---