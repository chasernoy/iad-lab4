# Лабораторная работа №4 «Поиск ассоциативных правил»

## Данные
Файл: `data/kz.csv`

Характеристики:
- 1,201,482 транзакции (заказы)
- 444 уникальные категории товаров
- Средняя длина корзины: 4.5 товаров

**Примечание:** Файл слишком большой для GitHub (284 MB). Его нет в папке /data**

## Структура репозитория
- `notebooks/lab4_association.ipynb` — основной ноутбук с анализом (Apriori, FP-Growth, ассоциативные правила).

## Запуск

### 1) Клонирование репозитория
```bash
git clone https://github.com/chasernoy/iad-lab4.git
cd iad-lab4
```
### 2) Окружение и зависимости
``` python3 -m venv .venv
source .venv/bin/activate
pip install -U pip
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter networkx
```
### 3) Запуск ноутбука 
```
python3 -m jupyter lab
