# 📝 To-Do List Angular

Uma aplicação simples e moderna de lista de tarefas desenvolvida com **Angular**, **TypeScript** e **SCSS**, com foco em aprendizado e boas práticas de componentização.

## 🚀 Sobre o projeto

Esta To-Do List foi desenvolvida com o objetivo de praticar conceitos fundamentais do Angular, como **standalone components**, **serviços reativos (BehaviorSubject)**, **data binding**, **event emitters**, e **persistência local com LocalStorage**.

A aplicação permite gerenciar tarefas de forma simples e intuitiva:
- ➕ Adicionar novas tarefas com título e descrição  
- ✅ Marcar tarefas como concluídas  
- 🔁 Reabrir tarefas concluídas  
- ❌ Excluir tarefas  
- 💾 Salvar tudo automaticamente no navegador (LocalStorage)

---

## 🧱 Tecnologias utilizadas

- **Angular** (v16 ou superior)  
- **TypeScript**  
- **RxJS** (para reatividade com `BehaviorSubject`)  
- **SCSS** (estilização com nesting e variáveis)  
- **HTML5** e **CSS3**  
- **LocalStorage API**

---

## 🧩 Estrutura principal do projeto

```text
src/
 ├── app/
 │   ├── models/
 │   │   └── task.ts
 │   ├── services/
 │   │   └── task.service.ts
 │   ├── components/
 │   │   ├── task-card/
 │   │   ├── task-form/
 │   │   └── tasks-list/
 │   └── app.component.ts
 │
 ├── assets/
 ├── styles.scss
 └── main.ts
⚙️ Funcionalidades
Funcionalidade	Descrição
🧾 Adicionar tarefa	Cria uma nova tarefa com título e descrição.
🔄 Marcar como concluída	Alterna entre pendente e concluída.
🗑️ Excluir tarefa	Remove a tarefa definitivamente.
💽 Salvar localmente	Armazena e carrega tarefas via LocalStorage.
🌗 Interface moderna	Layout limpo, responsivo e intuitivo, com SCSS.

markdown
Copiar código
![To-Do List Screenshot](./src/assets/todo-screenshot.png)
🧠 Conceitos aprendidos / praticados
Componentização com standalone components

Comunicação entre componentes (@Input / @Output)

Serviços reativos com RxJS (BehaviorSubject e Observable)

Persistência de dados com localStorage

Estilização modular com SCSS

Organização de pastas e arquitetura de projeto Angular

Pipes (date, async) e diretivas estruturais (*ngFor, *ngIf)

▶️ Como executar o projeto
Clonar o repositório

bash
Copiar código
git clone https://github.com/seu-usuario/todo-list-angular.git
Instalar dependências

bash
Copiar código
cd todo-list-angular
npm install
Rodar o servidor de desenvolvimento

bash
Copiar código
ng serve -o
Acesse http://localhost:4200

📚 Próximas melhorias (ideias futuras)
🌓 Modo claro/escuro

🗓️ Filtro por data de criação

🔍 Barra de busca de tarefas

📱 Melhorias de responsividade mobile

☁️ Integração com backend (API REST)

🧑‍💻 Autor
Pedro Soares Silva
📍 Desenvolvido como parte de estudos em Angular e boas práticas de frontend.
📧 pedrosoarex@outlook.com
🌐 
