# Readme


Области видимости
Нативный js (селекторы, события)


ООП
Замыкания.
Регулярные выражения
Vue

Long Poling
Short Poling
Sent event



### Ajax [&uarr;](#Other-tasks)

AJAX расшифровывается как асинхронный JavaScript и XML и позволяет асинхронно извлекать контент с внутреннего сервера без
обновления страницы. Таким образом, он позволяет обновлять содержимое веб-страницы без перезагрузки.

Общий вызов AJAX работает примерно так:

![](images/how-to-use-ajax-with-php-and-jquery.jpg)

Давайте быстро пройдемся по обычному потоку AJAX:

    1. Сначала пользователь, как обычно, открывает веб-страницу синхронным запросом.
    2. Затем пользователь нажимает на элемент DOM - обычно кнопку или ссылку - который инициирует асинхронный запрос к серверу. Конечный пользователь не заметит этого, поскольку вызов выполняется асинхронно и не обновляет браузер. Однако вы можете распознать эти AJAX-вызовы с помощью такого инструмента, как Firebug.
    3. В ответ на запрос AJAX сервер может вернуть данные строки XML, JSON или HTML.
    4. Данные ответа анализируются с использованием JavaScript.
    5. Наконец, проанализированные данные обновляются в DOM веб-страницы.

### Pjax [&uarr;](#Other-tasks)

PJAX это виджет в Yii2 позволяющий обновлять вам только заданный участок страницы, без перезагрузки всего содержимого.

Pjax это js скрипт, он не связан с сервером и понятия не имеет что там происходит.
Он ждет ответ из которого надо взять контейнер с определенным селектором.
