# NoFloodWithAI: прогнозирование паводков на реке Амур

Хакатон по прогнозированию паводков на реке Амур на его различных участках

### Описание задачи

Необходимо разработать алгоритм прогнозирования уровней воды р. Амур для следующих населенных пунктов (гидропостов): Джалинда, Благовещенск, Иннокентьевка, Ленинское, Хабаровск, Комсомольск-на-Амуре, Николаевск-на-Амуре на 10 дней вперед.

Река Амур является трансграничной рекой, основная часть бассейна которой находится в пределах Российской Федерации. Для Амура характерна низкая водность в зимний период, небольшие половодья весной и неоднократные резкие подъемы воды во второй половине лета и в начале осени. Маловодные периоды сменяются годами большой воды.
В многолетнем режиме водного стока Амура отчётливо выражено чередование периодов пониженной и повышенной водности, каждый продолжительностью 12-17 лет. Амур по оценке гидрологов и исходя из истории наблюдений вошел в очередной период высокой водности в конце 2000-х. Исходя из данной гидрологической закономерности режима Амура, в ближайшие 5-7 лет следует ожидать сложную паводковую обстановку в течении Среднего и Нижнего Амура (наиболее сложная обстановка от слияния р. Сунгари и до Комсомольского района включительно). 

Наиболее крупномасштабные наводнения произошли в 2013 и 2019 гг. Причиной наводнений стали тропические циклоны, которые несли теплый влажный воздух, вызывали фронтальные разделы и сильные атмосферные осадки. В 2013 на значительной площади за 2-3 мес. сумма выпавших осадков превысила годовую, а местами и полуторагодовую норму.

В целях минимизации экономического ущерба необходимо создать инструмент для прогнозирования паводковых волн на Амуре и его притоках.

<p align="center">
  <img src="pics/map2.jpg" width="100%">
</p>

На карте выше представлен бассейн реки Амур и его основные притоки с градацией по среднему расходу воды. 
Синие точки — все гидропосты из датасета, белые — интересующие гидропосты, розовые — метеостанции.


### Описание данных

Данные можно скачать [тут](https://drive.google.com/file/d/1tGpsh9zO7v9Guy4K7xYu0ZHeAlda0k4-/view?usp=sharing).

Подробное описание этих данных можно найти в ```desc/datasets_description.pdf```


### Бейзлайн

Ноутбук с бейзлайном: ```baseline.ipynb```

### Оценка решения

Соревнование будет проходить в формате хакатона.

Решением считается репозиторий на [github.com](github.com) c кодом в jupyter notebook (очень хорошо и подробно описанным + всеми данными, необходимыми для его запуска), который должен без ошибок запускаться по кнопке Run All. Пример такого репозитория от организаторов хакатона можно найти [тут]().

Жюри будет выставлять оценки от 0 до 10, принимая во внимание как глубину идеи (в том числе возможность ее переиспользования для предсказания паводков на других реках), так и качество работы предложенного алгоритма в определенные (интересующие жюри) моменты времени.

