#cgrep

grep 'find' /var/log/file.log -A 10 найти искомую строку и 10 строк расположеных ниже

grep 'find' /var/log/file.log -B 10 найти искомую строку и 10 строк расположеных выше 

grep 'destination_addr: "380507777777"' /var/log/kannel/smsc-bulkness.log -A 10 -B 10    10 строк сверху и снизу

grep 'destination_addr: "380507777777"' /var/log/kannel/smsc-bulkness.log -C 10          то же что и предыдущее
