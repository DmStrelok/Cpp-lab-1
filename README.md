# Cpp-lab-1

## Задачи для практикума №1 (Типы, выражения, функции)

**Задача №1**

```
   Написать программу, определяющую, какое самое маленькое положительное целое 
   число делится на все числа из диапазона [1...20] без остатка.
```

**Состав проекта**

```
   - unsigned long findValue(unsigned int min,unsigned max) - функция поиска числа. 
     Делители: [min..max]
   - int main()
 ```
 
 **Файлы:** task1.h, task1.cpp, main1.cpp
 
 **Задача №2**

```
  Написать прототип библиотеки для работы с простыми (prime) числами.
```

**Состав проекта**

```
   - bool checkPrime(unsigned int value) - проверка числа на простоту.
   - unsigned int nPrime(unsigned n) - нахождение n-ого простого числа (в ряду).
   - unsigned int nextPrime(unsigned int value) - нахождение ближайшего следующего простого числа к value.
   - int main() - простая демонстрация (сценарий).
 ```
 **Файлы:** task2.h, task2.cpp, main2.cpp

 **Задача №3**

```
  Найти сумму всех простых чисел, меньше двух миллионов.
```

**Состав проекта**

```
  - unsigned long sumPrime(unsigned int hbound) - сумма всех чисел до hbound (не включая его)
  - main()
```

 **Файлы:** task2.h, task2.cpp, task3.h, task3.cpp, main3.cpp

