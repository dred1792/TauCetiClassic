Скрипт для локального создания тестового чейнджлога.

#### Перед запуском
Создать в папке со скриптом файл с именем `token`. В него поместить строку с ключом для GitHub API. Как его создать читать тут https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/ Токен должен иметь как минимум `repo` права.

#### Как запустить
Запустить `run.sh` скрипт и передать через пробел номера ПРов для которых нужно создать чейнджлог. После запуска локальный файл с чейнджлогом сразу же обновится.

Пример: `./run.sh 234 3455 4847`