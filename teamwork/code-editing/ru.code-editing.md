Перед началом редактирования кода, в случае необходимости, произвести [Полную локальную пересборку проекта без редактирования кода](https://github.com/maksymkushnirov/usefullnesses/blob/main/teamwork/reassembling/reassembling-without-code-editing/ru.reassembling-without-code-editing.md).

В случае наличия кода, который отсутствует на GitHub, и конфликтов при попытке сделать pull request, вместо всех действий, описанных в этом руководстве, ипользовать [Полную локальную пересборку проекта с редактированием кода](https://github.com/maksymkushnirov/usefullnesses/blob/main/teamwork/reassembling/reassembling-with-code-editing/ru.reassembling-with-code-editing.md).

**Редактирование кода (добавление новой фичи и т.д.):**

01) GitHub Desktop --> fetch origin
02) GitHub Desktop --> pull origin (если появится эта кнопка)
03) GitHub Desktop --> fetch origin (если был выполнен предыдущий пункт)
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
14) GitHub Desktop --> commit в созданную ветку
15) GitHub Desktop --> publish branch
16) GitHub Desktop --> pull origin (если появится эта кнопка)
17) GitHub Desktop --> publish branch (если появится эта кнопка после выполнения предыдущего пункта)
18) GitHub Desktop --> кнопка Create Pull Request / github.com - кнопка Compare and Create Pull Request
19) github.com - завершить создание pull request
20) GitHub Desktop --> ветка main --> fetch origin --> pull origin --> снова перейти в свою ветку --> вкладка branch --> нажать delete, чтобы удалить свою ветку
21) GitHub Desktop --> fetch origin
22) GitHub Desktop --> pull origin (если появится эта кнопка)
23) GitHub Desktop --> fetch origin



<!-- README.ru.md -->
