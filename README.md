# alfabank_campus_challenge


Ноутбук с решением *Kaggle Community* [соревнования](https://www.kaggle.com/competitions/alfabank-campus/leaderboard), организованного для ~500 потенциальных студентов программы [*Прикладной Data Science в финтехе*](https://alfa-campus.ru/ds-fintech) в Альфа Банке.

Задача — предсказать следующие 10 [*MCC*-кодов](https://www.banki.ru/wikibank/mcc-kod/) 7033 клиентов на основании предыдущих последовательностей *MCC*-кодов различной длины. Целевая метрика — MAP@10.

Решение из этого ноутбука по итогам соревнования заняло 26-е место с MAP@10, равняющимся **0.29414**.

Используемые алгоритмы и инструменты:

- *GRU4Rec*, алгоритм *sequential recommender system*, созданный с архитектурой *RNN* (*recurrent neural network*) и механизмом *GRU* (*gated recurrent unit*) для задачи последовательных рекомендаций. 
- *RecBole*, библиотека с реализациями *SOTA* рекомендательных систем, основанная на `PyTorch`.
- Блендинг предсказаний лучших инстанций моделей.
