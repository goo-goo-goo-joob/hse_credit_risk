# hse_credit_risk

**Проект по оценке кредитного риска физических лиц**

Используется датасет https://www.kaggle.com/wordsforthewise/lending-club

- [01_data.ipynb](01_data.ipynb) - подготовка выборок
- [01_int_rate_corr.ipynb](01_int_rate_corr.ipynb) - ноутбук с проверкой interest rate

- [02_train_catboost.ipynb](02_train_catboost.ipynb) - подбор гиперпараметров и отбор фичей для модели CatBoost
- [02_train_woe.ipynb](02_train_woe.ipynb) - обучение модели WoE

- [03_calibration.ipynb](03_calibration.ipynb) - проверка калибровки
- [03_catboost_calc_losses.ipynb](03_catboost_calc_losses.ipynb) - оценка результатов CatBoost
- [03_woe_calc_losses.ipynb](03_woe_calc_losses.ipynb) - оценка результатов WoE
- [03_validation_part1.ipynb](03_validation_part1.ipynb) - валидация часть 1
- [03_validation_part2.ipynb](03_validation_part2.ipynb) - валидация часть 2 (калибровки, uplift, shap, gini curve, gini per feature)

**Проект выполнили:** [Алексей Подчезерцев](https://github.com/AsciiShell),
  [Мария Самоделкина](https://github.com/goo-goo-goo-joob),
  [Андрей Солодянкин](https://github.com/andrsolo21)
  
