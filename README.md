# UV info

## Команды

```bash
uv init                          # Инициализация
uv activate                      # Активация окружения
uv add <package>                 # Установка пакета
uv add <package=0.1.0>           # Установка конкретной версии пакета
uv remove <package>              # Удаление пакетов
uv update                        # Обновление пакетов
uv venv                          # Создает виртуальное окружение
uv venv --python=python3.12.11   # Создает виртуальное окружение + версия
uv tree                          # Отображает дерево зависимостей проекта
uv python list                   # Показывает список доступных установленных версий Python
uv python install <version>      # Устанавливает указанную версию Python
uv python pin <version>          # Закрепляет использование указанной версии Python в проекте
uv python uninstall <version>    # Удаляет указанную версию Python
uv python dir                    # Показывает директорию установки текущей версии Python
uv python update-shell           # Обновляет оболочку, чтобы включить директорию с исполнимыми файлами Python в переменную окружения `PATH`.
uv cache clean                   # Очищает кэш `uv`
uv cache prune                   # Удаляет устаревшие файлы из кэша.
uv self update                   # Обновляет саму утилиту `uv` до последней версии
uv help                          # Справка
uv help <command>                # Показывает справку по конкретной команде
uv run <file>                    # Запускает файл
uv run --with <depends> <file>   # Запускает файл c конкретными зависимостями
uv lock                          # Фиксирует новые зависимости
uv install --locked              # Устанавливает зафиксированные версии

# --

# Установка базовых зависимостей
uv install

# Установка зависимостей для разработки
uv install --group dev

# Установка для staging
uv install --group staging

# Установка для продакшена
uv install --group prod

```
