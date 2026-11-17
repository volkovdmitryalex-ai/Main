git init  инициализация хранилища
git add main.py   Добавление файла проекта в отслеживаемые (учитывая регистр названия файла)
git commit -m "first commit"   Создание точки сохранения (коммит)
Создание текстового файла Readme
git add .   Добавление файлов проекта в отслеживаемые
git commit -m "Readme"   Создание второй точки сохранения (коммит)
создание облачного хранилища на GitHub
git branch -M main задание основной ветки проекта
git remote add origin https://github.com/volkovdmitryalex-ai/Main.git привязка облачного хранилища Main с локальным проектом
git push -u origin main  загрузка локального проекта в облако