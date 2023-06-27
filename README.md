<noautolink>
---+ Простой видеокурс (скрин-каст) (отдельными темами) по GIT на русском

=%ICON{presentation}%= Git курс (playlist): https://youtu.be/W4hoc24K93E?list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb

=%ICON{presentation}%= Git разное (playlist): https://youtu.be/8HxTHPkdedA?list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE
---
---++ <a href='https://www.youtube.com/watch?v=W4hoc24K93E&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=1' target='_blank'>%ICON{youtube}%</a> 1.1 Git – Введение – Что такое Git?
   * Как работает Git, репозиторий, общая схема использования Git.
   * Установка Git.
---++ <a href='https://www.youtube.com/watch?v=hWiqh6YUUS8&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=2' target='_blank'>%ICON{youtube}%</a> 2.1 Git – Основы – Конфигурация
   * Конфигурация Git: опции user.name, user.email.
   * Уровни конфигурации: локальный, глобальный и системный.
   * Команды для конфигурации Git.
---++ <a href='https://www.youtube.com/watch?v=j2F77U-2FuQ&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=3' target='_blank'>%ICON{youtube}%</a> 2.2 Git – Основы – Создание репозитория, первый коммит
   * Создание репозитория Git.
   * Рабочая зона, индекс и репозиторий.
   * Добавление и сохранение файла в git: что при этом происходит.
---++ <a href='https://www.youtube.com/watch?v=KrlYu1ToS-o&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=4' target='_blank'>%ICON{youtube}%</a> 2.3 Git – Основы – Git и права на файлы

Важно для проектов под Linux/MacOS: как Git работает с правами на файлы.
   * Учитывается только исполнимость файла.
   * Как установить/снять исполнимость с любой ОС.
---++ <a href='https://www.youtube.com/watch?v=_qWWtXu07GI&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=5' target='_blank'>%ICON{youtube}%</a> 2.4 Git – Основы – Git show, кто такие автор и коммиттер
   * git show: просмотр коммитов.
   * Форматирование вывода (кратко).
   * Указание автора и коммиттера.
---++ <a href='https://www.youtube.com/watch?v=xzEMA7rzN3Y&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=6' target='_blank'>%ICON{youtube}%</a> 2.5 Git – Основы – Добавление файлов и директорий, git status
   * Разные сценарии добавления файлов в репозиторий с git add.
   * .gitignore для игнорирования служебных файлов.
---++ <a href='https://www.youtube.com/watch?v=WlIzoLK46is&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=7' target='_blank'>%ICON{youtube}%</a> 2.6 Git – Основы – Хороший коммит

Важно для разработчиков в команде, а также при участии в open-source проектах.
Основные принципы хорошего коммита:
   * атомарность,
   * консистентность
---++ <a href='https://www.youtube.com/watch?v=75TOiisShWw&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=8' target='_blank'>%ICON{youtube}%</a> 2.7 Git – Основы – Зачем нужен индекс?

Почему Git устроен именно так? Зачем же нужен этот вредный (поначалу) индекс?
   * Частичное добавление изменений с git add -p
---++ <a href='https://www.youtube.com/watch?v=UX7O3oekwFA&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=9' target='_blank'>%ICON{youtube}%</a> 2.8 Git – Основы – Коммиты без git add
   * Быстрое сохранение файлов в Git: commit -a, add -A.
   * Алиас для ещё большей скорости.
---++ <a href='https://www.youtube.com/watch?v=W71P4I0MGr0&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=10' target='_blank'>%ICON{youtube}%</a> 2.9 Git – Основы – Удаление и переименование файлов
   * Удаление файлов из индекса и репозитория.
   * Удаление с оставлением в рабочей директории.
---++ <a href='https://www.youtube.com/watch?v=aSohh-m5vJY&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=11' target='_blank'>%ICON{youtube}%</a> 3.1 Git – Ветки – Введение
   * Что такое вообще ветки и зачем они нужны?
   * Процесс разработки с использованием веток Git
