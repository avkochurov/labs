








**Лабораторная работа №10**
### **Дисциплина: Операционные системы**

## Кочуров Арсений Владимирович




**Содержание**

1. [Цель работы](#_bookmark0)	5**
1. [**Задание](#_bookmark1)	**6**
1. [**Выполнение лабораторной работы](#_bookmark2)	**7**
1. [**Библиография](#_bookmark37)	**40**
1. [**Выводы](#_bookmark38)	**41**



41
![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.001.png)

**List of Tables**


**List of Figures**

[3.1	Открытие редактора](#_bookmark3) .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .	7

[3.2	Создание файла](#_bookmark4)	.  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .	8

[3.3	Работа с текстом](#_bookmark5)  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .	8

[3.4	Вырезание строки](#_bookmark6)  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .  .	9

5. [Вставила строку](#_bookmark7)	10
5. [Выделила область текста](#_bookmark8)	11
5. [Область в конце файла](#_bookmark9)	12
5. [Выделила область](#_bookmark10)	13
5. [Вырезание строки](#_bookmark11)	14
5. [Отмена последнего действия](#_bookmark12)	15
5. [Переместила курсор](#_bookmark13)	16
5. [Перемещение курсора](#_bookmark14)	17
5. [Перемещение курсора](#_bookmark15)	18
5. [Перемещение курсора](#_bookmark16)	19
5. [Перемещение курсора](#_bookmark17)	20
5. [Список активных буферов](#_bookmark18)	21
5. [Список открытых буферов](#_bookmark19)	22
5. [Переключение на буфера](#_bookmark20)	23
5. [Закрыла окно буфера](#_bookmark21)	24
5. [Переключение между буферами](#_bookmark22)	25
5. [Работа с фреймом](#_bookmark23)	26
5. [Работа с фреймом](#_bookmark24)	27
5. [Работа с фреймом](#_bookmark25)	28
5. [Создание файлов](#_bookmark26)	28
5. [Команда для работы с файлами](#_bookmark27)	29
5. [Вводим текст в документы](#_bookmark28)	30
5. [Режим поиска](#_bookmark29)	31
5. [Поиск слов в тексте](#_bookmark30)	32
5. [Переключение между поисками](#_bookmark31)	33
5. [Переключение между поисками](#_bookmark32)	34
5. [Выходим из режима поиска](#_bookmark33)	35
5. [Переходим в режим поиска](#_bookmark34)	36
5. [Переходим в режим поиска](#_bookmark35)	37
5. [Другой режим поиска](#_bookmark36)	38







1. # **Цель работы**

Цель данной лабораторной работы — Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.







1. # **Задание**

1. Сделать отчёт по лабораторной работе №10 в формате Markdown.
1. Познакомиться с операционной системой Linux.







1. # **Выполнение лабораторной работы**

1. Открыл редактор Emacs с помощью команды «emacs &» (Скриншот [3.1 ](#_bookmark3)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.002.jpeg)

Figure 3.1: Открытие редактора

2. Создал файл lab07.sh с помощью комбинации «Ctrl-x» «Ctrl-f» (Скриншот [3.2 ](#_bookmark4)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.003.jpeg)

Figure 3.2: Создание файла

2. В открывшемся буфере набрал необходимый текст (алгоритм действий представлен на рис. [3.3 ](#_bookmark5)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.3: Работа с текстом

2. Сохранил файл с помощью комбинации «Ctrl-x»«Ctrl-s».

2. Выполнил следующие действия:
   1. Вырезал одной командой целую строку («Сtrl-k») (См. рисунок [3.4 ](#_bookmark6)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.4: Вырезание строки

1. Вставил эту строку в конец файла («Ctrl-y») (См. рисунок [3.5 ](#_bookmark7)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.5: Вставила строку

1. Выделил область текста («Ctrl-space») (алгоритм действий представлен на рис. [3.6 ](#_bookmark8)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.6: Выделила область текста

1. Скопировал область в буфер обмена («Alt-w»).
1. Вставил область в конец файла («Ctrl-y») (Скриншот [3.7 ](#_bookmark9)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.7: Область в конце файла

1. Вновь выделил эту область («Ctrl-space») (Скриншот [3.8 ](#_bookmark10)) и на этот раз вырежем её («Ctrl-w») (Скриншот [3.9 ](#_bookmark11)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.8: Выделила область

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.9: Вырезание строки

1. Отменил последнее действие («Ctrl-/») (См. рисунок [3.10 ](#_bookmark12)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.10: Отмена последнего действия

2. Выполним следующие действия:
   1. Переместил курсор в начало строки («Ctrl-a») (алгоритм действий пред- ставлен на рис. [3.11 ](#_bookmark13), [3.12 ](#_bookmark14)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.11: Переместил курсор

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.12: Перемещение курсора

1. Переместил курсор в конец строки («Ctrl-e») (Скриншот [3.13 ](#_bookmark15)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.13: Перемещение курсора

1. Переместил курсор в начало буфера («Alt-<») (Скриншот [3.14 ](#_bookmark16)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.14: Перемещение курсора

1. Переместил курсор в конец буфера («Alt->») (Скриншот [3.15 ](#_bookmark17)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.15: Перемещение курсора

2. Выполнил следующие действия:
   1. Вывел список активных буферов на экран («Ctrl-x»«Ctrl-b») (алгоритм действий представлен на рис. [3.16 ](#_bookmark18)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.16: Список активных буферов

1. Переместился во вновь открытое окно («Ctrl-xo») со списком открытых буферов (См. рисунок [3.17 ](#_bookmark19)) и переключился на другой буфер (для этого нажал на «enter» после выбора необходимого буфера) (См. рисунок [3.18 ](#_bookmark20)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.17: Список открытых буферов

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.18: Переключение на буфера

1. Закрыл это окно («Ctrl-x0») (алгоритм действий представлен на рис. [3.19 ](#_bookmark21)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.19: Закрыла окно буфера

1. Теперь вновь переключился между буферами, но уже без вывода их списка на экран («Ctrl-x b») (алгоритм действий представлен на рис. [3.20 ](#_bookmark22)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.20: Переключение между буферами

2. Выполнил следующие действия:
   1. Поделил фрейм на 4 части: разделил фрейм на два окна по вертикали («Ctrl-x 3»), а затем каждое из этих окон на две части по горизонтали («Ctrl-x 2») (алгоритм действий представлен на рис. [3.21 ](#_bookmark23), [3.22 ](#_bookmark24), [3.23 ](#_bookmark25)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.21: Работа с фреймом

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.22: Работа с фреймом

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.23: Работа с фреймом

1. В каждом из четырёх созданных окон открыла новый буфер (файл) и ввел несколько строк текста. Для этого предварительно создал эти файлы с помощью команд «touch example1.txt», «touch example2.txt», «touch example3.txt», «touch example4.txt» (алгоритм действий представлен на рис. [3.24 ](#_bookmark26), [3.25 ](#_bookmark27), [3.26 ](#_bookmark28)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.002.jpeg)

Figure 3.24: Создание файлов

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.25: Команда для работы с файлами

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.26: Вводим текст в документы

2. Выполнила следующие действия:
   1. Переключил в режим поиска («Ctrl-s») и нашла несколько слов, присут- ствующих в тексте (алгоритм действий представлен на рис. [3.27 ](#_bookmark29), [3.28 ](#_bookmark30)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.27: Режим поиска

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.28: Поиск слов в тексте

1. Переключился между результатами поиска, нажимая «Ctrl-s» (алгоритм действий представлен на рис. [3.29 ](#_bookmark31), [3.30 ](#_bookmark32)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.29: Переключение между поисками

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.30: Переключение между поисками

1. Вышел из режима поиска, нажав «Ctrl-g» (См. рисунок [3.31 ](#_bookmark33))

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.31: Выходим из режима поиска

1. Перешел в режим поиска и замены («Alt-%»), ввел текст, который следует найти и заменить, нажмем «enter», затем введем текст для замены. После того как будут подсвечены результаты поиска, нажмем«!» для подтверждения замены (ал- горитм действий представлен на рис. [3.32 ](#_bookmark34), [3.33 ](#_bookmark35)). Важно, чтобы курсор находился в начале текста.

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.32: Переходим в режим поиска

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.33: Переходим в режим поиска

1. Пробую другой режим поиска, нажав «Alt-so» (алгоритм действий пред- ставлен на рис. [3.34 ](#_bookmark36)).

![](Aspose.Words.1e246301-5ab9-4b08-b9f3-2e4067e297d2.004.png)

Figure 3.34: Другой режим поиска

Ответы на контрольные вопросы:

1. Emacs − один из наиболее мощных и широко распространённых редакторов, используемых в мире Unix. По популярности он соперничает с редактором vi и его клонами. В зависимости от ситуации, Emacs может быть текстовым редакто- ром; программой для чтения почты и новостей Usenet; интегрированной средой разработки (IDE); операционной системой и т.д.Всё это разнообразие достигается благодаря архитектуре Emacs, которая позволяет расширять возможности редак- тора при помощи языка Emacs Lisp. На языке C написаны лишь самые базовые и низкоуровневые части Emacs, включая полнофункциональный. интерпретатор языка Lisp. Таким образом, Emacs имеет встроенный язык программирования, который может использоваться для настройки, расширения и изменения пове- дения редактора. В действительности, большая часть того редактора, с которым пользователи Emacs работают в наши дни,написана на языке Lisp.
1. Основную трудность для новичков при освоенииданного редактора мо-

гутсоставлять большое количество команд, комбинаций клавиш, которые не получится все запомнить с первого раза и поэтоупридется часто обращаться к справочным материалам.

1. Буфер –это объект, представляющий собой текст. Если имеется несколько буферов, то редактировать можно только один. Обычно буфер считывает данные из файла или записывает в файл данные из буфера.Окно –это область экрана, отображающая буфер. При запуске редактора отображается одно окно, но при обращении к некоторым функциям могут открыться дополнительные окна. Окна Emacsи окна графической среды XWindow–разные вещи. Одно окно XWindow- может быть разбито на несколько окон в смысле Emacs, в каждом из которых отображается отдельный буфер.
1. Да, можно.
1. При запуске Emacsпо умолчанию создаются следующие буферы: «scratch»(бу- фер для несохраненного текста) «Messages»(журнал ошибок, включающий также- информацию, которая появляется в области EchoArea) «GNUEmacs»(справочный буфер о редакторе).
1. C-c |сначала, удерживая «ctrl»,нажимаю «c»,после –отпускаюобе клавишии нажимаю «|» C-cC-|сначала, удерживая «ctrl»,нажимаю «с», после –отпускаю обе клавиши и, удерживая «ctrl», нажимаю «|».
1. Чтобы поделить окно на две части необходимо воспользоваться комбина- цией «Ctrl-x 3»(по вертикали) или «Ctrl-x 2» (по горизонтали).
1. Настройки Emacsхранятся в файле .emacs.
1. По умолчанию клавиша «�» удаляет символперед курсором, нов редакторе её можно переназначить. Для этого необхдимоизменить конфигурацию файла

.emacs.

1. Более удобным я считаю редактор emacs, потому чтов нем проще открывать другие файлы, можно использовать сразу несколько окон, нет «Командногорежи- ма», «Режима ввода», «Режима командной строки», которые являются немного непривычными и в какой-то степени неудобным.







1. # **Библиография**

1. Программное обеспечение GNU/Linux. Лекция 2. Терминал и командная строка (Г. Курячий, МГУ);
1. Программное обеспечение GNU/Linux. Лекция 3. FHS и процессы (Г. Курячий, МГУ);
1. Электронный ресурс: https://alexott.net/ru/writings/altlinux-emacs/

1. Электронный	ресурс:	https://yandex.ru/turbo/pythonist.ru/s/tekstovyj- redaktor-emacs/







1. # **Выводы**

В ходе выполнения данной лабораторной работы я познакомилась с операци- онной системой Linux и получила практические навыки работы с редактором Emacs.
