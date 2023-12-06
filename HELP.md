# Подсказки по командной строке


Команда инициализации 
```sh
git init
```

Команда отображения текущей директории для MacOS и Linux
```sh
pwd
```

Листинг текущей директории
Windows:
```sh
dir
```
Linux или MacOS:
```sh
ls
```

Удаление файла:
Windovs:
```sh
del file_name
```

Linux или MacOS:
```sh
rm file_name
```

Посмотреть не внесенные изменения
```sh
git diff
```

Внести изменения
```sh
git add
```

Создать комментарий
```sh
git commit -m "комментарий"
```

Посмотреть изменения
```sh
git log
или
git log --oneline
```

Переключение между изменениями
```sh
git checkout №_нужного_лога
что бы вернуться в мастера
git checkout master
```

Работа с ветками
```sh
git branch (показывает наши ветки и ветку, в которой мы находимся)
git branch imya_vetki (создание ветки)
git checkout imya_vetki (переключаемся на ветку)
git branch master (что бы вернуться в ветку мастера)
git merge imya_vetki (перед слиянием необходимо находиться в ветке, в которую объединяют, master)
git branch -d imya_vetki
```