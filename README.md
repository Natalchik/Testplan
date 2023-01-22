# Тест-план по автоматизации тестирования возможности записаться на обучение профессии "Тестировщик ПО".
## 1. Перечень автоматизируемых сценариев:
###1.1. Переход к форме записи на курс "Тестировщик ПО":
- Открыть стартовую страницу сайта [Нетология]( https://netology.ru).
- Перейти к форме записи на курс (несколько вариантов):
1. В начале страницы кликнуть на "Каталог курсов", выбрать направление "Программирование", нажать на категорию "Тестировщик ПО", нажать на кнопку "Записаться", происходит переход к форме записи на курс.
2. Прокрутить страницу до категории "Направление обучения", кликнуть, выбрать направление "Программирование", выбрать профессию "Тестировщик ПО", нажать на кнопку "Записаться", происходит переход к форме записи на курс.
3. Прокрутить страницу до категории "Направление обучения", кликнуть, ввести в поле поиска "Тестировщик ПО", выбрать курс "Тестировщик ПО", нажать на кнопку "Записаться", происходит переход к форме записи на курс.
4. В начале страницы кликнуть на "Каталог курсов", в поле поиска "Какой курс вам нужен?" ввести "Тестировщик ПО", выбрать курс "Тестировщик ПО", нажать на кнопку "Записаться", происходит переход к форме записи на курс.
5. В начале страницы кликнуть на "Каталог курсов", выбрать "Все курсы", в поле поиска ввести "Тестировщик ПО", выбрать курс "Тестировщик ПО", нажать на кнопку "Записаться", происходит переход к форме записи на курс.
- Тестирование формы записи на обучение профессии "Тестировщик ПО".
## 2. Перечень используемых инструментов с обоснованием выбора:
   - Java 11 - язык программирования (проверенная версия, на ней разрабатываются большинство проектов).
   - Gradle - система автоматической сборки, инструмент управления проектами (более гибкая и современная система сборки по сравнению с другими)
   - JUnit5 - фреймворк для тестирования ПО на языке Java (наиболее удобный).
   - Selenide - фреймворк для автоматизированного запуска веб-приложений по поиску веб-элементов на странице (в отличие от Selenium не требует настройки окружения, установки специального драйвера)
   - Allure — фреймворк, предназначенный для создания визуально наглядной картины отчета о выполнении тестов. (наиболее распространен)
   - Git - система контроля версий (самая популярная).
   - GitHub - веб-сервис для хостинга IT-проектов основанный на системе контроля версий Git (крупнейший).
## 3. Перечень необходимых разрешений/данных/доступов:
   - Разрешение на тестирование и автоматизацию;
   - Доступ к API сайта "Нетология" и базе данных;
   - Доступ к техническому заданию (документации) по тестированию, при наличии.
## 4. Перечень и описание возможных рисков при автоматизации:
   - Отсутствие тз;
   - Необходимость поддержки кода автотестов;
   - Отсутствие нагрузочного тестирования, тестирования безопасности;
   - Изменения верстки повлекут за собой неработоспособность автотестов.
## 5. Перечень необходимых специалистов для автоматизации:
   - Тестировщик ПО со знаниями языка программирования для написания автотестов;
   - Специалист для предоставления права доступа к базе данных "Нетологии"
## 6. Интервальная оценка с учётом рисков (в часах):
   Ориентировочно 30 рабочих часов.
