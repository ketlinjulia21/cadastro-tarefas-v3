📋 Cadastro de Tarefas



Uma aplicação web simples e funcional para cadastro e controle de tarefas. Desenvolvida com backend em Node.js, Express e MySQL, utilizando Sequelize como ORM.

✨ Funcionalidades
🔹 Cadastrar novas tarefas
🔹 Listar tarefas existentes
🔹 Atualizar o status (pendente/concluída)
🔹 Interface simples e responsiva
🔹 Persistência de dados com MySQL

🖥️ Tecnologias e Ferramentas
💡 Ferramenta	💬 Descrição
Node.js	Ambiente de execução JavaScript no backend
Express	Framework leve para criação de APIs
Sequelize	ORM que facilita a comunicação com banco relacional
MySQL	Banco de dados relacional
HTML/CSS	Estrutura e estilo da interface do usuário
Postman (opcional)	Testes de rotas da API

📁 Estrutura do Projeto
pgsql
Copiar
Editar
cadastro-tarefas/
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
├── public/
│   ├── index.html
│   └── style.css
├── screenshot.png
└── README.md
📸 Demonstração
<img src="./screenshot.png" width="700" alt="Captura de tela da aplicação"/>
🧪 Rotas da API
Método	Rota	Descrição
GET	/tarefas	Lista todas as tarefas
POST	/tarefas	Cadastra nova tarefa
PUT	/tarefas/:id	Atualiza status da tarefa
DELETE	/tarefas/:id	Deleta uma tarefa

▶️ Como executar localmente
bash
Copiar
Editar
# Clone o repositório
git clone https://github.com/seuusuario/seurepositorio.git

# Acesse a pasta
cd seurepositorio

# Instale as dependências
npm install

# Inicie o servidor
node backend/server.js
Acesse no navegador:
http://localhost:3000

📚 O que eu aprendi com esse projeto
Práticas com Node.js e Express

Uso de Sequelize para conectar com MySQL

Manipulação de dados no backend

Construção de interface HTML com estilo próprio

Organização de arquivos em padrão MVC básico

📝 Licença
Este projeto está sob a licença MIT.
Sinta-se à vontade para usar, modificar e compartilhar.

Se quiser, posso adicionar:

✔️ GIF animado mostrando o funcionamento

✔️ Tradução para inglês

✔️ Autores/contribuintes

✔️ Banco de dados .sql para importar
