# Анализ бизнес-показателей развлекательного приложения Procrastinate Pro+

Я - маркетинговый аналитик развлекательного приложения Procrastinate Pro+. Несколько прошлых месяцев мой бизнес постоянно нес убытки - в привлечение пользователей была вложена куча денег, а толку никакого.

Цель исследования -разобраться в причинах убытков бизнеса.

Есть данные о пользователях, привлечённых с 1 мая по 27 октября 2019 года:
- лог сервера с данными об их посещениях,
- выгрузка их покупок за этот период,
- рекламные расходы.
Мне предстоит изучить:
- откуда приходят пользователи и какими устройствами они пользуются,
- сколько стоит привлечение пользователей из различных рекламных каналов;
- сколько денег приносит каждый клиент,
- когда расходы на привлечение клиента окупаются,
- какие факторы мешают привлечению клиентов.

Описание данных:
В нашем распоряжении три датасета. Файл visits_info_short.csv хранит лог сервера с информацией о посещениях сайта, orders_info_short.csv — информацию о заказах, а costs_info_short.csv — информацию о расходах на рекламу.

Структура visits_info_short.csv:

| Название столбца | Описание |
| ------ | ------ |
| User Id | уникальный идентификатор пользователя |
| Region | страна пользователя |
| Device | тип устройства пользователя |
| Channel | идентификатор источника перехода |
| Session Start | дата и время начала сессии |
| Session End | дата и время окончания сессии |

Структура orders_info_short.csv:

| Название столбца | Описание |
| ------ | ------ |
| User Id | уникальный идентификатор пользователя |
| Event Dt | дата и время покупки |
| Revenue | сумма заказа |

## Вывод

Было проведено маркетинговое исследование развлекательного приложения Procrastinate Pro+. Пользователи данного приложения из 4 регионов: США, Великобритания, Франция и Германия. Существенный отрыв в количестве пользователей наблюдается у США, но у них наблюдается самая высокая стоимость рекламы и низкая окупаемость. Самое популярное устройство у пользователей приложения - iPhone. Среди каналов продвижения самые большие расходы на рекламу у каналов TipTop и FaceBoom.
В целом реклама на привлечение пользователей не окупилась из-за чрезмерных нерациональных расходов. 
