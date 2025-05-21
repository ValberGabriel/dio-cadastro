Tela de Cadastro - DIO
Este é um projeto React que implementa uma tela de cadastro simples e estilizada , inspirada na plataforma da DIO (Digital Innovation One) . Foi desenvolvido com boas práticas, hooks, formulários controlados e estilização usando styled-components.

Objetivo
Recriar uma tela de cadastro com interface moderna e funcionalidade básica, aplicando os conceitos aprendidos em:

Criação de projetos com React CLI
Estilização com styled-components
Manipulação de estado com Hooks (useState)
Formulários controlados
Estruturação de componentes reutilizáveis

🛠️ Tecnologias Utilizadas
React – Biblioteca principal
Vite (ou Create React App) – CLI para criação rápida do projeto
styled-components – Para estilização customizada e modular
React Hooks – Controle de estado dos campos do formulário
ES6+ – Sintaxe moderna do JavaScript

📁 Estrutura do Projeto
src/
├── components/
│   └── FormCadastro.jsx       # Componente reutilizável do formulário
├── pages/
│   └── Home.jsx               # Página inicial com o formulário centralizado
├── styles/
│   └── globalStyles.js        # Estilos globais da aplicação
├── App.jsx                    # Componente raiz
└── main.jsx                   # Ponto de entrada da aplicação

Funcionalidades
Campos de nome, e-mail, senha e confirmação de senha
Validação simples de senhas (verifica se as duas senhas coincidem)
Interface responsiva e estilizada
Código organizado por componentes e páginas

Como Rodar o Projeto
Clone o repositório:
bash
git clone https://github.com/seu-usuario/dio-cadastro.git 
cd dio-cadastro
Instale as dependências:
bash



npm install
Inicie o servidor de desenvolvimento:

bash
npm run dev
Acesse a aplicação no navegador:

http://localhost:5173  Ou outra porta conforme sua configuração
Se você usou Create React App , use: 

bash
npm start

Melhorias Futuras (Sugestões)
Adicionar validação de e-mail e CPF
Integração com Firebase ou API real
Roteamento com react-router-dom
Armazenamento com localStorage ou contexto global
Testes unitários com Jest + React Testing Library

Créditos
Desenvolvido durante o módulo de React CLI, hooks e formulários da DIO .
Por: Valber Gabriel
Data: Maio/2025