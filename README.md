# grep

grep 'find' /path/to/file.log -A 10           найти строку find и отобразить с 10 строками расположенными ниже

grep 'find' /path/to/file.log -B 10           найти строку find и отобразить с 10 строками расположенными выше 

grep 'find' /path/to/file.log -A 10 -B 10     10 строк сверху и снизу

grep 'find' /path/to/file.log -C 10           то же что и предыдущее

grep -x 'string_one.*string_two' /path/to/file.log -C 10 ищем строку начинающуюся с string_one и заканчивающуюся на string_two
