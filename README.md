# Репозиторий с проектами курса "Специалист по Data Science" от Яндекс Практикум
**Статус проекта:** завершён.

В репозитории собраны все проекты выполненные на курсе, в том числе проекты с
автоматической проверкой. 

**Цель** - обобщить полученные знания и опыт,
продемонстрировать полученные навыки.


## Структура репозитория
Каждый проект помещён в одельный каталог, каталоги пронумерованы в порядке 
выполнения проектов. В каждом каталоге есть описание проекта и тетрадка с 
выполненным заданием.

## Список наиболее интересных проектов
Ниже приведены проекты лучше всего показывающие приобретённые навыки:
1. [**Выпускной проект**](15%20Выпускной%20проект) - Решение задачи регрессии, применение моделей градиентного бустинга: **CatBoost** и **LightGBM**, настройка гиперпараметров с **gridSearch**, анализ остатков, оценка значимости признаков с **get_features_importance**.
1. [Классификация тональности текстов](13%20Машинное%20обучение%20для%20тектов) - Создание векторных представлений текстов с **BERT** и классификация комментариев на негативные и позитивные.
1. [Прогнозирование заказов такси](12%20Прогнозирование%20заказов%20такси) - Анализ временных рядов и предсказание следующего значения целевой переменной (регрессия).
1. [Определение стоимости автомобилей](11%20Определение%20стоимости%20автомобилей) - Пример решения задачи регрессии в том числе с применением моделей градиентного бустинга: **CatBoost** и **LightGBM**.
1. [Определение возраста покупателей](14%20Компьютерное%20зрение) - Пример работы с изображениями, модель, определяющая по фотографии возраст человека.
1. [Сборный проект №2](09%20%D0%A1%D0%91%D0%9E%D0%A0%D0%9D%D0%AB%D0%99%20%D0%9F%D0%A0%D0%9E%D0%95%D0%9A%D0%A2%20-%202) - Исследование данных, тестирование 
статистических гипотез, красивые графики, настройка гиперпараметров моделей.
1. [Отток клиентов](07%20Обучение%20с%20учителем) - Борьба с дисбалансом классов целевой переменной сравнение нескольких моделей между собой, настройка гиперпараметров.
1. [Выбор локации для скважины](08%20Машинное%20обучение%20в%20бизнесе) - Оценка возможных прибыли и убытков с помощью техники **Bootstrap**.
1. [Сборный проект №1](05%20СБОРНЫЙ%20ПРОЕКТ%20-%201) - Довольно тщательное исследования данных с выводами, 
красивые графики, тестирование гипотез.


## Выполненные проекты
Проекты расположены в хронологической последовательности, чтобы можно было оценить рост качества.

