hd.rustem
=======
HELPDESK веб-система, для организации учёта выполнения задач (заявок) между структурными подразделениями и пользователями или клиентами организации.
<img src="http://habrastorage.org/getpro/habr/post_images/1dd/ab7/eb0/1ddab7eb053c4368b46e959e71ea991d.png">

<h4>Функционал</h4>
<ul>
<li>Многоуровневая система прав пользователей</li>
<li>JQuery-ориентированая структура интерфейса</li>
<li>Возможность регистрации в системе из «белого списка» e-mail адресов</li>
<li>Извещение о новых заявках по e-mail, sms, и другим системам</li>
<li>Пользовательские настройки</li>
<li>Поддержка языков: Украинский, Русский, Английский</li>
<li>Всплывающие сообщения о событиях с заявками (как в VK)</li>
<li>Центр знаний — раздел для файлов документации, инструкций и хелпов со структурой прав</li>
<li>Блокнот — личный блокнот пользователя с возможностью делиться ссылкой</li>
<li>Статистика заявок</li>
<li>«Умное» создание заявок по номеру, ФИО, логину клиента</li>
<li>Приоритеты заявок</li>
<li>Комментарии и чат в заявке</li>
<li>Полное логирование всех действий всеми пользователями заявки</li>
<li>И другое...</li>
</ul>

<h4>Как установить?</h4>
<ul>
<li>Скачать файлы</li>
<li>Распаковать в каталог веб-сервера</li>
<li>Найти HD.db.sql и импортировать в БД MySQL</li>
<li>Найти conf-default.php и в нём поправить данные подключения к БД, переименовать в conf.php</li>
<li>Зайти по вебу, используя логин/пароль: system/1234</li>
</ul>

<h4>Какие требования?</h4>
<ul>
<li>UNIX-like OS</li>
<li>Apache (mod_rewrite), PHP (PDO, short_open_tag), MySQL</li>
<li>Access to cron (для переноса заявок в архив)</li>
<li>Access to mail (для отправки писем)</li>
</ul>

<h4>Нужны в команду</h4>
<ul>
<li>Дизайнер интерфейса (bootstrap 3)</li>
<li>Тестировщик интерфейса и логики</li>
</ul>

<h4>Ссылки и обсуждения</h4>
<ul>
<li>http://habrahabr.ru/post/227277/</li>
<li>http://hd.rustem.com.ua/</li>
</ul>


<h4>Благодарности за вклад в проект</h4>
<ul>
<li><a href='https://github.com/dima-bzz'>dima-bzz</a></li>
<li><a href='https://github.com/Vaflan'>Vaflan</a></li>
<li><a href='https://github.com/insp63'>insp63</a></li>
</ul>

<h4>Вопросы по внедрению и разработке ($)</h4>
<ul>
<li>Skype: rustem_ck</li>
</ul>