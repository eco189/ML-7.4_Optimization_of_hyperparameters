# ML-7.4: Оптимизация параметров

## Оглавление  
[1. Описание проекта](https://github.com/eco189/ML-7.4_Optimization_of_hyperparameters/blob/main/README.md#Описание-проекта)  
[2. Какой кейс решаем?](https://github.com/eco189/ML-7.4_Optimization_of_hyperparameters/blob/main/README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](https://github.com/eco189/ML-7.4_Optimization_of_hyperparameters/blob/main/README.md#Краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/eco189/ML-7.4_Optimization_of_hyperparameters/blob/main/README.md#Этапы-работы-над-проектом)  
[5. Результат](https://github.com/eco189/ML-7.4_Optimization_of_hyperparameters/blob/main/README.md#Результат)    
[6. Выводы](https://github.com/eco189/ML-7.4_Optimization_of_hyperparameters/blob/main/README.md#Выводы)

### Описание проекта
Оптимизация гиперпараметров моделей логистической регрессии и случайного леса четырьмя способами: GridSeachCV, RandomizedSearchCV, Hyperopt, Optuna.

:arrow_up:[к оглавлению](https://github.com/eco189/ML-7.4_Optimization_of_hyperparameters/blob/main/README.md#Оглавление)


### Какой кейс решаем?
Необходимо предсказать биологический ответ молекул (столбец 'Activity') по их химическому составу (столбцы D1-D1776).

:arrow_up:[к оглавлению](https://github.com/eco189/ML-7.4_Optimization_of_hyperparameters/blob/main/README.md#Оглавление)

**Условия задания:**
- Предварительная обработка не требуется, данные уже закодированы и нормализованы.
- В качестве метрики используется F1-score.
- Необходимо обучить две модели: логистическую регрессию и случайный лес. Далее нужно сделать подбор гиперпараметров с помощью базовых и продвинутых методов оптимизации. Важно использовать все четыре метода (GridSeachCV, RandomizedSearchCV, Hyperopt, Optuna) хотя бы по разу, максимальное количество итераций не должно превышать 50.


### Краткая информация о данных
Данные о резюме находятся в хранилище Google Диск. Название файла: dst-3.0_16_1_hh_database.csv Разделитель: sep=';' Ссылка: https://drive.google.com/file/d/1X0DHXtnNS58Y3CPS78gjAI49QetcHQeY/view?usp=sharing

Данные представлены в формате CSV. Каждая строка представляет молекулу.
- Первый столбец Activity содержит экспериментальные данные, описывающие фактический биологический ответ [0, 1]
- Остальные столбцы D1-D1776 представляют собой молекулярные дескрипторы — это вычисляемые свойства, которые могут фиксировать некоторые характеристики молекулы, например размер, форму или состав элементов

:arrow_up:[к оглавлению](https://github.com/eco189/ML-7.4_Optimization_of_hyperparameters/blob/main/README.md#Оглавление)


### Этапы работы над проектом
Реализован подбор гиперпараметров для моделей логистической регрессии и случайного леса четырьмя способами:
- GridGridSeachCV
- RandomizedSearchCV
- Hyperopt
- Optuna

:arrow_up:[к оглавлению](https://github.com/eco189/ML-7.4_Optimization_of_hyperparameters/blob/main/README.md#Оглавление)


### Результат:
- В результате оптимизации были улучшены метрики F1-score на тестовых выборках каждой модели. Метрика была улучшена после применения каждого из четырех методов оптимизации.   
- Блоки кода можно использовать в качестве готовых шаблонов при построении ML-моделей.

:arrow_up:[к оглавлению](https://github.com/eco189/ML-7.4_Optimization_of_hyperparameters/blob/main/README.md#Оглавление)
