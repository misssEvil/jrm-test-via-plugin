##Задание

Необходимо создать первое приложение, которое будет выводить на консоль: «Моя первая программа». Для этого нужно пройти по шагам и отправить
задание на проверку. Важно! Перед началом выполнения задания ознакомьтесь с видео, которое есть в модуле инструментарий. Там мы рассматриваем
как пользоваться IDE IDEA.

**Step 1.**
Создать класс Test в пакете jrm. Если Вы никогда не сталкивались с созданием классов, посмотрите видео, о котором мы говорили в задании.

**Step 2.**
В классе Test создать константу private static final String HELLO = "Моя первая программа".

**Step 3.**
В классе Test создать метод main(String[] args). Решение в шаге 4.

**Step 4.**
В методе main вызвать метод println() и передать ему в качестве параметра константу hello.

**Step 5.**
Можно запустить приложение (метод main) и убедиться, что в консоли ниже будет выведено сообщение: Моя первая программа

##Решение
~~~~
package jrm;

public class Test {

    private static final String HELLO = "Моя первая программа";

    public static void main(String[] args) {

        System.out.println(HELLO);
    }

}
~~~~

<br>
<br>

**Case .**

1.


**Expected outcome:**
<br>
**Real outcome:**

<br>
<br>


**Case 1. Позитивный сценарий**
1. Выполнить все шаги:
    - создаем класс Test
    - иницилиазируем в нем константу HELLO типа String и присваиваем ей значение "Моя первая программа"
    - создаем psvm
    - вызываем метод sout и передаем ему в качестве параметра нашу константу
2. Нажать кнопку плагина complete task

**Expected outcome:** сообщение плагина "Completed! Go to next task!" <br>
**Real outcome:** сообщение плагина "Completed! Go to next task!"

<br>
<br>

**Case 2. Пошаговый негативный для step 1**
1. Создаем класс с другим названием (не Test)
2. Жмем кнопку проверки на плагине

**Expected outcome:** сообщение об ошибке выполнения step1
**Real outcome:** собщение об ошибке выведено "Some errors in your task, check please: Кажется, класса Test не существует
java.lang.ClassNotFoundException: "

<br>
<br>

**Case 3. Негативный для step 2 - неправильное имя константы**

1. Создать класс Test
2. Инициализировать в нем контанту _с другим именем_, например, HELLO2

**Expected outcome:** сообщение плагина с указанием на ошибку
<br>
**Real outcome:** "Some errors in your task, check please: Проверьте, что создали поле HELLO"

<br>
<br>


**Case 4. Негативный для step 2 - неправильное значение константы**

1. Создать класс Test
2. Инициализировать в нем константу HELLO и присвоить ей значение, отличное от требующешося в задании

**Expected outcome:** сообщение плагина с указанием на ошибку
<br>
**Real outcome:** "Some errors in your task, check please: полю String HELLO мы должны были присвоить значение = Моя первая программа ==> expected: <Моя первая программа> but was: <Моя первая >
"

<br>
<br>


> **Case 5. Негативный для step 2 - неправильный тип константы**

1. Создать класс Test
2. Инициализировать константу типа char/int с именем HELLO

**Expected outcome:** сообщение с укзаанием на ошибку
<br>
**Real outcome:** "Some errors in your task, check please: class java.lang.Integer cannot be cast to class java.lang.String (java.lang.Integer and java.lang.String are in module java.base of loader 'bootstrap')"
`
<br>
<br>

**Case 6. Негативный для step 2 - отсутствует константа**

1. Создать класс Test
2. Создаеть в нем psvm
3. Нажать кнопку complete task


**Expected outcome:** сообщение плагина с указанеим на ошибку
<br>
**Real outcome:** "Some errors in your task, check please: Проверьте, что создали поле HELLO"

<br>
<br>

**Case 7. Негативный для step 3 - отсутствует метод main**

1. Создать класс Test
2. Создать константу и присовить ей значение
3. Нажать конпку проверки на плагине


**Expected outcome:** сообщение с указанием на ошибку
<br>
**Real outcome:** сообщение "Кажется, метода main() в классе Test не существует
java.lang.NoSuchMethodException: jrm.Test.main([Ljava.lang.String;)"

<br>
<br>

>**Case 8. Негативный для step 4 - отсутствует метод println()**

1. Создать класс Test
2. Создать константу и присовить ей значение
3. Создать метод main
4. Нажать кнопку проверки на плагине


**Expected outcome:** сообщение с указанием на ошибку отсутствия метода println()
<br>
**Real outcome:** ошибка "Some errors in your task, check please: на консоль должно быть выведено " моя первая программа " ==> expected: <моя первая программа> but was: <>"

<br>
<br>

**Case 9. Негативный для step 4 - вызвать пустой метод println()**

1. Создать класс Test
2. Создать константу и присовить ей значение
3. Создать метод main
4. Вызвать метод sout без параметра


**Expected outcome:** сообщение с указанием на ошибку
<br>
**Real outcome:** " на консоль должно быть выведено " моя первая программа " ==> expected: <моя первая программа> but was: <>"

<br>
<br>


**Case 10. Негативный для step 4 - вызавать метод println() с другим параметром**

1. Создать класс Test
2. Создать константу и присовить ей значение
3. Создать метод main
4. Вызвать метод sout, передав ему значение "lala"


**Expected outcome:** сообщение с указанием на ошибку
<br>
**Real outcome:** на консоль должно быть выведено " моя первая программа " ==> expected: <моя первая программа> but was: lala "

<br>
<br>
