# Зерно — магазин кофе на Bootstrap

## Контрольная работа №2

Тема: «CSS-фреймворки: разработка интерфейса на Bootstrap или альтернативном CSS-фреймворке».

Сайт интернет-магазина кофе, сделанный с помощью Bootstrap.

## Автор

ФИО: Проценко Никита Вадимович

Группа: ЭФБО-01-25

## Ссылка на опубликованный проект

GitHub Pages: https://Boss921832137.github.io/kr2-bootstrap-shop/

Репозиторий: https://github.com/Boss921832137/kr2-bootstrap-shop

## Используемый фреймворк

Bootstrap 5.3.8.

## Способ подключения

Bootstrap подключён через CDN (jsDelivr).

- CSS подключается в `head`, после него подключается `css/custom.css`.
- JS Bundle подключается в конце `body`. Он нужен для мобильного меню, модального окна и accordion.

## Структура проекта

```
kr2-bootstrap-shop/
├── index.html
├── catalog.html
├── product.html
├── order.html
├── css/
│   └── custom.css
├── images/
├── README.md
└── .gitignore
```

## Страницы

- `index.html` — главная: навигация, hero-блок, преимущества, популярные товары.
- `catalog.html` — каталог: сетка карточек товаров со значками и кнопками.
- `product.html` — страница товара: описание, характеристики, цена, значок, кнопки, модальное окно, accordion.
- `order.html` — форма заявки и сообщение alert.

## Реализованные компоненты

- сетка: `container`, `row`, `col-12`, `col-md-*`, `col-lg-*`, `g-4`;
- `navbar`;
- `card`;
- `btn` (`btn-primary`, `btn-success`, `btn-secondary`, `btn-outline-primary`, `btn-outline-secondary`);
- `badge`;
- `alert`;
- `modal`;
- `form-control`;
- `form-select`;
- `input-group`;
- `form-check`;
- `accordion`;
- `table`.
