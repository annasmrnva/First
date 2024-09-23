# Тема 5. Базовые коллекции: строки и списки. 
Отчет по Теме #5 выполнил(а):
- Смирнова Анна Евгеньевна
- ИВТ-22-2

| Задание | Лаб_раб | Сам_раб |
| ------ | ------ | ------ |
| Задание 1 | + | + |
| Задание 2 | + | + |
| Задание 3 | + | + |
| Задание 4 | + | + |
| Задание 5 | + | + |
| Задание 6 | + | - |
| Задание 7 | + | - |
| Задание 8 | + | - |
| Задание 9 | + | - |
| Задание 10 | + | - |


знак "+" - задание выполнено; знак "-" - задание не выполнено;

Работу проверили:
- к.э.н., доцент Панов М.А.

## Лабораторная работа №1
Друзья предложили вам поиграть в игру “найди отличия и убери повторения (версия для программистов)”. Суть игры состоит в том, что на вход программы поступает два множества, а ваша задача вывести все элементы первого, которых нет во втором. А вы как раз недавно прошли множества и знаете их возможности, поэтому это не составит для вас труда.

### Результат.
![Меню]()

## Лабораторная работа №2
Напишите две одинаковые программы, только одна будет использовать set(), а вторая frozenset() и попробуйте к исходному множеству добавить несколько элементов, например, через цикл.

### Результат.
![Меню]()

## Лабораторная работа №3
На вход в программу поступает список (минимальной длиной 2 символа). Напишите программу, которая будет менять первый и последний элемент списка.

### Результат.
![Меню]()

 
## Лабораторная работа №4
На вход в программу поступает список (минимальной длиной 10 символов). Напишите программу, которая выводит элементы с индексами от 2 до 6. В программе необходимо использовать “срез”.

### Результат.
![Меню]()

## Лабораторная работа №5
Иван задумался о поиске «бесполезного» числа, полученного из списка. Суть поиска в следующем: он берет произвольный список чисел, находит самое большое из них, а затем делит его на длину списка. Студент пока не придумал, где может пригодиться подобное значение, но ищет у вас помощи в реализации такой функции useless().

### Результат.
![Меню]()


## Лабораторная работа №6
Ребята не могут определится каким супергероем они хотят стать. У них есть случайно составленный список супергероев, и вы должны определить кто из ребят будет каким супергероем. Необходимо использовать разделение списков.

### Результат.
![Меню]()


## Лабораторная работа №7
Вовочка, насмотревшись передачи "Слабое звено" решил написать программу, которая также будет находить самое слабое звено (минимальный элемент) и удалять его, только делать он это хочет не с людьми, а со списком. Помогите Вовочке с реализацией программы. Подсказка: для этого вам необходимо отсортировать список и удалить значение при помощи рор().

### Результат.
![Меню]()


## Лабораторная работа №8
Михаил решил создать большой n-мерный список, для этого он случайным образом создал несколько списков, состоящих минимум из 3, а максимум из 10 элементов и поместил их в один большой список. Он также как и Иван не знает зачем ему это сейчас нужно, но надеется на то, что это пригодится ему в будущем.

### Результат.
![Меню]()



## Лабораторная работа №9
Вы работаете в ресторане и отвечает за статистику покупок, ваша задача сравнить между собой заказы покупателей, которые указаны в разном порядке. Реализуйте функцию superset(), которая принимает 2 множества. Результат работы функции: вывод в консоль одного из сообщений в зависимости от ситуации:
1 - «Супермножество не обнаружено»
2- «Объект {X} является чистым супермножеством»
3 - «Множества равны»

### Результат.
![Меню]()


## Лабораторная работа №10
Предположим, что вам нужно разобрать стопку бумаг, но нужно начать работу с нижней, "переверните стопку". Вам дан произвольный список. Представьте его в обратном порядке. Программа должна занимать не более двух строк в редакторе кода.

### Результат.
![Меню]()

