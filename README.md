# "Telegram-Бот для записи на услуги"

**Оглавление**
- [Описание проекта ](#Описание-проекта )
- [Цели проекта](#Цели-проекта)
- [Функциональность](#функциональность)
- [Команды](#Команды)
- [Система Черного Списка](#Система-Черного-Списка)
- [Пользовательское Соглашение](#Пользовательское-Соглашение)
- [Оценка Услуги](#Оценка-Услуги)
- [Технологии](#Технологии)
- [Контактная информация](#Контактная-информация)

## Описание проекта 
Проект "Telegram-Бот для Записи на Услуги" разработан с целью упростить процесс записи клиентов на различные услуги и управления расписанием. Этот бот предоставляет удобный способ для клиентов записаться на услугу через Telegram, а также для сотрудников и администраторов управлять записями и расписанием. Для более удобного управления данными бота, доступен веб-интерфейс, построенный на базе fastAPI.

## Цели проекта

1. **Упростить процесс записи:** Бот облегчит процесс записи клиентов на услуги, сократив необходимость вручную согласовывать дату и время с клиентами.
2. **Увеличить доступность:** Запись на услуги будет доступна 24/7 через Telegram, что позволит клиентам делать запись в удобное для них время.
3. **Улучшить управление записями:** Администраторы и сотрудники смогут легко просматривать и управлять расписанием и записями через интерфейс бота.
4. **Множество сфер применения:** Бот может быть успешно использован в разных сферах, от маникюра до тату салонов, благодаря возможности добавления и изменения разных видов услуг и подуслуг.
5. **Разделение мастеров:** В боте предусмотрено разделение между мастерами, у каждого из них свой индивидуальный календарь, и клиенты могут сами выбирать, к какому мастеру записаться.
6. **Добавление новых функций:** Планирую расширить функциональность бота, интеграцию с платежными системами и многое другое.

## Функциональность

- **Календарь с доступными датами:** Клиенты могут просматривать календарь с доступными датами для записи на услуги в виде красочных инлайн-кнопок, что делает процесс выбора даты максимально удобным и интуитивно понятным.



  <img alt="calendar.jpg" height="300" src="img%2Fcalendar.jpg" width="300"/>




- **Выбор даты и времени:** Клиенты могут выбирать удобные даты, после чего им предоставляется список свободных временных интервалов для записи на услугу.




  <img alt="time.jpg" height="300" src="img%2Ftime.jpg" width="600"/>



- **Запись на услугу:** После выбора даты и времени, бот автоматически записывает клиента на выбранную услугу и уведомляет мастера, отправляя ему SMS-сообщение с информацией о новой записи.



  <img alt="end-service.jpg" height="300" src="img%2Fend-service.jpg" width="600"/>


- **Роли и доступ:** Бот поддерживает роли клиента, сотрудника и администратора с разными правами доступа.
- **Автоматические напоминания и оценки услуг:** Бот автоматически напоминает клиентам о возможности оценить оказанную услугу после начала процедуры.

## Команды
- `/start`: Начальная команда, которая запрашивает у пользователя согласие на обработку персональных данных, а затем предоставляет доступ к основным функциям бота.

- `/menu`: Меню, где пользователь может выбрать различные функции, такие как изменение имени, фамилии, номера телефона и доступ к услугам.

- `/employee`: Для сотрудников, чтобы просматривать и добавлять записи.

- `/admin`: Для администраторов, чтобы управлять сотрудниками и услугами.


## Система Черного Списка

Бот также предоставляет администраторам возможность добавлять клиентов в черный список и управлять им.

## Пользовательское Соглашение

При первом использовании бота, пользователи будут запрошены предоставить свои имя, фамилию, номер телефона и согласие на обработку персональных данных в соответствии с политикой конфиденциальности.

## Оценка Услуги

После определенного времени начала услуги клиентам автоматически приходит SMS-сообщение с просьбой оценить оказанные услуги в виде звезд, что помогает нам получать важную обратную связь от клиентов и постоянно совершенствовать качество предоставляемых услуг.

## Отмена записи

После записи на услугу клиентам предоставляется возможность отменить ее. Кнопка для отмены записи доступна в меню (/menu). После отмены записи мастеру отправляется SMS-уведомление о том, что его запись была отменена.

## Технологии

- **Фреймворк для бота:** Aiogram
- **Система управления базой данных:** PostgreSQL
- **ORM для работы с базой данных:** SQLAlchemy
- **Веб-интерфейс для администрирования:** FastAPI

## Контактная информация

- **Разработчик:** Амир
- **Электронная почта:** amir.66garaev@gmail.com
- **Telegram:** @de_la_verrier
- **GitHub:** https://github.com/DeLaVerrierr





