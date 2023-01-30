## 1) Посмотреть где я
pwd

## 2) Создать папку
mkdir example_1

## 3) Зайти в папку
cd example_1

## 4) Создать 3 папки
mkdir example_2 example_3 example_4

##5) Зайти в любоую папку
cd example_2

##6) Создать 5 файлов (3 txt, 2 json)
touch file1.txt file2.txt file3.txt test1.json test2.json

##7) Создать 3 папки
mkdir example_5 example_6

##8) Вывести список содержимого папки
ls -la

##9) Открыть любой txt файл
vim file1.txt

##10) Написать туда что-нибудь, любой текст. 
i , "text text text"

##11) Сохранить и выйти.
Ctri;l + C, :wq

##12) Выйти из папки на уровень выше
cd ../
—
##13) Переместить любые 2 файла, которые вы создали, в любую другую папку.
mv file1.txt file2.txt ../example_3

##14) Скопировать любые 2 файла, которые вы создали, в любую другую папку.
cp test1.json test2.json ../example_4

##15) Найти файл по имени
find test1.json

##16) Просмотреть содержимое в реальном времени
grep "name" test1.json

17) Вывести несколько первых строк из текстового файла
head -5 test1.json

18) Вывести несколько последних строк из текстового файла
tail 5 test1.json

19) Просмотреть содержимое длинного файла (команда less) 
less test1.json

20) Вывести дату и время
date

21) Отправьте запрос
curl http://162.55.220.72:5005/terminal-hw-request

22) Напишите скрипт
touch myscript ; vim myscript 
#!/bin/bash
# This is a comment
cd example_4
mkdir folder1 folder2 folder3
cd folder1
touch text1.txt text2.txt text3.txt info1.json info2.json
mkdir test1 test2 test3
ls -la
mv text1.txt text2.txt test1
