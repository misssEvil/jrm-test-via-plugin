#Урок 3. Знакомство с примитивными типами данных

##Задание

В пакете jrm, который вы получили необходимо создать класс jrm.ShowAllPrimitiveDataTypes, и закодировать в нем все типы данных, присвоив им значение из шагов.

**Step 1.** Создать класс jrm.ShowAllPrimitiveDataTypes в пакете jrm.

**Step 2.** Инициализировать переменные типа byte, short, int, long, float, double, boolean и char.
Вывести на консоль значение каждого типа данных.



##Решение
~~~~
тут будет решение
~~~~

<br>
<br>

##Сценарии проверки работы плагина

**Case 0. Позитивный сценарий**

1. Создать класс ShowAllPrimitiveDataTypes в пакете jrm.
2. Инициализировать переменные типа byte, short, int, long, float, double, boolean и char.
Вывести на консоль значение каждого типа данных.
   
3. Нажать кнопку проверки на плагине


**Expected outcome:** сообщение плагина "Completed! Go to next task!"
<br>
**Real outcome:** сообщение плагина "Completed! Go to next task!"

<br>
<br>

>**Case 1.1 Негативный пошаговый для step 1 - неверное имя класса**

1. Создать класс WhateverNameIWant в пакете jrm.
2. Нажать кнопку проверки на плагине

**Expected outcome:** сообщение плагина с указанием на тип ошибки
<br>
**Real outcome:** сообщение плагина "Compilation error, check please error message: null"

<br>
<br>

>**Case 1.2 Негативный пошаговый для step 1 - искомый класс не входит в пакет jrm**

1. Создать класс ShowAllPrimitiveTypes в пакете jrm.
2. Нажать кнопку проверки на плагине

**Expected outcome:** сообщение плагина с указанием на тип ошибки
<br>
**Real outcome:** сообщение плагина "Compilation error, check please error message: null"

<br>
<br>

>**Case 2.1 Негативный пошаговый для step 2 - переменные объявлены, но не инициализированы**

1. Создать класс ShowAllPrimitiveTypes в пакете jrm.
2. Объявить переменные типа byte, short, int, long, float, double, boolean и char. Присвоить им значения в рамках нужного диапазона.
3. Нажать кнопку проверки на плагине

**Expected outcome:** сообщение плагина с указанием на тип ошибки
<br>
**Real outcome:** сообщение плагина "Incorrect answer from server on our request! Please, contact with admins."

<br>
<br>

>**Case 2.2 Негативный пошаговый для step 2 - переменные не выведены на консоль**

1. Создать класс ShowAllPrimitiveTypes в пакете jrm.
2. Объявить переменные типа byte, short, int, long, float, double, boolean и char.
3. Нажать кнопку проверки на плагине

**Expected outcome:** сообщение плагина с указанием на тип ошибки
<br>
**Real outcome:** сообщение плагина "Incorrect answer from server on our request! Please, contact with admins."

<br>
<br>


##НЕ ПРОВЕРЕНЫ
**Case 2.3 Негативный пошаговый для step 2 - отсутствует переменная типа byte**

1. Создать класс ShowAllPrimitiveTypes в пакете jrm.
2. Объявить и иницилизировать переменные типов short, int, long, float, double, boolean и char.
3. sout для них
4. Нажать кнопку проверки на плагине

**Expected outcome:** сообщение плагина с указанием на тип ошибки
<br>
**Real outcome:** ?

<br>
<br>

**Case 2.4 Негативный пошаговый для step 2 - отсутствует переменная типа short**

1. Создать класс ShowAllPrimitiveTypes в пакете jrm.
2. Объявить и иницилизировать переменные типов byte, int, long, float, double, boolean и char.
3. sout для них
4. Нажать кнопку проверки на плагине

**Expected outcome:** сообщение плагина с указанием на тип ошибки
<br>
**Real outcome:** ?

<br>
<br>

**Case 2.4 Негативный пошаговый для step 2 - отсутствует переменная типа int**

1. Создать класс ShowAllPrimitiveTypes в пакете jrm.
2. Объявить и иницилизировать переменные типов byte, short, long, float, double, boolean и char.
3. sout для них
4. Нажать кнопку проверки на плагине

**Expected outcome:** сообщение плагина с указанием на тип ошибки
<br>
**Real outcome:** ?

<br>
<br>

**Case 2.5 Негативный пошаговый для step 2 - отсутствует переменная типа long**

1. Создать класс ShowAllPrimitiveTypes в пакете jrm.
2. Объявить и иницилизировать переменные типов byte, short, int, float, double, boolean и char.
3. sout для них
4. Нажать кнопку проверки на плагине

**Expected outcome:** сообщение плагина с указанием на тип ошибки
<br>
**Real outcome:** ?

<br>
<br>

**Case 2.6 Негативный пошаговый для step 2 - отсутствует переменная типа float**

1. Создать класс ShowAllPrimitiveTypes в пакете jrm.
2. Объявить и иницилизировать переменные типов byte, short, int, long, double, boolean и char.
3. sout для них
4. Нажать кнопку проверки на плагине

**Expected outcome:** сообщение плагина с указанием на тип ошибки
<br>
**Real outcome:** ?

<br>
<br>

**Case 2.7 Негативный пошаговый для step 2 - отсутствует переменная типа double**

1. Создать класс ShowAllPrimitiveTypes в пакете jrm.
2. Объявить и иницилизировать переменные типов byte, short, int, long, float, boolean и char.
3. sout для них
4. Нажать кнопку проверки на плагине

**Expected outcome:** сообщение плагина с указанием на тип ошибки
<br>
**Real outcome:** ?

<br>
<br>

**Case 2.8 Негативный пошаговый для step 2 - отсутствует переменная типа boolean**

1. Создать класс ShowAllPrimitiveTypes в пакете jrm.
2. Объявить и иницилизировать переменные типов byte, short, int, long, float, double и char.
3. sout для них
4. Нажать кнопку проверки на плагине

**Expected outcome:** сообщение плагина с указанием на тип ошибки
<br>
**Real outcome:** ?

<br>
<br>

**Case 2.9 Негативный пошаговый для step 2 - отсутствует переменная типа char**

1. Создать класс ShowAllPrimitiveTypes в пакете jrm.
2. Объявить и иницилизировать переменные типов byte, short, int, long, float, double, boolean.
3. sout для них
4. Нажать кнопку проверки на плагине

**Expected outcome:** сообщение плагина с указанием на тип ошибки
<br>
**Real outcome:** ?

<br>
<br>