---++ <a href='https://www.youtube.com/watch?v=ydtgQSaUzw0&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=12' target='_blank'>%ICON{youtube}%</a> 3.2 Git – Ветки – Создание и переключение
   * Ветка по умолчанию.
   * Создание новых веток и переключение между ними.
---++ <a href='https://www.youtube.com/watch?v=KxKjBneF_NI&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=13' target='_blank'>%ICON{youtube}%</a> 3.3 Git – Ветки – Команда checkout при незакоммиченных изменениях

Проблемы с checkout при наличии изменения, варианты их решения:
   * удаление с checkout -f
   * сохранение с git stash
---++ <a href='https://www.youtube.com/watch?v=mlxmxsBzIMs&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=14' target='_blank'>%ICON{youtube}%</a> 3.4 Git – Ветки – Перенос незакоммиченных изменений
   * Создание новой ветки для текущих изменений.
---++ <a href='https://www.youtube.com/watch?v=6oZG-pAeHRE&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=15' target='_blank'>%ICON{youtube}%</a> 3.5 Git – Ветки – Перенос веток "вручную"
   * Перенос последних коммитов в новую ветку: общий подход.
   * Создание и перенос веток на нужный коммит.
---++ <a href='https://www.youtube.com/watch?v=g0GgtqlhHaw&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=16' target='_blank'>%ICON{youtube}%</a> 3.6 Git – Ветки – Состояние отделённой HEAD
   * Git checkout на произвольный коммит
   * Состояние "detached HEAD", выход из него.
---++ <a href='https://www.youtube.com/watch?v=3z-LjQacu2Q&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=17' target='_blank'>%ICON{youtube}%</a> 3.7 Git – Ветки – Восстановление предыдущих версий файлов
   * Получение предыдущих версий файлов из репозитория в текущее состояние проекта.
   * Замена/восстановление файлов на предыдущие.
---++ <a href='https://www.youtube.com/watch?v=l-sTQBr3rXY&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=18' target='_blank'>%ICON{youtube}%</a> 3.8 Git – Ветки – Просмотр истории и старых файлов, символы ~, ^, @, поиск с :/
   * Просмотр истории: git log.
   * Просмотр отдельных коммитов: git show.
   * Спецсимволы для коммитов: ~ ^ @
---++ <a href='https://www.youtube.com/watch?v=g--N6QHbt6Q&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=19' target='_blank'>%ICON{youtube}%</a> 3.9 Git – Ветки – Слияние веток "перемоткой"
   * Команда git merge (простейший случай).
   * Отмена простого git merge.
---++ <a href='https://www.youtube.com/watch?v=yFVPNYSTlLQ&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=20' target='_blank'>%ICON{youtube}%</a> 3.10 Git – Ветки – Удаление веток
   * Удаление ветки после merge: git branch -d.
   * Удаление любой ветки: git branch -D.
---++ <a href='https://www.youtube.com/watch?v=FxyGx_XTRhA&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=21' target='_blank'>%ICON{youtube}%</a> 3.11 Git – Ветки – История переключений веток: лог ссылок reflog
   * Что такое reflog?
   * Зачем он полезен (восстановление удалённой ветки)
   * Форматирование вывода reflog, поиск по дате.
---++ <a href='https://www.youtube.com/watch?v=h9kYvAQoXjo&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=22' target='_blank'>%ICON{youtube}%</a> 4.1 Git – Удаление "лишних" файлов и незакоммиченных изменений
   * Удаление незакоммиченных изменений с git checkout -f или reset --hard.
   * Удаление неотслеживаемых "лишних" файлов при помощи git clean.
---++ <a href='https://www.youtube.com/watch?v=DMncFUqzDuM&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=23' target='_blank'>%ICON{youtube}%</a> 5.1 Git – Reset – Жесткий reset --hard: отмена изменений, удаление коммитов
   * Команда reset --hard
   * Удаление изменений: до коммита и после коммита.
