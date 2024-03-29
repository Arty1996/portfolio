# Определение наиболее выгодного региона нефтедобычи


Мне предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Нужно построить модель для определения региона, где добыча принесёт наибольшую прибыль.

**Задача проекта:** на основе данных геологи разведки выбрать район добычи нефти.

**Сфера деятельности:** добывающие компании.

**Направление деятельности:** машинное обучение, регрессия, разработка бизнес-модели, финансовый анализ.

**Инструменты:** Python, Pandas, Scikit-learn, бутстреп

**Краткий вывод:** среди представленных трёх регионов второй регион обладает приемлемым уровнем риска. Так же для этого региона характерна наиболее высокая средняя прибыль несмотря на то, что средние запасы на скважину оказались самыми низкими. Это связано с тем, что именно для этого региона модель работает наиболее адекватно (RMSE около погрешности). Следовательно, **для разработки скважен следует выбрать второй регион**.