# Instruções para Rodar o Projeto

1. **Descompactar o projeto.**

2. **Certifique-se de que o editor de código reconhece o Java e as classes.**

3. **Rodar o projeto através do arquivo `ProjetoApplication` com Java 17.**

4. **Abrir o projeto no editor de código.**

5. **Navegar para o diretório `frontend` e depois para o diretório `App`:**
    ```bash
    cd frontend
    cd App
    ```

6. **Instalar as dependências do projeto:**
    ```bash
    npm install
    ```

7. **Iniciar o frontend:**
    ```bash
    npm start
    ```

8. **Configuração do Banco de Dados:**
   - O banco de dados utilizado é o PostgreSQL.
   - **Login:** postgres
   - **Senha:** postgres
   - **Criação do Banco de Dados:**
     ```sql
     CREATE DATABASE clinica;
     ```

9. **Para rodar os testes:**
   - Navegue até a pasta `test`.
   - Dentro da pasta `test`, você encontrará duas pastas: `model` e `service`.
   - Execute os testes nos arquivos dentro dessas pastas.

10. **Configuração Adicional:**
    - O frontend precisa rodar na porta: [http://localhost:3000](http://localhost:3000).
    - A documentação Swagger está disponível em: [http://localhost:8080/swagger-ui/index.html#/](http://localhost:8080/swagger-ui/index.html#/).

11. **Cadastro de Clientes:**
    - **Nome:** Nick
    - **Descrição:** Poodle marrom
    (Você pode copiar e colar um link da internet para cadastrar a foto do seu pet)
    - **Foto:** ![Foto do Nick](https://i.pinimg.com/236x/e3/c4/c2/e3c4c29c96682867a1b5ea9ee98bcddf.jpg)
    - **Categoria:** Cachorro
    - **Data de Nascimento:** 08/05/2024
    - **Disponível:** Sim

    Após cadastrar, você será redirecionado para a lista de clientes, onde poderá excluir ou editar os clientes salvos.
