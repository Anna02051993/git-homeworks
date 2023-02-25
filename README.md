# Домашние задания по курсу «Git - система контроля версий»

1. [Создание репозитория на Github](1_self/)
2. [Внедрение системы контроля версий](2_introduction/)

Вам может пригодиться [руководство по работе в терминале](https://github.com/netology-code/guides/blob/master/git-terminal/git-terminal.md).

## Почему терминал?
На данном курсе мы будем работать с GIT при помощи так называемой консоли или терминала.

Да, существуют так называемые графические интерфейсы — программы в более привычном для нас понимании для работы с GIT. Интерфейсы часто скрывают большую часть механизмов, и это не позволяет до конца понять всю цепочку действий.

При работе с GIT очень важно понимать последовательность действий и возможные последствия, которые с ними связаны. Хотя мы в данный момент и не берём в расчёт никаких других функций, кроме хранения кода, на самом деле в командах разработки на основе GIT строится множество процессов, в том числе связанных с продуктами компании. 

Умение работать с GIT  из консоли сделает из вас универсального солдата, не привязанного к операционной системе, к конкретному компьютеру или программному обеспечению. А все близкие и друзья будут впечатлены тем, как вы ловко пишите команды в консоли. 

> По ссылке ниже собраны полезные фишки для терминальных ниндзя 🤓
> 
> [Git. Краткое руководство по терминалу](https://netology-code.github.io/guides/git-terminal/git-terminal.html)

Поняв принцип работы через терминал, вы в дальнейшем без труда сможете освоить любую из существующих программ. Но в процессе обучения мы настаиваем на использовании именно терминала. Пожалуйста, не загружайте файлы через программы или интерфейс GitHub.

> Самое время установить GIT на ваш компьютер. 👾 
> 
>[Инструкция по установке GIT](https://netology-code.github.io/guides/git/)

<div style="padding: 10px; font-size: 1.2em; border: 1px solid rgba(255 0 0 / 0.5)">
С 13 августа 2021 году GitHub отменил авторизацию по паролю. Теперь нужно указывать так называемый токен. Вы будете указывать этот токен вместо пароля при работе с репозиториями. Его нужно сгенерировать в настройках вашего профиля на сайте и сохранить в надёжном месте.

<div style="margin: 15px 0;">
    <a href="https://github.com/netology-code/guides/tree/master/github-access-token">Инструкция по созданию токена для GitHub</a>
</div>

Если вы уже успели ранее ввести пароль и GitHub не спрашивает у вас авторизационные данные снова и у вас нет возможности ввести токен, то воспользуйтесь этой инструкцией:

<div style="margin: 15px 0;">
    <a href="https://github.com/netology-code/guides/tree/master/github-403">Решение ошибки 403 при работе с репозиторием</a>
</div>
</div>

## Важно

При появлении любых вопросов и проблем, используйте следующий простой шаблон для того, чтобы мы могли вам оперативно помочь:

1. Номер лекции, название темы, номер страницы, к которой относится вопрос/проблема (если это ДЗ - то номер ДЗ с гиперссылкой, если видео - то название видео и номер минуты)
2. Пронумерованные шаги для воспроизведения (1. Я создал папку и открыл её в Git Bash, 2. Инициализировал репо через `git init`, 3. Сделал `git add index.html`)
3. Ожидаемый и фактический результат (Файл должен был добавиться, вместо этого я получил `fatal: pathspec 'index.html' didn't match any files`)
4. Скриншот окна ошибки
5. Скриншот вывода команды `ls -laR` (нужно выполнить в консоли)
6. ОС (версия и разрядность) - Windows, Mac, Linux, версия Git'а (`git --version`)
7. zip-архив папки с вашим репо (если что-то не коммититься, не ищется и т.д.)
Аня
gfjhgjhg