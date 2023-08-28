##How to run:

1. Download repository on your computer with the command:
`git clone _repository_url_ `
2. From the game repository, run:
`flask run`

The terminal will display a localhost link by which you can access the game.

Or, if you have Docker installed:

1. Copy game/docker-compose.yml to your computer
2. From the repository with the docker-compose file, run:
`docker compose up -d`

##Description

The game is going to be accessible on the assigned port on your localhost.

It is a game with two caracters, each belongs to one of the two classes, is equipped with one of three types of armor and with one of three types of weapon. Each class grants a special skill, that a hero can use in battle. Heroes can attack, use a special skill or skip turns. Their attacks depend on their stamina and the stats of their equipment, the usage of a skil depends on stamina as well. The hero who lost all of it's health points first loses.

This project was an excercize of the best practices of object-oriented programming, as well as an example of the not so harmful use of the singleton pattern. The frontend part was provided by tutors.