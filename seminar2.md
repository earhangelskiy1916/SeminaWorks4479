# Справка (туториал) по основам системы конроля версий GIT
## Как инициализировать GIT
**Чтобы инициализировать репозиторий, в терминале надо прописать:**

```
git init
```

## Как добавить файл для отслеживания в GIT
**Чтобы GIT начал отслеживать изменения в файле используется команда:**

```
git add
```

## Как зафиксировать изменения в отслеживаемом файле
**Чтобы зафиксировать изменения в отслеживаемом файле используется команда:**
```
git commit
```
## Как вывести на экран историю фиксаций файла
**Для выведения на экран терминала истории фиксаций файла используется команда**
```
git log
```

# Туториал (справка) для работы с языком разметки Markdown




## Заголовки






## Цитаты
bla




## Исходный код
В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть более удобный способ: ставим по три апострофа (на букве Ё) до и после кода. Также можно указать язык исходного кода.

```html
<nav class="nav nav-primary">
  <ul>
    <li class="tab-conversation active">
      <a href="#" data-role="post-count" class="publisher-nav-color" data-nav="conversation">
        <span class="comment-count">0 комментариев</span>
        <span class="comment-count-placeholder">Комментарии</span>
      </a>
    </li>
    <li class="dropdown user-menu" data-role="logout">
      <a href="#" class="dropdown-toggle" data-toggle="dropdown">
        <span class="dropdown-toggle-wrapper">
          <span>
            Войти
          </span>
        </span>
        <span class="caret"></span>
      </a>
    </li>
  </ul>
</nav>
```





## Таблицы


В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть.

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Для красоты можно и по бокам линии нарисовать:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

