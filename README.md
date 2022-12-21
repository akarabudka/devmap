# devmap

# Организация разработки
   ### Система
   * [на каких ОС работал](#на-каких-ОС-работал-)
   * [базовые знания `UNIX`](#базовые-знания-UNIX-)
   * Основы работы с файлами
   * [Как найти файл с определенной подстрокой в директории со вложенностями?](#Как-найти-файл-с-определенной-подстрокой-в-директории-со-вложенностями?-)
   ### Система контроля версий
   * [Знакомы ли c `SCM` системами - `Git`, `Mercurial`, `SVN`, etc?](#Знакомы-ли-c-SCM-системами---Git,-Mercurial,-SVN,-etc?-)
   * [зачем нужна](#зачем-нужна-)
   * [какими пользовались](#какими-пользовались-)
   ### Git (если есть опыт)
   * [`gitflow`, `cherypick`](#gitflow,-cherypick-)
   * [как перенести изменения из одной ветку в другую (2 способа)](#как-перенести-изменения-из-одной-ветку-в-другую-(2-способа)-)
   * [зачем нужна команда `git rebase`](#зачем-нужна-команда-git-rebase-)
   * [Чем отличается `rebase` от `merge`](#Чем-отличается-rebase-от-merge-)
   * [разница между `git` и `svn` (если есть)](#разница-между-git-и-svn-(если-есть)-)
   ### Система тикетов и организация задач
   * [зачем нужна](#зачем-нужна-)
   * [какими пользовались](#какими-пользовались-)
   * [как была организована работа в команде](#как-была-организована-работа-в-команде-)
   * [методы разрешения конфликтов](#методы-разрешения-конфликтов-)
   * [понимание методологии `Scrum` и ее атрибутов (стендапы, грумминг/оценка бэклога, ретроспективы)](#понимание-методологии-Scrum-и-ее-атрибутов-(стендапы,-грумминг/оценка-бэклога,-ретроспективы)-)


# Кэширование
* [какие виды кэширования использовал](#какие-виды-кэширования-использовал-)
* [`Memcache`, `Redis`](#Memcache,-Redis-)
* [Если использовал `Memcache`, то с какими проблемами сталкивался.](#Если-использовал-Memcache,-то-с-какими-проблемами-сталкивался.-)

# Тесты
* [зачем нужны](#зачем-нужны-)
* [функциональные, стресс, юнит тесты](#функциональные,-стресс,-юнит-тесты-)
* [что такое `TDD`](#что-такое-TDD-)


# Web специфика
* [виды сетевых протоколов](#виды-сетевых-протоколов-)
* [Что такое `https` и зачем он нужен](#Что-такое-https-и-зачем-он-нужен-)
* [Понимание базовых аспектов функционирования сети - протоколы, `DNS`, и т.д.;](#Понимание-базовых-аспектов-функционирования-сети---протоколы,-DNS,-и-т.д.;-)
* [Что происходит при открытии вкладки браузера](#Что-происходит-при-открытии-вкладки-браузера-)
* [C каким серверным ПО приходилось работать?](#C-каким-серверным-ПО-приходилось-работать?-)
* [Настройка `http`-серверов](#Настройка-http-серверов-)
* [Что такое `Apache` и `mod_rewrite`?](#Что-такое-Apache-и-mod_rewrite?-)
* [`nginx`, его отличие от `apache`](#nginx,-его-отличие-от-apache-)
* [балансировка нагрузки на сервера приложений (`haproxy`)](#балансировка-нагрузки-на-сервера-приложений-(haproxy)-)
* [работы с системами очередей (`RabbitMQ`, `Kafka`)](#работы-с-системами-очередей-(RabbitMQ,-Kafka)-)
* [`CI` (`Continuous Integration`)](#CI-(Continuous-Integration)-)
* [Деплой](#Деплой-)
* [`Composer`](#Composer-)
* [`docker`](#docker-)
* [Стандарты написания кода](#Стандарты-написания-кода-)
* [Шаги по оптимизации сайта](#Шаги-по-оптимизации-сайта-)


# Разработка
* [Интересный крон (запуск скрипта раз в 30 секунд)](#Интересный-крон-(запуск-скрипта-раз-в-30-секунд)-)
* [Защита от спама - предложить интересный способ](#Защита-от-спама---предложить-интересный-способ-)
* [Защита от повторной отправки форм](#Защита-от-повторной-отправки-форм-)
* [Сортировка пузырьком, сложность алгоритма](#Сортировка-пузырьком,-сложность-алгоритма-)
* [Веб-сервисы, отличия, когда что использовать (`soap`, архитектура `rest`)](#Веб-сервисы,-отличия,-когда-что-использовать-(soap,-архитектура-rest)-)
* [`raise condition`](#raise-condition-)
* [`CORS`](#CORS-)
* [`SPINX`](#SPINX-)
* [гексагональная архитектура](#гексагональная-архитектура-)
* [`reflection API`](#reflection-API-)
* [`SPL`](#SPL-)
* [`SOLID`](#SOLID-)
* [`DRY`](#DRY-)
* [`ajax`](#ajax-)
* [`mapping` в `Doctrine`](#mapping-в-Doctrine-)


# Повышение квалификации
* [С какими `CMS`, фреймворками приходилось работать](#С-какими-CMS,-фреймворками-приходилось-работать-)
* [Что самое интересное приходилось делать](#Что-самое-интересное-приходилось-делать-)
* [Что больше всего нравится/не нравится в работе](#Что-больше-всего-нравится/не-нравится-в-работе-)
* [Отношение к работе с чужим кодом](#Отношение-к-работе-с-чужим-кодом-)
* [Интересные проекты / задачи](#Интересные-проекты-/-задачи-)
* [Какой твой любимый язык или фреймворк? Теперь расскажи его минусы.](#Какой-твой-любимый-язык-или-фреймворк?-Теперь-расскажи-его-минусы.-)
* [Почему вообще программируешь и что тебя драйвит?](#Почему-вообще-программируешь-и-что-тебя-драйвит?-)
* [Как получаешь новую информацию](#Как-получаешь-новую-информацию-)
* [какие ресурсы читаются и как часто](#какие-ресурсы-читаются-и-как-часто-)
* [какие задачи интересуют](#какие-задачи-интересуют-)
* [что интересно по жизни, какие хобби](#что-интересно-по-жизни,-какие-хобби-)
* [есть свой блог](#есть-свой-блог-)
* [какие три последние книги прочитал](#какие-три-последние-книги-прочитал-)
* [что сделал в своей жизни такого, чем можешь гордиться](#что-сделал-в-своей-жизни-такого,-чем-можешь-гордиться-)

# Организация разработки

### на каких ОС работал [&uarr;](#devmap)

Ubuntu, mac os, и WSL немного

### базовые знания `UNIX` [&uarr;](#devmap)

#### bash

    Оболочка, или шелл (shell) — это программа, в нашем случае названная «bash», что является сокращением от Bourne Again Shell. 
    Оболочка принимает ваши команды и передаёт их операционной системе. 
    Для взаимодействия с системой используются терминалы, такие как gnome-terminal, eterm, nxterm и т. п.

    Bash - это интерпретатор команд. По сути, это обычная программа, которая запускается при старте сеанса оболочки. 
    Мы могли бы запускать не Bash, а скажем, интерпретатор python или ruby, и тогда нам пришлось бы выполнять методы этих языков вместо команд Bash для администрирования системы.

    Bash принимает команды от пользователя и передает их системному загрузчику, а также обеспечивает взаимодействие между командами, 
    обмен информацией и потоками ввода-вывода. Также оболочка предоставляет пользователю удобный интерфейс для работы с историей команд, поиска и замены, а также исправления ранее выполненных команд, а также автодополнение путей.

#### grep

    Утилита grep решает множество задач, в основном она используется для поиска строк, соответствующих строке в тексте или содержимому файлов. 
    Также она может находить по шаблону или регулярным выражениям. Команда в считанные секунды найдёт файл  с нужной строчкой, текст в файле или отфильтрует из вывода только пару нужных строк. А теперь давайте рассмотрим, как ей пользоваться.
     
    Синтаксис команды выглядит следующим образом:
    
    $ grep [опции] шаблон [имя файла...]
    
    Или:
    
    $ команда | grep [опции] шаблон

    Опции - это дополнительные параметры, с помощью которых указываются различные настройки поиска и вывода, например количество строк или режим инверсии.
    Шаблон - это любая строка или регулярное выражение, по которому будет вестись поиск
    Файл и команда - это то место, где будет вестись поиск. Как вы увидите дальше, grep позволяет искать в нескольких файлах и даже в каталоге, используя рекурсивный режим.


#### alias

    Используйте alias, чтобы поименовать часто используемые команды. Например, alias ll='ls -latr' создаст новое сокращение ll

#### xargs

    Не забывайте использовать xargs (или parallel). Это очень мощная штука. 
    Обратите внимание, что вы можете контролировать количество команд на каждую строку (-L), а также параллельность (-P). Если вы не уверены, что делаете что-то правильно, начните с xargs echo. Еще -I{} – полезная штука. Примеры:

    Возможность объединения нескольких команд Linux в терминале и использования их в качестве конвейера, когда каждая следующая команда получает вывод предыдущей - очень мощный и гибкий инструмент. Но команды можно объединять не только так. 
    С помощью утилиты xargs вывод предыдущей команды можно передать в аргументы следующей.

    Синтаксис команды немного запутанный, но в нём можно разобраться:
    
    $ первая_команда | xargs опции вторая_команда аргументы
    
    Сначала выполняется любая первая команда и весь её вывод по туннелю передается в xargs. Затем этот вывод разбивается на строки и для каждой строки вызывается вторая команда, а полученная строка передаётся ей в аргументах.

      find . -name '*.py' | xargs grep some_function
      cat hosts | xargs -I{} ssh root@{} hostname

#### cd
    Перейти в домашнюю директорию можно с помощью cd. Для указания пути к файлам из домашней директории можно воспользоваться префиксом ~ (например, ~/.bashrc). В sh скриптах для обращения к домашней директории можно использовать переменную $HOME.
    Для того, чтобы перейти к предыдущей рабочей директории, используйте cd -

#### netstat

    Узнайте, какие процессы слушают порты через netstat -lntp или ss -plat (для TCP; добавьте -u для UDP).

#### history

    `Для просмотра последних команд используйте history. Повторить команду: !n (где n - порядковый номер истории). `

#### ssh

    Синтаксис команды выглядит следующим образом:

    $ ssh [опции] имя пользователя@сервер [команда]
    Чтобы просто подключиться к серверу по SSH:
    
    ssh user@host

    Мы привыкли подключаться к удаленному серверу, а уже потом выполнять нужные команды, 
    но на самом деле утилита ssh позволяет сразу выполнить нужную команду без открытия терминала удаленной машины. Например:
    
    ssh user@host ls

### Как найти файл с определенной подстрокой в директории со вложенностями? [&uarr;](#devmap)

    использовать find либо же grep

### Знакомы ли c `SCM` системами - `Git`, `Mercurial`, `SVN`, etc? [&uarr;](#devmap)
### зачем нужна [&uarr;](#devmap)
### какими пользовались [&uarr;](#devmap)
### `gitflow`, `cherypick` [&uarr;](#devmap)
### как перенести изменения из одной ветку в другую (2 способа) [&uarr;](#devmap)
### зачем нужна команда `git rebase` [&uarr;](#devmap)
### Чем отличается `rebase` от `merge` [&uarr;](#devmap)
### разница между `git` и `svn` (если есть) [&uarr;](#devmap)
### зачем нужна [&uarr;](#devmap)
### какими пользовались [&uarr;](#devmap)
### как была организована работа в команде [&uarr;](#devmap)
### методы разрешения конфликтов [&uarr;](#devmap)
### понимание методологии `Scrum` и ее атрибутов (стендапы, грумминг/оценка бэклога, ретроспективы) [&uarr;](#devmap)

# Кэширование

### какие виды кэширования использовал [&uarr;](#devmap)
### `Memcache`, `Redis` [&uarr;](#devmap)
### Если использовал `Memcache`, то с какими проблемами сталкивался. [&uarr;](#devmap)

# Тесты

### зачем нужны [&uarr;](#devmap)
### функциональные, стресс, юнит тесты [&uarr;](#devmap)
### что такое `TDD` [&uarr;](#devmap)

# Web специфика

### виды сетевых протоколов [&uarr;](#devmap)
### Что такое `https` и зачем он нужен [&uarr;](#devmap)
### Понимание базовых аспектов функционирования сети - протоколы, `DNS`, и т.д.; [&uarr;](#devmap)
### Что происходит при открытии вкладки браузера [&uarr;](#devmap)


#### 1. Пользователь вводит в браузере адрес сайта
#### 2. Браузер начинает искать сервер

За работу любого сайта обычно отвечает один из миллионов серверов, подключенных к интернету. 
Адрес сервера — это уникальный набор цифр, который называется IP-адресом. 
Например, для vc.ru— это сервер 85.119.149.83.

Поэтому первым делом браузеру нужно понять, какой IP-адрес у сервера, на котором находится сайт.

Такая информация хранится в распределенной системе серверов — DNS (Domain Name System). 
Система работает как общая «контактная книга», хранящаяся на распределенных серверах и устройствах в интернете.

Однако перед тем, как обращаться к DNS, браузер пытается найти запись об IP-адресе сайта в ближайших местах, чтобы сэкономить время:

    Сначала в своей истории подключений. Если пользователь уже посещал сайт, то в браузере могла сохраниться информация c IP-адресом сервера.
    В операционной системе. Не обнаружив информации у себя, браузер обращается к операционной системе, которая также могла сохранить у себя DNS-запись. Например, если подключение с сайтом устанавливалось через одно из установленных на компьютере приложений.
    В кэше роутера, который сохраняет информацию о последних соединениях, совершенных из локальной сети.

#### 3. Браузер отправляет запрос к DNS-серверам

Не обнаружив подходящих записей в кэше, браузер формирует запрос к DNS-серверам, расположенным в интернете.

Например, если нужно найти IP-адрес сайта mail.vc.ru, браузер спрашивает у ближайшего DNS-сервера «Какой IP-адрес у сайта mail.vc.ru?».

Сервер может ответить: «Я не знаю про mail.vc.ru, но знаю сервер, который отвечает за vc.ru». Запрос переадресовывается дальше, на сервер «выше», пока в итоге один из серверов не найдет ответ об IP-адресе для сайта.

#### 4. Браузер устанавливает соединение с сервером

Как только браузер узнал IP-адрес нужного сервера, он пытается установить с ним соединение. В большинстве случаев для этого используется специальный протокол — TCP.

TCP — это набор правил, который описывает способы соединения между устройствами, форматы отправки запросов, действия в случае потери данных и так далее.

Например, для установки соединения между браузером и сервером в стандарте TCP используется система «трёх рукопожатий». Работает она так:

    Устройство пользователя отправляет специальный запрос на установку соединения с сервером — называется SYN-пакет.
    Сервер в ответ отправляет запрос с подтверждением получения SYN-пакета — называется SYN/ACK-пакет.
    В конце устройство пользователя при получении SYN/ACK-пакета отправляет пакет с подтверждением — ACK-пакет. В этот момент соединение считается установленным.

#### 5. Браузер отправляет HTTP-запрос, чтобы получить контент сайта

После установки соединения браузер отправляет специальный запрос, в котором просит сервер отправить данные для отображения страницы. В этом запросе содержится информация о самом браузере, временные файлы, требования к соединению и так далее.

Задача браузера — как можно подробнее объяснить серверу, какая именно информация ему нужна.

В общении браузера и сервера выделяют два типа запросов. GET-запрос используется для получения данных с сервера — например, отобразить картинку, текст или видео. POST-запрос — используется для отправки данных из браузера на сервер, например, когда пользователь отправляет сообщение, картинку или загружает файл.

    Почти все сайты обмениваются информацией с сервером в зашифрованном формате — с помощью HTTPS-протокола. 
    В отличие от HTTP-протокола, в HTTPS используется шифрование, а безопасность подключения подтверждается специальным сертификатом.


#### 6. Сервер обрабатывает запрос

Сервер получил запрос от браузера с подробным описанием того, что ему требуется. 
Теперь ему нужно обработать этот запрос. Этой задачей занимается специальное серверное программное обеспечение — например, nginx или Apache. 
Чаще всего такие программы принято называть веб-серверами.

Веб-сервер в свою очередь перенаправляет запрос на дальнейшую обработку к программе-обработчику — например, PHP, Ruby или ASP.NET. 
Программа внимательно изучает содержимое запроса — например, понимает, в каком формате нужно отправить ответ и какие именно файлы нужны. И собирает ответ.

#### 7. Сервер отправляет ответ браузеру

Когда ответ сформирован, он отправляется веб-сервером обратно браузеру. В ответе как правило содержится контент для отображения веб-страницы, информация о типе сжатия данных, способах кэширования, файлы cookie, которые нужно записать и так далее.
    
    👉 Чтобы обмен данными был быстрым, браузер и сервер обмениваются сразу множеством небольших пакетов данных — как правило, в пределах 8 КБ. 
    Все пакеты имеют специальные номера, которые помогают отслеживать последовательность отправки и получения данных.

#### 8. Браузер обрабатывает полученный ответ и «рисует» веб-страницу

Браузер распаковывает полученный ответ и постепенно начинает отображать полученный контент на экране пользователя — этот процесс называется рендерингом.

Сначала браузер загружает только основную структуру HTML-страницы. Затем последовательно проверяет все теги и отправляет дополнительные GET-запросы для получения с сервера различных элементов — картинки, файлы, скрипты, таблицы стилей и так далее. Поэтому по мере загрузки страницы браузер и сервер продолжают обмениваться между собой информацией.

Параллельно с этим на компьютер как правило сохраняются статичные файлы пользователя — чтобы при следующем посещении не загружать их заново и быстрее отобразить пользователю содержимое страницы.

Как только рендеринг завершен — пользователю отобразится полностью загруженная страница сайта.




### C каким серверным ПО приходилось работать? [&uarr;](#devmap)
### Настройка `http`-серверов [&uarr;](#devmap)
### Что такое `Apache` и `mod_rewrite`? [&uarr;](#devmap)
### `nginx`, его отличие от `apache` [&uarr;](#devmap)
### балансировка нагрузки на сервера приложений (`haproxy`) [&uarr;](#devmap)
### работы с системами очередей (`RabbitMQ`, `Kafka`) [&uarr;](#devmap)
### `CI` (`Continuous Integration`) [&uarr;](#devmap)
### Деплой [&uarr;](#devmap)
### `Composer` [&uarr;](#devmap)
### `docker` [&uarr;](#devmap)
### Стандарты написания кода [&uarr;](#devmap)
### Шаги по оптимизации сайта [&uarr;](#devmap)

# Разработка

### Интересный крон (запуск скрипта раз в 30 секунд) [&uarr;](#devmap)

Крон это минимум минута.
Раз в 30 секунд это значит запускать каждую минуту скрипт который что-то делает, потом спит 30 секунд и еще раз делает.
Как вариант, написать скрипт, который будет запускаться раз в минуту и дёргать файл дважды, между двумя дёрганьями спать 30 секунд.

### Защита от спама - предложить интересный способ [&uarr;](#devmap)

Google ReCaptcha
Блэк лист
Hidden поле которое потом сможем проверять на бэке

### Защита от повторной отправки форм [&uarr;](#devmap)

Ограниченои частоты отправки сообщений
Ограничение количества сообщний от одного пользователя
ограничение количества отправляемых сообщений за определенный отрезок времени

### Сортировка пузырьком, сложность алгоритма [&uarr;](#devmap)
### Веб-сервисы, отличия, когда что использовать (`soap`, архитектура `rest`) [&uarr;](#devmap)
### `raise condition` [&uarr;](#devmap)
### `CORS` [&uarr;](#devmap)
### `SPINX` [&uarr;](#devmap)
### гексагональная архитектура [&uarr;](#devmap)
### `reflection API` [&uarr;](#devmap)
### `SPL` [&uarr;](#devmap)
### `SOLID` [&uarr;](#devmap)
### `DRY` [&uarr;](#devmap)
### `ajax` [&uarr;](#devmap)
### `mapping` в `Doctrine` [&uarr;](#devmap)

# Повышение квалификации

### С какими `CMS`, фреймворками приходилось работать [&uarr;](#devmap)
### Что самое интересное приходилось делать [&uarr;](#devmap)
### Что больше всего нравится/не нравится в работе [&uarr;](#devmap)
### Отношение к работе с чужим кодом [&uarr;](#devmap)
### Интересные проекты / задачи [&uarr;](#devmap)
### Какой твой любимый язык или фреймворк? Теперь расскажи его минусы. [&uarr;](#devmap)
### Почему вообще программируешь и что тебя драйвит? [&uarr;](#devmap)
### Как получаешь новую информацию [&uarr;](#devmap)
### какие ресурсы читаются и как часто [&uarr;](#devmap)
### какие задачи интересуют [&uarr;](#devmap)
### что интересно по жизни, какие хобби [&uarr;](#devmap)
### есть свой блог [&uarr;](#devmap)
### какие три последние книги прочитал [&uarr;](#devmap)
### что сделал в своей жизни такого, чем можешь гордиться [&uarr;](#devmap)
