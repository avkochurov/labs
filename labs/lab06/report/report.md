# **Лабораторная**

#

# **работа**

#

# **№6**

### Дисциплина:Операционныесистемы

## Кочуров Арсений Владимирович

# **Содержание**

1. **[Цельработы](#_bookmark0)5**
2. **[Задание](#_bookmark1)6**
3. **[Выполнениелабораторнойработы](#_bookmark2)7**
4. **[Выводы](#_bookmark14)24**

# **List**

#

# **of**

#

# **Tables**

# **List**

#

# **of**

#

# **Figures**

  1. [Копированиекаталоговифайлов](#_bookmark3). . . . . . . . . . . . . . . . . . 7
  2. [Перемещениеипереименованиефайловикаталогов](#_bookmark4). . . . . . . 8[3.3 Изменениеправдоступа](#_bookmark5) . . . . . . . . . . . . . . . . . . . . . . 9

  1. [Копирование исозданиекаталогов](#_bookmark6) 10
  2. [Копирование исозданиекаталогов](#_bookmark7) 10
  3. [Созданиефайлов](#_bookmark8) 11
  4. [Определениеопцииchmod](#_bookmark9) 12
  5. [Копированиефайлов](#_bookmark10) 14
  6. [Созданиекаталогов](#_bookmark11) 15
  7. [Изменяемправавладельца](#_bookmark12) 15
  8. [Работасконсолью](#_bookmark13) 17

1.
# Цельработы

Цель данной лабораторной работы — Ознакомление с файловой системой Linux,еёструктурой,именамиисодержаниемкаталогов.Приобретениепрактическихнавыков по применению команд дляработы с файлами и каталогами, по управле-нию процессами (и работами), по проверке использования диска и обслуживаниюфайловойсистемы.

1.
# Задание

1.Сделатьотчётполабораторнойработе№6вформатеMarkdown.2.Ознакомить-сясфайловойсистемойLinux,еёструктурой,именамиисодержаниекаталогов.

1.
# Выполнениелабораторнойработы

1. Выполнил примеры, описанные в первой части лабораторной работы (трипункта). (алгоритм действий представлен на рис. [3.1)](#_bookmark3)1.1.1. Копирование файла втекущем каталоге. Скопировала файл ~/abc1 в файл april и в файл may: создаёмфайлabcl(команда&quot;touchabcl&quot;),копируем,используякоманду&quot;cpabclapril&quot;и &quot;cp abcl may&quot;. 1.1.2. Копирование нескольких файлов в каталог. Скопировал файлы april и may в каталог monthly. 1.1.3. Копирование файлов в произвольномкаталоге. Скопировал файл monthly/may в файл с именем june. 1.1.4. Копиро-вание каталогов в текущем каталоге. Скопировал каталог monthly в каталогmonthly.00. 1.1.5. Копирование каталогов в произвольном каталоге. Скопировалкаталогmonthly.00вкаталог/tmp.

![](RackMultipart20220507-1-2gh1ky_html_4140600fde29f6ab.jpg)

Figure3.1:Копированиекаталоговифайлов

Продолжаемвыполнятьпримеры(пункт2смотритенарис.[3.2)](#_bookmark4)1.2.1.Пере-

именование файлов в текущем каталоге. Изменил название файла april на july вдомашнемкаталоге.1.2.2.Перемещениефайловвдругойкаталог.Переместил файл july в каталог monthly.00 (с помощью команды mv). 1.2.3. Переименованиекаталогов втекущем каталоге.Переименовал каталогmonthly.00в monthly.01.

![](RackMultipart20220507-1-2gh1ky_html_4e48e9f370136f30.png)1.2.4.Перемещениекаталогавдругойкаталог.Переместилкаталогmonthly.01в каталог reports. 1.2.5. Переименование каталога, не являющегося текущим.Переименовалкаталогreports/monthly.01вreports/monthly.

Figure 3.2: Перемещение и переименование файлов и каталоговПродолжаемвыполнятьпримеры(пункт 3смотритенарис.[3.3)](#_bookmark5)1.3.1.Созда-

л файл ~/may с правом выполнения для владельца. 1.3.2. Лишил владельцафайла~/may права на выполнение. 1.3.3. Создал каталог monthly с запретом начтениедлячленовгруппыи всехостальныхпользователей.1.3.4.Создал файл

~/abc1справомзаписидлячленовгруппы.

![](RackMultipart20220507-1-2gh1ky_html_3b29ec0cbe50636a.png)

Figure3.3:Изменениеправдоступа

  1. Выполняем следующие действия, представленные на рис. [3.4](#_bookmark6) , [3.5](#_bookmark7) 2.1.Скопировалфайл /usr/include/io.h в домашний каталог (используя коман-ду«cp/usr/include/io.h~»),иназываемегоequipment(команда«mvio.hequipment»).2.2.Вдомашнемкаталогесоздалдиректорию~/ski.plases(спомощьюкоманды«mkdirski.plases»).2.3.Переместилфайлequipmentвкаталог ~/ski.plases(используем команду«mvequipmentski.plases»). 2.4. Пе-реименовалфайл~/ski.plases/equipmentв~/ski.plases/equiplist(спомощьюкоманды «mvski.plases/equipment ski.plases/equiplist»). 2.5. Создал в домашнемкаталоге файл abc1 (команда «touchabc1») и скопировал его в каталог ~/ski.plases(команда «cp abcl ski.plases»), назвал его equiplist2 (с помощью команды «mvski.plases/abc1 ski.plases/equiplist2»). 2.6. Создал каталог с именем equipment вкаталоге ~/ski.plases (команда «mkdir ski.plases/equipment»). 2.7. Переместилфайлы ~/ski.plases/equiplist и equiplist2 в каталог ~/ski.plases/equipment . 2.8.Создала(команда«mkdirnewdir»)ипереместилкаталог~/newdirвкаталог

~/ski.plases(команда«mvnewdirski.plases»)иназываемегоplans(команда«mvski.plases/newdirski.plases/plans»).

![](RackMultipart20220507-1-2gh1ky_html_755b77f29876e8bc.png)

Figure3.4:Копированиеисозданиекаталогов

![](RackMultipart20220507-1-2gh1ky_html_c2016739a4336203.png)

Figure3.5:Копированиеисозданиекаталогов

  1. Определил опции команды chmod, необходимые для того, чтобы присвоитьсоответствующим файлам выделенные права доступа, считая, что в начале такихправнет.Предварительносоздаёмнеобходимыефайлыспомощьюкоманд:

![](RackMultipart20220507-1-2gh1ky_html_3b681fdf0eb94674.png)«mkdiraustralia»,«mkdirplay»,«touchmy\_os»,«touchfeathers» (алгоритмдействийпредставленнарис.[3.6](#_bookmark8),[3.7](#_bookmark9)

Figure3.6:Созданиефайлов

![](RackMultipart20220507-1-2gh1ky_html_5da65d475f693ad1.png)

Figure3.7:Определениеопцииchmod

1. drwxr–r–… australia: команда «chmod 744 australia» (это каталог, владелецимеетправоначтение,записьивыполнение,группавладельцаиостальные

–толькочтение)(Рисунок[3.6).](#_bookmark8)

1. drwx–x–x … play: команда «chmod 711 play» (это каталог, владелец имеетправо на чтение, запись и выполнение, группа владельца и остальные –тольковыполнение)(Рисунок[3.6).](#_bookmark8)
2. -r-xr–r–… my\_os: команды «chmod 544 my\_os» (это файл, владелец имеетправоначтениеивыполнение,группавладельцаиостальные–толькочтение)(Рисунок[3.6).](#_bookmark8)
3. -rw-rw-r–… feathers: команды «chmod 664 feathers» (это файл, владелец игруппавладельцаимеютправоначтениеизапись,остальные–толькочте-ние) (Рисунок [3.6).](#_bookmark8)Командой «ls-l» проверяем правильность выполненныхдействий.

  1. Выполняемследующиедействия,представленныенарис.[3.8](#_bookmark10),[3.9](#_bookmark11),[3.10](#_bookmark12)

4.1.Просмотрелсодержимоефайла/etc/passwd(команда«cat/etc/passwd»).4.2.Скопировал файл ~/feathers в файл ~/file.old (используем команду «cp feathersfile.old»).4.3.Переместилфайл~/file.oldвкаталог~/play(спомощьюкоманды

«mv file.ordplay»). 4.4. Скопировал каталог ~/play в каталог ~/fun (команда «cp - rplayfun»).4.5.Переместилкаталог~/funвкаталог~/play(используемкоманда

«mvfunplay»)иназвалегоgames(используемкоманда«mvplay/funplay/games»).

4.6. Лишаем владельца файла ~/feathers права на чтение (команда «chmod u-rfeathers»). 4.7. Если мы попытаемся просмотреть файл ~/feathers командой cat,тополучимотказвдоступе,т.к.впредыдущемпунктелишиливладельцаправаначтениеданногофайла.4.8.Еслимыпопытаемсяскопироватьфайл~/feathers,например,вкаталогmonthly,тополучимотказвдоступе,попричине,описаннойв предыдущем пункте. 4.9. Даём владельцу файла ~/feathers право на чтение(команда «chmod u+r feathers»). 4.10. Лишаем владельца каталога ~/play права навыполнение(спомощьюкоманды«chmodu-xplay»).4.11.Перейдалавкаталог

~/play(команда «cdplay»).Получимотказ вдоступе,т.к.впредыдущем пунктелишили владельца права на выполнение данного каталога. 4.12. Даём владельцукаталога~/playправонавыполнение(команда«chmodu+xplay»).

![](RackMultipart20220507-1-2gh1ky_html_a8e3a5f2d2c6cd4b.png)

Figure3.8:Копированиефайлов

![](RackMultipart20220507-1-2gh1ky_html_ec81e4a5f96edc60.jpg)

Figure3.9:Созданиекаталогов

![](RackMultipart20220507-1-2gh1ky_html_2c6f2307f09b8024.png)

Figure3.10:Изменяемправавладельца

  1. Используякоманды«manmount»,«manfsck»,«manmkfs»,«mankill»,получиминформациюосоответствующихкомандах(Алгоритмсм.нарис.[3.11),](#_bookmark13)

5.1) Командаmount:предназначенадлямонтированияфайловой

системы. Все файлы, доступные в Unix системах, составляют иерархическую фай-ловую структуру, которая имеет ветки (каталоги) и листья (файлы в каталогах).Корень этого дерева обозначается как слеш. Физически файлы могут располагаться на различных устройствах. Команда mount служит для подключения файловыхсистемразныхустройствкэтомубольшому дереву.Наиболеечастовстречающая-

ся форма команды mount выглядит следующим образом: «mount -t vfstype devicedir». Такая команда предлагает ядру смонтировать (подключить) файловую си-стему указанного типа vfstype, расположенную на устройстве device, к заданномукаталогуdir,которыйчастоназываютточкоймонтирования.

  1. Команда fsck: это утилита командной строки, которая позволяет выполнятьпроверки согласованности и интерактивное исправление в одной или несколь-ких файловых системах Linux. Он использует программы, специфичные для типафайловой системы, которую он проверяет.У команды fsck следующий синтак-сис: fsck [параметр] –[параметры ФС] [. . .]. Например, если нужно восстановить(«починить») файловую систему на некотором устройстве /dev/sdb2, следует вос-пользоваться командой: «sudo fsck -y /dev/sdb2». Опция -y необходима, т.к. приеёотсутствиипридётсяслишкомчастодаватьподтверждение.
  2. Команда mkfs: создаёт новую файловую систему Linux. Имеет следующийсинтаксис: mkfs[-V] [-tfstype] [fs-options] filesys [blocks] mkfs используется длясозданияфайловойсистемыLinuxнанекоторомустройстве,обычновразде-ле жёсткого диска. В качестве аргумента file sys для файловой системы можетвыступать или название устройства (например,/dev/hda1,/dev/sdb2) или точкамонтирования (например,/,/usr,/home). Аргументом blocks указывается количе-ство блоков, которые выделяются для использования этой файловой системой.По окончании работы mkfs возвращает 0 -в случае успеха, а 1 при неудачнойоперации. Например, команда «mkfs -t ext2 /dev/hdb1» создаёт файловую системутипаext2вразделе/dev/hdb1(второйжёсткийдиск).
  3. Команда kill: посылает сигнал процессу или выводит список допустимыхсигналов.Имеетследующийсинтаксис:kill[опции]PID,гдеPID–этоPID(чис-ловой идентификатор) процесса или несколько PID процессов, если требуетсяпослать сигнал сразу нескольким процессам. Например, команда «kill -KILL 3121»посылает сигнал KILL процессу с PID 3121, чтобы принудительно завершитьпроцусс.

![](RackMultipart20220507-1-2gh1ky_html_519fbe19f7eee011.png)

Figure3.11:Работасконсолью

man mountman fsckman mkfsmankill

Ответынаконтрольныевопросы:

1. Чтобы узнать, какие файловые системы существуют на жёстком диске моегокомпьютера, использую команду «df-Th». Из рисунка видно, что на моем ком-пьютере есть следующие файловые системы: dev tmpfs,tmpfs,ext4,iso9660. devtmpfs позволяет ядру создать экземпляр tmpfs с именем devtmpfs при иници-ализации ядра, прежде чем регистрируется какое-либо устройство с драйвера-ми. Каждое устройство с майором / минором будет предоставлять узел устрой-ства в devtmpfs.devtmpfs монтируется на /dev и содержит специальные файлыустройствдлявсехустройств.tmpfs−временноефайловоехранилищевомногихUnix-подобных ОС. Предназначена для монтирования файловой системы, норазмещаетсяв ОЗУ вместо ПЗУ. Подобная конструкция является RAM диском.Данная файловая система также предназначенная для быстрого и ненадёжногохранения временных данных. Хорошо подходит для /tmp и массовой сборкипакетов/образов.Предполагаетналичиедостаточногообъёмавиртуальнойпамя-ти.Файловая система tmpfs предназначенадля того, чтобы использовать частьфизической памяти сервера как обычный дисковый раздел, в котором можносохранять данные (чтение и запись). Поскольку данные размещены в памяти,точтениеилизаписьпроисходятвомногоразбыстрее,чемсобычногоHDD

диска.ext4− имеет обратную совместимость с предыдущими версиями ФС. Этаверсиябылавыпущенав2008году.ЯвляетсяпервойФСиз«семейства»Ext,ис-пользующая механизм «extentfile system», который позволяет добиться мень-шей фрагментации файлов и увеличить общую производительностьфайловойсистемы. Кроме того, вExt4реализован механизм отложенной записи (delayedallocation−delalloc),которыйтакжеуменьшаетфрагментациюдискаиснижаетнагрузку на CPU. С другой стороны, хотя механизм отложенной записи и ис-пользуется во многих ФС, но в силу сложности своей реализации он повышаетвероятность утери данных.Характеристики:максимальный размер файла: 16 TB;максимальный размер раздела: 16TB;максимальный размер имени файла: 255символов.Рекомендациипоиспользованию:наилучшийвыбордляSSD;наилуч-шая производительность по сравнению с предыдущимиEtx-системами;она также отлично подходит в качестве файловой системы для серверов баз данных, хотясама система и моложеExt3.ISO 9660−стандарт, выпущенный Международнойорганизацией по стандартизации, описывающий файловую систему для дисковCD-ROM. Также известен как CDFS (Compact Disc File System). Целью стандартаявляется обеспечить совместимость носителей под разными операционнымисистемами,такими,какUnix,MacOS,Windows.

1. Файловая система Linux/UNIX физически представляет собой пространствораздела диска разбитое на блоки фиксированного размера, кратные размерусектора − 1024, 2048, 4096 или 8120 байт. Размер блока указывается при созданиифайловойсистемы.ВфайловойструктуреLinuxимеетсяодинкорневойраздел

−/ (он же root, корень). Все разделы жесткого диска (если их несколько) пред-ставляютсобойструктуруподкаталогов,&quot;примонтированных&quot;копределеннымкаталогам. - &quot;/&quot; − корень. Это главный каталог в системе Linux. По сути, это и естьфайловая система Linux.Адреса всех файлов начинаются с корня, а дополнитель-ные разделы, флешки или оптические диски подключаются в папки корневогокаталога.Толькопользовательrootимеетправочитатьиизменятьфайлывэтомкаталоге.-&quot;/BIN&quot;–бинарныефайлыпользователя.Этоткаталогсодержитиспол-

няемые файлы. Здесь расположены программы, которые можно использовать воднопользовательскомрежимеилирежимевосстановления.-&quot;/SBIN&quot;–систем-ные испольняемые файлы. Так же как и &quot;/bin&quot;, содержит двоичные исполняемыефайлы, которые доступны на ранних этапах загрузки, когда не примонтированкаталог /usr. Но здесь находятся программы, которые можно выполнять толь-ко с правами суперпользователя. - &quot;/ETC&quot; – конфигурационные файлыВ этойпапке содержатся конфигурационные файлы всех программ, установленных всистеме.Кроме конфигурационных файлов, в системе инициализации Init Scripts,здесь находятся скрипты запуска и завершения системных демонов, монтиро-ванияфайловыхсистемиавтозагрузкипрограмм.-&quot;/DEV&quot;–файлыустройствВLinux все, в том числе внешние устройства являются файлами. Таким образом,всеподключенныефлешки,клавиатуры,микрофоны,камеры−этопростофайлыв каталоге /dev/. Выполняется сканирование всех подключенных устройств исозданиедляних специальныхфайлов.-&quot;/PROC&quot;–информацияо процессахПосути,этопсевдофайловаясистема,содержащаяподробнуюинформациюокаж-дом процессе, его Pid, имя исполняемого файла, параметры запуска, доступ коперативной памяти и так далее. Также здесь можно найти информацию обиспользовании системных ресурсов. - &quot;/VAR&quot; – переменные файлы. Названиекаталога &quot;/var&quot; говорит само за себя, он должен содержать файлы, которые частоизменяются. Размер этих файлов постоянно увеличивается. Здесь содержатсяфайлысистемныхжурналов,различныекеши,базыданныхитакдалее.-&quot;/TMP&quot;

– временные файлыВ этом каталоге содержатся временные файлы, созданныесистемой, любыми программами или пользователями. Все пользователи имеютправо записи в эту директорию. - &quot;/USR&quot; – программы пользователяЭто самыйбольшой каталог с большим количеством функций. Здесь находятся исполняе-мые файлы, исходники программ, различные ресурсы приложений, картинки,музыку и документацию. - &quot;/HOME&quot; – домашняя папка. В этой папке хранятсядомашние каталоги всех пользователей. В них они могут хранить свои личныефайлы,настройкипрограммит.д.-&quot;/BOOT&quot;–файлызагрузчика.Содержитвсе

файлы,связанные с загрузчиком системы. Это ядро vmlinuz, образ initrd, а такжефайлы загрузчика, находящие в каталоге /boot/grub. - &quot;/LIB&quot; – системные библио-теки.Содержитфайлысистемныхбиблиотек,которыеиспользуютсяисполняе-мымифайламивкаталогах/binи/sbin.-&quot;/OPT&quot;–дополнительныепрограммыВэтупапкуустанавливаютсяпроприетарныепрограммы,игрыилидрайвера.Этопрограммысозданныеввидеотдельныхисполняемыхфайловсамимипроизво-дителями.-&quot;/MNT&quot;–монтирование.Вэтоткаталогсистемныеадминистраторымогутмонтироватьвнешниеилидополнительныефайловыесистемы.-&quot;/MEDIA&quot;

–съемныеносители.Вэтоткаталогсистемамонтируетвсеподключаемыевнеш-ниенакопители –USBфлешки, оптическиедискиидругиеносителиинформации.

-&quot;/SRV&quot;–сервер.Вэтомкаталогесодержатсяфайлысерверовисервисов.-&quot;/RUN&quot;

-процессыКаталог,содержащий PID файлы процессов, похожий на &quot;/var/run&quot;, но вотличие от него, он размещен в TMPFS, а поэтому после перезагрузки все файлытеряются.

1. Чтобы содержимое некоторой файловойсистемы было доступно операци-оннойсистеменеобходимовоспользоватьсякомандойmount.
2. Целостностьфайловойсистемыможетбытьнарушенаиз-заперебоеввпи-тании,неполадоквоборудованииилииз-занекорректного/внезапноговыключе-ния компьютера. Чтобы устранить повреждения файловой системы необходимоиспользоватькомандуfsck.
3. Файловую систему можно создать, используя команду mkfs. Ее краткоеописаниедановпункте5)входевыполнениязаданийлабораторнойработы.
4. Для просмотра текстовых файлов существуют следующие команды: - сat.Задача команды cat очень проста −она читает данные из файла или стандартноговводаивыводитихнаэкран.Синтаксисутилиты:cat[опции]файл1файл2…Ос-новные опции:-b–нумеровать только непустые строки-E–показыватьсимвол $ вконцекаждойстроки-n–нумероватьвсестроки-s–удалятьпустыеповторяющие-ся строки -T–отображать табуляции в виде ^I-h–отобразить справку-v–версияутилиты-nl.Командаnlдействуетаналогичнокомандеcat,новыводитещеино-

мерастроквстолбцеслева.-less.Cущественноболееразвитаякомандадляпро-листывания текста. При чтении данных со стандартного ввода она создает буфер,который позволяет листать текст как вперед, так и назад, а также искать как понаправлению к концу, так и по направлению к началу текста.Синтаксис анало-гичный синтаксисукоманды cat.Некоторые опции:-g –при поиске подсвечиватьтолько текущее найденное слово (по умолчанию подсвечиваются все вхождения)-N –показывать номера строк - head. Команда head выводит начальные строки (поумолчанию − 10) из одного или нескольких документов. Также она может показы-вать данные, которые передает на вывод другая утилита.Синтаксис аналогичныйсинтаксису команды cat.Основные опции:-c (–bytes) −позволяет задавать количе-ство текста не в строках, а в байтах-n (–lines) −показывает заданное количествострок вместо 10, которые выводятся по умолчанию-q (–quiet, –silent) −выводиттолькотекст,недобавляякнемуназваниефайла-v(–verbose)−передтекстомвы-водитназваниефайла-z(–zero-terminated)−символыпереходанановуюстрокузаменяет символами завершения строк - tailЭта командапозволяет выводитьзаданное количество строк с конца файла, а также выводить новые строки винтерактивномрежиме.Синтаксисаналогичныйсинтаксисукомандыcat.Основ-ные опции:-c −выводить указанное количество байт с конца файла-f −обновлятьинформацию по мере появления новых строк в файле-n −выводить указанноеколичество строк из конца файла–pid −используется с опцией -f, позволяет за-вершить работу утилиты, когда завершится указанный процесс-q −не выводитьименафайлов–retry−повторятьпопыткиоткрытьфайл,еслионнедоступен-v

−выводитьподробнуюинформациюофайле.

1. Утилита cpпозволяет полностью копировать файлы и директории.Cинтак-сис:cp [опции] файл-источник файл-приемникПосле выполнения команды файл-источник будет полностью перенесен в файл-приемник. Если в конце указан слэш,файлбудетзаписанвзаданнуюдиректориюсоригинальнымименем.Основныеопции:–attributes-only−некопироватьсодержимоефайла,атолькофлагидосту-паивладельца-f,–force−перезаписыватьсуществующиефайлы-i,–interactive

−спрашивать, нужно ли перезаписывать существующие файлы-L −копироватьне символические ссылки, а то, на что они указывают -n −не перезаписыватьсуществующие файлы-P −не следовать символическим ссылкам-r −копироватьпапку Linux рекурсивно-s −не выполнять копирование файлов в Linux, асозда-ватьсимволическиессылки-u−скопироватьфайл, толькоеслионбылизменён-x

−не выходить за пределы этой файловой системы-p −сохранять владельца, вре-менные метки и флаги доступа при копировании-t −считать файл-приемникдиректориейикопироватьфайл-источниквэтудиректорию.

1. Команда mv используется для перемещения одного или нескольких фай-лов (или директорий) вдругую директорию, атакже для переименования файловидиректорий. Синтаксис:mv [-опции] старый\_файл новый\_файлОсновные оп-ции:–help−выводитнаэкранофициальнуюдокументациюобутилите–version

−отображает версию mv-b−создает копию файлов, которые были перемещеныилиперезаписаны-f−приактивациинебудетспрашиватьразрешениеувладель-ца файла, если речь идет о перемещении или переименовании файла -i −наобо-рот, будет спрашивать разрешение у владельца-n −отключает перезапись ужесуществующихобъектов–strip-trailing-slashes—удаляетзавершающийсимвол/у файла при его наличии-t [директория] —перемещает все файлы в указаннуюдиректорию-u−осуществляетперемещениетольковтомслучае,еслиисходныйфайл новее объекта назначения -v −отображает сведения о каждом элементе вовремяобработкикомандыКомандаrenameтакжепредназначена,чтобыпереиме-новать файл.Синтаксис:rename [опции] старое\_имя новое\_имя файлы. Основныеопции:-v −вывести список обработанных файлов-n −тестовый режим, на самомделе никакие действия выполнены не будут -f −принудительно перезаписыватьсуществующиефайлы.

1. Правадоступа−совокупностьправил,регламентирующихпорядокиусло-вия доступа субъекта к объектам информационной системы (информации, еёносителям,процессамидругимресурсам)установленныхправовымидокумен-тамиилисобственником,владельцеминформации.Правадоступакфайлуили

каталогу можно изменить,воспользовавшиськомандой chmod.Сделатьэто мо-жет владелец файла (или каталога) или пользователь с правами администратора.Синтаксис команды:chmod режим имя\_файлаРежим имеет следующие компо-ненты структуры и способзаписи:= установить право-лишить права+ датьправоrчтениеwзаписьxвыполнениеu(user)владелецфайлаg(group)группа,ккоторойпринадлежитвладелецфайлаo(others)всеостальные.

1.
# Выводы

В ходе выполнения данной лабораторной работы я ознакомился с файловойсистемой Linux, её структурой, именами и содержанием каталогов, получил на-выки по применению команд для работы с файлами и каталогами, по управлениюпроцессами (и работами), по проверке использования диска и обслуживаниюфайловойсистемы.
