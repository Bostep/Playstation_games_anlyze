Данный проект, состоит из анализа датасета игр для игровых приставок PlayStation и примения моеделей машинного обучения из готовых библиотек питона для предсказания рейтинга игры и кол-во отзывов о ней. В итоге ожидаются выовды о важности каждого из критереив и их свзяь с рейтингом игр и кол-во отзывов (поупялрность).
Также можно исипользовать обученные модели для предсказания. Предсказание может быть использовано для определения оценки выгодности при создании компьютерной игры.  
Для обучения использовались данные Information on PlayStation games from the PS Store as of 3 June 2024. https://www.kaggle.com/datasets/evgeny1928/playstation-games-info находятся в файле archive(1).zip. имеет вид:
For all csv:

    title - game title. Data in format - string
    platforms - platforms on which the game is available. Data in format - list of strings
    rating - game rating. Data in the format - real number
    votes - number of votes. Data in the format - integer
    developer - game developer. Data in the format - string
    release_date - game release date. Data in the format - date
    price - price of the game in $. Data in the format - real number
    genres - game genres. Data in format - list of strings
    url - link to the game. Data in format - string


План работы:
0) разобраться с библиотеками для анлиза данных и машинного обучения
1) провести подготовку данных и предварительный анализ
2) провести базовый предварительный анализ данных (построить корреляционную матрицу и т.п.)
3) использовать несколько моделей машинного обучени для предсказания целевых переменных (rating, votes)
4) поппытаться улучшить результат с помощью подбора гиперпараметров
5) посмотреть важность признаков

P.S часть кода работы сгенерирована с помощью chat GPT 
