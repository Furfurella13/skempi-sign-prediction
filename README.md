# skempi-sign-prediction

Этот проект посвящён анализу данных из базы SKEMPI 2.0 — набора экспериментальных измерений аффинности мутаций белков.

### Описание проекта
- Загружены и обработаны данные мутаций белков из SKEMPI.
- Проведена очистка данных: обработка NaN, удаление аномальных значений аффинности.
- Вычислена переменная sign_ddG (положительное/отрицательное влияние мутации).
- Подготовлены признаки для классификации.
- Разделение данных на train/test.
- Готова основа для обучения моделей машинного обучения на этих данных.

### Данные
SKEMPI 2.0 — экспериментальные измерения изменений в связывании белков при мутациях.

### Как использовать
1. Скачать skempi.ipynb.
2. Установить библиотеки: pandas, numpy, sklearn.
3. Запустить ячейки ноутбука.
4. При желании — обучить модели классификации (sign_ddG).

### Зачем это?
1. Для предсказания эффекта мутаций на связывание белков.
2. Для тренировки моделей машинного обучения в биоинформатике.
