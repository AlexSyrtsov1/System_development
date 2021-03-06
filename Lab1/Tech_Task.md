# Техническое задание по разработке сервиса для резервирования в гостинице

Выполнил: Сырцов Александр | НФИбд-03-19

-------------

## Содержание
- [Цель проекта](#цель)
- [Миссия проекта](#миссия)
- [Взаимодействие с сервисом](#взаимодействие-с-сервисом)
- [Примеры иных сервисов](#примеры-сервисов)
- [Требования по корпоративному стилю](#стиль)
- [Технические требования к сервису](#технические-требования)

-------------

## Цель

Цель проекта — разработать сервис работающий по принципу агрегатора, который позволит легко производить резервирование номеров в гостиницах для получения прибыли за предоставление спектра виртуальных услуг взаимодействия организаций и персон с гостиницами.

-------------

## Миссия

Сервис решит множество проблем, связанных с взаимодействием между пользователем и гостиницами. Мы планируем помочь малому бизнесу, который не может позволить дорогостоящее продвижение, и пользователям, чьи поиски подходящей гостиницы превращаются в бюрократический кошмар. 

-------------

## Взаимодействие с сервисом

### Возможности клиента

Сервис должен обеспечивать клиенту, то есть физическому лицу, возможность регистрироваться в системе; просматривать данные о гостиницах; осуществлять поиск гостиницы по названию и/или местоположению, поиск выгодного номера по стоимости, относительно времени резервирования, и/или по месту вне зависимости от названия конкретной гостиницы; применять купоны по их номеру; выбирать разные категории номеров; создавать заявки на помощь от службы поддержки сервиса; резервировать несколько номеров; производить оплату внутри сервиса.

При этом сервис должен обрабатывать ситуации одновременного резервирования одного номера разными клиентами.

### Возможности организации

Сервис должен обеспечивать возможности физического лица, а также дополнительные возможности организации, то есть юридического лица, напрямую контактировать с гостиницами без возможности контрактинга.

### Возможности гостиницы

Сервис должен обеспечивать возможность получать заявки о регистрации и денежные переводы, с вычитом стоимости пользования сервисом, от пользователей; регистрироваться в качестве поставщика гостиничных услуг; оставлять временные заявки на предоставление номера(ов); редактировать информацию о своей организации; общаться с организациями - заказчиками услуг напрямую.

### Возможности по администрированию сервиса

У администрации должен быть доступ к действиям пользователей и гостиниц с возможностью ограничивать функционал и доступ к сервису при нарушении соглашений.

-------------

## Примеры сервисов

Стиль и подход к построению сервиса в виде приложения на смартфоны и ПК отлично реализован в агрегаторе HH.ru.

-------------

## Стиль

Оформление сервиса должно содержать затемнённые оттенки синего цвета для панелей меню/ опций, и белый для контента в светлом оформлении и тёмно-серый для тёмного оформления, которое может настраивать пользователь.

-------------

## Технические требования

Сервис должен быть разработан как приложение под платформу `Android`, `IOS`, `Windows 10`(`11`) и в виде сайта оптимизирован под браузеры `Opera`, `Chome`, `Firefox`, `Edge`.
Доступ к сервису должны иметь все пользователи интернет-услуг на территории РФ.
Сервис должен работать с типами трафика BG и BE.
Предлагаемая платформа для разработки — `.NET core`.
