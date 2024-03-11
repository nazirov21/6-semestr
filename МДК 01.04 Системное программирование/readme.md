ЛК 15.01
gitbash - это команды для работы с гид из терминала

![bash](https://github.com/Hottabik/6semestr/assets/113089655/b7031917-6ab5-495c-b330-3c6ce41dbfe5)

создание репозитория на компьюторе: инициализация

![1](https://github.com/Hottabik/6semestr/assets/113089655/64d71d54-65a9-4a44-8f36-2a320f053a7e)

$ git status
On branch main
указывает имя ветки
No commits yet
нет сохранений
Untracked files: - неотслеживаемые файлы 
  (use "git add <file>..." to include in what will be committed) - нужна команда добавить , чтобы зафиксировать версию
        index.html - список файлов для сохранения 
        pictures/

nothing added to commit but untracked files present (use "git add" to track) - найдены файла для добавления 
Настраиваем ползователя в git
git config --global user.name PK303-0
git config --global user.email PK303-0@gmail.com

git config --global --unset htpp.proxy
git config --global --unset htpps.proxy
git config --global --unset core.gitproxy
![3](https://github.com/Hottabik/6semestr/assets/113089655/f7386b4a-239b-410c-957a-1d8241220424)

![2](https://github.com/Hottabik/6semestr/assets/113089655/208ab0c6-cf11-42d0-b307-7322e6fb7ad8)

подтверждение 

![5](https://github.com/Hottabik/6semestr/assets/113089655/0b670c40-5a8a-4a02-8858-f7272fa2595b)

![push](https://github.com/Hottabik/6semestr/assets/113089655/4da52c50-f50c-435b-9826-7a22a6199455)

основные ошибки:
1) remote - подключение к удаленном репозиторию (показывает на какой репозиторий мы хотим сохранить данные), может быть ошибка , что неправильно указали ссылку, чтобы изменить добавить set-url
2) авторизация - github нужно передать данные пользователя (логин,пароль или токин)
3) прокси сервер - проверям включен или нет
лк 3
если есть папка .git то команду git init
команда config настраиваются на пк (1 раз)
git remote используется один раз

Пароли :
qwerty - debian
12345678 - red os

![изображение](https://github.com/Hottabik/6semestr/assets/113089655/7c4fc59d-369f-48c9-aee7-5bce4042e30e)

![изображение](https://github.com/Hottabik/6semestr/assets/113089655/a9c805ff-ee42-420e-9e43-fe7028971dd1)

05.02 - Работа с файлами
1) Создание
2) Перемещение
3) Редактировани
4) Удаление
Обычный файл (Regular file)
1) touch churka.txt
2) mv churka.txt /home/stud
3) nano /home/stud/churka.txt ; cat  /home/stud/churka.txt
4) rm  /home/stud/churka.txt
   
![image](https://github.com/Hottabik/6semestr/assets/113089655/945d2fe0-4784-4de9-9abe-ae114f47e2ff)

Папка (DIrectory)
1) mkdir ussr
2) mv  /home/stud/ussr /home/stud/reich
3) ls /home/stud/reich
4) rm -r  /home/stud/reich

![image](https://github.com/Hottabik/6semestr/assets/113089655/c8be093a-37a2-4f48-84ad-94d12ab7817a)

жесткая ссылка:
ln London.txt Manch.txt

12.02.24
Устройства:
1. Символьные (мышка клавиатура)
2. Блочные (Флешки)
   ![image](https://github.com/Hottabik/6semestr/assets/113089655/5343dd85-e6d1-452b-b6e7-0e4cf3fe9427)
mknod blockf b 5 100
ls -la
nano blockf
rm blockf
ls -la
![image](https://github.com/Hottabik/6semestr/assets/113089655/729bb147-4503-48f0-b1c4-33a5a182b253)
Файлам присваивается уникальный номер (инод), посмотреть командой i1
Жесткие ссылки имеют тот же номер , что и исходный файл и это можно использовать , чтобы найти все жесткие ссылки.
![image](https://github.com/nazirov21/6-semestr/assets/113089463/56e41bdd-c0a4-4ab9-8bcd-0a77207cce86)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/ddd394d4-7f32-43ca-bc8f-4fb0b1ceaa31)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/cb83ab10-b881-4dab-8662-1c756488f934)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/9644f9b4-4208-4186-907b-5fb8daf9cdeb)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/9d296dab-27a7-4c8d-a098-864483052310)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/77415e51-7a62-49c9-96aa-d114899d5499)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/10c33502-e789-49c9-a957-540bd4d58bef)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/290ca147-98a5-4c2e-97ec-cb611a8188c4)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/6daf9a01-59f7-4c52-8976-0d25a1e50bb7)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/2d7149ab-706e-4a0c-bd06-ea53663691fe)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/ecfc16c7-4d66-4bed-9cd5-5c11d4e24f0a)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/b4c2d178-bb65-4053-b72d-7824a4c7dc7d)


![image](https://github.com/nazirov21/6-semestr/assets/113089463/ebe97be8-ab4c-4792-807b-23e418509f23)

![image](https://github.com/nazirov21/6-semestr/assets/113089463/7492cfc6-6965-4f58-af49-d829dc955135)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/add51f26-4c62-404e-a2a9-4cbb968e56de)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/6ca74f47-80e0-4566-a094-ab72cac48dc5)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/47749846-de3a-4585-82a1-702469df34e7)
Red os
![image](https://github.com/nazirov21/6-semestr/assets/113089463/80ab8ac7-543d-40b3-8d5d-0ce9035d3f2e)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/7bdb0033-ab5b-4443-9b1d-9a90a52caad0)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/343a5d10-4740-4c83-9b22-0fb9c1bfd172)
![image](https://github.com/nazirov21/6-semestr/assets/113089463/a2c4ab56-3627-43e2-b468-24d39bb4ee83)

4 тема

![image](https://github.com/nazirov21/6-semestr/assets/113089463/74596d4c-c8a5-4dd0-9ea6-f0a43f058a09)

5 тема
Атрибуты процесса 
1) Pid - уникальный идентификатор
2) Адресация областей памяти
3) fd открытые файловые дескрипторы( файлы которые использует процес
4) Обработчик сигналов процема, введение запросов пользователя 
5) Код выхода
ctrl + c
6) Рабочий каталог
7) Переменные окружения комментарий
8) состояние процесса
9) аппаратный контекст - это все что зависит от компьюьера
![Uploading image.png…]()

