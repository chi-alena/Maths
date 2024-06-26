# МЕТОД КООРДИНАТНОГО СПУСКА

Это тип алгоритма оптимизации, который обычно используется для «сильно выпуклого» случая регрессии — регрессионной функции Lasso и для регрессионной модели Elastic Net.

Метод координатного спуска можно считать одним из простейших методов оптимизации , который  в целом достаточно эффективно ищет локальные минимумы для гладких функций.

При поиске минимума с помощью этого метода мы всегда изменяем положение точки в направлении осей координат, т. е. всегда изменяется только одна координата, и благодаря этому задача становится одномерной.

Если визуализировать работу алгоритма, то мы увидим, что за счёт того, что каждый шаг происходит параллельно одной или другой координатной оси, ход алгоритма становится похож на «лесенку».

# ПРАКТИКА

Мы посмотрели на прописанный без готовых функций алгоритм классического градиентного спуска, чтобы построить прогностическую модель для продаж некоторого продукта на основе количества денег, потраченных на рекламу.

Пришло время попрактиковаться и попробовать самостоятельно реализовать алгоритмы, с которыми вы познакомились для решения той же задачи.

## Вам необходимо:

Скачать файл с данными.
Открыть ноутбук-шаблон с заданием.
Загрузить данные и определить целевую переменную и предикторы.
Нормализовать признаки, с помощью которых вы будете осуществлять предсказание.
Реализовать координатный спуск, следуя подсказкам в файле-шаблоне.
Реализовать стохастический градиентный спуск, следуя подсказкам в файле-шаблоне.
Оценить качество обеих полученных моделей с помощью MSE и MAE.
Сделать содержательные выводы.

# БОНУСНОЕ ЗАДАНИЕ

Разумеется, в реальности специалисты по машинному обучению не прописывают алгоритмы с нуля, а пользуются готовыми реализациями из библиотек. 
Реализованный Вами стохастический градиентный спуск представлен в библиотеке sklearn.

## Что необходимо сделать:

Выберите в документации класс, подходящий для вашей задачи, и обучите стохастический градиентный спуск.
Оцените качество с помощью среднеквадратичной ошибки и сравните результат с результатом алгоритма, реализованного вами самостоятельно.
В одном из предыдущих модулей качество решения задачи регрессии оценивалось с помощью ещё одной метрики. Найдите её реализацию в библиотеке sklearn и оцените качество полученной модели.
Данное задание не является обязательным, но, выполнив его, вы получите возможность заработать дополнительные 3 балла.

