# Тема 5. Базовые коллекции: множества, списки
Отчет по Теме #5 выполнил:
- Легков Иван Серргеевич
- ПИЭ-21-1

| Задание | Лаб_раб | Сам_раб |
| ------ | ------ | ------ |
| Задание 1 | + | + |
| Задание 2 | + | + |
| Задание 3 | + | + |
| Задание 4 | + | + |
| Задание 5 | + | + |
| Задание 6 | + | |
| Задание 7 | + | |
| Задание 8 | + |  |
| Задание 9 | + |  |
| Задание 10 | + |  |
# Лабараторные работы 
   ## Лабараторная работа 1
   Друзья предложили вам поиграть в игру “найди отличия и убери повторения (версия для программистов)”. Суть игры состоит в том, что на вход программы поступает два множества, а ваша задача вывести все элементы первого, которых нет во втором. А вы как раз недавно прошли множества и знаете их возможности, поэтому это не составит для вас труда.

  ```python
set_1={'White','Black','Red','Pink'}
set_2={'Red','Green','Blue','Red'}
print(set_1 - set_2 )
```
  ### Результат
  ![image](https://github.com/armuane/laba5/blob/main/1.JPG?raw=true)

## Краткий вывод:
Исходные множества:

set_1: {'White', 'Black', 'Red', 'Pink'}
set_2: {'Red', 'Green', 'Blue', 'Red'}
Результат операции set_1 - set_2:

В set_1 есть 'White', 'Black', 'Pink'
'Red' есть в обоих множествах, поэтому он не включается в результат.
Таким образом, на экран будет выведено множество {'White', 'Black', 'Pink'}.


   ## Лабараторная работа 2
Напишите две одинаковые программы, только одна будет использовать set(), а вторая frozenset() и попробуйте к исходному множеству добавить несколько элементов, например, через цикл. 

  ```python
a = set('asdfgh')
#
# print(a)
#
# for i in range(1,5):
#     a.add(i)
# print(a)

# a = frozenset('asdfgh')
#
# print(a)
#
# for i in range(1,5):
#     a.add(i)
# print(a)

```
  ### Результат
  ![image](https://github.com/armuane/laba5/blob/main/2.JPG?raw=true)

## Краткий вывод:
В этом коде создается множество a, содержащее элементы 'a', 'b', 'c', 'd', 'e', 'f', 'g'. Затем в цикле добавляется элемент 'i' в это множество несколько раз.


   ## Лабараторная работа 3
На вход в программу поступает список (минимальной длиной 2 символа). Напишите программу, которая будет менять первый и последний элемент списка

  ```python
def replace(input_list):
#     memory = input_list[0]
#     input_list[0] = input_list[-1]
#     input_list[-1] = memory
#
#     return input_list
#
# print(replace([1,2,3,4,5]))
```
  ### Результат
![image](https://github.com/armuane/laba5/blob/main/3.JPG?raw=true)
## Краткий вывод:
Этот код определяет функцию replace, которая принимает на вход список (input_list). Внутри функции первый элемент списка (input_list[0]) сохраняется в переменной memory. Затем первый элемент списка заменяется последним (input_list[0] = input_list[-1]). Функция возвращает измененный список.


   ## Лабараторная работа 4
На вход в программу поступает список (минимальной длиной 10 символов). Напишите программу, которая выводит элементы с индексами от 2 до 6. В программе необходимо использовать “срез”

  ```python
a = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19]
print(a[2:6])

```
  ### Результат
  ![image](https://github.com/armuane/laba5/blob/main/4.JPG?raw=true)
## Краткий вывод:
В данном коде создается список a, и затем выводится подсписок этого списка, начиная с элемента с индексом 2 и заканчивая элементом с индексом 5 (не включая элемент с индексом 6).


   ## Лабараторная работа 5
Иван задумался о поиске «бесполезного» числа, полученного из списка. Суть поиска в следующем: он берет произвольный список чисел, находит самое большое из них, а затем делит его на длину списка. Студент пока не придумал, где может пригодиться подобное значение, но ищет у вас помощи в реализации такой функции useless()

  ```python
def useless(lst):
#     return max(lst) / len(lst)
#
#
# a = [1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19]
#
# print(useless(a))
```
  ### Результат
  ![image](https://github.com/armuane/laba5/blob/main/5.JPG?raw=true)


 
## Краткий вывод:

Этот код определяет функцию useless, которая принимает на вход список (lst). Функция возвращает результат деления максимального значения в списке на его длину.

   ## Лабараторная работа 6
 Ребята не могут определится каким супергероем они хотят стать. У них есть случайно составленный список супергероев, и вы должны определить кто из ребят будет каким супергероем. Необходимо использовать разделение списков

  ```python
superheroes = ['batman', 'houmlandar', 'onlyman']
#
# kola, ivan, vano = superheroes
#
# print('Kola - ', kola)
# print('Ivan - ', ivan)
# print('Vano - ', vano)
```
  ### Результат
 ![image](https://github.com/armuane/laba5/blob/main/6.JPG?raw=true)


 
## Краткий вывод:
В данном коде создается список superheroes с тремя строковыми элементами. Затем эти элементы распаковываются в три переменные: nikolay, vasiliy, и ivan. И, наконец, значения этих переменных выводятся на экран.

   ## Лабараторная работа 7
Вовочка, насмотревшись передачи “Слабое звено” решил написать программу, которая также будет находить самое слабое звено (минимальный элемент) и удалять его, только делать он это хочет не с людьми, а со списком. Помогите Вовочке с реализацией программы. Подсказка: для этого вам необходимо отсортировать список и удалить значение при помощи pop()

  ```python
a = [234, 4, 45, 656, 56, 65, 656, 77, 44, 63, 78, 897, 234, 123]
#
# a.sort()
#
# print(a)
# a.pop(0)
# print(a)
```
 
# Результат
![image](https://github.com/armuane/laba5/blob/main/7.JPG?raw=true)


 
## Краткий вывод:
a = [-25.8, 86, 12.5, -56, 73.2, 0, 43, -91.5, 65.9, -7]: Создается список a с десятью числовыми элементами.

a.sort(): Список a сортируется в порядке возрастания. После этой операции a будет [ -91.5, -56, -25.8, -7, 0, 12.5, 43, 65.9, 73.2, 86].

print("Отсортированный список:\n", a): Выводится отсортированный список.

a.pop(0): Удаляется первый элемент списка. Теперь a будет [ -56, -25.8, -7, 0, 12.5, 43, 65.9, 73.2, 86].

print("Отсортированный список без наименьшего элемента: \n", a): Выводится отсортированный список без удаленного элемента.


   ## Лабараторная работа 8
Михаил решил создать большой n-мерный список, для этого он случайным образом создал несколько списков, состоящих минимум из 3, а максимум из 10 элементов и поместил их в один большой список. Он также как и Иван не знает зачем ему это сейчас нужно, но надеется на то, что это пригодится ему в будущем.

  ```python
from random import  randint

def list_maker():
#     a = [randint(1, 100)] * randint(3, 10)
#     return a
#
# if __name__ == '__main__':
#     result = []
#     for i in range(randint(1,5)):
#         result.append(list_maker())
#     print(result)

```
  ### Результат
![image](https://github.com/armuane/laba5/blob/main/8.JPG?raw=true)


 
## Краткий вывод:
В этом коде определена функция list_maker(), которая создает список случайной длины от 3 до 10 элементов, где каждый элемент - случайное число от 1 до 100. Затем в основной части программы создается список result, в который добавляются результаты вызова функции list_maker() несколько раз (от 1 до 5 раз).


   ## Лабараторная работа 9
Вы работаете в ресторане и отвечает за статистику покупок, ваша задача сравнить между собой заказы покупателей, которые указаны в разном порядке. Реализуйте функцию superset(), которая принимает 2 множества. Результат работы функции: вывод в консоль одного из сообщений в зависимости от ситуации: 1 - «Супермножество не обнаружено»
2 – «Объект {X} является чистым супермножеством» 
3 – «Множества равны

  ```python
def superset(set1,set2):
#     if set1 > set2:
#         print(f' Обьект ${set1} является супермножеством')
#     elif set1 == set2:
#         print('множества равны')
#     elif set2 > set1:
#         print(f' Обьект ${set2} является супермножеством')
#     else:
#         print('Множество не обнаружено')
#
# if __name__ == '__main__':
#     superset({12,123,44}, {12,123,44})
```
  ### Результат
![image](https://github.com/armuane/laba5/blob/main/9.JPG?raw=true)


 
## Краткий вывод:
def superset(set_1, set_2):: Определяется функция superset, которая сравнивает два множества и выводит информацию о том, является ли одно из них супермножеством другого.

if set_1 > set_2:: Если set_1 является супермножеством set_2 (все элементы set_2 также присутствуют в set_1), то выводится сообщение о том, что set_1 является чистым супермножеством.

elif set_1 == set_2:: Если множества равны, выводится сообщение об этом.

elif set_1 < set_2:: Если set_2 является супермножеством set_1, выводится сообщение о том, что set_2 является чистым супермножеством.

else:: Если ни одно из вышеперечисленного не выполняется, выводится сообщение о том, что супермножество не обнаружено.

if __name__ == '__main__':: Проверяется, запущен ли скрипт напрямую (а не импортирован как модуль).

Вызывается функция superset несколько раз с разными множествами.


   ## Лабараторная работа 10
Предположим, что вам нужно разобрать стопку бумаг, но нужно начать работу с нижней, “переверните стопку”. Вам дан произвольный список. Представьте его в обратном порядке. Программа должна занимать не более двух строк в редакторе кода.

  ```python
my_list=[2,5,8,3]
print(my_list[::-1])
```
  ### Результат
 ![image](https://github.com/armuane/laba5/blob/main/10.JPG?raw=true)


 
## Краткий вывод:
my_list = [2, 5, 8, 3]: Создается список my_list с элементами 2, 5, 8, 3.

my_list[::-1]: Используется срез для создания нового списка, который является обратным порядком элементов из списка my_list. [::-1] означает "взять все элементы с шагом -1", что приводит к обратному порядку.

print(my_list[::-1]): Выводится новый список, который является обратным порядком исходного списка.


# Самостоятельные работы
   ## Самотоятельная работа 1
Ресторан на предприятии ведет учет посещений за неделю при помощи кода работника. У них есть список со всеми посещениями за неделю. Ваша задача почитать: • Сколько было выдано чеков • Сколько разных людей посетило ресторан • Какой работник посетил ресторан больше всех раз Список выданных чеков за неделю: [8734, 2345, 8201, 6621, 9999, 1234, 5678, 8201, 8888, 4321, 3365, 1478, 9865, 5555, 7777, 9998,1111, 2222, 3333, 4444, 5556, 6666, 5410, 7778, 8889, 4445, 1439, 9604, 8201, 3365, 7502, 3016, 4928, 5837, 8201, 2643, 5017, 9682, 8530, 3250, 7193, 9051, 4506, 1987, 3365, 5410, 7168, 7777, 9865, 5678, 8201, 4445, 3016, 4506, 4506] Результатом выполнения задачи будет: листинг кода, и вывод в консоль, в котором будет указана вся необходимая информация.

  ```python


a = [8734, 2345, 8201, 6621, 9999, 1234, 5678, 8201, 8888, 4321, 3365,
# 1478, 9865, 5555, 7777, 9998, 1111, 2222, 3333, 4444, 5556, 6666,
# 5410, 7778, 8889, 4445, 1439, 9604, 8201, 3365, 7502, 3016, 4928,
# 5837, 8201, 2643, 5017, 9682, 8530, 3250, 7193, 9051, 4506, 1987,
# 3365, 5410, 7168, 7777, 9865, 5678, 8201, 4445, 3016, 4506, 4506]
#
#
# print(len(a))
# b = set(a)
#
# print(len(b))
# c = []
#
# for i in a:
#     c.append(a.count(i))
#
# for i in a:
#     if a.count(i) == max(c):
#         print(i)
#         break


```
  ### Результат
![image](https://github.com/armuane/laba5/blob/main/11.JPG?raw=true)


 
## Краткий вывод:
Выводится количество элементов в списке a.
Создается множество b с уникальными элементами из списка a.
Выводится количество уникальных элементов в множестве b.
Инициализируется пустой список c.
Выполняется первый цикл for i in a, подсчитываются повторения каждого элемента i в списке a, результаты добавляются в список c.
Выполняется второй цикл for i in a. Если количество повторений элемента i равно максимальному количеству повторений в списке c, то выводится этот элемент, и цикл прерывается.

  ## Самотоятельная работа 2
На физкультуре студенты сдавали бег, у преподавателя физкультуры есть список всех результатов, ему нужно узнать • Три лучшие результата • Три худшие результата • Все результаты начиная с 10 Ваша задача помочь ему в этом. Список результатов бега: [10.2, 14.8, 19.3, 22.7, 12.5, 33.1, 38.9, 21.6, 26.4, 17.1, 30.2, 35.7, 16.9, 27.8, 24.5, 16.3, 18.7, 31.9, 12.9, 37.4] Результатом выполнения задачи будет: листинг кода, и вывод в консоль, в котором будет указана вся необходимая информация.
 ```python
# a = [10.2, 14.8, 19.3, 22.7,12.5, 33.1,38.9, 21.6, 26.4, 17.1, 30.2,35.7, 16.9,
27.8, 24.5, 16.3, 18.7, 31.9, 12.9, 37.4]

a.sort()
print(a[-1])
print(a[-2])
print(a[-3])
print('-----------')
print(a[0])
print(a[1])
print(a[2])
print('---------')
print(a[10:])

```

  ### Результат
![image](https://github.com/armuane/laba5/blob/main/12.JPG?raw=true)
## Краткий вывод:
Этот код использует функцию sorted() для сортировки списка результатов бега. Затем мы используем срезы для выбора три лучших и три худших результатов, а также всех результатов начиная с 10-го.
 ## Самотоятельная работа 3
Преподаватель по математике придумал странную задачку. У вас есть три списка с элементами, каждый элемент которых – длина стороны треугольника, ваша задача найти площади двух треугольников, составленные из максимальных и минимальных элементов полученных списков. Результатом выполнения задачи будет: листинг кода, и вывод в консоль, в котором будут указаны два этих значения. Три списка:
one = [12, 25, 3, 48, 71] two = [5, 18, 40, 62, 98] three = [4, 21, 37, 56, 84]
```python
one = [12, 25, 3, 48, 71]
two = [5, 18, 40, 62, 98]
three = [4, 21, 37, 56, 84]

a = max(one)
b = max(two)
c = max(three)
p = (a + b + c) / 2
MaxS = math.sqrt(p*(p-a)*(p-b)*(p-c))
print(MaxS)

a1 = min(one)
b1 = min(two)
c1 = min(three)
p = (a1 + b1 + c1) / 2
MinS = math.sqrt(p*(p-a1)*(p-b1)*(p-c1))
print(MinS)

```
![image](https://github.com/armuane/laba5/blob/main/13.JPG?raw=true)
## Краткий вывод:
Этот код использует формулу Герона для вычисления площади треугольника по длинам его сторон. Затем мы находим минимальные и максимальные значения в каждом из трех списков и вычисляем площади треугольников, составленных из минимальных и максимальных элементов.

  ## Самотоятельная работа 4
  Никто не любит получать плохие оценки, поэтому Борис решил это исправить. Допустим, что все оценки студента за семестр хранятся в одном списке. Ваша задача удалить из этого списка все двойки, а все тройки заменить на четверки. Списки оценок (проверить работу программы на всех трех вариантах): [2, 3, 4, 5, 3, 4, 5, 2, 2, 5, 3, 4, 3, 5, 4] [4, 2, 3, 5, 3, 5, 4, 2, 2, 5, 4, 3, 5, 3, 4] [5, 4, 3, 3, 4, 3, 3, 5, 5, 3, 3, 3, 3, 4, 4] Результатом выполнения задачи будет: листинг кода, и вывод в консоль, в котором будут три обновленных массива


  ```python
a = [2,2,2,2,2,2,2,2,2,2,2,2,2,3,3,3,3,3,3,4,4,4,4,4,4,5,5,5]
b = []
a.sort()
for i in a:
    if i != 2:
        b.append(i)


print(b)

for i in range(len(b)):
    if b[i] == 3:
        b[i] = 4

print(b)

```
### Результат
![image](https://github.com/armuane/laba5/blob/main/14.JPG?raw=true)

## Краткий вывод:
Список a сортируется по возрастанию.
Создается пустой список b.
В цикле for i in a каждый элемент, отличный от 2, добавляется в список b.
Затем в цикле for i in range(len(b)) каждый элемент списка b сравнивается с числом 3, и если элемент равен 3, то он заменяется на 4.
Таким образом, первый цикл создает список b, содержащий все элементы из списка a, кроме 2. Второй цикл заменяет все вхождения числа 3 в списке b на число 4. На выходе будет список b, в котором все числа 3 заменены на 4


## Самотоятельная работа 5
Вам предоставлены списки натуральных чисел, из них необходимо сформировать множества. При этом следует соблюдать это правило: если какое-либо число повторяется, то преобразовать его в строку по следующему образцу: например, если число 4 повторяется 3 раза, то в множестве будет следующая запись: само число 4, строка «44», строка «444». Множества для теста: list_1 = [1, 1, 3, 3, 1] list_2 = [5, 5, 5, 5, 5, 5, 5] list_3 = [2, 2, 1, 2, 2, 5, 6, 7, 1, 3, 2, 2] Результаты вывода (порядок может отличаться, поскольку мы работаем с set()): {'11', 1, 3, '33', '111'} {5, '5555', '555555', '55555', '555', '55', '5555555'}  {'11', 1, 3, 2, 5, 6, '222222', '222', 7, '2222', '22222', '22'}
  ```python
def process_list(input_list):
    result_set = set()
    for num in set(input_list):
        count = input_list.count(num)
        if count > 1:
            result_set.add(str(num) * count)
        else:
            result_set.add(num)
    return result_set

# Три списка натуральных чисел
list_1 = [1, 1, 3, 3, 1]
list_2 = [5, 5, 5, 5, 5, 5, 5]
list_3 = [2, 2, 1, 2, 2, 5, 6, 7, 1, 3, 2, 2]

# Обработка списков
result_1 = process_list(list_1)
result_2 = process_list(list_2)
result_3 = process_list(list_3)

# Вывод результатов
print(result_1)
print(result_2)
print(result_3)

```
  ### Результат
![image](https://github.com/armuane/laba5/blob/main/15.JPG?raw=true)


 
## Краткий вывод:
Этот код создает функцию process_list, которая обрабатывает список натуральных чисел в соответствии с указанными правилами и возвращает соответствующее множество. Затем эта функция вызывается для каждого из трех списков.
решении задач по теме множества и операции с ними использовались различные аспекты работы с множествами, такие как операции над множествами, создание множеств, обход элементов множества, сортировка, использование условий и функций для обработки данных.


В некоторых задачах использовались стандартные модули Python, такие как math, для выполнения математических и коллекционных операций.
Циклы и условия:

В коде присутствовали циклы для обработки элементов списка и условия для проверок и принятия решений.
Работа с множествами в Python предоставляет множество удобных инструментов для обработки данных. Операции над множествами, условия, циклы и использование функций помогают решать разнообразные задачи, начиная от простых операций с элементами до сложных математических вычислений.
