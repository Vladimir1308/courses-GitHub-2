# Это репозиторий для обучения pull request
1. Создаем репозиторий на Git Hub c именем (*courses-GitHub-2*).

2. Ищем кнопку Fork на странице репозитория 

https://github.com/Vladimir1308/courses-GitHub-2.git

3. Открываем ДЗ 2 в Visual Studio Code.

Выполняем команды для переноса ДЗ 2:
``` 
1.ggit remote add origin https://github.com/Vladimir1308/courses-GitHub-2.git
2.git branch -M main
3.git push -u origin main
``` 
Проверяем перенос файла.

4. Создаем папку на ПК (*git courses GitHub*).

Открываем папку в Visual Studio Code
и клонируем перенесенные фаилы командой 
```
git clone https://github.com/Vladimir1308/courses-GitHub-2.git
```
5. Создаем новую ветку и вносим необходимые изменения в файл

```
git add learning_pull_request.md
git commit -m "обучеия pull request"
```
6. Делаем push

```
git push 
```
Переходим на свою страницу репозитория. Выбираем ветку courses-GitHub-2  и жмем кнопку Compare & pull request

Заметки
Что бы сделать push от другого пользователя необходимо выполнить команду

```
GIT_SSH_COMMAND='ssh -i ~/.ssh/user-private-key -o IdentitiesOnly=yes' git push https://github.com/Vladimir1308/courses-GitHub-2.git
```
вместо user-private-key подставьте свой ключ

Можно прописать настройки для подсоединения по ssh

git config remote.origin.url git@github.com:gitusername/reponame
git config core.sshCommand "ssh -i ~/.ssh/user-private-key -o IdentitiesOnly=yes"

