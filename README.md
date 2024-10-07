# Проект: Страница формы для публикации путешествий

## Описание

Данный проект представляет собой веб-страницу, где пользователи могут поделиться своими предложениями о путешествиях. Страница включает форму для ввода данных о новых направлениях, которые пользователи хотят видеть в блоге, и позволяет отправить их на рассмотрение. Форма включает поля для ввода имени, названия направления, выбора страны и категории съёмки, а также текстовое поле для описания.

## Структура проекта

Проект состоит из **HTML** и **CSS** файлов:

1. **HTML**:
    - Структура страницы представлена с использованием элементов формы (`<form>`, `<input>`, `<select>`, `<textarea>`) и разделов для текста.
    - Основные блоки включают заголовки, текстовые описания и саму форму для ввода данных.

2. **CSS**:
    - Стили оформления формы и остальных элементов страницы.
    - Используются стили для гибкого расположения блоков, фоновых изображений и элементов управления формой (поля ввода, выпадающие списки и кнопки).

## Структура классов

HTML и CSS файлы используют следующие классы:

### HTML:

- **Основной контейнер**: 
    - `community_section` — основной блок секции формы.
- **Заголовки**: 
    - `community_title` — заголовок "LET’S BUILD A COMMUNITY".
    - `join_text` — текст приглашения "Join our next destination".
    - `travel_share_text` — заголовок формы "Share your travels".
- **Форма**:
    - `travel_form` — контейнер для всех элементов формы.
    - `input_field` — поля ввода текста.
    - `dropdown_select` — выпадающие списки.
    - `textarea_field` — текстовое поле для описания.
- **Кнопка**:
    - `form_button` — кнопка отправки формы.

### CSS:

Стили применяются к вышеуказанным классам, отвечая за:

- Размеры и внешний вид элементов (ширина, высота, цвета).
- Расположение элементов на странице.
- Взаимодействие с пользователем (стили кнопок и полей).

## Как использовать

1. Склонируйте проект с помощью команды:

    ```bash
    git clone https://github.com/DanilGefest/WEB
    ```

2. Откройте файл `index.html` в браузере для просмотра страницы.

3. Для кастомизации стилей изменяйте соответствующие классы в файле `styles.css`.
