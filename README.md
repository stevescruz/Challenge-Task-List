<br />
<p align="center">
    <img src="https://res.cloudinary.com/dmct8cfu9/image/upload/v1620183656/carbon_todolist-cli.png" alt="Logo" width="250">

  <h3 align="center">Todo List CLI by <a href="https://github.com/stevescruz">Steve</a></h3>
 <br />
  <p align="center">
     Command-line based task list
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
The following requirements should be implemented in a command-line interface. This CLI should be controlled by using commands (including subcommands and arguments), a menu with options or other creative methods.
1. **[optional]** If you decide to use commands keep in mind that they have to be an explicit action, while arguments use a dash (`-a` or `--argument`) and are responsible for modifying a command's behavior. Example:

```bash
task <subcommand> # Accepts add, complete, delete, list and next as subcommands

task add <description> [-p <priority>] # Adds a pending task. Can set the task's priority to low, normal or high with the -p (or --priority) option

task complete <id> # Marks a task as done
task delete <id> # Deletes a task
task list [-a] # Shows pending tasks. The -a (or --all) option shows all tasks
task next # Shows the next task of each priority
```
2. **[add task]** : It should be possible to register a new task.

    A task must have a unique id, a description, a creation date, a status (shows if a task is pending or done) and a priority (high, normal or low). Example:
    
    ```javascript
    { id: 1, description: 'Buy 6 eggs', created: 2021-04-01T20:54:19.410Z, status: 'pending', priority: 'high' };
    ```
3. **[mark task as done]** : Should be able to update a task's status to done.
4. **[delete task]** : Should be able to delete a task by providing its corresponding id.
5. **[list tasks]** : Should be able to list the tasks with status that isn't done.
    
    Instead of showing the creation date of each task, that property should be substituted by a new property that displays how long ago the task was created (1 month). Example:
    ```javascript
    [{ id: 1, description: 'Buy 6 eggs', age: 22 hours, status: 'pending', priority: 'high' }]
    ```
6. **[list all tasks]** : Should be able to list all tasks, including those with status done.
    
    Instead of showing the creation date of each task, that property should be substituted by a new property that displays how long ago the task was created (1 month).
7. **[list next tasks]** : Should be able to list a task from each priority. In other words, a high priority task, a normal priority task and a low priority task, if they exist. The listed task of each priority with be the oldest from its group.

    Instead of showing the creation date of each task, that property should be substituted by a new property that displays how long ago the task was created (1 month).
8. **[local file or database]** : Should be able to persist data so it isn't lost after the CLI finishes execution.

# Techs: 
- Any technology that you prefer! But, we have some suggestions. :)

## JavaScript

[Commander.js](https://github.com/tj/commander.js/) : tool for creating command-line interfaces that allow the usage of commands, arguments and flags.

[Inquirer.js](https://github.com/SBoudrias/Inquirer.js/) : allows us to create more interactive command-line interfaces. So it can ask questions, display checklists and hide password input.

[Chalk](https://github.com/chalk/chalk) : allows us to style command-line interfaces.

[TTY Table](https://github.com/tecfu/tty-table) : makes it easier to create and display tables in command-line interfaces.

Other options: Vorpal.js, Caporal.js, Yargs.js, Glue Gun, Seeli.js, Figlet.js, Oclif, Meow, Color.js, CLI Table 3, Progressbar, Clui.js, Enquirer.

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