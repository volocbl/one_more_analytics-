# Оптимизация расходов на маркетинг
Определим факторы, влияющие на результативность кампаний. Перед нами данные сервиса "Яндекс.Афиша".
Нам необходимо помочь маркетологам снизить расходы — отказаться от невыгодных источников трафика и перераспределить бюджет.

Нам предстоит изучить:
- Как клиенты пользуются сервисом;
- Когда делают первые покупки на сайте;
- Сколько денег приносит компании каждый клиент;
- Когда расходы на привлечение клиента окупаются.

***(!) Выручка измеряется в условных единицах — у.е.***

## Для работы над проектом использовались следующие библиотеки:
- pandas;
- numpy;
- seaborn;
- pyplot from matplotlib.

## Содержание проекта:
Импортируем библиотеки и прочитаем данные
1. Импортируем библиотеки и прочитаем данные, запишем их в переменные
2. Изменим тип данных и наименование столбцов

Рассчитаем метрики и построим графики
1. Продуктовые метрики:
   1. Рассчитаем DAU, WAU и MAU;
   2. Определим, сколько раз за день пользователи в среднем заходят на сайт;
   3. Исследуем, сколько времени пользователи проводят на сайте;
   4. Рассчитаем Retention Rate, применяя когортный анализ.
2. Метрики электронной коммерции:
   1. Исследуем, сколько времени в среднем проходит с момента первого посещения сайта до совершения покупки;
   2. Рассчитаем среднее количество покупок на одного клиента за период;
   3. Рассчитаем среднюю выручку с пользователя, проанализируем изменение;
   4. Выясним, как меняется во времени накопительный LTV по когортам.
3. Маркетинговые метрики:
   1. Посчитаем общую сумму расходов на маркетинг и в разрезе источников;
   2. Рассчитаем среднюю стомимость привлечения CAC на одного покупателя в целом и для каждого источника трафика;
   3. Рассчитаем ROMI по когортам в разрезе источников. Сравним окупаемость за одинаковые периоды жизни когорт.

Сформулируем выводы и рекомендации
1. Определим источники трафика и тип устройств, на которые маркетологам стоит делать упор;
2. Суммируем выводы, которые мы сделали после подсчёта метрик каждого вида;
3. Подведем итоги когортного анализа. Определим самые перспективные для компании когорты клиентов;
4. Опишем, как различаются метрики в разрезе устройств.