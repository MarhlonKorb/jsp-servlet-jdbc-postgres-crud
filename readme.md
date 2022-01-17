# jsp-servlet-jdbc-postgres-crud
Cadastro de dados de usuários utilizando conceitos de Servlets e JSP, integrando PostgreSQL 10 para realizar o armazenamento das informações no banco de dados.

<h2>Tecnologias utilizadas</h2>
<p>As tecnologias utilizadas no projeto foram Servlet, uma classe Java que permite realizar requisições Http para um container Web, que nesse caso foi o TomCat versão 9 e o gerenciador de banco de dados escolhido foi o PostgreSQL na versão 10.</p>
<h2>Aprendizado</h2>
<p>Nesse projeto consegui compreender melhor o uso do padrão MVC de projeto, possibilitando separar uma classe Servlet(onde são realizadas as requisições http), a classe "Usuário", a conexão com o SGBD e a parte de front end.</p>
<p>Na parte de front end foi utilizado estilizações em CSS e Bootstrap.</p>
<p>Foram adicionadas as libraries jstl-1.2.jar para para gerar linguagens de marcação para necessidades especiais nas jsp´s e o driver postgresql-42.3.1.jar para a conexão com o banco de dados.</p>

<h2>Criação da tabela no banco de dados "demo"</h2>

```
create table users(
id  serial not null,
name CHARACTER(250),
email CHARACTER(150),
country CHARACTER(150)
)
```

<h2>Imagens do funcionamento das pages</h2>

![](https://github.com/MarhlonKorb/jsp-servlet-jdbc-postgres-crud/blob/master/.settings/Captura%20de%20Tela%20(122).png)

![](https://github.com/MarhlonKorb/jsp-servlet-jdbc-postgres-crud/blob/master/.settings/Captura%20de%20Tela%20(123).png)

![](https://github.com/MarhlonKorb/jsp-servlet-jdbc-postgres-crud/blob/master/.settings/Captura%20de%20Tela%20(121).png)

<p>O projeto foi inspirado em um vídeo didático de um canal do youtube.</p>

Clone meu repositório:

```
gh repo clone MarhlonKorb/jsp-servlet-jdbc-postgres-crud
```

<p>Agradeço por você ter lido até aqui. Para entrar em contato envie um email para: marhlonkorb@hotmail.com </p>