| Название проекта | Описание | Используемые библиотеки | Подробное описание | 
| :---------------------- | :---------------------- | :---------------------- | :---------------------- |
| [Музыка больших городов](01%20Музыка%20больших%20городов) | Сравнение предпочтений пользователей Яндекс.Музыки из Москвы и Санкт-Петербурга в зависимости от времени (утро и вечер) и дня недели (понедельник, среда, пятница). | *pandas* | [README.md](01%20Музыка%20больших%20городов/README.md) |
| [Исследование надёжности заёмщиков](02%20Исследование%20надёжности%20заёмщиков) | Задача определить какие факторы влияют на возврат кредита в срок, в частности, разобраться какое влияние оказывает семейное положение и количество детей. | *pandas*, *seaborn*, *matplotlib* | [README.md](02%20Исследование%20надёжности%20заёмщиков/README.md) |
| [Исследование объявлений о продаже квартир](03%20Исследовательский%20анализ%20данных) | Задача выполнить предобработку данных и изучить их, чтобы найти интересные особенности и зависимости, которые существуют на рынке недвижимости в Санкт-Перербурге и соседних населённых пунктах. | *pandas*, *numpy*, *matplotlib* | [README.md](03%20Исследовательский%20анализ%20данных/README.md) |
| [Статистический анализ данных](04%20Статистический%20анализ%20данных) | Предварительный анализ тарифов на небольшой выборке клиентов. | *pandas*, *seaborn*, *scipy.stats* | [README.md](04%20Статистический%20анализ%20данных/README.md) |
| [Сборный проект №1](05%20СБОРНЫЙ%20ПРОЕКТ%20-%201) | По историческим данным из открытых источников выявить определяющие успешность игры закономерности. | *matplotlib*, *numpy*, *pandas*, *scipy.stats* | [README.md](05%20СБОРНЫЙ%20ПРОЕКТ%20-%201/README.md) |
| [Рекомендация тарифов](06%20Введение%20в%20машинное%20обучение) | Задача по данным о поведении клиентов мобильного оператора определить какой из двух новых тарифов предложить пользователю. | *imblearn*, *matplotlib*, *numpy*, *seaborn*, *sklearn*, *pandas* | [README.md](06%20Введение%20в%20машинное%20обучение/README.md) |
| [Отток клиентов](07%20Обучение%20с%20учителем) | Задача по историческим данным о поведении клиентов банка спрогнозировать уйдёт клиент из банка в билжайшее время или нет. | *category_encoders*, *imblearn*, *matplotlib*, *numpy*, *seaborn*, *sklearn*, *pandas* | [README.md](07%20Обучение%20с%20учителем/README.md) |
| [Выбор локации для скважины](08%20Машинное%20обучение%20в%20бизнесе) | Задача решить где бурить скважину с помощью линейной регрессии и техники *bootstrap*. | *matplotlib*, *numpy*, *pandas*, *seaborn*, *sklearn* | [README.md](08%20Машинное%20обучение%20в%20бизнесе/README.md) |
| [Сборный проект №2. Восстановление золота из руды](09%20СБОРНЫЙ%20ПРОЕКТ%20-%202) | Задача подготовить модель, которая предскажет коэффициент восстановления золота из золотосодержащей руды, используя данные с параметрами добычи и очистки. | *matplotlib*, *numpy*, *pandas*, *seaborn*, *scipy.stats*, *sklearn* | [README.md](09%20СБОРНЫЙ%20ПРОЕКТ%20-%202/README.md) |
| [Защита персональных данных клиентов](10%20Защита%20персональных%20данных%20клиентов) | Необходимо защитить данные клиентов страховой компании и разработайть такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию, обосновать корректность его работы. | *matplotlib*, *numpy*, *pandas*, *seaborn*, *sklearn* | [README.md](10%20Защита%20персональных%20данных%20клиентов/README.md) |
| [Определение стоимости автомобилей](11%20Определение%20стоимости%20автомобилей) | Необходимо предсказать стоимость автомобиля по историческим данным: техническим характеристикам, комплектации и ценам. | *CatBoost*, *category_encoders*, *LightGBM*, *matplotlib*, *numpy*, *pandas*, *seaborn*, *sklearn*, *scipy.stats* | [README.md](11%20Определение%20стоимости%20автомобилей/README.md) |
| [Прогнозирование заказов такси](12%20Прогнозирование%20заказов%20такси) | Анализ временных рядов. Необходимо построить модель, предсказывающую количество заказов такси на следующий час. | *category_encoders*, *LightGBM*, *matplotlib*, *numpy*, *pandas*, *sklearn*, *statsmodels.tsa.seasonal* | [README.md](12%20Прогнозирование%20заказов%20такси/README.md) |
| [Классификация тональности текстов](13%20Машинное%20обучение%20для%20тектов) | Необходимо построить модель, классифицирующую комментарии на позитивные и негативные. | *joblib*, *LightGBM*, *matplotlib*, *numpy*, *pandas*, *seaborn*, *sklearn*, *torch*, *transformers* | [README.md](13%20Машинное%20обучение%20для%20тектов/README.md) |
| [Определение возраста покупателей](14%20Компьютерное%20зрение) | Необходимо построить модель, определяющую по фотографии приблизительный возраст человека. | *keras*, *matplotlib*, *pandas* | [README.md](14%20Компьютерное%20зрение/README.md) |
| [**Выпускной проект**](15%20Выпускной%20проект) | Необходимо построить модель, прогнозирующую температуру стали в ковше перед разливкой. | *catboost*, *lightgbm*, *matplotlib*, *numpy*, *gridsearch*, *pandas*, *seaborn*, *sklearn* | [README.md](15%20Выпускной%20проект/README.md) |
