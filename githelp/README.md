# Git Help

### Создать пустой git репозиторий (Делается один раз при создании)

`$git init`

### Настройка Git (В случае необходимости)

```sh
$ git config --(global) user.name "John Doe"
$ git config --(global) user.email(example@example.example)
```

### Шаг первый: Индексация

`$ git add .`

### Проверка статуса файлов для Git

`$ git status`

### Сохранение заиндексированного кода в истории версий кода Git (Репозиторий)

`$ git commit -m "Комментарий (на англ языке)"`

### Просмотр истории версии кода

`$ git log`

### Добавление удалённого репозитория

`$ $ git remote add origin https://github.com/username/repositoryname.git`

### Просмотр списка удалённых репозиториев

`$ git remote show`

### Отправление в удалённый репозиторий 

`$ git push origin master`

## Работа с ветвями

### Создание новой ветви

`$ git branch new_branch`

### Переключение на новую ветвь

`$ git checkout new_branch`

### Внесение изменений в фаилы с последующим commit'ом 

`$ git commit -am "commit_name"`

### Переход обратно в главную ветвь 

`$ git checkout master`

### Внесение изменений в фаилы с последующим commit'ом (Необязательно)

`$ git commit -am "commit_name"`

### Слияние ветвей (Необходимо находится в ветке master)

`$ git merge new-branch`

### Редактирование файлов и выполнение индексации файлов с последующим commit'ом (Выполняется только в случае конфликтов)

`$ git commit -am commit_name`

### Удаление ветви

`$ git branch -d new-branch`

