# aplicacao-nodejs
- models 		<!-- Nossos arquivos de definições de models no MongoDB -->
----- Contato.js 	<!-- Define o model Contato utilizando a biblioteca mongoose -->
- public 			<!-- Onde colocaremos os arquivos de front-end do AngularJS -->
----- core.js 		<!-- Códigos do AngularJS -->
----- index.html 	<!-- Nossa view principal -->
- routes 			<!-- Nossos arquivos de definições de rotas -->
----- index.js 		<!-- Todas as rotas da nossa aplicação ficarão no arquivo index.js -->
- package.json 	<!-- Configurações npm para instalar nossas dependências/módulos -->
- app.js 			<!-- Configurações do node -->


Método HTTP	URL	Descrição:

GET	/api/contatos	                Buscar todos os contatos
POST	/api/contatos	            Criar um novo contato
DELETE	/api/contatos/:contato_id	Deletar um contato pelo ID
GET	/api/contatos/:contato_id	    Buscar um contato pelo ID
PUT	/api/contatos/:contato_id	    Atualizar um contato pelo ID

Nossa view

Aqui iremos criar nosso html para interagir com nossa aplicação em Angular. Este html terá as seguintes ações:

- Especificar nosso módulo e controller
- Iniciar a página para buscar todos os contatos
- Fazer um loop nos contatos recebidos
- Ter um formulário para criarmos um novo contato
- Deletar um contato
