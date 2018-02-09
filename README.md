# grep

grep 'find' /var/log/file.log -A 10 найти искомую строку и отобразить с 10 строками расположенными ниже

grep 'find' /var/log/file.log -B 10 найти искомую строку и отобразить с 10 строками расположенными выше 

grep 'destination_addr: "380507777777"' /var/log/kannel/smsc-bulkness.log -A 10 -B 10    10 строк сверху и снизу

grep 'destination_addr: "380507777777"' /var/log/kannel/smsc-bulkness.log -C 10          то же что и предыдущее

grep -x 'string_one.*string_two' /path/to/file.log -C 10 ищем строку начинающуюся с string_one и заканчивающуюся на string_two
