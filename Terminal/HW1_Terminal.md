1. Посмотреть где я 
```
pwd
```
___
2. Cоздать папку
``` 
mkdir folder
```
___
3. Зайти в папку 
```
cd folder
```
___
4. Создать 3 папки 
```
mkdir folder1 folder2 folder3
```
___
5. Зайти в любую папку 
```
cd folder2
```
___
6. Создать 5 файлов (3 txt, 2 json)  
```
touch file1.txt file2.txt file3.txt file4.json file5.json
```
___
7. Создать 3 папки
```
mkdir folder4 folder5 folder6
```
___
8. Вывести список содержимого папки 
```
ls -la
```
___
9. +Открыть любой txt файл 
```
vim file2.txt
```
___
10. +Написать туда что-нибудь, любой текст 
```
i "Hello, it's me"
```
___
11. +Cохранить и выйти  
```
esc :wq
```
___
12. Выйти из папки на уровень выше  
```
cd ..
```
___
13. Переместить любые 2 файла, которые вы создали, в любую другую папку 
```
mv file1.txt ../folder3/file1.txt
mv file4.json ../folder3/file4.json
```
___
14. Скопировать любые 2 файла, которые вы создали, в любую другую папку
```
cp file2.txt ../folder1/file2.txt
cp file5.json ../folder1/file5.json
```
___
15. Найти файл по имени 
```
find . -name file1.txt 
```
___
16. Просмотреть содержимое в реальном времени (команда grep) 
```
grep -rin "Hello"
```
___
17. Вывести несколько первых строк из текстового файла 
```
head -n3 file1.txt
```
___
18. Вывести несколько последних строк из текстового файла 
```
tail -n3 file1.txt
```
___
19. Просмотреть содержимое длинного файла (команда less) изучите как она работает 
```
less file1.txt
```
___
20. Вывести дату и время 
```
date
```
___
####Задания*

1. Отправить http запрос на сервер http://162.55.220.72:5006/terminal-hw-request

```
curl "http://162.55.220.72:5005/get_method?name=Julia&age=21"
```
___
2. Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13
```
#!/bin/bash
rm -rf folder
mkdir folder
cd folder
mkdir folder1 folder2 folder3
cd folder2
touch file1.txt file2.txt file3.txt file4.json file5.json
mkdir folder4 folder5 folder6
ls
mv file1.txt ../folder3/file1.txt
mv file4.json ../folder3/file4.json
ls
```