---++ <a href='https://www.youtube.com/watch?v=bUdLmdSMm7E&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=24' target='_blank'>%ICON{youtube}%</a> 5.2 Git – Reset – Мягкий reset --soft: замена и объединение коммитов
   * Команда reset --soft: передвижение указателя ветки без индекса и данных.
   * Использование reset для исправления последнего коммита (или даже нескольких).
---++ <a href='https://www.youtube.com/watch?v=Hho9WBgWil0&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=25' target='_blank'>%ICON{youtube}%</a> 5.3 Git – Reset – Правка последнего коммита: commit --amend
   * Быстрое исправление последнего коммита: commit --amend.
---++ <a href='https://www.youtube.com/watch?v=r1oUTfqKXac&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=26' target='_blank'>%ICON{youtube}%</a> 5.4 Git – Reset – Смешанный reset (без флагов), сравнение видов reset
   * Таблица основных видов reset, их сравнение.
   * Отмена индексации с reset без флагов.
---++ <a href='https://www.youtube.com/watch?v=hb-x1SJB43s&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=27' target='_blank'>%ICON{youtube}%</a> 5.5 Git – Reset – Таблица с действиями reset

Документация Git: таблица с действиями разных видов reset в разных состояниях проекта.
---++ <a href='https://www.youtube.com/watch?v=1oExHLJXBIg&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=28' target='_blank'>%ICON{youtube}%</a> 6.1 Git – Просмотр – Сравнение коммитов, веток и не только: git diff
   * Вывод git diff, сравнение коммитов.
   * Сравнение веток с git diff.
   * Синтаксис для сравнения с учётом рабочей директории/индекса/HEAD.
---++ <a href='https://www.youtube.com/watch?v=Oim9dbpbCMc&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=29' target='_blank'>%ICON{youtube}%</a> 6.2 Git – Просмотр – Вывод истории: git log, форматирование коммитов
   * Базовое использование git log
   * Примеры полезных флагов и форматирования вывода git log
---++ <a href='https://www.youtube.com/watch?v=nRYSu3wbNXo&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=30' target='_blank'>%ICON{youtube}%</a> 6.3 Git – Просмотр – Диапазоны коммитов для git log и не только
   * Синтаксис git для диапазонов коммитов.
   * Вывод истории для одной ветки.
   * Вывод дерева веток с флагом --graph.
---++ <a href='https://www.youtube.com/watch?v=7A68GxROZ2I&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=31' target='_blank'>%ICON{youtube}%</a> 6.4 Git – Просмотр – Вывод git log коммитов, меняющих нужный файл
   * Вывод git log коммитов, меняющих интересные нам файлы или директории.
---++ <a href='https://www.youtube.com/watch?v=lhrchh5dqH0&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=32' target='_blank'>%ICON{youtube}%</a> 6.5 Git – Просмотр – Поиск в истории, фильтры для git log
   * Поиск коммитов по строке в описании.
   * Поиск коммитов по строке в изменениях.
   * Поиск коммитов, меняющих интересный нам фрагмент файла (по регэкспу).
---++ <a href='https://www.youtube.com/watch?v=o9du71FpLLM&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=33' target='_blank'>%ICON{youtube}%</a> 6.6 Git – Просмотр – Кто написал эту строку? git blame
   * Вывод авторов для каждой строки кода с git blame.
   * Флаги git blame, форматирование вывода.
---++ <a href='https://www.youtube.com/watch?v=PXK1hIifpWU&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=34' target='_blank'>%ICON{youtube}%</a> 7.1 Git – Слияние – "Истинное" слияние и разрешение конфликтов в git merge
   * Процесс слияния веток и файлов при помощи git merge.
   * Конфликты и их разрешение.
---++ <a href='https://www.youtube.com/watch?v=EJKw_qW5pgI&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=35' target='_blank'>%ICON{youtube}%</a> 7.2 Git – Слияние – Коммит слияния, дальнейшие слияния
   * Как устроены коммиты слияния, получение их родителей.
   * Структура веток после слияний.
   * Удобное описание для коммитов слияния.
