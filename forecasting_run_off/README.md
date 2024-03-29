# Прогнозирование оттока клиентов


Оператор связи хочет научиться прогнозировать отток клиентов. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и договорах.

**Задача проекта:** построить модель прогнозирования оттока клиентов с метрикой ROC-AUC более 0.85.

**Сфера деятельности:** телеком

**Направление деятельности:** машинное обучение, классификация

**Инструменты:** Python, Pandas, Scikit-learn, lightgbm, phik, Seaborn

**Краткий вывод:** В ходе исследования была получена модель, которая правильно предсказывает 85% случаев (остаётся клиент или уходит). Модель угадывает более 87% клиентов, которые действительно расторгли договор, однако среди действующих клиентов модель неправильно предсказала уход для 25% клиентов. Т.к. действующих абонентов гораздо больше ушедших, такое количество False Positive клиентов может существенно увеличить затраты на маркетинговые компании. Наиболее важными признаками в модели оказались длительность договора и совокупные платежи.