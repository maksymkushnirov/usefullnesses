В случае, если нету кода, который отсутствует на GitHub, достаточно произвести [Полную локальную пересборку проекта без редактирования кода](https://github.com/maksymkushnirov/usefullnesses/blob/main/teamwork/reassembling/reassembling-without-code-editing/ru.reassembling-without-code-editing.md).

Полная локальная пересборка проекта с редактированием кода (выполнить в случае наличия кода, который отсутствует на GitHub, и конфликтов при попытке сделать pull request):

01) сохранить новый (отсутствующий на GitHub) личный код в папку не связанную с GitHub (не скопировать весь файл (*.html, *.js...), а сохранить новые личные строки, например в файл блокнота)
02) полностью удалить папку с проектом с компьютера
03) склонируйте репозиторий используя один из двух вариантов:
    - вариант 1:
    GitHub Desktop --> Clone Again
    - вариант 2:
    "github .com/username/repositoryname" --> Code --> Open with GitHub Desktop --> Clone Again / Locate
04) GitHub Desktop --> Open in Visual Studio Code
открыть Terminal (Git Bash) нажав комбинацию Ctrl+~ или другим удобным способом
05) npm ci
06) npm run dev
07) Ctrl+C 
08) npm run build
09) GitHub Desktop --> fetch origin
10) GitHub Desktop --> pull origin (если появится эта кнопка)
11) GitHub Desktop --> fetch origin (если был выполнен предыдущий пункт)
04) GitHub Desktop --> создать новую ветку
05) GitHub Desktop --> Open in Visual Studio Code
06) открыть Terminal (Git Bash) нажав комбинацию Ctrl+~ или другим удобным способом
07) npm ci
08) npm run dev
09) Ctrl+C
10) npm run build
11) npm run dev
12) Visual Studio Code - внести строки (сохранённые в пункте 1) и, при необходимости, отредактировать код / файлы
13) Terminal --> Ctrl+C
14) npm run prettier
15) npm run dev
16) Ctrl+C
17) npm run build
18) GitHub Desktop --> commit в созданную ветку
19) GitHub Desktop --> publish branch
20) GitHub Desktop --> pull origin (если появится эта кнопка)
21) GitHub Desktop --> publish branch (если появится эта кнопка после выполнения предыдущего пункта)
22) GitHub Desktop --> кнопка Create Pull Request / github.com - кнопка Compare and Create Pull Request
23) github.com - завершить создание pull request
24) GitHub Desktop --> ветка main --> fetch origin --> pull origin --> снова перейти в свою ветку --> вкладка branch --> нажать delete, чтобы удалить свою ветку
25) GitHub Desktop --> fetch origin
26) GitHub Desktop --> pull origin (если появится эта кнопка)
27) GitHub Desktop --> fetch origin

Далее использовать алгоритм [Редактирование кода (добавление новой фичи и т.д.)](https://github.com/maksymkushnirov/usefullnesses/blob/main/teamwork/code-editing/ru.code-editing.md).



<!-- README.ru.md -->
