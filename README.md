🔐 Firebase Authentication com React + Vite
📌 Descrição

Este projeto é uma aplicação web desenvolvida com React (Vite) que utiliza o Firebase Authentication para realizar:

Cadastro de usuários
Login
Controle de sessão
Logout

A aplicação altera a interface dinamicamente conforme o estado de autenticação do usuário.

🚀 Tecnologias utilizadas
React
Vite
Firebase Authentication
⚙️ Funcionalidades

✅ Cadastro com email e senha
✅ Login de usuário
✅ Tratamento de erros (senha fraca, email inválido, etc.)
✅ Persistência de sessão (usuário continua logado ao recarregar)
✅ Loading durante autenticação
✅ Interface dinâmica (logado vs não logado)
✅ Logout

🔥 Configuração do Firebase
Acesse o Firebase
Crie um projeto
Ative o Authentication
Habilite o método:
Email/Senha
Copie as credenciais do projeto e adicione no arquivo:
src/firebase.js
📦 Instalação e execução
Instale as dependências:
npm install
Execute o projeto:
npm run dev
Acesse no navegador:
http://localhost:5173
📂 Estrutura básica
src/
 ├── App.jsx
 ├── firebase.js
 └── assets/
👤 Uso da aplicação
Usuário pode se cadastrar com email e senha
Após cadastro/login, o sistema mostra o email do usuário
É possível sair da conta clicando em "Logout"
📄 Observação

Este projeto foi desenvolvido como atividade prática para aprendizado de autenticação com Firebase.
