# Разширена функционалност за Outlook (Outlook extended) #

* Автори: Cyrille Bougot, Ralf Kefferpuetz
* Съвместимост с NVDA: от 2018.3 и по-нови
* Изтегляне на [стабилна версия][1]
* Изтегляне на [тестова версия][2]

Тази добавка подобрява използването на Microsoft Outlook чрез озвучаване на
някои команди и добавяне на допълнителни команди.

## Команди

* От Alt+1 до Alt+9, Alt+0, Alt+-, Alt+=: Съобщава полето на заглавката за
  колоните от 1 до 12 в съобщение, елемент от календара или в прозореца на
  задачите. При двукратно натискане, ако е възможно, премества фокуса в това
  поле. Трикратното натискане копира съдържанието му в клипборда.
* NVDA+Shift+I (настолна подредба) / NVDA+Control+Shift+I (лаптоп подредба):
  Съобщава информационната лента в съобщение, елемент от календара или в
  прозореца на задачите. Двукратното натискане премества фокуса в
  нея. Трикратното натискане копира съдържанието й в клипборда.
* NVDA+Shift+A (настолна подредба) / NVDA+Control+Shift+A (лаптоп подредба):
  Съобщава броя и имената на прикачените файлове в прозореца за
  съобщения. Двукратното натискане премества фокуса в полето с прикачените
  файлове.
* NVDA+Shift+M (настолна подредба) / NVDA+Control+Shift+M (лаптоп подредба):
  Премества фокуса в полето със съдържанието на съобщението.
* Control+Alt+Стрелка наляво и Control+Alt+Стрелка надясно: В списъка с
  резултати от търсенето в адресната книга обхожда полетата на текущо
  избрания ред.
* Control+Q: В списъка със съобщения отбелязва избраното съобщение или група
  от съобщения като прочетени.
* Control+U: В списъка със съобщения отбелязва избраното съобщение или група
  от съобщения като непрочетени.

## Бележки

Всички жестове/команди могат да се променят в диалоговия прозорец на NVDA
"Жестове на въвеждане". Може да пожелаете да промените някои от тях, особено
в следните ситуации:

* Жестовете по подразбиране за отбелязване на съобщения като прочетени или
  непрочетени са тези за версията на Outlook на английски. Ако те се
  различават от тези на Outlook на вашия език, ще трябва да ги промените в
  съответствие.
* Жестовете по подразбиране за четене на заглавките съответстват на Alt,
  комбиниран с клавишите на първия ред на буквено-цифровата клавиатура. Може
  да се наложи да промените жестовете за прочитане на заглавките за колони
  11 и 12, ако символно те не съвпадат с използваната от вас клавиатурна
  подредба.

## Списък с промените

### Версия 1.7

* Обновяване с цел съвместимост с NVDA 2021.1.
* Обновени преводи.

### Версия 1.6

* Отстранени разни проблеми при четене на заглавките на съобщенията в
  Outlook 365.
* Поправена е грешка в скрипта за съобщаване на прикачените файлове при
  използване на брайлова клавиатура.
* Добавена е работна среда за тестване на елементи.
* Обновени преводи.

### Версия 1.5

* Четенето на информационната лента вече работи с NVDA 2019.3.
* Навигацията по таблиците в резултатите от адресната книга вече работи с
  NVDA 2019.3.

### Версия 1.4

* Скриптът за преместване на фокуса в заглавките работи отново.
* Скриптът за придвижване към прикачените файлове вече работи, когато има
  повече прикачени файлове.
* Добавени са нови преводи.

### Версия 1.3

* Поправено е четенето на заглавките на съобщенията за по-новите издания на
  Office 365.
* Обновления с цел поддръжка на по-нови версии на NVDA (съвместимост с
  Python 2 и 3).
* Добавени са нови преводи.
* Изданията вече се изпълняват посредством appveyor.

### Версия 1.2

* Поправено е четенето на заглавката при препращане на срещи.
* Добавени са нови преводи.

### Версия 1.1

* Добавени са нови преводи.

### Версия 1.0

* Първо издание.

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=outlookextended

[2]: https://addons.nvda-project.org/files/get.php?file=outlookextended-dev
