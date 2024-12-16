# Portfolio
# Портфолио и резюме 
## Содержание
* Функциональное тестирование веб-сервиса
* Чек-лист, текст-кейсы тестирования мобильных приложений
* API проверки приложений
* Стек и техники тестирования
* SQL работа с данными
* Итоговое тестирование веб и мобильного приложентя Яндекс.Самокаты
* Примеры баг-репортов в YouTrack и YandexTracker
* Примеры работы в прогрммах Postman, Charles, Cygwin64
* Полные решения практических заданий и тестирования: Яндекс. Маршрутов, Яндекс.Самокатов, Яндекс.
* Заключение
## Функциональное тестирование веб-сервиса Яндекс Маршруты
Я хотел бы вам продемонстировать навыки и знания, которые важны для работы quality engineer. Поделиться своими ключевыми навыками и проектами, которые демонстрируют мой подход к тестированию, после прохождения курсов @yandex.practicum. 

Одним из основных инструментов в работе тестировщика является создание чек-листов и текст-кейсов для тестирования веб-приложений. Чек-листы помогают систематизировать процесс тестирования, обеспечивая полное покрытие функционала приложения.
Первым делом были выучены основные техники тестирования, финальный проект спринта помог мне закрепить на практике следующие знания:
* анализ и декомпозиция требований;
* mindmap для визуализации требований;
* составление тест-кейсов;
* классы эквивалентности и граничные значения.

Итоговой первой крупной темой были закрепления всех описанных сверху полученных навыках в ходе прктического тестирования сервиса Яндекс.Маршруты. Так в работу были даны следующие задачи: 
### Тестирование валидации полей в форме:
***1. Провести тест-анализ требований на валидацию полей.(ссылка на требования)***

***2. Создать набор тест-кейсов на проверку валидации полей формы Яндекс Маршрутов. Применив техники тест-дизайна: классы эквивалентности и граничные значения. (Пример выполненных техник)***

***3. Протестировать валидацию полей и завести баг-репорты. (Пример баг-репорта)***

В результате на проверку были сданы следующие таблицы:

**1. Таблица с классами эквивалентности и граничными значениями. (ссылка на табилцу)** 

**2. Набор тест-кейсов на валидацию полей. (ссылка на табилцу)**

**3. Баг-репорты. (ссылка на табилцу)**

### Тестирование расчета стоимости и времени поездки на собственном автомобиле:

  Сервис Яндекс Маршруты рассчитывают время и стоимость поездки, в том числе на своем автомобиле. В требованиях есть таблицы средней скорости автомобиля и расстояний между адресами, на основе которых должен производиться расчет времени поездки. В рамках задания нужно:
  
***1. Провести тест-анализ требований расчёта времени и стоимости маршрута на собственном автомобиле.***

***2. Применить технику тест-дизайна «Классы эквивалентности» и создать набор тест-кейсов на проверку правильности расчета времени и стоимости поездки на собственном автомобиле.***

На второе задание были сделаны следующие проверки и кейсы: 

**1. Таблица с классами эквивалентности.**

**2. Набор тест-кейсов к расчетам.**

**3. Баг-репорты.**

## Функциональное тестирование веб-сервиса: чек-лист и тест-кейсы на логику работы окон и верстки

Сначала мне предстояло протестировать каршеринг: составить тестовую документацию, выполнить проверки, завести баг-репорты. Проверить, что данная функциональность сайта выполняет свою работу верно. 

Для этого я выполнил следующие действия: 

***1. Подготовил чек-лист на вёрстку полей***
После подробного изучения требований и макетов, выбирается один тариф для проверки тестирования логики и верстки.

**Составлен чек-лист на вёрстку следующих блоков:**

* форма бронирования;
* элементы на навигационной карте: это иконки автомобилей и действия с ними.

***2. Подготовил чек-лист и тест-кейсы на логику работы окон.***

Составлена следующующая тестовая документация: 
* чек-лист на логику окон «Способ оплаты» и «Добавление карты», (требования к окнам) 
* тест-кейсы на кнопку «Забронировать». (требования к окнам)

##  Чек-лист, текст-кейсы тестирования мобильных приложений
В этом задании были поставлены следующие задачи: 
Команда Яндекс Метро сделала рефакторинг мобильного приложения на Android — внесла правки в код. Чтобы выпустить новую версию, предварительно нужно:  протестировать те части продукта, которых коснулись изменения;
**провести регрессионное тестирование и убедиться, что новую версию можно заливать в стор.**
По результатам проверок необходимо предоставить отчёт о тестировании менеджеру.
Ссылки для работы даются: 
* текущая версия приложения, которую пользователи скачивают из стора;
* готовящаяся сборка;
* требования к Яндекс Метро.

  Одно из основных требований: **По итогам прошлого релиза команда определила, на каком устройстве возникает больше всего багов. Поэтому сейчас решили тестировать именно на этой конфигурации: Honor 8, ОС Android 9.0 Pie, разрешение экрана 1080х1920, диагональ 5.5. Важно: тестирование необходимо провести на эмуляторе Android Studio.**

### Подготовка к функциональному тестированию

Требования, которые затронул рефакторинг приложения, выделили полужирным шрифтом: (ссылка на требования)

Нужно написать к ним тесты и оформить проверки в виде чек-листа.

