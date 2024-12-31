Важливі файли pullrequests-list.txt - файл для списку pull-requests. Кожен
створює сам.

Бібліотеки

1. swiper - https://swiperjs.com/swiper-api
2. Accordion -https://github.com/michu2k/Accordion
3. Axios - https://axios-http.com/
4. iziToast - https://github.com/marcelodolza/iziToast

Порядок дій при роботі

1. Робимо git pull стягуємо актуальну версію (Робимо це на гілкі main)
2. Створюємо нову гілку для своєї задачі: git switch -c "branch_name" -
   створення нової гілки з переходом в неї
3. Робимо роботу
4. Все перевіряємо
5. Пушимо зміни:
   - git add . - зберігаємо зміни в файлах
   - git commit -m "commit message" - підписуємо збережені зміни в файлах
   - git push - відправляємо зміни на сайт GitHub
6. Перекидаємо в трелло свою таску, на гітхабі робимо пулреквест і ставимо
   тімліда ревьюєром і чекаємо на ревью від тім ліда
7. Якщо все ок то видаляємо свою гілку (локально теж не забувайте)
8. Повертаємось в пункт 1 (перед цим заглянути в трелло)

Список корисних команд для роботи з git

- git clone - копіює репозиторій (папку з файлами) на комп'ютер
- git branch "branchName" - створює гілку з назвою "branchName"
- git checkout "branchName" - переходить на гілку з назвою "branchName"
- git checkout -b "branchName" - створюємо гілку з назвою "branchName" і
  переходимо на неї
- git add . - зберігаємо зміни в файлах git commit -m "commit message" -
  підписуємо збережені зміни в файлах
- git push - відправляємо зміни на сайт GitHub git pull - отримуємо останні
  зміни з сайту GitHub
- git status - показуємо статус проєкту
- git branch - показуємо список гілок в проєкті
- git branch -r - показуємо список гілок на сайті GitHub
- git branch -a - показуємо список гілок на комп'ютері та на сайті GitHub
- git fetch - отримуємо зміни з сайту GitHub
- git stash - зберігаємо незбережені зміни в файлах і кладемо їх в буфер обміну
- git stash apply - вставляємо збережені зміни з буфера обміну
- git merge "branchName" - зливаємо гілку з назвою "branchName" в поточну гілку
- git merge --abort - відміняємо злиття гілок
- git branch -d branchName - видаляє гілку локально з проєкту
- git push origin --delete branchName - видаляє гілку з сайту GitHub
- git diff - показує відрізки рядків між двома версіями файлу (між двома
  комітами)
- git log - показує історію комітів
- git log --oneline - компактний вигляд історії коммітів Для того, щоб вийти з
  режиму перегляду комітів, використовуйте клавішу q (стосується команди №20 і
  №21).

- git switch -c "branch_name" - створення нової гілки з переходом в неї
- git switch "branch_name" - зміна гілки (перехід в іншу гілку)
- git branch -d "branch_name" - видалення локальної гілки
- git pull - стягнути зміни з гітхабу
- git merge "branch_name" - злити зміни з гілки branch_name в поточну гілку в
  якій знаходитесь.
