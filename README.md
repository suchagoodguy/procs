# procs
iotest выполняет заполнение одновременно двух файлов размером 256 МиБ нолями с разными приоритетами ввода-вывода.
iotests запускать через sudo, ибо ionice требует прав суперпользователя
iotests.log содержит результат выполнения

cputest считает одновременно два 20000! с разными приоритетами процессора
cputest.log содержит результат выполнения
