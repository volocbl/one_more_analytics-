# Исследование изменения шрифтов в мобильном приложении

Перед нами данные стартапа, который продаёт продукты питания. Разберемся, как ведут себя пользователи мобильного приложения и изучим воронку продаж.
Дизайнеры захотели поменять шрифты во всём приложении, а менеджеры считают, что пользователям будет непривычно.
Договорились принять решение по результатам A/A/B-теста. Пользователей разбили на 3 группы: 2 контрольные со старыми шрифтами и одну экспериментальную — с новыми.
Выясним, какой шрифт лучше.

## В работе над этим проектом использовались следующие библиотеки:
- pandas;
- scipy.stats;
- datetime;
- numpy;
- matplotlib.pyplot;
- math;
- plotly.express.

## Содержание проекта:
Первичный анализ и подготовка данных
1. Изучение информации о данных;
2. Изменение наименований столбцов;
3. Проверка данных на наличие в них пропусков и дубликатов;
4. Анализ и изменение типов данных и добавление необходимых аналитик;

Изучение и проверка данных
1. Сколько всего событий и пользователей в логе?;
2. Сколько в среднем событий приходится на пользователя?;
3. Анализ полноты данных;
4. Оценка потери данных после фильтрации;
5. Проверка наличия в отфильтрованных данных пользователей всех групп;

Изучение воронки событий
1. Анализ событий;
2. Предположительный порядок событий;
3. На каком шаге больше всего пользователей теряется?;
4. Какая доля пользователей доходит от первого события до оплаты?;

Изучение результата эксперимента
1. Сколько пользователей в каждой экспериментальной группе?;
2. Анализ различий между группами АА;
3. Анализ группы событий в группе В и поиск различий с контрольными группами;
4. Анализ выбранного уровня значимости;

Общий вывод
1. Вывод;
