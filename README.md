# *HP Project*

# Введение
Делая этот проект, мы хотели создать что-то полезное. Возможно, даже получить нобелевскую премию за корпусное исследование текстов, но магия вне Хогвартса почему-то не подействовала, и нам все еще не позвонили. Зато теперь у нас есть классный красивый проект о динамике мотивов в Гарри Поттере.


![](2019-06-05_13-54-09.png)


Мы решили поисследовать, как менялись идеи и Джоан Ролинг, а вместе с тем вселенная и ее персонажи. Что у нас получилось, смотрите сами.

# Цель
Изучить развитие тем и мотивов в серии книг о Гарри Поттере (далее - ГП):
* учебная жизнь в Хогвартсе
* магия и использование заклинаний
* мотивы смерти, добра и зла, дружбы, семьи и любви

# Инструменты
* MyStem
* AntConc
* Voyant Tools

![](instrument_meme.jpg)

# Методы
* Мы собрали тексты всех 7 частей ГП в переводе издательства "Росмэн" и лемматизировали их с помощью MyStem (к сожалению, он работает только на русском - изначально мы хотели исследовать оригинал произведения, потому что нам такое измерение показалось более точным). 
* Затем мы использовали AntConc, чтобы выявить самых популярных героев и самые часто употребляемые слова. Так мы выбрали мотивные ряды для анализа.
* Последним шагом стала визуализация результатов исследования, для чего нам пришлось поработать с Voyant Tools.

![](meme2.jpg)

*когда понимаешь, что MyStem можно использовать только для лемматизации русских текстов, но тебе очень нужен третий инструмент*

# Лемматизация текста и ~~немного нытья~~ трудности, с которыми мы столкнулись
Лемматизация текста, в котором есть множество слов, нетипичных для русского языка, оказалась очень болезненной. Семья Дурсль превращалась в "семья дурсль|дурсля|дурслить", Когтевран и Пуффендуй становились глаголами (MyStem предлагал нам пуффендовать и пуффендовывать, а также когтевирать). Большинство заклинаний также пришлось выискивать вручную, так как, например, сложно найти заклинание для вправления конечностей и остановки кровотечений "эпискеи", если MyStem превратил его в "эпискея".

# Учебная жизнь в Хогвартсе
Выявить самых популярных учеников и учителей Хогвартса оказалось совсем нетрудно:

![](characters.jpg)

Профессор Макгонагалл, к нашему удивлению, гораздо менее популярна по сравнению со своими коллегами, но ведь она не принимала такого активного участия во внеучебной жизни учеников. На этой диаграмме видно, как менялась популярность некоторых преподавателей Хогвартса:

![](professors.jpg)

А вот самым популярным факультетом, как ни странно, оказался Слизерен:

![](faculties.jpg)

Визуализировать волшебные дисциплины в полной мере нам не удалось, так как названия многих из них используются в другом контексте (например, заклинания). Поэтому мы решили перейти к самой животрепещущей теме - экзаменам. О них ученики всерьез задумываются только с появлением Амбридж (до этого экзамены имели привычку время от времени отменяться):

![](2019-06-04_13-11-40.png)

Также можно наблюдать интеллектуальное развитие героев (не очень значительное, но все же):

![](2019-06-04_13-09-54.png)

Всему виной халатное отношение к учебе: чем старше становятся ученики, тем меньше они задумываются о школьных успехах :(

![](stuDYING.jpg)

# Магия и использование заклинаний
Мир ГП известен магией - к ней мы сейчас и обратимся. Сначала посмотрим на соотношение маглов и волшебников в книгах:

![](vs.jpg)

Как видно, маглы и волшебники постоянно борются за популярность, а к концу книги находят баланс.
А еще мы нашли героев-аутсайдеров, о которых обычно вспоминают только в начале и/или конце каждой части, да и то не всегда:

![](2019-06-04_13-04-48.png)

Перейдем непосредственно к магии.
В книге много раз использовалось слово "заклинание" и раз слово "заклятие":

![](spells.jpg)

Чем старше становились герои, тем больше заклинаний они узнавали.

![](spells_meme.jpg)

Посмотрим, как распределены заклинания по книгам.
1) В первой части ("ГП и Философский камень") появились следующие заклинания:
* Алохомора
* Вингардиум Левиоса
* Локомотор Мортис 
* Петрификус Тоталус (aka "Остолбеней")

![](spells1.jpg)

2) С "Тайной комнатой" все сложнее - там уже 7 заклинаний:
* Апарекиум
* Люмос
* Риктусемпра
* Серпенсортия
* Таранталлегра
* Фините Инкантатем
* Экспеллиармус

![](spells2.jpg)

3) "Узник Азкабана" известен нам заклинанием "Экспекто Патронум":

![](patronus.jpg)

Другое известное заклинание - "Ридикулус" - используется, чтобы сделать страшного боггарта смешным:

![](ridiculus.jpg)

Остальные 6 заклинаний из этой части:
* Ваддивази 
* Диссендиум  
* Импервиус (это водоотталкивающие чары, а не запретное заклинание)
* Мобилиарбус  
* Нокс  
* Ферула 

![](spells3.jpg)

4) В "Кубке Огня" появляется 21 новое заклинание. Такое количество, скорее всего, связано с конкурсом волшебников. Вот те из них, что были использованы больше двух раз:
* Акцио 
* Диффиндо
* Импедимента (aka "Замри")   
* Приори Инкантатем 
* Редукто
* Репаро
* Сонорус 

![](spells4.jpg)

В отдельную группу мы выделили запретные заклинания, также появившиеся в четвертой части. Вот как менялось отношение к ним:

![](forbid_sp.jpg)

5) В "ордене Феникса" упоминается 11 новых заклинаний. Мы выделили те из них, которые использовались более одного раза:
* Инкарцеро
* Коллопортус 
* Легилименс  
* Протего
* Силенцио   

![](spells5.jpg)

6) В "Принце-полукровке" Гарри Поттер узнает о могущественном заклинании "Сектумсемпра". Его создателем оказался профессор Снегг.

![](snape_sp.jpg)

# Мотивы
* Тема смерти. Чем дальше, тем ее больше:

![](2019-06-04_13-03-24.png)

* Цвета становятся все темнее, придавая трагизма.

![](2019-06-04_13-22-14.png)

* Зла во всех частях стабильно больше, чем  добра, но в последней части оно уже, к нашему удивлению, не так популярно. 

![](2019-06-04_13-05-42.png)

Возможно, причина в победе добра.
* Все говорят, что "Гарри Поттер" - это о дружбе. И это правда, особенно в 1, 2 и 7 частях


![](2019-06-04_13-08-08.png)


# Выводы
Первый вывод, который стоит сделать - цифровые методы в литературе это интересно и весело, особенно если уметь их использовать.
Второй - вселенная Гарри Поттера - не единственная вещь, которую можно не просто читать, но и считать, и визуализировать.
Третий - Digital Humaninties, оказывается, не просто сочетание букв, а область науки, котрая, судя по волшебному шару, будет развиваться.
А еще теперь мы можем хвастаться, что ушли в диджитал и как крутые программисы можем делать корпусные исследования.


![](last_meme.jpg) ![](last_meme_.jpg) 

PS: [ссылочка на "корпус"](https://drive.google.com/open?id=1vjY69vORgXMt14hTy-5TEvv4U-1Qx0ar)
