 Шпаргалка по Git

## Основные команды

### Настройка Git

- **Настройка имени пользователя и email**:
  ```bash
  git config --global user.name "Ваше Имя"
  git config --global user.email "ваш.email@example.com"

- **Создание нового репозитория**:
  ```bash
  git init
- **Клонирование существующего репозитория**:
  ```bash
  git clone <url>
- **Добавление изменений в индекс**:
  ```bash
  git add <файл>
  git add .  # Добавляет все измененные файлы
- **Удаление ветки**:
  ```bash
  git branch -d <имя_ветки>  # Локально
  git push origin --delete <имя_ветки>  # Удаление удаленной ветки

## На этом хватит Дальше-больше! 