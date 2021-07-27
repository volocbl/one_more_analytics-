# Определение закономерностей успеха игр
### Определим факторы, влияющие на успех игры, проверим гипотезы.
### Исследование разделим на несколько частей.

Перед нами исторические данные из открытых источников о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

## Для работы над этим проектом использовались следующие библиотеки:
- pandas
- numpy
- math
- matplotlib.pyplot
- stats from scipy


Часть 1. Импортируем библиотеки и прочитаем данные
- Импортируем библиотеки и прочитаем данные

Часть 2. Подготовим данные
- Приведем названия столбцов к нижнему регистру
- Обработаем пропуски
- Изменим тип данных
- Добавим столбец с суммарными продажами по всем регионам

Часть 3. Проанализируем данные
    Посмотрим сколько игр выпускалось в разные годы
    Посмотрим как менялись продажи по платформам
    Выберем актуальные данные для анализа
    Проанализируем платформы
    Посмотрим на распределение глобальных продаж игр в разрезе платформ
    Посмотрим, как влияют на продажи внутри одной популярной платформы отзывы пользователей и критиков
    Сравним выводы по одной платформе с выводами по всем платформам
    Посмотрим на общее распределение игр по жанрам

Часть 4. Составим портрет пользователя кажджого региона
    Составим портрет пользователя для региона NA
    Составим портрет пользователя для региона EU
    Составим портрет пользователя для региона JP

Часть 5. Проверим гипотезы
    Действительно ли средние пользовательские рейтинги платформ Xbox One и PC одинаковые
    Действительно ли средние пользовательские рейтинги жанров Action и Sports разные

Часть 6. Заключение
    Общий вывод

Описание данных:
    Name — название игры
    Platform — платформа
    Year_of_Release — год выпуска
    Genre — жанр игры
    NA_sales — продажи в Северной Америке (миллионы проданных копий)
    EU_sales — продажи в Европе (миллионы проданных копий)
    JP_sales — продажи в Японии (миллионы проданных копий)
    Other_sales — продажи в других странах (миллионы проданных копий)
    Critic_Score — оценка критиков (максимум 100)
    User_Score — оценка пользователей (максимум 10)
    Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.

Данные за 2016 год могут быть неполными.