#################################
Домашнее задание 4 [https://stepik.org/lesson/1244182/step/1?unit=1257999] 

Декораторы
       Один из базовых принципов разработки любой программы  довольно прост – «не повторяйтесь» (DRY, dont' repeat yourself). Код с большим количеством повторений трудно модифицируем и читаем. Элегантное решение состоит в обращении к метапрограммированию, когда программы могут работать с другими программами как со своими данными. Например, порой возникает необходимость изменять существующую функцию, не меняя при этом ее исходный код.

  Познакомимся с тем, как для этих целей применяются декораторы:

ведение протокола операций (журналирование);
обеспечение контроля за доступом и аутентификацией; 
хронометраж; 
ограничение частоты вызова API; 
кэширование и другие.