---++ <a href='https://www.youtube.com/watch?v=TEsjp1eDLx4&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=36' target='_blank'>%ICON{youtube}%</a> 7.3 Git – Слияние – Отмена слияния
   * Как отменить слияние, если что-то пошло не так?
   * Отмена успешных слияний, возврат назад по истории.
---++ <a href='https://www.youtube.com/watch?v=h4jxghOE9e0&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=37' target='_blank'>%ICON{youtube}%</a> 7.4 Git – Слияние – Семантические конфликты и их разрешение
   * Git merge не обнаруживает семантические конфликты.
   * Примеры, исправление.
---++ <a href='https://www.youtube.com/watch?v=AHjS9MWsNm0&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=38' target='_blank'>%ICON{youtube}%</a> 7.5 Git – Слияние – Полезный приём: сохранение веток с флагом --no-ff
   * Сохранение истории разработки веток при помощи запрета "перемотки".
   * Важно для удобной отмены слияния, а также хорошей истории проекта.
---++ <a href='https://www.youtube.com/watch?v=1v-dxpobjlY&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=39' target='_blank'>%ICON{youtube}%</a> 7.6 Git – Слияние – Создание коммита из ветки: merge --squash
   * Альтернативный способ слияния, когда из ветки делается один коммит (а ветку можно потом удалить).
   * Удобен, если история разработки ветки и сама ветка не нужна.
---++ <a href='https://www.youtube.com/watch?v=TZJxBSfR0NE&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=40' target='_blank'>%ICON{youtube}%</a> 8.1 Git – Копирование коммитов – Копирование коммитов: cherry-pick
   * Копирование одного или нескольких коммитов на другую ветку командой git cherry-pick.
   * Копирование изменений в индекс, без создания нового коммита.
---++ <a href='https://www.youtube.com/watch?v=jxwPgfmutjs&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=41' target='_blank'>%ICON{youtube}%</a> 9.1 Git – Перемещение коммитов – Перебазирование вместо слияния: rebase
   * Команда git rebase: перенос ветки поверх master.
   * Подробное описание, как работает команда rebase.
---++ <a href='https://www.youtube.com/watch?v=Z3Q2RaEUQO0&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=42' target='_blank'>%ICON{youtube}%</a> 9.2 Git – Перемещение коммитов – Rebase и merge: сравнение подходов
   * При разработке новой ветки для интеграции изменений с master можно использовать merge или rebase.
   * Сравнение этих подходов.
---++ <a href='https://www.youtube.com/watch?v=dnT8YzpqEYA&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=43' target='_blank'>%ICON{youtube}%</a> 9.3 Git – Перемещение коммитов – Rebase с тестами, флаг -x
   * Аккуратное перебазирование, с запуском автотестов на каждом коммите.
---++ <a href='https://www.youtube.com/watch?v=t_sPfT8m0s8&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=44' target='_blank'>%ICON{youtube}%</a> 9.4 Git – Перемещение коммитов – Перенос части ветки, rebase --onto
   * Как rebase ищет коммиты для переноса?
   * Перенос части ветки, флаг --onto.
   * Альтернативный подход с cherry-pick.
---++ <a href='https://www.youtube.com/watch?v=P89rsHliIpM&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=45' target='_blank'>%ICON{youtube}%</a> 9.5 Git – Перемещение коммитов – Перебазирование слияний, --rebase-merges
   * Rebase по умолчанию пропускает коммиты слияния вместе с внесёнными в них изменениями.
   * Пример перебазирования с сохранением слияний.
---++ <a href='https://www.youtube.com/watch?v=4K9X1Aa1nvA&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=46' target='_blank'>%ICON{youtube}%</a> 9.6 Git – Перемещение коммитов – Интерактивное перебазирование, rebase -i

Интерактивное перебазирование позволяет привести историю ветки "в порядок" перед её публикацией.
---++ <a href='https://www.youtube.com/watch?v=exYHemsk1V8&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=47' target='_blank'>%ICON{youtube}%</a> 9.7 Git – Перемещение коммитов – Исправляем коммит посередине ветки: autosquash

