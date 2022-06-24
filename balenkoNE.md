git config --global user.name "Your Name" - указать имя, которым будут подписаны коммиты

git config --global user.email "e@w.com"  - указать электропочту, которая будет в описании коммитера

git init - создать новый проект в текущей директории

git status - показать состояние репозитория (отслеживаемые, изменённые, новые файлы и пр.)

git diff - сравнить рабочую директорию и индекс (неотслеживаемые файлы ИГНОРИРУЮТСЯ)

git add . - добавить в индекс все новые, изменённые, удалённые файлы из текущей директории и её поддиректорий

git add text.txt - добавить в индекс указанный файл (был изменён, был удалён или это новый файл)

git commit -m "Name of commit" - зафиксировать в коммите проиндексированные изменения (закоммитить), добавить сообщение

git commit -a -m "Name of commit" - проиндексировать отслеживаемые файлы (ТОЛЬКО отслеживаемые, но НЕ новые файлы) и закоммитить, добавить сообщение

gti log - показывать список комитов

git branch - показать имеющиеся ветки

git checkout - переход на ветку или комит

git merge - слияние веток