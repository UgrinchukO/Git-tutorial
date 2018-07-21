
<a href="https://github.com/DmitriyChernobrivets/test-repository/blob/master/Layer%2041%401x.png"></a>
# Day-2-Git
* **git clone** - Клонує репозиторій
* **git pull** - Стягує оновлення з репозиторію
* **git push** - Записує оновлення коду на віддалений репозиторій
* **git status** - показує статус в локальному репозитрії
* **git add .** - гіт починає відслідковувати зміни що внесені в файл
* **git commit -m “commit text”** - зберігає поточний стан файла
* **git commit -am “text commit ”** - короткий запис команда git add . та git commit -m “” (Працює лише для вже відстежуваних файлів)
* **git log** - показує історію комітів
* **git branch** - показує список локальних гілок
* **git branch name** - створює гілку з ім’ям name
* **git branch -a** - показує список віддалених гілок
* **git checkout -b name** - створює нову гілку з ім’ям “name” і переходить в неї
* **git checkout name** - перехід до потрібної гілки
* **git merge name** - злятя гілки “name” в поточну
* **git merge --abort** -  відміна злиття гілок
* **git push -u origin name** - перший пуш нової локальної гілки на гітхаб
* **git branch -d name** -  видалення локальної гілки (потрібно з неї вийти)
* **git push origin --delete name** - видалення віддаленої гілки на гітхабі
* **git stash** - ховає внесені зміни в “карман”. (Використовується тоді коли потрібно перейти в іншу гілку але не хочеться робити коміт)
* **git stash apply** - відновлює код з “кармана” (Повертає схований код)
