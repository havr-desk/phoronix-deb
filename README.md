# phoronix-deb #
Здесь можно скачать .deb файл для установки Phoronix-test-suite

Чтобы начать установку из файла необходимо ввести команду:

dpkg -i <name>.deb

Данный файл потребует докачать ещё некоторые файлы, которые необходимы для работы.
Команда для установки: apt-get install <name>
Если файлы не смогут докачаться или произойдёт какая-то ошибка, то попробуйте добавить официальные репозитории:

deb https://www.phoronix-test-suite.com/ buster main
deb-src https://www.phoronix-test-suite.com/ buster main

deb https://www.phoronix-test-suite.com/ buster-updates main
deb-src https://www.phoronix-test-suite.com/ buster-updates main

deb https://www.php.net/downloads.php buster main
deb-src https://www.php.net/downloads.php buster main

deb https://www.php.net/downloads.php buster-updates main
deb-src https://www.php.net/downloads.php buster-updates main

Чтобы добавить репозитории необходимо ввести следующую команду:
nano /etc/apt/sources.list
Откроется редактор. Введите репозитории и затем нажмите Ctrl+O - сохранить файл; нажмите Enter, чтобы сохранить в том же файле.
Ctrl+X - exit.

Затем попробуйте заново установить нужные вам утилиты.

Как только необходимые утилиты будут установлены, повторите установку phoronix-test-suite.
