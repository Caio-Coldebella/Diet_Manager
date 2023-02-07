# gerenciador_dieta

 &nbsp;&nbsp;&nbsp;&nbsp;Esse é um projeto pessoal, feito utilizando React, Node.js e PostgreSQL, trata-se de um MPV (Mínimo Projeto Viável) de um aplicativo de alimentação e fitness.<br/>
 &nbsp;&nbsp;&nbsp;&nbsp;Na tela inicial há a aba para realização de login ou redirecionamento para o cadastro de usuário, aonde é pedido email e senha (a qual é salva criptografada).
 A aplicação utiliza persistência de login através do armazenamento em localstorage.<br/>&nbsp;&nbsp;&nbsp;&nbsp;Na tela home podemos observar a aba de cadastro da dieta, aonde o usuário pode adicio
 nar uma nova refeição, abrir cada refeiçao para observar seu conteúdo, e analizar as informações de macros e calorias de todas as refeições. Dentro de cada aba de
 refeição é possível observar as informações de toda a refeição, apagar a refeição, acessar cada alimento e inserir novos alimentos na refeição. Ao clicar em cada
 alimento da refeição podemos remover este e observar suas informações, e para inserir um alimento, a cada letra digitada o app busca no banco local alimentos que 
 começem com aquelas iniciais e sugere para o usuário, ao selecionar o alimento é perguntada a quantidade em gramas deste.<br/>&nbsp;&nbsp;&nbsp;&nbsp;Ao pesquisar o alimento, caso este não esteja no banco é feita uma requisição para uma API externa, com informações
 de diversos alimentos (Edaman API), caso seja encontrado ele é adicionado ao banco de dados para requisições futuras. Além desta aba da dieta, é possível inserir um alimento no
 banco manualmente, com suas informações, ao clicar no canto superior direito da tela. No canto inferior da tela podemos acessar o painel de informações físicas pessoasi, uma implementação futura do projeto.
 
 ## Executando o projeto (com Docker)
 Clonar este repositório, e dentro deste clonar os repositorios front-end e back-end. Executar o docker-compose com "docker-compose up --build nginx",
 lembrar de adicionar o .env.development na raíz do back-end
 
 ## Executando o projeto (com Node)
 Clonar os repositórios front-end e back-end, adicionar o .env no front e o .env.development no back-end. Executar o front-end com "npm run start", e o back-end
 com "npm run dev"
 
 ## Link dos repositórios
 Front-end: https://github.com/Caio-Coldebella/gerenciador_dieta_frontend <br/>
 Back-end: https://github.com/Caio-Coldebella/gerenciador_dieta_backend
