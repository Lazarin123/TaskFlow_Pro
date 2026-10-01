# 🚀 TaskFlow Pro

> **Gerenciamento de projetos Kanban em um único arquivo HTML.**

O **TaskFlow Pro** é uma aplicação moderna de gerenciamento de tarefas baseada no conceito **Kanban**, desenvolvida com foco em **simplicidade, performance, responsividade e experiência do usuário**.

Toda a aplicação está concentrada em um único arquivo `index.html`, contendo estrutura HTML, estilos CSS e lógica JavaScript, tornando o projeto extremamente simples de executar, estudar, compartilhar e publicar.

O sistema oferece gerenciamento completo de tarefas, movimentação por **Drag & Drop**, suporte a dispositivos móveis, dashboard analítico com gráficos, múltiplos temas visuais e persistência de dados utilizando `localStorage`.

---

## ✨ Preview

O TaskFlow Pro apresenta uma interface moderna para organização de projetos e tarefas através de quatro etapas principais:

```text
┌──────────────┐   ┌──────────────┐   ┌──────────────┐   ┌──────────────┐
│   A FAZER    │ → │ EM ANDAMENTO │ → │    REVISÃO   │ → │  CONCLUÍDO   │
├──────────────┤   ├──────────────┤   ├──────────────┤   ├──────────────┤
│   Task #01   │   │   Task #03   │   │   Task #05   │   │   Task #02   │
│   Task #04   │   │   Task #06   │   │              │   │   Task #07   │
└──────────────┘   └──────────────┘   └──────────────┘   └──────────────┘
```

---

# 🎯 Funcionalidades

## 📋 Kanban Completo

O sistema possui quatro colunas padrão:

- 📝 **A Fazer**
- 🔄 **Em Andamento**
- 🔍 **Revisão**
- ✅ **Concluído**

Cada coluna possui contador atualizado automaticamente de acordo com a quantidade de tarefas presentes.

---

## 📝 Gerenciamento de Tarefas

É possível criar e gerenciar tarefas contendo:

- Título
- Descrição
- Prioridade
- Categoria
- Data de vencimento
- Status

As tarefas podem ser:

- Criadas
- Editadas
- Excluídas
- Movidas entre colunas
- Reorganizadas através de Drag & Drop

---

## 🖱️ Drag & Drop

O TaskFlow Pro possui movimentação intuitiva de tarefas através de **Drag & Drop**.

### Desktop

Compatível com movimentação utilizando o mouse.

### 📱 Mobile

O sistema também possui suporte para interação através de **touch**, permitindo movimentar tarefas em smartphones e tablets.

### ➡️ Navegação por botões

Além do Drag & Drop, cada tarefa pode ser movimentada rapidamente utilizando botões direcionais:

```text
← Recuar     Avançar →
```

Isso permite controlar o fluxo das tarefas mesmo em dispositivos onde o Drag & Drop não seja conveniente.

---

# 📊 Dashboard Analítico

O TaskFlow Pro possui uma área dedicada à análise das tarefas.

## 🥧 Gráfico de Pizza

Apresenta a distribuição das tarefas de acordo com seus respectivos status:

```text
A Fazer
Em Andamento
Revisão
Concluído
```

---

## 📊 Gráfico de Barras

Apresenta a quantidade de tarefas distribuídas por nível de prioridade.

Exemplo:

```text
Alta      ███████████
Média     ███████
Baixa     ████
```

Os gráficos são atualizados dinamicamente conforme as tarefas são adicionadas, editadas, removidas ou movimentadas.

---

# 🎨 Sistema de Temas

O projeto possui **5 temas visuais** que podem ser alterados instantaneamente através do seletor presente na interface.

### 🌑 Dark Navy

Tema escuro com estética profissional e moderna.

### ☀️ Light Modern

Interface clara e minimalista.

### 🌈 Cyberpunk Neon

Visual inspirado em interfaces futuristas e neon.

### 🌲 Emerald Forest

Paleta baseada em tons verdes e natureza.

### 🌅 Sunset Orange

Tema com tons quentes inspirados no pôr do sol.

A preferência do usuário é automaticamente armazenada no navegador.

---

# 💾 Persistência de Dados

O projeto utiliza o **Web Storage API**, através do `localStorage`, para manter os dados mesmo após o fechamento ou atualização da página.

São armazenados:

- Tarefas
- Status
- Prioridades
- Categorias
- Descrições
- Datas
- Preferência de tema

Dessa forma, não é necessário configurar banco de dados ou backend para utilizar a aplicação.

---

# ⚡ Arquitetura Single-File

Uma das principais características do TaskFlow Pro é sua arquitetura simplificada.

Todo o sistema está presente em:

```text
index.html
```

O arquivo contém:

```text
HTML
 ├── Estrutura da aplicação
 ├── Modal de tarefas
 ├── Kanban
 └── Dashboard

CSS
 ├── Layout responsivo
 ├── Temas
 ├── Cards
 ├── Modais
 └── Animações

JavaScript
 ├── CRUD de tarefas
 ├── Drag & Drop
 ├── Touch interaction
 ├── Navegação entre colunas
 ├── localStorage
 ├── Estatísticas
 └── Chart.js
```

