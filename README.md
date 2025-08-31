# Тестовий локальний репозиторій

## Опис
Цей репозиторій був спочатку створений локально на моєму комп'ютері, а потім прив'язаний до віддаленого репозиторію на GitHub.  

## Команди для створення

```bash
# Створення локальної папки для репозиторію
mkdir ~/projects/TestRepoLocal

# Перехід у створену папку
cd ~/projects/TestRepoLocal

# Ініціалізація локального Git-репозиторію
git init

# Створення README.md з назвою репозиторію
echo "# Тестовий локальний репозиторій" > README.md

# Створення .gitignore для ігнорування об'єктних файлів (*.o)
echo "*.o" > .gitignore

# Додавання файлів до індексу Git
git add README.md .gitignore

# Створення першого коміту з повідомленням
git commit -m "Initial commit with README and .gitignore"

# Прив'язка локального репозиторію до віддаленого на GitHub
git remote add origin https://github.com/Panzedon/TestRepoLocal.git

# Відправка локальних комітів на GitHub у гілку master
git push -u origin master
