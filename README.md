meteoboard-project
==================

Библиотеки для работы с устройством измерения условий внешней среды(температура, влажность, давление и др.)

Репозиторий содержит библиотеку для языка GNU C (Ubuntu 12.10) и Python 2.7 (Win7)

<p><b>rs232.c</b> - файл содержит функции необходимые для работы с COM-портами в linux </p>   
<p><b>meteoboardlib.c</b> - файл содержит необходимые функции для работы непосредственно с устройством</p>
<p><b>main.c</b> - использует библиотеку meteoboardlib.c и выводит данные с устройства в консоль linux</p>
<p><b>MeteoBoardlib.py</b> - файл содержит необходимые функции для работы с устройством (win7)</p>
<p><b>csv_import_test.py</b> - файл использует библиотеку MeteoBoardlib.py, считывает данные с устройства и записывает их в csv файл в виде таблицы

