# 🌿 Portal de Notícias Ambientais - *Ecológica Verde*

## 🎯 Objetivo

Criar um portal de notícias com temática ambiental, utilizando PHP, MySQL e HTML/CSS. O sistema inclui autenticação de usuários, gerenciamento de notícias, funcionalidades extras e uma interface pública e privada.

---

## 🛠️ Funcionalidades

### 🔐 Usuários

* Cadastro e login
* Recuperação de conta por e-mail
* Edição e exclusão de conta
* Logout seguro

### 📰 Notícias

* Cadastro de notícias (somente logado)
* Edição/exclusão apenas pelo autor
* Listagem pública das notícias
* Visualização completa da notícia
* Busca de notícias por título ou conteúdo
* Exportar notícia em PDF

### 🌦️ Recursos Extras

* Previsão do tempo na página inicial
* Anúncios dinâmicos na área pública
* Modo escuro ativável pelo usuário


---

## 🧩 Estrutura do Sistema

### 📁 Páginas Públicas

* `index.php`: Lista de notícias públicas + previsão do tempo
* `noticia.php`: Exibição de uma notícia (com opção de exportar PDF)
* `login.php`: Login de usuários
* `cadastro.php`: Cadastro de conta
* `recuperar.php`: Recuperação de conta
* `logout.php`: Encerra a sessão

### 🔐 Páginas Privadas

* `dashboard.php`: Painel do usuário logado
* `nova_noticia.php`: Cadastro de notícia
* `editar_noticia.php`: Edição de notícia
* `excluir_noticia.php`: Exclusão de notícia

### 🔧 Suporte

* `conexao.php`: Conexão com banco
* `verifica_login.php`: Proteção de páginas privadas
* `busca.php`: Lógica da busca de notícias
* `tempo_api.php`: Script da previsão do tempo
* `exportar_pdf.php`: Exportação de notícia em PDF
* `style.css`: Estilização com modo claro/escuro
* `dump.sql`: Estrutura e dados do banco

---

## 🎨 Interface

* HTML + CSS puro
* Responsiva e intuitiva
* Visual limpo e separado entre público e restrito
* Modo escuro ativável com toggle

---

## 📦 Entrega

* Projeto completo no GitHub
* Inclui todos os arquivos + `dump.sql`
* README com instruções claras

---

## 📋 Ficha de Planejamento

### *Etapa 1: Planejamento do Projeto*

* **Responsável**: Jeremias
* **Data Início**: 10-Jun.
* **Data Entrega**: 13-Jun.

### *Etapa 2: Banco de Dados*

* **Responsável**: João
* **Data Início**: 10-Jun.
* **Data Entrega**: 12-Jun.

### *Etapa 3: Interface*

* **Responsável**: Vitor
* **Data Início**: 10-Jun.
* **Data Entrega**: 15-Jun.

### *Etapa 4: Autenticação*

* **Responsável**: Jeremias
* **Data Início**: 10-Jun.
* **Data Entrega**: 14-Jun.

### *Etapa 5: Notícias*

* **Responsável**: João
* **Data Início**: 10-Jun.
* **Data Entrega**: 16-Jun.

### *Etapa 6: Testes*

* **Responsável**: Vitor
* **Data Início**: 13-Jun.
* **Data Entrega**: 16-Jun.

### *Etapa 7: Funcionalidades Extras*

* **Modo Escuro / Previsão / PDF / Busca / Anúncios / Recuperação de Conta**
* **Responsáveis**: Jeremias, João e Vitor
* **Data Início**: 14-Jun.
* **Data Conclusão**: 09-Jul.

### *Etapa 8: Entrega Final*

* **Responsáveis**: Jeremias, João e Vitor
* **Data Início**: 10-Jun.
* **Data Entrega Final**: 09-Jul.

---

## ✅ Conclusão

Projeto criado como parte da disciplina de Desenvolvimento Web.
Tema escolhido: **Meio Ambiente 🌱**.

Sistema completo, com foco em usabilidade, acessibilidade e recursos modernos para informação ambiental confiável e acessível.
