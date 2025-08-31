## Опис
Цей репозиторій був спочатку створений локально на моєму комп'ютері, а потім прив'язаний до віддаленого репозиторію на GitHub.

## Команди для створення
```bash
mkdir ~/projects/TestRepoLocal
cd ~/projects/TestRepoLocal
git init
echo "# Тестовий локальний репозиторій" > README.md
echo "*.o" > .gitignore
git add README.md .gitignore
git commit -m "Initial commit with README and .gitignore"
git remote add origin https://github.com/Panzedon/TestRepoLocal.git
git push -u origin master