### Подготовка к регрессионному тестированию

Кроме проверок функциональности, затронутой рефакторингом, нужно провести регрессионное тестирование. Для этого написаны чек-листы, которые учитывают особенности мобильного приложения.
Было определено, какая функциональность Яндекс Метро взаимодействует с мобильным устройством.
Зафиксированы мобильные проверки, которые связаны с этой функциональностью.

Вот несколько примеров из проделанной работы: (ссылки)

## API проверки приложений
Для успешного прохождения этого спринта мне понадобились знания, полученные за курс по проверке API:
* создавать и отправлять запросы в API через Postman;
* читать документацию к API;
* проектировать первые тесты для API.
* Теоретические знания по тестированию API:
* структура HTTP;
* формат JSON;
* техники тест-дизайна для API.

### Задание тестирования API 
Разработчики сделали новую функциональность в API Яндекс.Прилавка. Новую версию API передали на тестирование. 
Изуча документацию, были выделены основные ручки для работы с Яндекс.Прилавком.

Работа с наборами: возможность добавлять продукты в набор —
* ручка * *POST /api/v1/kits/{id}/products.* (Ссылки на пример чеклиста-ручки ручки)
  
Работа с курьерами: возможность проверить, есть ли доставка курьерской службой «Привезём быстро» и сколько она стоит:

* ручка * *POST /fast-delivery/v3.1.1/calculate-delivery.xml.* (Ссылки на пример чеклиста-ручки ручки)

Работа с корзиной:
* возможность получить список продуктов, которые добавили в корзину. Ручка * *GET /api/v1/orders/id;* (Ссылки на пример чеклиста-ручки ручки)
* возможность добавлять продукты в корзину. Ручка * *PUT /api/v1/orders/:id;* (Ссылки на пример чеклиста-ручки ручки)
* возможность удалять корзину. Ручка * *DELETE/api/v1/orders/:id.* (Ссылки на пример чеклиста-ручки ручки)

### Постановка задачи
Проанализиpовать требования к новой функциональности бэкенда Яндекс.Прилавка. Изучить документацию к API в Apidoc.  (Требования к бэкенду находятся здесь)

Спроектировать тесты в виде чек-листа, чтобы покрыть функциональность, которую  передали на тестирование.
Протестировать API через Postman и завести баг-репорты в YouTrack, если это понадобится.

### Примеры выполненных задач, тест-кейсов и чек-листов

## Стек и техники тестирования
Благодаря двум новым проектам от @yandex.practicum: тестирование веб-приложения Яндекс Маршруты и мобильного приложения Яндекс Метро.
Для этих проектов мне нужно было:
* составить чек-листы и тест-кейсы, позитивные и негативные проверки;
* провести кроссплатформенное и кросбраузерное тестирование;
* протестировать вёрстку на адаптивность;
* тестировать API.
* Инструменты и стек: #AndroidStudio #Postman #Swagger #Apidoc

## SQL работа с данными
Результатом успешного выполнения проекта будут считаться правильно написанные SQL-запросы. В этой части учебы был проведен уклон на работу с Базами данных и SQL-запросами. 
Ниже приведу примеры запросов и их верно написанных ответов. 

## Итоговое тестирование веб и мобильного приложентя Яндекс.Самокаты
В этом заключительном курсе дипломной работой выступает совокупность всех полученных знаний. 

Первое задание — **тестирование веб-приложения.** Требования к веб-приложению можно посмотреть здесь.

Краткое описание того, что делать и небольшой пример как состоит таблица

Второе задание — **тестирование мобильного приложения.** Требования к мобильному приложению можно посмотреть здесь

Краткое описание того, что делать и небольшой пример как состоит таблица

Третье задание — **тестирование API.** Требования к API можно посмотреть здесь

Краткое описание того, что делать и небольшой пример как состоит таблица

## Примеры баг-репортов в YouTrack и YandexTracker

Заводить баг-репорты приходилось не только в таблице, но и на специальных сайтах, посвященных созданию репортов. Так были успешно созданы баг-репорты на популярных сервисах: **YouTrack**
### YouTrack баг-репорты
Несколько скриншотов, несколько ссылок
### Yandex.Tracket баг-репорты
Несколько скриншотов, несколько ссылок

## Примеры работы в прогрммах Postman, Charles, Cygwin64
В течение курса приходилось оставивать новые программы. 

Так, например, были практические работы в Postman для работы с API структурой. Предлагаю ознакомиться с скриншотами работы в программе:  

Charles для перехвата ответов и отправки брэйкпоинтов. Предлагаю ознакомиться с скриншотами работы в программе: 

Cygwin64 для изменения базы данных на сервере. Предлагаю ознакомиться с скриншотами работы в программе: 

Так же работы в других приложениях, по типу Figma, Tracker.

## Полные решения практических заданий и тестирования: Яндекс. Маршрутов, Яндекс.Самокатов, Яндекс.

## Заключение 

После прохождения курсов от Яндекс.Практикума, где Первый спринт познакомил с основами проектирования тестов. Второй и третий помогли освоить инструменты ручного тестирования. Четвёртый позволил узнать больше об операционных системах и SQL. Пятый познакомил с основами программирования и автотестами. После проделанной работы и потраченного времени, могу сказать — готовность к новой ступени в жизни и профессиональной карьере брулят, как никогда. 


