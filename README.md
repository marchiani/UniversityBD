# Проект на тему система управління базами даних
## Учасники:
* Бойченко Дмитро (Team Lead)
* Андріанов Микита
* Грисюк Михайло
* Чорноморець Владислав
* Матвійчук Андрій
 
# Визначення СУБД
**Система управління базами даних (СУБД) або database management system** (*[DBMS](https://searchsqlserver.techtarget.com/definition/database-management-system)*) - це системне програмне забезпечення для створення та управління базами даних. СУБД надає користувачам та програмістам систематичний спосіб створення, отримання, оновлення та управління даними. 

![](https://itknowledgeexchange.techtarget.com/overheard/files/2015/01/DBMS-database-management-system.png)

*СУБД* дозволяє кінцевим користувачам створювати, читати, оновлювати та видаляти дані в базі даних. СУБД, по суті, служить інтерфейсом між базою даних та кінцевими користувачами чи прикладними програмами, забезпечуючи послідовну організацію даних та доступність їх легкодоступних.

# Data life cycle
![](https://roaringelephant.org/wp-content/uploads/sites/5/2019/01/lifecycle-management.png)

**Життєвий цикл даних** (*[Data life cycle](https://whatis.techtarget.com/definition/data-life-cycle)*) - це послідовність етапів, через які певна одиниця даних проходить від свого початкового генерування або захоплення до її можливого архівного та/або видалення наприкінці строку корисного використання. 

Хоча специфіка відрізняється, фахівці з управління даними часто визначають шість або більше етапів життєвого циклу даних. Ось один приклад:

1. *Генерація або захоплення*. На цій фазі дані надходять в організацію, як правило, шляхом введення даних, отримання із зовнішнього джерела або прийому сигналу, наприклад переданих датчиків даних.

2. *Технічне обслуговування*. На цій фазі дані обробляються до її використання. Дані можуть бути піддані таким процесам, як  інтеграція , очищення та завантаження екстракту-трансформації.

3. *Активне використання*. На цій фазі дані використовуються для підтримки цілей та операцій організації.

4. *Публікація*. На цій фазі дані не обов'язково стають доступними для широкої громадськості, а просто надсилаються поза організацією. Публікація може бути або не бути частиною життєвого циклу для певної одиниці даних.

5. *Архівування*. На цій фазі дані вилучаються з усіх активних виробничих середовищ. Він більше не обробляється, не використовується або публікується, але зберігається у випадку, якщо це буде потрібно знову в майбутньому.

6. *Чистка*. У цій фазі видаляється кожна копія даних. Як правило, це виконується на даних, які вже архівуються.

Управління життєвим циклом даних набуває все більшого значення після вибуху великих даних та постійного розвитку Інтернету речей. Величезні обсяги даних генеруються завдяки зростаючій кількості пристроїв у всьому світі. Правильний нагляд за даними протягом його життєвого циклу є важливим для оптимізації його корисності та мінімізації потенціалу помилок. Нарешті, архівування або видалення даних наприкінці терміну їх експлуатації гарантує, що воно не споживає більше ресурсів, ніж потрібно.

# Data Source
![][image1]
![][image2]

[image1]: https://upload.wikimedia.org/wikipedia/commons/7/77/Icon_New_File_256x256.png
[image2]: https://upload.wikimedia.org/wikipedia/commons/e/e2/Spreadsheet.png

**Джерело данних** (*[Data Source](https://www.techopedia.com/definition/30323/data-source)*) у контексті інформатики та комп’ютерних програм - це місце, звідки беруться дані, які використовуються. У системі управління базами даних основним джерелом даних є база даних, яка може бути розміщена на диску або віддаленому сервері. Джерелом даних для комп'ютерної програми можуть бути файл, опис даних, електронна таблиця, XML-файл або навіть жорстко закодовані дані в межах програми.

Джерела даних можуть відрізнятися залежно від заявки чи галузі. Комп'ютерні програми можуть мати кілька джерел даних, залежно від їх призначення та функції. Такі програми, як системи управління реляційними базами даних і навіть веб-сайти, використовують бази даних як основні джерела даних. Апаратні засоби, такі як пристрої введення та датчики, використовують середовище як основне джерело даних. Хорошим прикладом є система контролю температури та тиску для системи циркуляції рідини, наприклад, тієї, що використовується на заводах і на нафтопереробних заводах, які беруть усі супутні дані з навколишнього середовища або що б там не було; тому джерелом даних тут є середовище. Такі дані, як температура і тиск рідини, датчики приймаються регулярно і потім зберігаються в базі даних.

Джерело даних найчастіше використовується в контексті з базами даних та системами управління базами даних або будь-якою системою, яка в першу чергу займається даними, і називається ім'ям джерела даних (DSN), яке визначено в додатку, щоб воно могло знайти місцеположення даних. Це просто означає, що означають слова: звідки беруться дані.

# Data set
![](http://docs.akana.com/ev/envision_reference/images/env_intro_dataset1.jpg)

**Набір даних** (*[Data set](https://en.wikipedia.org/wiki/Data_set)*) - колекція однотипних даних, що застосовується в задачах машинної обробки даних.

Найчастіше набір даних відповідає змісту однієї таблиці бази даних або статистичній матриці даних, де кожна з колонок таблиці містить однорідні значення, а кожен з рядків таблиці відповідає певному члену набору даних.

Термін набір даних також використовується при визначенні даних в сукупності тісно пов'язаних таблиць, зображень тощо, що описують результати конкретного експерименту або подію. Прикладом такого типу є набори даних, зібрані космічними агентствами, що виконують експерименти з приладами на борту космічного зонда, або світлини, передані з космосу.

Окремі набори даних широко використовуються в академічних колах як тестові набори, що підтверджують результати наукових досліджень.

# DDF
## Вступ до DDF
**[DDF](https://open-numbers.github.io/ddf.html)** - це модель даних для спільної гармонізації багатовимірної статистики.
*	**Модель даних** DDF - це модель даних, тобто вона описує спосіб організації даних та визначення того, як частини даних співвідносяться один з одним.
*	**Узгодження** DDF може використовуватися для узгодження даних, тобто воно може поєднувати дані з різних джерел в інтегровані, послідовні та однозначні набори даних. DDF підтримує практичний робочий процес, який призводить до простого обслуговування та постійно зростаючої колекції порівнянних даних.
*	**Спільна робота** DDF - це загальна модель даних у відкритих числах. Відкриті номери - це ініціатива збору та узгодження світових даних.
*	**Багатовимірна статистика** DDF призначена для зберігання статистики з декількома вимірами. Наприклад, населення в країні та році, а також по країні, році, статі та віковій групі.

## Всесвіт DDF
Щоб ефективно використовувати DDF, він постачається з форматами даних та мовою запитів.

### Модель: DDF
Як було сказано вище, DDF - це модель даних. Це система організації даних та визначення того, як частини даних співвідносяться один з одним. Сам DDF не визначає формат, в якому зберігаються дані. Не має значення, чи зберігається він у csv-файлах, базі даних SQL чи базі даних. Іншими словами: DDF - це концептуальна модель.

### Формати: DDFcsv та DDFmongo
Однак концептуальної моделі недостатньо для прагматичного використання.  DDF потребує формату даних. Для двох різних цілей було визначено два формати: DDFcsv та DDFmongo .
*	**DDFcsv** - це табличне подання даних DDF у відомому форматі значень, розділених комами (csv). DDFcsv легко працювати з людьми, які знайомі з табличними даними та дозволяють легко трансформуватися з інших табличних моделей в DDF. Це покликане читати і люди, і машини. Це формат, який використовується у Відкритих номерах.
*	**DDFmongo** - це представлення документа DDF в базі даних mongo. Це використовується для сторінки інструментів Gapminder. Цей формат ще не задокументований.
Надалі цілком можливо, що DDF буде представлений в інших форматах для різних цілей.

## DDFcsv
DDF - модель даних, яка використовується Gapminder Foundation для структурування своїх даних в рамках ініціативи відкритих номерів. Модель даних може бути представлена багатьма способами. В даний час він представлений як у форматі документа, який називається DDFmongo, так і в табличному форматі csv під назвою DDFcsv.

### Шлях файлу
Точки даних, сутності, поняття та метадані, які можна знайти в файлах, визначені у розділі ресурсів файлу datapackage.json. Це точка входу для будь-якої машини, яка хоче вивчити набір даних. Цей файл завжди буде названий: datapackage.json і повинен бути розміщений у кореневій папці набору даних.

Назви файлів у цьому документі - лише вказівки. Це забезпечує послідовне, систематичне називання файлів у кожному наборі даних DDF, що робить їх легким для розуміння та дослідження будь-яким новим у наборі даних. Це також дозволяє автоматично створити файл datapackage.json за допомогою одного з наших інструментів.

### Структура файлу
Всі файли DDFcsv, що містять дані, починаються з
	
	ddf-- <collection>
	
Де

	<collection> - це збір даних, який цей файл містить. Це може бути одна і лише одна з: точок даних, сутностей, понять або метаданих.
	
Файли DDFcsv обов’язково розміщуватись у кореневому каталозі або у підкаталозі кореня набору даних. Однак їх не може бути розміщено в каталозі /lang/. Цей каталог зарезервований для перекладів.

Файли у форматі csv із обов'язковим рядком заголовка у першому рядку. Кодування обов'язково має бути UTF-8. Відсутні або відсутні дані повинні бути представлені порожнім полем.

Всі дані в DDF представлені парами ключ-значення. Один файл може містити дані лише з одним ключем. У різних колекціях ніколи немає одного ключа.

Різні колекції ніколи не можуть бути в одному файлі.

## DataPoints

DataPoint - пара ключових значень, яка зберігає те, як змінюються показники в різних розмірах. Наприклад, як змінюється чисельність населення за роками та країнами.

### File name
Точки даних у DDFcsv зберігаються у файлах, названих із таким малюнком:
	
	ddf--datapoints--<indicators>--by--<dimensions>.csv

Де

	<indicators> - це список показників у цьому файлі.
	<dimensions> - це список розмірів у цьому файлі.

Кожен параметр у списку розмірів має такий малюнок:
	
	<dimension>[-<values>]

Де

	<dimension> - концепція цього виміру.
	<values> - вичерпний перелік значень цього виміру, знайдених у цьому файлі.

Наприклад:

	ddf--datapoints--population--by--geo--year.csv
	ddf--datapoints--gdp--gdp_per_cap--by--geo--year--gender.csv
  	ddf--datapoints--population--by--geo-usa-swe--year.csv
  	ddf--datapoints--population--by--geo--year-2000.csv
  	ddf--datapoints--population--by--geo-ukr--year-2001.csv

### Структура файлу
DataPoints - пари ключових значень з одним або кількома вимірами (ключ) та одним показником (значення).

Загальне правило лише одного ключа в одному файлі також застосовується до DataPoints. Один файл може містити лише точки DataPoint з тим самим одним ключем, тобто тим самим набором розмірів. Для цих розмірів в одному файлі може бути кілька індикаторів, оскільки вони не є частиною ключа.

# Відкриті дані

**[Відкриті дані](https://uk.wikipedia.org/wiki/Відкриті_дані)** - це концепція, за якою певні дані мають бути вільними для використання та розповсюдження будь-якою особою, за умов дотримання правил атрибуції share-alike ліцензії.

Концепція відкритості даних загалом не нова, але її активне поширення почалось з розвитком інформаційних технологій та Інтернету.

Cеред множини відкритих даних окрема увага приділяється відкритим державним даним, як інструменту оцінки та контролю роботи влади та держави, що входить до моделі електронного уряду.

В багатьох країнах світу розвиток відкритих державних даних підтримується на державному рівні досить давно. І цей процес включає створення відповідної законодавчої бази, виконавчих органів та інформаційних ресурсів.

### США
<img src="https://upload.wikimedia.org/wikipedia/commons/a/a4/Flag_of_the_United_States.svg" alt="США" width="400"/>

У США цілеспрямований розвиток області відкритих державних даних почався у 2009 році зі створення ресурсу [Data.gov](https://uk.wikipedia.org/wiki/Data.gov) та оприлюднення Директиви Відкритого Уряду США. В свою чергу, ці ініціативи були продовженням політики розбудови [електронного уряду](https://uk.wikipedia.org/wiki/%D0%95%D0%BB%D0%B5%D0%BA%D1%82%D1%80%D0%BE%D0%BD%D0%BD%D0%B8%D0%B9_%D1%83%D1%80%D1%8F%D0%B4) США, що впроваджується з 2002 року.

### Європейський союз
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b7/Flag_of_Europe.svg/1024px-Flag_of_Europe.svg.png" alt="Європейський союз" width="400"/>

В Європі, разом із національними, існує багато загальноєвропейських програм підтримки та розвитку відкритих даних і відповідних ресурсів, що фінансуються за рахунок коштів ЄС. Тут можна згадати проекти DOPA, що розвивається в рамках програми [Seventh Framework Programme](https://cordis.europa.eu/fp7/home_en.html) [Європейської комісії](https://uk.wikipedia.org/wiki/%D0%84%D0%B2%D1%80%D0%BE%D0%BF%D0%B5%D0%B9%D1%81%D1%8C%D0%BA%D0%B0_%D0%BA%D0%BE%D0%BC%D1%96%D1%81%D1%96%D1%8F).

### Росія
<img src="https://upload.wikimedia.org/wikipedia/commons/f/f3/Flag_of_Russia.svg" alt="Росія" width="400"/>

Щодо країн СНГ та України, зокрема, то найбільшу активність в даному напрямі демонструє Росія.

Так влітку 2013 року був прийнятий [федеральний закон № 112-ФЗ](https://web.archive.org/web/20140804152026/http://xn--d1abbgf6aiiy.xn--p1ai/%D0%B4%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D1%8B/18302), що вводить поняття відкритих даних та визначає порядок їх оприлюднення на державних ресурсах.

# Приклади Відкритих Баз Даних
На сьогоднішній день важливу частину для існування і просування даних є база даних, також відома як СУБД. За допомогою неї більшість підприємств, компаній і організацій аналізують якусь інформацію для прогнозу певного результату.
Одним з таких БД може бути **Google Dataset Search**. Цей движок надає необхідний **ІНСТРУМЕНТ** для знаходження **ВІДКРИТИХ** Баз Даних.

![](https://i.ibb.co/Y0tysqZ/1.png)

Наприклад, ми можемо дізнатися інформацію за коефіцієнтом дитячої смерті в Україні, яка знаходиться у відкритому доступі для будь-якого користувача.

![](https://i.ibb.co/Zfchh3T/2.png)

Як ми бачимо, **Google Dataset Search** надає нам доступ до кількох баз даних, які пов'язані між собою однією спільною темою. Користувачеві надається можливість вибору необхідного йому БД, за кількома параметрами.

![](https://i.ibb.co/Qc4sYyz/3.png)

Перейшовши за необхідним посиланням [Україна - коефіцієнт смертності дітей](https://knoema.ru/atlas/%D0%A3%D0%BA%D1%80%D0%B0%D0%B8%D0%BD%D0%B0/topics/%D0%97%D0%B4%D1%80%D0%B0%D0%B2%D0%BE%D0%BE%D1%85%D1%80%D0%B0%D0%BD%D0%B5%D0%BD%D0%B8%D0%B5/%D0%A1%D0%BE%D1%81%D1%82%D0%BE%D1%8F%D0%BD%D0%B8%D0%B5-%D0%B7%D0%B4%D0%BE%D1%80%D0%BE%D0%B2%D1%8C%D1%8F/%D0%9A%D0%BE%D1%8D%D1%84%D1%84%D0%B8%D1%86%D0%B8%D0%B5%D0%BD%D1%82-%D0%BC%D0%BB%D0%B0%D0%B4%D0%B5%D0%BD%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B9-%D1%81%D0%BC%D0%B5%D1%80%D1%82%D0%BD%D0%BE%D1%81%D1%82%D0%B8) 
ми потрапляємо на сайт, який показує найнеобхіднішу інформацію на наш запит. Ці дані, в основному, можуть бути представлені у вигляді якихось таблиць, діаграм, схем і т.д.

![](https://i.ibb.co/KDfnKCd/4.png)

Завдяки такому формату зберігання даних, користувач з легкістю може розібратися в ситуації та оцінити необхідні йому дані.
>Якщо ми перейдемо на їх основний сайт і відкриємо вкладку  **[Бази Даних](https://knoema.ru/atlas)**  то нам буде забезпечено повний список все-можливих джерел інформації, звідки були взяті необхідні дані з потрібними схемами. Також користувачеві надається невелика частина даних для ознайомлення.

![](https://i.ibb.co/sJTHDMg/5.png)

Такі БД зберігають інформацію протягом тривалого часу, в наслідок чого, пізніше, можуть бути модифікованні для розширення своєї функціональності в подальшому. Так-же, це не єдина БД яка може надавати доступ до таких даних. Наприклад можемо взяти **[Google Public Data](https://www.google.com/publicdata/explore?ds=d5bncppjof8f9_&hl=en_US&dl=en_US#!ctype=l&strail=false&bcs=d&nselm=h&met_y=employment&fdim_y=gdp_production_component:2&scale_y=lin&ind_y=false&rdim=region&idim=region:NAC:MEA:LCN:ECS:EAS:SAS:SSF&ifdim=region&tdim=true&hl=en_US&dl=en_US&ind=false)**, який також відображує можливість пошуку потрібних даних.

![](https://i.ibb.co/VHy0dGp/6.png)

Все це показує, що БД спирається на якісь джерела інформації, факти, експерименти і т.д, для більш точного прогнозування інформації про той чи інший продукт. У світі існують різні БД, які надають дані по необхіднії інформації для різних цілей. Наприклад, як показано на малюнку вище, даний БД відображає відомості про статистику продуктів, що випускаються в світі або в якихось певних територіях землі за певний проміжок часу.
>Але, невже тільки спеціальні пошукові бази можуть надавати нам такі дані? **Відповідь: НІ**.

Наприклад такий сайт як **[GapMinder](https://www.gapminder.org/)** надає користувачеві якийсь набір даних, які можуть бути відображені у вигляді цікавих відео від **TedTalk** або деяких інструментів, які також представляють інформацію але в своєму стилі, більш захоплюючим.

![](https://i.ibb.co/3FSTFfc/7.png)
