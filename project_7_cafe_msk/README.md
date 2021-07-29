# Рынок заведений общественного питания Москвы

Решено открыть небольшое кафе в Москве. Оно оригинальное — гостей должны обслуживать роботы.
Рассмотрим текущее положение дел на рынке с помощью исследования открытых данных о заведениях общественного питания в Москве,
оценим насколько уверенно новое кафе сможет стать популярным долгое время.

## В работе над проектом использовались следующие библиотеки:
- pandas;
- scipy.stats;
- datetime;
- numpy;
- matplotlib.pyplot;
- seaborn;
- plotly.expressl;
- re;
- requests.

## Содержание:
Подготовка данных к анализу
1 Загрузим библиотеки и изучим общую информацию о данных;
1. Проанализируем пропуски и дубликаты;

Анализ данных
1. Исследуем соотношение видов объектов общественного питания по количеству;
2. Исследуем соотношение сетевых и несетевых заведений по количеству;
3. Исследуем для какого вида объекта общественного питания характерно сетевое распространение;
4. Исследуем что характерно для сетевых заведений: много заведений с небольшим числом посадочных мест в каждом или мало заведений с большим количеством посадочных мест;
5. Для каждого вида объекта общественного питания опишем среднее количество посадочных мест. Изучим какой вид предоставляет в среднем самое большое количество посадочных мест;
6. Выделим в отдельный столбец информацию об улице из столбца "address";
7. Построим график топ-10 улиц по количеству объектов общественного питания. Ответим на вопрос в каких районах Москвы находятся эти улицы;
8. Найдем число улиц с одним объектом общественного питания. Определим в каких районах Москвы находятся эти улицы;
9. Изучим распределение количества посадочных мест для улиц с большим количеством объектов общественного питания. Выясним какие закономерности можно выявить;
10. Общий вывод и рекомендации;

Презентация
1. Презентация.

Презентация расположена тут: 
https://drive.google.com/file/d/1ZjSJhQnUoBJYV2pERtRdDIKmT2JHzb2n/view?usp=sharing