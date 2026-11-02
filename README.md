# kr2-bootstrap-shop

## Контрольная работа №2

Тема: «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

## Описание проекта

Учебный интернет-магазин «ТехноМаг» с каталогом товаров. Сайт состоит из четырёх страниц: главная, каталог, страница товара и форма заявки. Интерфейс собран на Bootstrap 5.3.8 с собственными стилями в `css/custom.css`.

## Используемый фреймворк

Bootstrap 5.3.8.

## Способ подключения Bootstrap

Bootstrap подключён через CDN (jsDelivr):

```html
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet">
<link rel="stylesheet" href="css/custom.css">
...
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js"></script>
``'

## Структура проекта

```
kr2-bootstrap-shop/
├── index.html      главная страница
├── catalog.html    каталог с фильтрами, карточками и модальным окном
├── product.html    страница товара, аккордеон, модальное окно покупки
├── order.html      форма заявки
├── css/
│   └── custom.css  собственные стили поверх Bootstrap
├── images/         изображения товаров (SVG)
├── README.md
└── .gitignore
```

## Реализованные компоненты Bootstrap

Обязательные:
- `container`, `row`, `col-*`, `g-*`, `row-cols-*` (сетка);
- `navbar` (адаптивное меню с бургер-кнопкой на всех страницах);
- `card` (карточки товаров на главной и в каталоге);
- `btn` и варианты `btn-primary`, `btn-outline-primary`, `btn-outline-secondary`, `btn-light`;
- `badge` (статусы «Новинка», «Хит», «Скидка», «Спорт»);
- `alert` (информационные, успешные и предупреждающие сообщения);
- `modal` (быстрый просмотр в каталоге и покупка в один клик на странице товара);
- `form-control`, `form-select`, `input-group`, `form-check`.

Дополнительные:
- `accordion` (доставка и гарантия на странице товара);
- `carousel` (слайдер на главной);
- `pagination` (навигация по страницам каталога);
- `breadcrumb` (хлебные крошки на странице товара);
- `table` (таблица характеристик).
