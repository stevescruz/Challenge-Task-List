<br />
<p align="center">
    <img src="https://res.cloudinary.com/dmct8cfu9/image/upload/v1618085857/task-master_task-add_wzpz3g.png" alt="Logo" width="250">

  <h3 align="center">Todo List CLI by <a href="https://github.com/stevescruz">Steve</a></h3>
 <br />
  <p align="center">
     Lista de tarefas por interface de linha de comando
       <br />
    <br />
    <a href="https://github.com/stevescruz/Challenge-Task-List">Desafio</a>
    ·
    <a href="https://www.devchallenge.com.br/">DevChallenge</a>
  </p>
</p>

## Índice

* [DevChallenge](#devchallenge) 
* [Desafio](#desafio)
* [Galeria da Fama](#galeria-da-fama)
* [Requisitos](#requisitos)
* [Techs](#techs)
* [Como começar](#como-começar)
* [Compartilhe](#compartilhe)

# DevChallenge
<a href="https://devchallenge.now.sh/"> DevChallenge</a> permite que você evolua suas skills como programador! Participe da nossa <a href="https://discord.gg/yvYXhGj">comunidade</a> o/

# Desafio
Seu desafio é criar uma interface de linha de comando que lhe permita manter uma lista de tarefas com atividades pendentes e finalizadas!

# Galeria da Fama
Os projetos mais interessantes criados pelos usuários serão exibidos nesta seção para servir de inspiração para quem vai fazer o desafio. Portanto não apenas cumpre os requisitos, leve o seu projeto para o próximo nível.

- [Task Master CLI](https://github.com/stevescruz/task-master) (JavaScript e Node.js) by [Steve](https://github.com/stevescruz).

# Requisitos:
Os seguintes requisitos deverão ser implementados em uma interface de linha de comando. Esse CLI deverá ser controlado por meio de comandos, menu de opções ou outros métodos criativos.
1. <b>[adicionar tarefa]</b> :  Deverá ser possível cadastrar uma nova tarefa.

    Uma tarefa terá obrigatoriamente um id único, uma descrição, uma data de criação, o status (mostra se uma tarefa está pendente ou finalizada) e uma prioridade (pode ser alta, normal ou baixa). Exemplo:
    
    `{ id: 1, descricao: 'Comprar 6 ovos', criado: 2021-04-01T20:54:19.410Z, status: 'pendente', prioridade: 'alta' };`
2. <b>[marcar tarefa como finalizada]</b> : Deverá ser possível alterar o status de uma tarefa para finalizada.
3. <b>[deletar tarefa]</b> : Deverá ser possível deletar uma tarefa informando o id correspondente a ela.
4. <b>[listar tarefas]</b> : Deverá ser possível listar as tarefas que possuem um status diferente de finalizada.
    
    Ao invés de mostrar a data de criação de cada tarefa, a propriedade deverá ser substituída por uma nova propriedade que mostra há quanto tempo a tarefa foi criada (1 mês). Exemplo:

    `[{ id: 1, descricao: 'Comprar 6 ovos', criado: 22 horas, status: 'pendente', prioridade: 'alta' }]`
5. <b>[listar todas tarefas]</b> : Deverá ser possível listar todas tarefas, inclusive as que possuem o status finalizada.
    
    Ao invés de mostrar a data de criação de cada tarefa, a propriedade deverá ser substituída por uma nova propriedade que mostra há quanto tempo a tarefa foi criada (1 mês).
6. <b>[listar próximas tarefas]</b> : Deverá ser possível listar uma tarefa de cada prioridade, ou seja, uma tarefa de prioridade alta, uma tarefa de prioridade normal e uma tarefa de prioridade baixa, caso existam. A tarefa listada de cada prioridade será a mais antiga do seu grupo.

    Ao invés de mostrar a data de criação de cada tarefa, a propriedade deverá ser substituída por uma nova propriedade que mostra há quanto tempo a tarefa foi criada (1 mês).<br>
7. Deverá haver persistência dos dados para que eles não sejam perdidos após o fechamento da interface de linha de comando.

# Techs: 
- Tecnologia que preferir! Mas, temos algumas sugestões. :)

## JavaScript

[Commander.js](https://github.com/tj/commander.js/) : ferramentas para criar uma interface de linha de comando que permite o uso de comandos, argumentos e flags.

[Inquirer.js](https://github.com/SBoudrias/Inquirer.js/) : permite criar interfaces de linha de comando mais interativas. Lhe permitem criar perguntas, checklists e input de senhas.

[Chalk](https://github.com/chalk/chalk) : permite a estilização de interfaces de linha de comando.

[CLI Table 3](https://github.com/cli-table/cli-table3) : facilita a criação e exibição de tabelas em interfaces de linha de comando.

Outras opções: Vorpal.js, Caporal.js, Yargs.js, Glue Gun, Seeli.js, Figlet.js, Oclif, Meow, Color.js, Progressbar, Clui.js, Enquirer.

## Java

Aceitamos sugestões de ferramentas do Java nos issues.

## PHP

Aceitamos sugestões de ferramentas do PHP nos issues.

## Python

Aceitamos sugestões de ferramentas do Python nos issues.

# Como começar:
1 - Use esse template (clicando em *Use this template*) ou faça um fork deste repositório com o código inicial<br>
2 - Leia as instruções no README.md<br>
3 - Comece a codar! Sinta-se livre para utilizar o fluxo de trabalho que ache mais confortável<br>
4 - Compartilhe seu resultado com a comunidade! Utilize a seguinte hashtag: #devchallenge

# Compartilhe!
Inicie seu projeto utilizando esse template no seu GitHub como um repositório público<br>
Faça um print, GIF ou vídeo e compartilhe o resultado com a #devchallenge ou marcando nosso perfil @devchallenge!<br>

Desafio criado por <a href="https://www.linkedin.com/in/stevescruz/">Steve</a> :)


# Comunidade DevChallenge
Site: https://www.devchallenge.com.br/ <br>
Discord: https://discord.gg/yvYXhGj <br>
LinkedIn: https://www.linkedin.com/company/devchallenge/<br>
Twitter: https://twitter.com/dev_challenge<br>
Instagram: https://www.instagram.com/devchallenge/<br>