# Изучение закономерностей, определяющих успешность игр

## Основная задача: 
Исходя их открытых данных об играх, необходимо выявить определяющие успешность игры закономерности.

## Цель:
На основании проведенного анализа можно будет сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.

## Используемые библиотеки:
pandas, matplotlib, numpy, math, scipy, warnings

## Данные
В наличии были следующие данные:

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

## Статус
Проект выполнен и проверен.

В ходе выполнения проекта были сделаны следующие выводы:

- При выборе игр, следует обратить на игры, выпускаемые на платформах нового поколения - PS4 и XOne, персональных компьютерах и портативной приставке 3DS.
- Из жанров следует обратить внимание на игры жанра Action, Shooter и Role-Playing. Причем, для рекламы Action и Role-Playing следует выбирать игры известных серий или производителей, среди Shooter можно вкладываться в рекламу и малоизвестных новинок - для оценок этого нужен более глубокий анализ на более детальных данных.
- При рекламе, ориентированной на игроков Северной Америки и Евросоюза, следует больше внимания уделять платфорам PS4 и XOne и жанрам Action и Shooter. При рекламе, ориентированной на Японию, следует уделить влияние играм на портативных консолях в жанрах Role-Playing и Action.
