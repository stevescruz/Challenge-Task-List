<br />
<p align="center">
    <img src="https://res.cloudinary.com/dmct8cfu9/image/upload/v1618085857/task-master_task-add_wzpz3g.png" alt="Logo" width="250">

  <h3 align="center">Todo List CLI by <a href="https://github.com/stevescruz">Steve</a></h3>
 <br />
  <p align="center">
     command-line based task list
       <br />
    <br />
    <a href="https://www.devchallenge.com.br/challenges/607785ac40398e001f6046c6/details">Challenge</a>
    ·
    <a href="https://www.devchallenge.com.br/">DevChallenge</a>
  </p>
</p>

## Table of Contents

* [DevChallenge](#devchallenge) 
* [Challenge](#challenge)
* [Hall of Fame](#hall-of-fame)
* [Requirements](#requirements)
* [Techs](#techs)
* [How to start](#how-to-start)
* [Share](#share)
* [Community](#devchallenge-community)

## Translations

* :us: [EN-US](README.md)
* :brazil: [PT-BR](translations/README_PT-BR.md)

# DevChallenge
<a href="https://devchallenge.now.sh/"> DevChallenge</a> allows you to evolve your skills as a programmer! Join our <a href="https://discord.gg/yvYXhGj">community</a> o/

# Challenge
Your challenge is to create a command-line interface that allows you to maintain a task list with pending and done activities!

# Hall of Fame
The most interesting projects created by users will be displayed at this section to serve as inspiration for other people doing this challenge. Therefore, do not only fulfill the requirements, take your project to the next level.

- [Task Master CLI](https://github.com/stevescruz/task-master) (JavaScript and Node.js) by [Steve](https://github.com/stevescruz).

# Requirements:
The following requirements should be implemented in a command-line interface. This CLI should be controlled by using commands, a menu with options or other creative methods.
1. <b>[add task]</b> : It should be possible to register a new task.

    A task must have a unique id, a description, a creation date, a status (shows if a task is pending or done) and a priority (high, normal or low). Example:
    
    `{ id: 1, description: 'Buy 6 eggs', created: 2021-04-01T20:54:19.410Z, status: 'pending', priority: 'high' };`
2. <b>[mark task as done]</b> : Should be able to update a task's status to done.
3. <b>[delete task]</b> : Should be able to delete a task by providing its corresponding id.
4. <b>[list tasks]</b> : Should be able to list the tasks with status that isn't done.
    
    Instead of showing the creation date of each task, that property should be substituted by a new property that displays how long ago the task was created (1 month). Example:

    `[{ id: 1, description: 'Buy 6 eggs', age: 22 hours, status: 'pending', priority: 'high' }]`
5. <b>[list all tasks]</b> : Should be able to list all tasks, including those with status done.
    
    Instead of showing the creation date of each task, that property should be substituted by a new property that displays how long ago the task was created (1 month).
6. <b>[list next tasks]</b> : Should be able to list a task from each priority. In other words, a high priority task, a normal priority task and a low priority task, if they exist. The listed task of each priority with be the oldest from its group.

    Instead of showing the creation date of each task, that property should be substituted by a new property that displays how long ago the task was created (1 month).<br>
7. <b>[local file or database]</b> : Should be able to persist data so it isn't lost after the CLI finishes execution.

8.  Command line programs must have commands and arguments, then you can use this template in you CLI:
    <ul>
       <li><b> task-master task (-o|--operation) add (-d|--description) "Buy some apples"</b></li>
       <li><b> task-master task (-o|--operation) finish (-t|--task) TASK_ID -> complete task </b></li>
       <li><b> task-master task (-o|--operation) delete (-t|--task) TASK_ID -> delete task </b></li>
       <li><b> task-master task (-l|--list-all) -> list all tasks </b></li>
       <li><b> task-master task (-ln|--list-next) -> list all tasks </b></li>
    </ul>

# Techs: 
- Any technology that you prefer! But, we have some suggestions. :)

## JavaScript

[Commander.js](https://github.com/tj/commander.js/) : tool for creating command-line interfaces that allow the usage of commands, arguments and flags.

[Inquirer.js](https://github.com/SBoudrias/Inquirer.js/) : allows us to create more interactive command-line interfaces. So it can ask questions, display checklists and hide password input.

[Chalk](https://github.com/chalk/chalk) : allows us to style command-line interfaces.

[CLI Table 3](https://github.com/cli-table/cli-table3) : makes it easier to create and display tables in command-line interfaces.

Other options: Vorpal.js, Caporal.js, Yargs.js, Glue Gun, Seeli.js, Figlet.js, Oclif, Meow, Color.js, Progressbar, Clui.js, Enquirer.

## Java

Suggest Java tools at our Discussions section.

## PHP

Suggest PHP tools at our Discussions section.

## Python

Suggest Python tools at our Discussions section.

# How to start:
1 - Use this template (click at *Use this template*) or fork this repository with the instruction<br>
2 - Read the instructions at README.md<br>
3 - Start to code! Feel free to use the workflow that is the most confortable for you.<br>
4 - Share your results with the community! Use the following hashtag: #devchallenge

# Share!
Start you project using this template in your GitHub as a public repository<br>
Capture a screenshot, GIF or video share the results with #devchallenge or tagging our account @devchallenge!<br>

Challenge created by <a href="https://www.linkedin.com/in/stevescruz/">Steve</a> :)


# DevChallenge Community
Website: https://www.devchallenge.com.br/ <br>
Discord: https://discord.gg/yvYXhGj <br>
LinkedIn: https://www.linkedin.com/company/devchallenge/<br>
Twitter: https://twitter.com/dev_challenge<br>
Instagram: https://www.instagram.com/devchallenge/<br>
