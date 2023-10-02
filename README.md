<i>Ридми на русском — внизу.</i>

# Singleton Game

## How to run:

1. Download the repository to your computer.
2. In terminal, from the root of the repository, run:
`flask run`

The terminal will display a localhost link which leads to the game.

Or, if you have Docker installed:

1. Copy the docker-compose.yml file to your computer.
2. In terminal, from the repository with the docker-compose file, run:
`docker compose up -d`

After that, go to Docker and open the game by the running container link.

## Description

It is a game with two characters, for each you can choose one of two classes, one of three armors, and one of three weapons. Each class grants a special skill, that a hero can use in battle. Heroes can attack each other, using a simple hit or a skill, or skip turns. The damage of the attack depends on the hero's class, stamina, and the equipment stats, whether the hero can use a skill or not depends on his stamina as well. The hero who lost all of his health points first loses.

This project was an exercise in object-oriented programming, as well as an example of the not-so-harmful use of the singleton pattern. The frontend part was provided by course tutors.

Currently, I am working on making a docker-compose file with a properly implemented NGINX for this project.

<i>The readme in Russian starts here.</i>

# Игра-синглтон

## Как запустить:

1. Скачайте репозиторий на компьютер.
2. В терминале, из корневой папки проекта введите команду:
`flask run`

В терминале отобразится локальная ссылка, по которой откроется игра.

Или, если у вас утсановлен Докер:

1. Скопируйте файл docker-compose.yml на компьютер.
2. В терминале, из папки с файлом docker-compose, введите команду:
`docker compose up -d`

После этого перейдите в Докер и откройте игру по ссылке запущенного контейнера.

## Описание

Это игра с двумя персонажами, для каждого можно выбрать один из двух классов, один из трех типов брони и один из трех типов оружия. У каждого класса есть специальный навык: который можно использовать в бою. Герои могут атаковать друг друга простым ударом или навыком, или пропускать ход. Урон от атаки зависит от класса, выносливости и экипировки героев, может герой использовать навык или нет также зависит от выносливости. Герой, первым потерявший все очки здоровья, проигрывает.

Этот проект был упражнением в объектно-ориентированном программировании и примером не такого уж и вредного использования паттерна "синглтон". Фронтенд для проекта был предоставлен на курсе.
