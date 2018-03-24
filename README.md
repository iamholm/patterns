# ШАБЛОНЫ (patterns)
шаблоны для программы АРМ-Предварительное расследование (и модуля Шаблонщи_к).
Данный репозиторий сделан для удобства разработки, обновления, обмена шаблонами документов для уголовного дела и других которые будет возможно создавать из программы АРМ-Предварительное расследование (пока только из модуля Шаблонщи-к)

# список принятых ключей
сохранен в файле "ключи"

# документы 
чистые без ключей лежат в папке document_origin

# шаблоны
лежат в папке patterns. 
внутри несколько папок - документы по службам (следствие, дознание и д.р.)
- SO - следствие
- OD - дознание 
- UR - уголовный розыск
- UU - участковые
(список не окончательный)

# установка
скопируйте папку с интересующей службой из папки patterns себе на компьютер и перенесите ее содержимое к себе в папку patterns в программе
! в тестовый модуль управления шаблонами функцию автоматического добавления шаблонов из данного репозитория 
  добавлю немного позднее, пока что ручками придется внести данные в модуль

# требования к шаблонам
1. Ключи замены текста необходимо указывать в квадратных скобках, например: [КЛЮЧ] 
2. Использовать ключи которые уже имеются (см. список ключей), если ключа нет, то можно добавить свой, следуя следующим правилам:
 - Из ключа должно быть понятно на текст какого содержания он будет заменен.
 - Ключ не должен содержать пробелов, заменяйте пробел символом _ (нижнее подчеркивание).
 - Ключ должен быть написан большими буквами.
 - некоторые данные используются в различных падежах, для указания падежа добавляйте к ключу подчеркивание _ и код: 
    - ИП для именительного падежа (кто)
    - РП для родительного падежа (кого)
    - ДП для дательного падежа (кому)
    - НП для направительного падежа (куда) (вроде так называется)
    - ТП для творительного падежа (кем) (тоже за правильность название не уверен)
      (список падежей не окончательный, если надо будем добавлять)
  - Текст во время замены вставляется с приминением стилей установленых для первой буквы ключа
3. Шаблоны должны быть сохранены в формате docx. Формат doc является достаточно проблематичным и на текущий момент нет нормально работающюго способа работы с данным форматом. Ограничений к содержимому текста в шаблоне нет. Текст может быть как в таблицах так и простым текстом. 
4. Таблицы необходимо использовать только в случае позиционирования текста (например как в угловом штампе), в остальных случаях пользуйтесь отступами, табуляцией, Большие тексты вложенные в таблицу приведут к перемещению таблицы на новый лист. 

# как добавить шаблоны
0. зарегистрируйтесь на сайте, это не сложно (и пройдите обучение [желательно если вы не знаете как пользоваться сайтом])
1. создайте ветку
2. добавте шаблоны
3. объедините ветку с репозиторием 

# как изменить шаблоны
1. создайте ветку
2. измените шаблон
3. объедините ветку с репозиторием

