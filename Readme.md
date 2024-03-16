Прогнозирование температуры звезды

Задача от обсерватории «Небо на ладони»: придумать, как с помощью нейросети определять температуру на поверхности обнаруженных звёзд. Обычно для расчёта температуры учёные пользуются следующими методами: Закон смещения Вина. Закон Стефана-Больцмана. Спектральный анализ. Каждый из них имеет плюсы и минусы. Обсерватория хочет внедрить технологии машинного обучения для предсказания температуры звёзд, надеясь, что этот метод будет наиболее точным и удобным. В базе обсерватории есть характеристики уже изученных 240 звёзд.

Характеристики:

Относительная светимость L/Lo — светимость звезды относительно Солнца.

Относительный радиус R/Ro — радиус звезды относительно радиуса Солнца.

Абсолютная звёздная величина Mv — физическая величина, характеризующая блеск звезды.

Звёздный цвет (white, red, blue, yellow, yellow-orange и др.) — цвет звезды, который определяют на основе спектрального анализа.

Тип звезды. Тип звезды Номер, соответствующий типу:

Коричневый карлик 0

Красный карлик 1

Белый карлик 2

Звёзды главной последовательности 3

Сверхгигант 4

Гипергигант 5

Абсолютная температура T(K) — температура на поверхности звезды в Кельвинах.

Необходимо разработать нейронную сеть, которая поможет предсказывать абсолютную температуру на поверхности звезды. Метрика RMSE не должна превышать 4500.