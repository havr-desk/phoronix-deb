# phoronix-deb #
Здесь можно скачать .deb файл для установки Phoronix-test-suite

<b>Чтобы начать установку из файла необходимо ввести команду</b>:

dpkg -i name.deb
<br>
Данный файл потребует докачать ещё некоторые файлы, которые необходимы для работы.<br>
Команда для установки: <p>apt-get install name-file</p>
<br>  
<b>Если файлы не смогут докачаться или произойдёт какая-то ошибка, то попробуйте добавить официальные репозитории:</b>

# Репозитории #
deb https://www.phoronix-test-suite.com/ buster main
deb-src https://www.phoronix-test-suite.com/ buster main

deb https://www.phoronix-test-suite.com/ buster-updates main
deb-src https://www.phoronix-test-suite.com/ buster-updates main

deb https://www.php.net/downloads.php buster main
deb-src https://www.php.net/downloads.php buster main

deb https://www.php.net/downloads.php buster-updates main
deb-src https://www.php.net/downloads.php buster-updates main

#Как добавить репозитории?#
Чтобы добавить репозитории необходимо ввести следующую команду:
nano /etc/apt/sources.list <br>
<b>Откроется редактор</b>. Введите репозитории и затем нажмите Ctrl+O - сохранить файл; нажмите Enter, чтобы сохранить в том же файле.
Ctrl+X - exit.<br>

<p>Пример редактора nano (вроде бы это Debian 9)</p>
<img src="https://i.yapx.ru/J9AFL.jpg">
<br>
Затем попробуйте заново установить нужные вам утилиты.

Как только необходимые утилиты будут установлены, повторите установку phoronix-test-suite.

# Один важный момент #

Если у вас Debian не 10-й версии, возможно, вместо <b>buster</b> вам необходимо будет писать кодовое имя своего дистрибутива.