Rebase позволяет в полуавтоматическом режиме создавать и применять "коммиты-заплатки", для исправления коммитов, которые были сделаны ранее в ветке.
---++ <a href='https://www.youtube.com/watch?v=FcwQrN9XOwU&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=48' target='_blank'>%ICON{youtube}%</a> 10.1 Git – Отмена коммитов через revert – Обратные коммиты, revert
   * Отмена коммита, который нельзя удалить из истории, так как он был отправлен другим людям.
   * Создание обратного коммита командой git revert.
---++ <a href='https://www.youtube.com/watch?v=aRbOsagYs8w&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=49' target='_blank'>%ICON{youtube}%</a> 10.2 Git – Отмена коммитов через revert – Отмена слияния через revert
   * Отмена слияния, которое было отправлено другим людям.
   * Особенности работы git revert с коммитами слияния.
---++ <a href='https://www.youtube.com/watch?v=3HDSLArx3qw&list=PLDyvV36pndZFHXjXuwA_NywNrVQO0aQqb&index=50' target='_blank'>%ICON{youtube}%</a> 10.3 Git – Отмена коммитов через revert – Повторное слияние с rebase

Альтернативные способы повторного слияния, не требующие отмены отмены:
   * С rebase ветки поверх master.
   * С rebase ветки на том же месте.
---
---++ <a href='https://www.youtube.com/watch?v=lHacJuru1bc&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=1' target='_blank'>%ICON{youtube}%</a> 1.1 Git – Теги – Теги, основные действия с тегами
   * Отличия тегов от веток git.
   * Область использования тегов.
   * Вывод тегов, поиск по тегам.
---++ <a href='https://www.youtube.com/watch?v=N0V1Cm6DT30&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=2' target='_blank'>%ICON{youtube}%</a> 1.2 Git – Теги – Использование тегов для релиза с describe и archive
   * Получение ближайшего тега по коммиту: git describe.
   * Релиз по тегу: git archive.
---++ <a href='https://www.youtube.com/watch?v=lEXIpOQGvEI&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=3' target='_blank'>%ICON{youtube}%</a> 2.1 Git – Продвинутый diff – Сравнение по словам, драйвер diff
   * Сравнение по словам, настройка поиска слов в git diff.
   * Продвинутая настройка, задание своих языков и правил.
---++ <a href='https://www.youtube.com/watch?v=aC0f4TPLDrc&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=4' target='_blank'>%ICON{youtube}%</a> 2.2 Git – Продвинутый diff – Сравнение картинок и не только с git diff
   * Настройка git diff для сравнения картинок и других "нестандартных" форматов
---++ <a href='https://www.youtube.com/watch?v=8HxTHPkdedA&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=5' target='_blank'>%ICON{youtube}%</a> 3.1 Git – ReReRe – Авторазрешение одинаковых конфликтов
   * Git умеет запоминать разрешение конфликтов и повторять его при необходимости автоматически.
   * Это полезно при повторных слияниях, перебазированиях, когда команды git повторно
---++ <a href='https://www.youtube.com/watch?v=MorghqcvWp0&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=6' target='_blank'>%ICON{youtube}%</a> 4.1 Git – Сборка мусора
   * Когда и как git удаляет "недостижимые" коммиты?
   * Регулярная чистка мусора.
   * Влияние reflog на чистку мусора.
---++ <a href='https://www.youtube.com/watch?v=6mOiduZ0hBU&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=7' target='_blank'>%ICON{youtube}%</a> 5.1 Git – Продвинутая конфигурация – Настройка редактора
   * Настройка редактора для ввода описаний коммитов Git
   * "Стандартные" редакторы и как настроить Git, чтобы использовал любой (почти)
---++ <a href='https://www.youtube.com/watch?v=2KEGbWqo-sQ&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=8' target='_blank'>%ICON{youtube}%</a> 5.2 Git – Продвинутая конфигурация – Проблема с переводами строк Windows/Linux

