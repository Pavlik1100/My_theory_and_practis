Задание и решение в файле Linux_terminal_(GitBash)_commands и ниже:
Linux terminal (GitBash) commands

1) Посмотреть где я ===//=== pwd
2) Создать папку ===//=== mkdir new_folder
3) Зайти в папку ===//=== cd new_folder
4) Создать 3 папки ===//=== mkdir folder_1 folder_2 folder_3 -//- mkdir {0..2}
5) Зайти в любоую папку ===//=== cd folder_2
6) Создать 5 файлов (3 txt, 2 json) ===//=== touch 1.txt 2.txt 3.txt 4.json 5.json 
7) Создать 3 папки ===//=== mkdir dir_1 dir_2 dir_3 
8. Вывести список содержимого папки ===//=== la -la
9) + Открыть любой txt файл ===//=== vim 1.txt
10) + написать туда что-нибудь, любой текст. ===//=== в открытом редакторе vim нажимаю клавишу "i" чтобы начать набирать текст
11) + сохранить и выйти. ===//=== нажмаю клавишу "esc", ввожу ":wq"
12) Выйти из папки на уровень выше ===//=== cd ..
—
13) переместить любые 2 файла, которые вы создали, в любую другую папку. ===//=== mv 4.json 5.json dir_1/
14) скопировать любые 2 файла, которые вы создали, в любую другую папку. ===//=== cp 1.txt 2.txt dir_2/
15) Найти файл по имени ===//=== find . -name '1.txt'
16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает. ===//=== tail -fn1 1.txt -//- grep 2 1.txt grep ищет строки в файлах, фильтрует вывод коман и др.
17) вывести несколько первых строк из текстового файла ===//=== head -n2 1.txt
18) вывести несколько последних строк из текстового файла ===//=== tail -n3 1.txt
19) просмотреть содержимое длинного файла (команда less) изучите как она работает. ===//=== less -s 1.txt 
20) вывести дату и время ===//=== date
=========

Задание *
1) Отправить http запрос на сервер.
http://162.55.220.72:5005/object_info_3?name=Vadim&age=32&salary=1000 ===//=== curl "http://162.55.220.72:5005/object_info_3?name=Vadim&age=32&salary=1000"
2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13 ===//==

запуск файла "script" со скриптом командой /.script 

#!/bin/bash
cd new_folder
mkdir {00..02}
cd 00
touch 01.txt 02.txt 03.txt 04.json 05.json
mkdir fold1 fold2 fold3
ls -la
mv -v 04.json 05.json fold3


=====================
1) Посмотреть где я - pwd
2) Создать папку - mkdir foldername
3) Зайти в папку - cd foldername

https://losst.ru/nachnite-izuchat-linux-pryamo-sejchas
