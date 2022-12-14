# План автоматизации тестирования приложения "Путешествие дня"

Приложение расположено в файле aqa-shop.jar

# Перечень автоматизируемых сценариев

План автоматизации включает проведение функционального тестирования приложения.

Тестирование будет включать в себя:

Тестирование переходов к оплате тура

Необходимо написать авто-тесты с двумя возможными сценариями переходов к оплате:

* Купить произведя оплату по дебитовой карте;
* Купить в кредит имея в наличии данные банковской карты;
* Тестирование формы отправки платежных данных.

Нужно написать авто-тесты, проверяющие форму отправки данных:
* позитивные
* негативные

Тестирование интеграции с СУБД

Здесь будут написаны авто-тесты отображающие интеграцию приложения с СУБД:
- MySQL
- PostgreSQL
 
Плюс тесты, проверяющие создаваемые приложением в СУБД записи: 
- каким способом был совершён платёж;
- успешно ли он был совершён.

#### ВАЖНО! Данные карт сохранять не допускается.

# Перечень используемых инструментов

IntelliJ IDEA Community Edition 

Базы данных, библиотеки, плагины - JUnit5, Selenide, Lombok, Allure, JavaFaker, DBeaver и др.

Git - система контроля версий

Java JDK 11 - язык программирования

Google Chrome - для работы с интерфейсом сайта

Node.js - программная платформа для запуска симулятора

MySQL - заявленная СУБД

PostgreSQL - заявленная СУБД

# Перечень возможных рисков при автоматизации

* Автоматизация может быть не оправдана с точки зрения трудовых и финансовых затрат.
* В случае внедрения нового функционала тесты могут стать неэффективными, нужна будет доработка. 
* Ошибки в автотестах могут приводить к мнимому отсутствию или наличию дефектов.
* Сложности с настройкой/запуском тестового окружения.
* Сбои работы ПО/ тестового окружения/ сетевых сервисов.

# Интервальная оценка с учётом рисков (в часах)

8-12 часов - подготовка тестовой среды

36-54 часа - написание автотестов

8-10 часов - подготовка отчетности

18-24 часов - интеграция проекта с CI

36 часов - наступление возможных рисков

# План сдачи работ

10.08.2022 - сдача кода автотестов

17.08.2022 - сдача отчетности о проведенном тестировании

24.08.2022 - интеграция проекта с CI

