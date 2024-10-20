# Оглавление
[Установка Git](#install)

[Основы работы с терминалом](#terminal)

[Создание удалённого репозитория на GitHub](#github)

[Основные команды Git](#comands)

# <h1 id="install">Установка Git</h1>
# <h1 id="terminal">Основы работы с терминалом</h1>
- pwd - напечатать текущую директорию
- ls - распечатать содержимое директории
- cd - перейти в директорию
- mkdir - создать директорию
- rm - удалить
- touch - создать файл
- cat - напечатать содержимое файла
- clear - очистить терминал
- ssh-keygen - сгенерировать ключи

Для алгоритма ed25519:
```bash
$ ssh-keygen -t ed25519 -C myemail@mail.com
```
Для алгоритма RSA:
```bash
$ ssh-keygen -t rsa -b 4096 -C myemail@mail.com
```
# <h1 id="github">Создание удалённого репозитория на GitHub</h1>
# <h1 id="comands">Основные команды Git</h1>
- git init - инициализировать локальный репозиторий
- git status - проверить статус репозитория
- git add - подготовить файлы к коммиту
-- git add --all - подготовить к коммиту все файлы в текущей папке
-- git add . - подготовить к коммиту все файлы в текущей папке
- git commit -m "*message*" - сделать коммит
- git log - история коммитов
- git remote
```bash
$ git remote add origin git@github.com:%ИМЯ_АККАУНТА%/first-project.git 
```
- git push
```bash
$ git push -u origin main
```