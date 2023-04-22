<h3> Интенсив Академии Яндекса | Весна 2023 | Большие данные </h3>


<h1> Анализ велопроката</h1>


## Тема проекта
Анализ велопроката [Divvy](https://divvybikes.com/) в Чикаго по открытому датасету
<p align="center">
  <img src="https://d21xlh2maitm24.cloudfront.net/chi/Divvy-Header-Logo.svg?mtime=20160809095032" width=30%  title="Divvy логотип"/> 
  <img src="https://avatars.mds.yandex.net/get-lpc/1520633/bf3e850c-30f0-4d25-b040-7b03bcc406b8/orig" width=30%  title="Логотип Яндекс Академии"/>
</p>


## Цели проекта
* **Анализ динамики бизнеса:** растет ли количество пользователей, поездок, прибыль
* **Расчет доходов**: по тарифам описанным на сайте и вычислив примерное количество подписчиков  
* **Расчет расходов**: учитывая несколько показателей (от затрат на аренду территории до перемещения велосипедов)
* **Анализ сезонности**: меняется ли популярность в зависимости от дня недели/месяца/времени суток
* **Расчет нагрузки на велосипеды**: сколько нужно доступных велосипедов чтобы покрыть запрос на велосипеды в 95% случаев
* **Подсчет расстояния** между самыми популярными парами станций
* **Анализ нагрузки на велосипеды**: сколько проезжает/находится в прокате один велосипед
* **Нанесение станций на карту Чикаго**
* **Изучение маятниковости станций**: определение станций с маятниковой миграцией

## Презентация 
 <p align="center">
    <a href="https://disk.yandex.ru/d/Nz5nRckohTuKRg"><img src="https://user-images.githubusercontent.com/78593359/233707041-131a39ef-56d3-47d7-8a96-5f07a554c96e.png" width=50%/></a>
 </p>

 ## Датасет
 Описание датасета доступно в [README](https://github.com/kapibarr/big-data-project/blob/0cfbc8fe06632e00b75f7d15ebf167e70813e28d/data/2017/README.txt) по годам и на [официальном сайте](https://divvybikes.com/system-data)
 

 
 ## Описание файлов
 | Название файла                        | Описание                                                                                                                   | Ссылки                                                                                                                                     |
 | ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
 | `2013-2023_3_months.ipynb`            | Сравнение первых трех месяцев 2023 с остальными годами                                                                     | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/2013-2023_3_months.ipynb)                                                  |
 | `amount_of_rides_per_year.ipynb`      | Подсчет количества поездок по годам                                                                                        | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/amount_of_rides_per_year.ipynb "amount_of_rides_per_year.ipynb")           |
 | `basic_statistic.ipynb`               | Базовые расчеты: распределение member/casual, поездок по месяцам/дням недели/времени суток/типу велосипеда/длительности... | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/basic_statistic.ipynb "basic_statistic.ipynb")                             |
 | `bicycle_losses.ipynb`                | Подсчет количества потерянных велосипедов                                                                                  | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/bicycle_losses.ipynb "bicycle_losses.ipynb")                               |
 | `circularity_stations_analysis.ipynb` | Нахождение станций с маятниковой миграцией                                                                                 | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/circularity_stations_analysis.ipynb "circularity_stations_analysis.ipynb") |
 | `costs_count.ipynb`                   | Оценка расходов                                                                                                            | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/costs_count.ipynb "costs_count.ipynb")                                     |
 | `distance_between_stations.ipynb`     | Расчет прямого расстояния между станциями                                                                                  | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/distance_between_stations.ipynb "distance_between_stations.ipynb")         |
 | `distance_per_bike.ipynb`             | Анализ расстояния пройденного велосипедами: сколько проезжает за год/все время + срок службы                               | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/distance_per_bike.ipynb "distance_per_bike.ipynb")                         |
 | `full_price_calculation.ipynb`        | Подсчет доходов                                                                                                            | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/full_price_calculation.ipynb "full_price_calculation.ipynb")               |
 | `gender-age.ipynb`                    | Анализ распределения по полу/возрасту                                                                                      | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/gender-age.ipynb "gender-age.ipynb")                                       |
 | `getting_big_tables.ipynb`            | Получение полных дататсетов из скачанных данных                                                                            | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/getting_big_tables.ipynb "getting_big_tables.ipynb")                       |
 | `load_model.ipynb`                    | Анализ нагрузки: количество велосипедов нужное для покрытия спроса по сезонам/нахождение самых загруженных станций         | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/load_model.ipynb "load_model.ipynb")                                       |
 | `map_station.ipynb`                   | Распределение станций по карте                                                                                             | [Ссылка](https://nbviewer.org/github/kapibarr/big-data-project/blob/59150fb95499eb7562cfbd66facf908c8ce1ce53/map_station.ipynb)            |
 | `members_procent_circularity.ipynb`   | Получение оценки количества подписчиков сверху (по станциям с маятниковой миграцией)                                       | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/members_procent_circularity.ipynb "members_procent_circularity.ipynb")     |
 | `minute_2022.ipynb`                   | Оценка стоимости минуты проезда в 2022                                                                                     | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/minute_2022.ipynb "minute_2022.ipynb")                                     |
 | `moving_bikes_model.ipynb`            | Расчет оптимального перемещения велосипедов к перегруженным станциям                                                       | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/moving_bikes_model.ipynb "moving_bikes_model.ipynb")                       |
 | `park_station.ipynb`                  | Получение оценки количества подписчиков снизу (по парковым станциям)                                                       | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/park_station.ipynb "park_station.ipynb")                                   |
 | `season_analysis.ipynb`               | Анализ сезонности поездок                                                                                                  | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/season_analysis.ipynb "season_analysis.ipynb")                             |
 | `station_graphs.ipynb`                | Проверка идеи о том что между станциями с похожим типом ID больше связей на графах                                         | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/station_graphs.ipynb "station_graphs.ipynb")                               |
 | `stations_statistic.ipynb`            | Статистика по станциям: абсолютная/средняя вместимость, количество                                                         | [Ссылка](https://github.com/kapibarr/big-data-project/blob/main/stations_statistic.ipynb "stations_statistic.ipynb")                       |





## Команда

<p>
  <img src="https://user-images.githubusercontent.com/78593359/233491427-a6211739-2db4-45cf-9608-98deb44e8613.png" width=20% align="left"/>
<h3> Фёдор Покрышкин  | Техлид | <a href="https://github.com/kapibarr">@kapibarr</a></h3>
  Ведение репозитория | Обработка данных | Расчет перемещения велосипедов
</p>


<br clear="left"/>
<br>

<p>  
  <img src="https://user-images.githubusercontent.com/78593359/233491501-b23f9af1-bb20-4b9a-9620-70aa32df8c34.png" width=20% align="left"/>
  <h3> Ульяна Коровина | Аналитик | <a href="https://github.com/ivame"> @ivame</a> </h3>
  Анализ сезонности | Презентация | Расчет окупаемости велосипеда
 </p>


<br clear="left"/>
<br>

<p>  
  <img src="https://user-images.githubusercontent.com/78593359/233491399-8d26dff9-233d-4d35-b324-8c278adbee59.png" width=20% align="left"/>
  <h3> Нелли Мазитова | Аналитик | <a href="https://github.com/Nelli0412"> @Nelli0412</a></h3>
  Расчет расходов | Нахождение количества подписчиков | Работа с картами
 </p>
