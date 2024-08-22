Instruções para de como rodar o Projeto:

1- *Descompactar* 
2 - ter certeza que o editor de codigos reconhece o java e as classes
2 - rodar o projeto através do arquivo: PtojryoAplicattion com java 17
3 - Abrir no editor de codigos 
4 - cd frontend 
5 - cd App 
6 - npm install
7 - npm start 

8 - O banco de dados nesse projeto é o postres
login: postgres
Senha: postgres

Dentro do postgres Crie um banco de dados com o seguinte comando: 
 create database clinica
9 - Para Rodar os testes vai entrar na pasta test e terá 2 pastas model e dervice dentro terá os arquivos de test
 
O frontend precisa rodar na porta: http://localhost:3000
A documentação em swagger está nesse link: http://localhost:8080/swagger-ui/index.html#/

10 - em cadastrar clientes adiciono nome: Nick, Descrição: Poodle marrom,
(Escolha uma imagem da internet para adicionar uma foto para o seu cão) Foto:https://i.pinimg.com/236x/e3/c4/c2/e3c4c29c96682867a1b5ea9ee98bcddf.jpg,
Categoria: Cachorro, data de nascimento:08/05/2024, disponivel: sim e Salve
Será redirecionado para a lista de clientes, onde vc pode excluir ou editar os clientes salvos.
