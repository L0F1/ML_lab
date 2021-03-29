Группа: М8О-107М-20
Студент: Сотников Иван

## Задача регрессии

Задача на kaggle: https://www.kaggle.com/c/bike-sharing-demand
По историческим данным о прокате велосипедов и погодным условиям необходимо оценить спрос на прокат велосипедов.

Признаки:
datetime - hourly date + timestamp  
season -  1 = spring, 2 = summer, 3 = fall, 4 = winter 
holiday - whether the day is considered a holiday
workingday - whether the day is neither a weekend nor holiday
weather - 1: Clear, Few clouds, Partly cloudy, Partly cloudy
2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog 
temp - temperature in Celsius
atemp - "feels like" temperature in Celsius
humidity - relative humidity
windspeed - wind speed
casual - number of non-registered user rentals initiated
registered - number of registered user rentals initiated
count - number of total rentals

## Задача классификации

Датасет digits из sklearn.datasets

Этот набор данных состоит из 1797 изображений 8x8. Каждое изображение представляет собой рукописную цифру.
В каждом изображении 64 признака - значения пикселя в оттенках серого.
