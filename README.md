# Прогнозирование оттока клиентов для кофейни Happy Beans Coffee

## Описание проекта
Проект по прогнозированию оттока клиентов сервиса доставки кофе. Используются модели машинного обучения для выявления клиентов с высокой вероятностью прекращения использования сервиса.

## Структура проекта
- `CoffeeDelivery.ipynb` - основной ноутбук с анализом и построением модели
- `coffee_churn_dataset.csv` - исходные данные
- `requirements.txt` - зависимости Python
- `coffee_preprocessor.joblib` - сохранённый препроцессор данных
- `final_coffee_model.joblib` - финальная модель машинного обучения

## Установка и запуск
1. Установите зависимости: `pip install -r requirements.txt`
2. Запустите Jupyter Notebook: `jupyter notebook CoffeeDelivery.ipynb`
