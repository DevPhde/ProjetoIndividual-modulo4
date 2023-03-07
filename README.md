<h1>Projeto Individual 4 - Programadores Cariocas - Sistema Resilia</h1>

<h2>🎯 Objetivo </h2>

O projeto intitulado Sistema Resilia é uma proposta do curso de Desenvolvimento Web Full-Stack do programa Programadores Cariocas, realizado através da parceria entre Resília Educação, Prefeitura do Rio de Janeiro e Senac RJ. Ele foi desenvolvido com a seguinte proposta

"A Resilia está pensando em lançar um novo sistema de acompanhamento e para isso precisa de ajuda para modelar um banco de dados que vai armazenar seus cursos, turmas e alunos. Para apoiar nesse sistema recebemos a tarefa de realizar essa modelagem e responder algumas perguntas com nosso modelo:

1) Existem outras entidades além dessas três?
2) Quais são os principais campos e tipos?
3) Como essas entidades estão relacionadas?

## :wrench: Tecnologias utilizadas
<img align="center" alt="CSS" height="50" width="60" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" />

<h2>📑 Resoluções </h2>

Quanto às respostas das perguntas:

### 1) Existem outras entidades além dessas três?
Sim. Na modelagem criada foi adicionado a entidade "Professor",a entidade professor é essencial para que a entidade turma faça sentido, uma turma precisa de um professor para ministrar as aulas.<br/>

### 2) Quais são os principais campos e tipos?<br/>
Aluno -> id(int - PK), nome(varchar),matricula(varchar), cpf(varchar), data_nascimento(date), id_turma(int - FK)
Professor -> id(int - PK), nome(varchar), cpf(varchar), email(varchar), id_turma(int - FK)
Turma -> id(int - PK), num_turma(int), serie(int), id_curso(int - FK)
curso -> (int - PK), nome_curso(varchar)

### 3) Como essas entidades estão relacionadas?<br/>
![MODELAGEM](https://user-images.githubusercontent.com/113299561/223325700-ae14f0ef-8108-42cf-ab48-6ceeb2c3226e.png)

## Consultas
<details><summary><strong>Curso</strong></summary>
  
![select curso](https://user-images.githubusercontent.com/113299561/223326070-2d95dcda-a9ba-496c-89d9-c99f955dfe40.png)

</details>&nbsp;
<details><summary><strong>Turma</strong></summary>
  
![select turma](https://user-images.githubusercontent.com/113299561/223326099-4ff45586-a831-4869-af89-e9a139602674.png)

</details>&nbsp;
<details><summary><strong>Aluno</strong></summary>
  
![select aluno](https://user-images.githubusercontent.com/113299561/223326123-78e239c6-21f6-49a5-a5a6-97b411de26f9.png)

</details>&nbsp;
<details><summary><strong>Professor</strong></summary>
  
![select professor](https://user-images.githubusercontent.com/113299561/223326160-50543ea2-48c2-447e-a6f4-d8e483582247.png)

</details>&nbsp;

## :dart: Status do projeto
Projeto finalizado.
