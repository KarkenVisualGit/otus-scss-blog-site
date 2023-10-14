# Макет сайта-блога &middot;

> Данный сайт создан в рамках учебного задания по верстке сайта-блога с 4-мя страницами (главная, обратная связь, список записей, страница записи) с использованием препроцессора SCSS.

## Структура проекта

- index.js - входная точка проекта для главной страницы, здесь мы подключаем стили из файла main.scss post.js - входная точка проекта для страницы поста с комментариями, подключаем стили из файла \_post.scss posts.js - входная точка проекта для страницы поста с комментариями, подключаем стили из файла_posts.scss feedback.js - входная точка проекта для страницы поста с комментариями, подключаем стили из файла \_feedback.scss

файл \_base.scss - файл нормализации шаблона страниц файл common.scss - файл для стилей футера, хэдера, для карточки блога файл post.scss - файл для дополнительных стилей карточки и для стилей комментариев файл posts.scss - файл для дополнительных стилей карточки файл feedback.scss - файл для формы обратной связи файл main.scss - файл для доп. стилей списка записей под карточкой блога

## Развернуть проект

1.Клонировать репозиторий

```shell

gh repo clone KarkenVisualGit/otus-scss-blog-site

```

2.Установить зависимости

```shell

npm install

```

3.Запустить локальный сервер

```shell

npm run start
```
