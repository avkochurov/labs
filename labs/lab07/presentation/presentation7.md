﻿![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.001.png)




# Отчёт по лабораторной работе №7
![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.002.png)

Кочуров Арсений Владимирович 

` `14 мая 2022

РУДН, Москва, Россия





1/7

![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.001.png)






# [Отчет по лабораторной работы №7](#_bookmark0)
![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.003.png)

![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.001.png)


Запись в файл
![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.004.png)Записал в файл file.txt название файлов, содержащийся в определённом каталоге. Для того, чтобы записать в файл file.txt названия файлов, содержащихся в каталоге /etc, использовал команду «ls–a/etc> file.txt». Далее с помощью команды «ls-a~ » file.txt» дописываю в этот же файл названия файлов, содержащихся в домашнем каталоге. Командой «catfile.txt» просматриваю файл, чтобы убедиться в правильности действий (алгоритм действий представлен на рис. [1 ](#_bookmark1), [2).](#_bookmark2)







![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.005.jpeg)2/7

![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.001.png)






Редактор gedit
![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.006.png)![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.007.png)Запускаю редактор gedit в фоновом режиме командой «gedit&» (Рисунок [3). ](#_bookmark3)После этого на экране появляется окно редактора.

Figure 3: Редактор gedit






3/7

![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.001.png)




Работа с командой gedit
![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.008.png)Чтобы определить идентификатор процесса gedit, использую команду

![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.009.png)«ps| grep-i“gedit”» (Скриншот [4). ](#_bookmark4)Из рисунка видно, что наш процесс имеет PID 24249. Узнать идентификатор процесса можно также, используя команду «pgrep gedit»или «pidof gedit».

Figure 4: команда «ps| grep-i“gedit”»




4/7

![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.001.png)


Команда kill
![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.010.png)![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.011.png)Прочитав информацию о команде kill с помощью команды «man kill», использую её для завершения процесса gedit (команда «kill 24249») (Алгоритм действий представлен на рис. [5 ](#_bookmark5), [6 ](#_bookmark6), [7).](#_bookmark7)

Figure 5: команда kill










![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.012.png)5/7

![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.001.png)![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.013.png)Команды df, du
















Figure 8: команды df, du



![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.014.png)6/7

![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.001.png)







Выводы
![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.015.png)В ходе выполнения данной лабораторной работы я изучил инструменты поиска файлов и фильтрации текстовых данных, а также приобрел практические навыки: по управлению процессами (и заданиями), по проверке использования диска и обслуживанию файловых систем.






7/7

![](Aspose.Words.6f4c21d0-3bbd-413a-b1a0-939e194d8d72.016.png)







# Спасибо за внимание!