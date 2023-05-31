# 📅 Tasks App (To-Do List)

Website de um organizador de tarefas (to-do list) feito com React JS, Tailwind CSS, TypeScript, Redux Toolkit e mais.

![página inicial](https://github.com/aridsm/tasks-app/blob/master/public/To-Do%20List%20_%20All%20tasks.png)

## Descrição

Applied to organize your tasks with the following data: title, description, date, mark as complete and mark as important.
Tasks are organized into routes: today's tasks, important tasks, incomplete, complete, all tasks and tasks by directory (folder). Directories and tasks can be edited or deleted. In addition, there is a main directory called "Main" which cannot be edited or deleted.
The list of tasks can be displayed first in: nearest, furthest, complete or incomplete.
You can search for any tasks in the search field.
Today's tasks are shown in the user section and notifications.
Tasks, directories, and darkmode data are saved to localStorage.

## Objetivo

O projeto teve principalmente como objetivo pôr em prática conhecimentos de TypeScript, Tailwind, Redux Toolkit e React Js.

## Ferramentas utilizadas

- React JS
- TypeScript
- Tailwind CSS
- Redux Toolkit
- React Router DOM
- HTML
- Figma (prototipagem)

## Como testar

Você pode acessar o projeto aqui: https://tasks-app-aridsm.netlify.app/

Ou rodar na sua máquina: 

``` 
git clone https://github.com/aridsm/tasks-app.git
cd tasks-app
npm install
npm start
```

## Observações

- Os dados de tarefas, diretórios e darkmode ficam salvos no localStorage do seu navegador. Você pode clicar no botão "delete all data" para removê-los do localStorage.
- Para fins demonstrativos, o aplicativo possui uma lista padrão de 3 tarefas e 1 diretório chamado "Main".
