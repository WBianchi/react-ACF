# react-ACF

Execução do projeto 

# Subindo o projeto no git

01-Primeiro vá no github e crie seu repositório. Clique no símbolo de + no topo da tela e depois em New Repository. Preencha um nome e uma descrição para o projeto e clique em Create repository.

02-Navegue até a pasta do seu repositório e dentro dela use o comando git init, isso vai transformar a sua pasta em um projeto git (Não vai mudar nada).

03-Agora precisamos linkar seu projeto com o seu repositório no github, pra isso você vai usar o comando git remote add origin https://github.com/user/repo.git. Você vai ter que mudar o link para o link do seu projeto, um projeto meu por exemplo é https://github.com/userr/nome-do-repo.git, use o link do seu projeto.

04-Pronto agora é só subir seus arquivos pro github. Use o comando git add . para adicionar todos os arquivos do projeto. Crie um commit inicial git commit -m "primeiro commit" e depois dê o push git push origin master.

05-E por fim depois dê uma olhada em como criar o seu arquivo .gitignore ele serve para fazer o git ignorar algumas pastas que você não precisa subir para o github (No caso do javascript a pasta node_modules e em outros projetos as pastas com outras libs que só são usadas localmente e etc).


# Baixando o Wordpress

01-Baixe a ultima versão do wordpress (https://br.wordpress.org/download/)
02-Se você possui uma hospedagem descompacte o arquivo na pasta public_html ou se for local (xampp/htdocs)

# Configure o seu banco de dados

01-Acesse (seuip/phpmyadmin) ou se você possuir uma hospedagem acesse (0.0.0.0/phpmyadmin ou vá até o gerenciador de banco de dados da sua hospedagem e crie uma tabela com o nome da sua aplicação, pois é com essa tabela que criaremos o nosso banco de dados) 

# Instalando o Wordpress

01-Após baixar o wordpress e configurar o seu banco de dados, vá para a pagina inicial da aplicação e vamos dar inicio a instalação.

02-Ao entrar na pagina e clicar no botão próximo você vera que uma tela solicitando algumas informações para instalar o wordpress, preencha essas informações da seguinte forma.
Nome do banco de dados (Nome do banco criado)
Nome de usuário do banco de dados (root)
Senha do banco de dados (geralmente vem padronizado sem a senha)
Servidor do banco de dados (localhost)
Prefixo de tabela (se quiser rodar mais de um WordPress no mesmo banco de dados)

# Seja bem-vindo ao Wordpress

Tudo preparado, vamos dar inicio a instalação do plugin e do build da aplicação

# Instalando o plugin ACF (Advanced Custom Fields)

01-Após acessar a pagina principal da sua aplicação WP você vera que no menu superior da pagina possui algumas informações, na onde esta descrito o nome do seu site, passe o mouse por cima e clique na opção painel.

02-Seja bem-vindo ao painel administrativo do Wordpress... No menu lateral esquerdo você vera que possui varias opções, vá até plugin e clique em adicionar plugin, você sera redirecionado para uma pagina onde podera instalar o plugin ACF, basta digitar o nome do plugin no campo busca, instalar, ativar e pronto, seu plugin esta ativo.










