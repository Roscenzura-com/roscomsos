Роскомсос - PHP скрипт для определения IP Роскомнадзора и других российских госорганов.

Скрипт практически не создает нагрузки на сайт, причем размера базы IP адресов не имеет значения - скрипт будет одинаково быстро работать с базами любых размеров. Дело в том, что скрипт сначала проверяет наличие файла, содержащего три первых байта IP пользователя (что соответствует маске 255.255.255.0) и только потом проверяет на соответствие более узкому диапазону IP (содержится в файле).  
