# laba5

условие

![image](https://github.com/KseniyaMaystrenko/laba5/assets/152999073/5c35316c-6144-4582-9bd8-145f0812e8eb)


![image](https://github.com/KseniyaMaystrenko/laba5/assets/152999073/8d4decae-880d-4341-8f02-daa88a38a1d2)


Объяснение решения:

Программа представляет собой генератор простых чисел, который создает указанное пользователем количество простых чисел в определенном диапазоне. Для проверки чисел на простоту используется функция isprime() из модуля sympy. 
Концепция генератора заключается в том, что он генерирует простое число, которое удовлетворяет условиям, затем передает его в основную программу и продолжает генерировать дальше, не храня все сгенерированные числа в памяти. Это значительно экономит ресурсы и позволяет эффективно работать с большим количеством чисел.
Пользователю предлагается ввести начальный и конечный диапазоны для генерации простых чисел, а также указать желаемое количество чисел. Далее, каждое сгенерированное простое число добавляется в список для последующих вычислений. 
Далее, программа суммирует все числа, которые были сгенерированы и сохранены в списке, используя функцию reduce() с использованием лямбда-функции для выполнения операции суммирования. 
В итоге, программа выводит на экран сгенерированный список простых чисел и их общую сумму. Это демонстрирует использование функций из модуля functools, таких как reduce, для манипуляций с данными списков. В данном случае, программа позволяет создавать простые числа и работать с ними эффективным способом, используя функциональное программирование и концепцию генераторов.
ответ:

!![image](https://github.com/KseniyaMaystrenko/laba5/assets/152999073/ea7dd031-dbd3-4a53-bffb-a07698b60578)


используемые ресурсы:

[Генераторы списков, множеств и словарей](https://youtu.be/MFo7PMH87oY?feature=shared)