Если вы и так знаете разницу между переводами строк, можно пропустить это видео.
   * Переводы строк: LF/CR+LF
   * Почему "одинаковые" текстовые файлы под Windows и Linux имеют разный размер?
---++ <a href='https://www.youtube.com/watch?v=SUMmeK1mL6Q&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=9' target='_blank'>%ICON{youtube}%</a> 5.3 Git – Продвинутая конфигурация – Нормализация переводов строк, core.autocrlf
   * Автоматическое преобразование переводов строк в Git.
---++ <a href='https://www.youtube.com/watch?v=V3z80lCvHJo&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=10' target='_blank'>%ICON{youtube}%</a> 5.4 Git – Продвинутая конфигурация – Атрибуты: .gitattributes, text, eol
   * Файл настроек .gitattributes
   * Текстовые и бинарные файлы, как Git их распознаёт?
---++ <a href='https://www.youtube.com/watch?v=oOC3Jd7lOAc&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=11' target='_blank'>%ICON{youtube}%</a> 5.5 Git – Продвинутая конфигурация – Формат файла .gitignore

Файл .gitignore имеет специфический формат, который с виду прост, но на самом деле не похож ни на какой другой.
---++ <a href='https://www.youtube.com/watch?v=6TIIYLyj5ak&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=12' target='_blank'>%ICON{youtube}%</a> 5.6 Git – Продвинутая конфигурация – Подключение файлов в конфиг: include
   * Сложный конфиг можно бить на части.
   * Можно повторно использовать части конфига для разных проектов.
---++ <a href='https://www.youtube.com/watch?v=b-Pn1EPzaBE&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=13' target='_blank'>%ICON{youtube}%</a> 6.1 Git – Продвинутое слияние – Объединение всех изменений, драйверы слияния
   * Драйвер слияния union, для объединения всех изменений.
   * Создание "нестандартных" драйверов слияния: для файлов с переводами или других.
---++ <a href='https://www.youtube.com/watch?v=KbQFf4H493I&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=14' target='_blank'>%ICON{youtube}%</a> 6.2 Git – Продвинутое слияние – Стратегии слияния
   * Дополнительные стратегии слияния для разных ситуаций.
---++ <a href='https://www.youtube.com/watch?v=JsJAmdyUWbM&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=15' target='_blank'>%ICON{youtube}%</a> 7.1 Git – Дополнительные виды reset – --keep: жёсткий с сохранением изменений
   * Команда git reset --keep: как --hard, но с сохранением незакоммиченных изменений там, где это возможно.
---++ <a href='https://www.youtube.com/watch?v=fIScteqHsR0&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=16' target='_blank'>%ICON{youtube}%</a> 7.2 Git – Дополнительные виды reset – --merge: для отмены слияний
   * Команда git reset --merge: как --keep, но с удалением проиндексированных изменений
---++ <a href='https://www.youtube.com/watch?v=QgT06OZYads&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=17' target='_blank'>%ICON{youtube}%</a> 8.1 Git – Даты в git – Ввод даты, форматы дат в git
   * Как и в каких форматах можно передать дату git, например, чтобы искать по дате.
   * Для git log, expire, gc и других команд.
---++ <a href='https://www.youtube.com/watch?v=WqKLD_c1F0s&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=18' target='_blank'>%ICON{youtube}%</a> 8.2 Git – Даты в git – Вывод даты, форматирование
   * Задаём формат, в котором git выводит даты.
   * Для git log и других команд.
---++ <a href='https://www.youtube.com/watch?v=E5Y-jNg-O2Y&list=PLDyvV36pndZEB7kWWocU4QSn-G78LoaEE&index=19' target='_blank'>%ICON{youtube}%</a> 9.1 Git – Просмотр эквивалентных коммитов – Команды cherry, log --cherry-mark

Пометка эквивалентных коммитов при выводе истории разработки.

---

</noautolink>
<div id='tap-translate'> </div>
