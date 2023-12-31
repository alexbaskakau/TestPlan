## План автоматизации тестирования возможности  записаться на обучение профессии «Тестировщик ПО».

## Уровни тестирования:
* Интеграционное тестирование - проверяем взаимодействие между компонентами (Переход с главной страницы на страницу с формой для записи на обучение профессии "Тестировщик ПО);

## Виды тестирования:
* Функциональное тестирование - проверяем функциональность на соответствие требованиям;
  

## Перечень автоматизируемых сценариев:

1. Проверка открытия страницы Нетологии;
1. Проверка наличия вкладки "Программирование" и кнопки "Каталог курсов";
1. Проверка открытия страницы "Программирование" через вкладку "Программирование";
1. Проверка открытия страницы "Программирование" через кнопку "Каталог курсов";
1. Проверка открытия страницы "Тестировщик" и клик на кнопку "Записаться";
1. Проверка открытия страницы с анкетой и проверяем появившийся интерфейс на позитивные и негативные сценарии заполнения анкеты;



## Перечень используемых инструментов:
* Java - язык, на котором будем писать код;
* IntelliJ IDEA - программа, в которой пишем код;
* Gradle - система автоматической сборки внутри IntelliJ IDEA;
* JUnit.jupiter - библиотека для тестирования;
* Faker - генерация пользовательских данных (имени и телефона);
* Selenide - так как работаем с веб-страницей и ищем появившиеся значения с помощью html и css;
* Allure - используем для наглядного изображения прохождения тестов и ошибок;

## Перечень необходимых разрешений/данных/доступов:
* Разрешение на тестирование страниц сайта с помощью автоматизированного ПО;
* Разрешение на доступ к приложению;
* Разрешение на доступ к базе данных;
* Предоставление тестовых аккаунтов для тестирования возможности записи на курс.

## Перечень и описание возможных рисков при автоматизации:
* Возможна смена кода страницы либо css-селекторов, придется править код;
* Смена формы заполнения после какого-либо времени;
* Невозможность написания в форме некоторых букв (например, буквы ё);
* Долгое открытие страницы сайта, либо вкладки;
* Недоступность сайта или страницы;
* Неоправданная стоимость автоматизации;
* Искажение результатов тестов в связи с отсутствием доступа к реальной БД;

## Перечень необходимых специалистов для автоматизации:
* Специалист по автоматизированному тестированию;

## Интервальная оценка с учётом рисков (в часах):
* Необходимое время на тестирование составляет 30 часов, с учетом рисков - 40 часов. 