Essa abordagem torna o projeto especialmente interessante para:

- Estudos de desenvolvimento web
- Portfólio
- Demonstrações
- Protótipos
- Projetos acadêmicos
- Hospedagem estática
- Experimentação de UI/UX

---

# 🛠️ Tecnologias Utilizadas

| Tecnologia                | Utilização                          |
| ------------------------- | ----------------------------------- |
| **HTML5**                 | Estrutura da aplicação              |
| **CSS3**                  | Estilização, responsividade e temas |
| **JavaScript**            | Lógica e interatividade             |
| **Chart.js**              | Gráficos analíticos                 |
| **LocalStorage API**      | Persistência local                  |
| **HTML5 Drag & Drop API** | Movimentação de tarefas             |
| **Touch Events**          | Interação em dispositivos móveis    |

---

# 📱 Responsividade

O TaskFlow Pro foi desenvolvido para funcionar em diferentes tamanhos de tela.

### 💻 Desktop

Interface otimizada para monitores e notebooks.

### 📱 Smartphone

Layout adaptado para telas menores e interação touch.

### 📲 Tablet

Experiência intermediária entre desktop e mobile.

A interface se adapta dinamicamente ao espaço disponível.

---

# 🚀 Como Executar

Por ser uma aplicação baseada em arquivo único, não é necessário instalar dependências ou configurar um servidor backend.

## 1. Clone o repositório

```bash
git clone <URL-DO-REPOSITORIO>
```

## 2. Entre na pasta

```bash
cd TaskFlow-Pro
```

## 3. Abra o projeto

Basta abrir:

```text
index.html
```

no navegador.

Também é possível utilizar uma extensão como **Live Server** no VS Code para executar o projeto localmente.

---

# 📂 Estrutura do Projeto

```text
TaskFlow-Pro/
│
├── index.html
│
└── README.md
```

A arquitetura minimalista elimina a necessidade de uma estrutura complexa de pastas.

---

# 🔄 Fluxo de uma Tarefa

O fluxo padrão de uma tarefa pode ser representado da seguinte maneira:

```text
                ┌─────────────┐
                │   A FAZER   │
                └──────┬──────┘
                       ↓
                ┌─────────────┐
                │EM ANDAMENTO │
                └──────┬──────┘
                       ↓
                ┌─────────────┐
                │   REVISÃO   │
                └──────┬──────┘
                       ↓
                ┌─────────────┐
                │  CONCLUÍDO  │
                └─────────────┘
```

A movimentação pode acontecer através de:

- Drag & Drop
- Touch
- Botões direcionais

---

# 🧠 Conceitos Aplicados

O projeto foi desenvolvido aplicando conceitos importantes de desenvolvimento frontend:

- Manipulação do DOM
- Eventos JavaScript
- Event handling
- Estado da aplicação
- CRUD
- Persistência local
- Responsividade
- Design de interfaces
- Componentização lógica
- Drag & Drop
- Touch interaction
- Data visualization
- UX/UI
- Clean Code

---

# 🔐 Privacidade dos Dados

O TaskFlow Pro não depende de um servidor para armazenar as tarefas.

Os dados são armazenados localmente no navegador através do:

```javascript
localStorage;
```

Isso significa que os dados permanecem associados ao navegador e dispositivo utilizados.

> **Importante:** limpar os dados do navegador pode remover as informações armazenadas pelo aplicativo.

---

# 🎯 Objetivo do Projeto

O TaskFlow Pro foi desenvolvido para demonstrar como é possível construir uma aplicação de gerenciamento de projetos funcional e visualmente sofisticada utilizando tecnologias web fundamentais.

Mesmo utilizando uma arquitetura **Single-File**, o projeto demonstra recursos encontrados em aplicações profissionais, incluindo gerenciamento de estado, persistência de dados, visualização analítica, responsividade e interação multiplataforma.

---

# 💡 Diferenciais

### ⚡ Simplicidade

Nenhuma instalação complexa é necessária.

### 📦 Single-File

Toda a aplicação pode ser transportada em um único arquivo.

### 📱 Multiplataforma

Compatível com desktop, tablet e smartphone.

### 🎨 Personalização

Cinco temas visuais disponíveis.

### 📊 Analytics

Dashboard com gráficos dinâmicos.

### 💾 Persistência

Dados armazenados automaticamente no navegador.

### 🖱️ Interação

Drag & Drop, touch e navegação por botões.

---

# 👨‍💻 Autor

**Samuel Lazarin**

Desenvolvedor Full Stack com foco em desenvolvimento de software, automação, qualidade e construção de soluções digitais.

### Tecnologias

```text
JavaScript
TypeScript
Node.js
React
HTML5
CSS3
QA / Test Automation
```

---

# 📄 Licença

Este projeto está disponível para fins de estudo, demonstração e desenvolvimento.

Consulte a licença definida no repositório caso uma licença específica tenha sido adicionada ao projeto.

---

<p align="center">
  Desenvolvido com foco em <strong>Clean Code</strong>, produtividade e experiência do usuário.
</p>

<p align="center">
  🚀 <strong>TaskFlow Pro</strong> — Organize. Execute. Conclua.
</p>
