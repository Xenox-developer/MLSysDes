# Predictive Maintenance

## Документация
Проект: Predictive Maintenance.  
  Цель — реализовать pipeline для предиктивного обслуживания: очистка данных, обучение модели (LSTM), индикация аномалий.

---------------------

## Документация
Основной документ с описанием архитектуры, метрик и бизнес-целей находится здесь:
👉 **[ML System Design Document](./docs/ml_system_design_doc.md)**

---------------------

## Структура проекта
```text
├── docs/                   # Документация проекта
│   └── ml_system_design_doc.md
├── src/                    # Исходный код
│   ├── __init__.py
│   ├── data/               # Скрипты для загрузки и обработки данных
│   ├── models/             # Архитектура моделей (LSTM и др.)
│   └── train.py            # Скрипт обучения
├── .gitignore
├── .pre-commit-config.yaml # Конфигурация линтеров
├── pyproject.toml          # Настройки black/ruff/isort
├── README.md
└── requirements.txt        # Зависимости проекта

---------------------

## Контакт
tg: @nikita_fof

---------------------
