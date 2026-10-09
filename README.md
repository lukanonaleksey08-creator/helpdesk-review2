# helpdesk-review

Учебный проект: простой AST-анализатор и модуль для работы с тикетами.

## Файлы
- `static_review.py` — ищет неиспользуемые импорты (W001) и mutable default arguments (W002).
- `helpdesk.py` — учебный модуль с тикетами (дефекты оставлены намеренно).

## Запуск
```bash
python static_review.py helpdesk.py