## Самостоятельная работа №1
Ресторан на предприятии ведет учет посещений за неделю при помощи кода работника. У них есть список со всеми посещениями за неделю. Ваша задача почитать:
• Сколько было выдано чеков
• Сколько разных людей посетило ресторан
• Какой работник посетил ресторан больше всех раз
Список выданных чеков за неделю:[8734, 2345, 8201, 6621, 9999, 1234, 5678, 8201, 8888, 4321, 3365, 1478, 9865, 5555, 7777, 9998, 1111, 2222, 3333, 4444, 5556, 6666, 5410, 7778, 8889, 4445, 1439, 9604, 8201, 3365, 7502, 3016, 4928, 5837, 8201, 2643, 5017, 9682, 8530, 3250, 7193, 9051, 4506, 1987, 3365, 5410, 7168, 7777, 9865, 5678, 8201, 4445, 3016, 4506, 4506].
### Результат.
![Меню]()
## Выводы
В этом решении мы определяем количество чеков с помощью функции len(), подсчитываем уникальных посетителей, преобразовав список в множество, и ищем работника с максимальным числом посещений, используя max() с ключом counts.
  
## Самостоятельная работа №2
На физкультуре студенты сдавали бег, у преподавателя физкультуры есть список всех результатов, ему нужно узнать
• Три лучшие результата
• Три худшие результата
• Все результаты начиная с 10
Ваша задача помочь ему в этом.
Список результатов бега:[10.2, 14.8, 19.3, 22.7, 12.5, 33.1, 38.9, 21.6, 26.4, 17.1, 30.2, 35.7, 16.9, 27.8, 24.5, 16.3, 18.7, 31.9, 12.9, 37.4]
### Результат.
![Меню]()
## Выводы
В данном решении мы сортируем список результатов для нахождения лучших и худших результатов. Для фильтрации результатов, начиная с 10, используем генератор списка.
  
## Самостоятельная работа №3
Преподаватель по математике придумал странную задачку. У вас есть три списка с элементами, каждый элемент которых - длина стороны треугольника, ваша задача найти площади двух треугольников, составленные из максимальных и минимальных элементов полученных списков. 
Три списка:
one=[12, 25, 3, 48, 71]
two = [5, 18, 40, 62, 98]
three=[4, 21, 37, 56, 84]
### Результат.
![Меню]()
## Выводы
В этом решении мы вычленяем максимальные и минимальные значения из списков и рассчитываем площади треугольников по формуле 0.5 основание высота.
  
## Самостоятельная работа №4
Никто не любит получать плохие оценки, поэтому Борис решил это исправить. Допустим, что все оценки студента за семестр хранятся в одном списке. Ваша задача удалить из этого списка все двойки, а все тройки заменить на четверки. Списки оценок (проверить работу программы на всех трех вариантах): 
[2, 3, 4, 5, 3, 4, 5, 2, 2, 5, 3, 4, 3, 5, 4] 
[4, 2, 3, 5, 3, 5, 4, 2, 2, 5, 4, 3, 5, 3, 4]
[5, 4, 3, 3, 4, 3, 3, 5, 5, 3, 3, 3, 3, 4, 4]
### Результат.
![Меню]()
## Выводы
В этом решении мы используем генератор списка для удаления всех двоек и замены троек на четверки, проходя по каждому списку оценок.
  
## Самостоятельная работа №5
Вам предоставлены списки натуральных чисел, из них необходимо сформировать множества. При этом следует соблюдать это правило: если какое-либо число повторяется, то преобразовать его в строку по следующему образцу: например, если число 4 повторяется 3 раза, то в множестве будет следующая запись: само число 4, строка «44», строка «444».
Множества для теста:
list_1 = [1, 1, 3, 3, 1]
list_2=[5, 5, 5, 5, 5, 5, 5]
list_3 = [2, 2, 1, 2, 2, 5, 6, 7, 1, 3, 2, 2]
Результаты вывода (порядок может отличаться, поскольку мы работаем c set()):
{'11', 1, 3, '33', '111'}
{5, '5555', '555555', '55555', '555', '55', '5555555'}
{'11', 1, 3, 2, 5, 6, '222222', '222', 7, '2222', '22222', '22'}
### Результат.
![Меню]()
## Выводы
В данном решении мы считаем количество каждого числа с помощью словаря и создаем результат, добавляя само число и его строковые представления в зависимости от количества повторений.
  

## Общие выводы по теме
Благодаря изучению темы "Базовые коллекции: строки и списки" я узнала о фундаментальных типах данных в Python, которые являются основой для работы с информацией. Списки представляют собой инструмент для хранения и управления последовательностями элементов, что позволяет легко добавлять, удалять и изменять данные. Я поняла, что списки могут содержать элементы различных типов, включая другие списки, что удобно для создания сложных структур данных. Также изучила множества, которые предоставляют эффективные способы работы с уникальными элементами. Я узнала о методах операций над множествами, таких как объединение и пересечение, что полезно для анализа данных и создания более сложных алгоритмов. 