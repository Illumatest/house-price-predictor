# 03.03 — Fork and Clone the Repository

## Цель урока

Подготовить собственную копию учебного репозитория для выполнения дальнейших заданий курса.

## Материал урока

Исходный репозиторий курса:

```text
https://github.com/mlopsbootcamp/house-price-predictor
```

Предлагаемый процесс:

1. Создать fork исходного репозитория в своём GitHub-аккаунте.
2. Клонировать личную копию локально.
3. Выполнять задания и сохранять историю изменений в личном репозитории.

## Проверка

Создан fork исходного репозитория курса:

```text
origin  https://github.com/Illumatest/house-price-predictor.git
upstream  https://github.com/mlopsbootcamp/house-price-predictor.git
```

Связи локального репозитория проверяются командой:

```powershell
git remote -v
```

GitHub подтверждает, что `Illumatest/house-price-predictor` является fork с parent `mlopsbootcamp/house-price-predictor`. Предыдущий самостоятельный репозиторий сохранён под именем `Illumatest/house-price-predictor-bootstrap`.

## Результат урока

Fork создан, локальная рабочая копия использует историю исходного проекта, а `upstream` позволяет получать обновления курса. Урок завершён.
