**_Задание 2_**: *Переведите четыре абзаца полученного после ваших исправлений текста на английский язык.*


**_Комментарий_**: it was difficult to strictly count four paragraphs, because I used lists in the original text.
 
**Оригинальный текст**

 
# Разработка SDK-библиотеки
Необходимо создать SDK-библиотеку, реализующую функционал магазина на основе Paystation API.  


Цели разработки:
- Упрощение использования платежного решения Xsolla для разработчиков альтернативных платформ;
- Снижение порога вхождения при использовании продукта на конкретной платформе.
## Назначение библиотеки
### Эксплуатационное
- Предоставить разработчикам удобный инструмент, чтобы снизить трудозатраты по внедрению биллингового решения компании Xsolla;
- Улучшить user experience конечного пользователя: инструмент должен быть наглядным, снижать или вовсе исключать дополнительные переходы на другие страницы интерфейса.
### Функциональное
- Назначение библиотеки не должно вызывать вопросов у разработчиков;
- Разработчик должен использовать только один запрос, чтобы получить полный функционал электронного магазина: модули виртуальной валюты, виртуальные товары, подписки и поддержку нескольких методов оплаты;
- Страницы магазина должны быть отрисованы со всеми внутренними взаимодействиями посредством API. Отрисовка должна включать следующие экраны:  
     + экран виртуальных товаров, 
     + экран виртуальной валюты, 
     + экран подписок, 
     + экраны выбора методов оплаты, 
     + экран оплаты, 
     + экран статуса, 
     + экран ошибки.
## Термины и определения
**Токен** – специальная шифрованная строка, необходимая для взаимодействия с Xsolla;  
**JSON** – формат обмена данными между SDK и сервисами Xsolla Paystation;  
**Серверная интеграция** – интеграция и взаимодействие с Xsolla, которые работают через специально настроенный сервер;  
**Упрощённая интеграция** –  интеграция и взаимодействие с Xsolla, которые работают через клиент; сервер игры отсутствует;  
**Header** – блок в верхней части страницы, который виден на всех страницах магазина. Включает в себя, как правило, логотип, меню, контакты, переключатель языков и корзину, а также пункты навигационного меню;  
**Footer** – блок в нижней части страницы, который виден на всех страницах магазина. Содержит полезную, но не первостепенную информацию.


**Перевод**


# Creating SDK-library
We need to create SDK-library, which implements the functional of the store on the basis of the Paystation API.


Creation goals of SDK:  
- Simplify of using Xsolla payment solution for developers of alternative platforms;  
- Decrease the input threshold for using product on a specific platform.  
## Appointment of the library
### Exploitation appointment
- Provide for developers comfortable instrument to reduce labor expenditures for implementing billig solution of Xsolla;
- Improve user experience: instrument should be native, and should reduce or exclude transition to the additional pages.
### Functional appointment
- Appointment of library shouldn’t made a questions from developers;
- Developer should use one query to get whole functionality of the online store: virtual currency modules, virtual products, subscriptions and support for a lot of payment methods;
- The online store pages should generated with all elements and cross-element interactions by API. Generated store should include following screens:  
     + the screen of virtual products;
     + the screen of virtual currency;
     + the screen of subscriptions;
     + the screen of payment methods;
     + the screen of payment;
     + the screen of status;
     + the screen of error.
## Terms and definitions
**Token** – special encrypted string for interaction with Xsolla services;  
**JSON** – the format for exchanging data between SDK and Xsolla Paystation services;  
**Server integration** – integration and interaction with Xsolla services, which work through the dedicated server;  
**Simplified integration** – integration and interaction with Xsolla services, which work through the client application itself;  
**Header** – block at the top of the website, which you can see on the all store pages. Header usually includes logo, menu, contacts, language switch and basket and points of navigation menu;  
**Footer** – block at the bottom of the website, which you can see on the all store pages. Footer includes useful, but not obligatory information.
