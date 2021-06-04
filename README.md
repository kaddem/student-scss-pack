# student-startpack
Простой сборщик на scss для студентов

**Version 1.1.0**

## Требования

Для работы необходимы

* [Node.js](http://nodejs.org) - ставь LTS версию.
* [Gulp](http://gulpjs.com/): `[sudo] npm install -g gulp`

## Начало работы

**Форкнуть себе этот репозиторий и далее склонировать свой форк!**

1 Клонируем с указанием названия папки проекта (название проекта в конце через пробел):
```
$ git clone git@github.com:your-login-on-github/student-scss-pack.git project-name
```

2 Избавляемся от привязки к удаленному репозиторию:
```
git remote rm origin
```

3 Создаем пустой репозиторий на github под проект

4 Привязываем наш проект к созданному удаленному репозиторию на github (пример команды):
```
git remote add origin git@github.com:your-login-on-github/project-name.git
```

5 Пушим в удаленный репозиторий на github:
```
git push -u origin master
```
6 Ставим зависимости:
```
npm install
```

## Запуск

В консоли выполняем команду:
```
npm start
```
* Поднимается localhost
* В браузере автоматом открывается index.html
* Происходит отслеживание изменений в scss файлах и их пересборка
* Происходит отслеживание изменений в html файлах
* При изменении происхожит перезагрузка страницы

## Структура папок и файлов
```
project
├───src
│   └───styles
│       ├───blocks (стили блоков)
│       │   ├───_header.scss
│       │   ├───_nav.scss
│       │   └───etc.
│       │
│       ├───common (общие стили)
│       │   ├───_fonts.scss
│       │   ├───_variables.scss
│       │   └───etc.
│       │
│       └───style.scss
│
└───www
    ├───fonts
    │   ├───font.woff2
    │   └───font.woff
    │
    ├───img
    │   ├───img.jpg
    │   └───etc.
    │
    ├───scripts
    │   ├───script.js
    │   └───etc.
    │
    ├───style
    │   ├───style.css (собранный из scss файлов - его не трогаем)
    │   └───etc.
    │
    ├───index.html
    ├───page1.html
    └───etc.
```

## Версии
* 1.0.0 - создание сборки