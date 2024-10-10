# Хакатон: "Аналитика больших данных"

__Цель__: с помощью данных, содержащих сведения о публикационной активности КНР, провести анализ организаний и научных учреждений, занимающихся физикой высоких энергий, а также определить научных партнеров с направлениями сотрудничества.

__Задачи__:
1. Отфильтровать данные, содержащие научные статьи, связанные с физикой высоких энергий;
2. На основе полученных данных определить организации и научные учреждения, которые публикуют работы в области «физики высоких энергий»;
3. Провести анализ сведений об организациях: вывести и визуализировать информацию об их публикационной активности, выступлениях на конференциях, частоте цитирования и пр.

__Описание методологии__:
Алгоритм для поиска активных организаций:
Сортировка по ключевым словам в полях: Название документа, Краткое описание, Ключевые слова автора, Ключевые слова указателя
Сортировка по году выпуска: например период в последнии 5 лет
Добавить фильтрацию в поле Авторы организаций по поиску китайских организаций


Сделанная работа:

Визуализация Организация -> Колличество статей по теме за последние 5 лет

Визуализация по кол-ву совместных статей Организация -> Кол-во совместных статей

Визуализация по Цитирования -> Организация

Идеи:

В кратком описании проанализировать кол-во ключевых слов + оценка от 0 до 10 от LLM насколько статья имеет ценность для ОИЯИ
Использовать веса: вес по кол-ву сравнений + вес от оценки LLM
Таким образом можно потробовать сделать топ и визуализацию организаций с набольшим кол-вом статей наиболее подходящих для ОИЯИ
