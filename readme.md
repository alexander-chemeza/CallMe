# Проект CallMe
## Основные требования
* Верстка должна быть адаптивной.
* Минимальная зависимость от вендоров (Bootstrap и т.д.).
* Иконки должны быть отрисованы с помощью SVG, написанного на JavaScript.
* Анимация средствами JavaScript.
## Функционал начальной страницы
* На начальной странице реализовать форму регистрации и аунтификации.
* Хранение данных пользователя в Cookie.
* Общение с СУБД с помощью JavaScript (см. npm mysql).
## Функционал приложения
### Шапка приложения
Шапка приложения содержит следующую информацию:
1. Аватар, либо стандартное изображение и данные пользователя.
2. Кнопка добавления контакта.
3. Кнопка выхода из приложения.
Пользователь имеет возможность изменения аватара и своих данных.
### Тело приложения
Тело приложения должно представлять собой список контактов.
Каждый элемент списка должен иметь доступ к следующей информации:
1. Аватар контакта (опционально), либо базовое изображение и его данные.
2. Номер телефона.
3. Адресс электронной почты (опционально).

Требования к списку:
1. В самом списке отображается только аватар, ФИО и кнопки управления. 
2. Фотография пользователя или стандартное изображение должно быть в рамке, 
отрисованной с помощью Canvas.<br>
3. Каждый элемент имеет свою кнопку раскрытия информации о контакте. По нажатию на данную кнопку 
в том же окне браузера открывается форма с информацией о пользователе с возможностью ее редактирования.
Изменения сохраняются в БД.
4. Каждый элемент списка имеет свою кнопку удаления контакта. При нажатии на данную кнопку открывается
форма с просьбой подтвердить действие. Если действие одобрено, соответствующая строка из БД для данного списка
удаляется.

## Дополнительные (опциональные) требования
1. Цветовые темы.
2. Реализовать основные способы защиты от атак.
3. Портирование приложения на Android.