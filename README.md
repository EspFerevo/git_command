# 🧠 Git Cheatsheet for Beginners

Полезные команды и пояснения для быстрого старта с Git.

---

## 📦 1. Инициализация репозитория

```
git init
```

Создаёт новый локальный репозиторий.

---

## 📂 2. Настройка Git

```
git config --global user.name "Ваше Имя"
git config --global user.email "you@example.com"
```

Настраивает имя и email, которые будут отображаться в коммитах.

---

## 📥 3. Клонирование репозитория

```
git clone https://github.com/user/repo.git
```

---

## 📋 4. Проверка статуса

```
git status
```

---

## ➕ 5. Добавление файлов в индекс

```
git add filename
git add .
```

---

## 💾 6. Создание коммита

```
git commit -m "Сообщение коммита"
```

---

## 🔄 7. Отправка изменений на удалённый репозиторий

```
git push origin main
```

---

## 📥 8. Получение изменений

```
git pull
```

---

## 🔍 9. Просмотр истории коммитов

```
git log
```

---

## 🔀 10. Работа с ветками

```
git branch
git branch new-branch
git checkout new-branch
git switch new-branch
```

---

## 🌐 11. Работа с удалёнными репозиториями

```
git remote -v
git remote add origin URL
```

---

## 🧹 12. Удаление и возврат изменений

```
git reset filename
git checkout -- filename
```

---

## 🛠️ 13. Слияние веток

```
git merge branch-name
```

---

## 🧼 14. Удаление ветки

```
git branch -d branch-name
```

---

## 💡 Полезные советы

- Используйте `.gitignore`, чтобы исключать файлы из отслеживания.
- Команда `git stash` — временно сохраняет изменения.
- `git diff` — показывает разницу между коммитами или рабочими файлами.

---

📚 Официальная документация: https://git-scm.com/doc
