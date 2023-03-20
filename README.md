# lecture_16_JS_типы_данных  
#  [Задачи ](https://github.com/schoolteacherMP/lecture_16_JS/blob/main/tasks.md)  

-  для вывода в консоль **console.log();**  
-  для отображения в сплывающем окне метод **alert()** выводит на экран модальное окно с указанным сообщением и кнопкой "OK"  
-  Метод **prompt(title, default);** выводит модальное окно с заголовком title, полем для ввода текста, заполненным строкой по умолчанию default и кнопками OK/CANCEL. 
-  Метод **confirm(question);** выводит окно с вопросом question с двумя кнопками: OK и CANCEL. Результатом будет true при нажатии OK и false – при CANCEL(Esc).  
-  Свойство **length** представляет длину строки. Это свойство возвращает количество кодовых значений в строке.  **console.log(text.length);**  
-  Метод **toUpperCase()** возвращает значение строки, на которой он был вызван, преобразованное в верхний регистр. Синтаксис str.toUpperCase()  
-  Оператор **typeof** возвращает строку, указывающую тип операнда. console.log(typeof 42);  
-  ![image](https://user-images.githubusercontent.com/113675674/211532126-33440812-147c-44f3-99bc-638f40f0ea8c.png) (бэктики \ обратные ковычки)- позволяют нам встраивать выражения в строку, заключая их в ${…}.  


# lecture_17_JS_преобразование_типов

## Задача 1  
Создайте переменную с именем num и присвойте ей числовое значение. Создайте вторую переменную с именем result и присвойте ей результат преобразования num к строке с помощью функции String(). Выведите result на экран.  

## Задача 2  
Создайте переменную с именем str и присвойте ей строковое значение, содержащее цифры. Создайте вторую переменную с именем result и присвойте ей результат преобразования str к числу с помощью функции parseInt(). Выведите result на экран. Обратите внимание, что результат будет разным в зависимости от того, содержит ли строка только цифры.  

## Задача 3  
Создайте переменную с именем bool и присвойте ей логическое значение. Создайте вторую переменную с именем result и присвойте ей результат преобразования bool к строке с помощью функции String(). Выведите result на экран.  

## Задача 4  
Создайте переменную с именем num1 и присвойте ей числовое значение. Создайте вторую переменную с именем num2 и присвойте ей строковое значение, содержащее цифры. Создайте третью переменную с именем result и присвойте ей результат суммирования num1 и num2, используя оператор +. Выведите result на экран. Обратите внимание, что результат будет разным в зависимости от того, как вы преобразуете num2 к числу.  
  
## Задача 5  
Создайте переменную с именем bool и присвойте ей булево значение. Создайте вторую переменную с именем result и присвойте ей результат преобразования bool к числу с помощью функции Number(). Выведите result на экран.  

## Задача 6  
Создайте переменную с именем str и присвойте ей строковое значение. Создайте вторую переменную с именем result и присвойте ей результат преобразования str к числу с помощью функции Number(). Выведите result на экран. Обратите внимание, что результат будет разным в зависимости от того, содержит ли строка только цифры.  

## Задача 7  
Создайте переменную с именем num5 и присвойте ей строковое(состоящие из цифр к примеру '123') значение.  
Преобразуйте эту переменную к числу всеми способами, которые вы знаете.  
