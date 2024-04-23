 #  Возможности отображения JavaScript

*   JavaScript может «отображать» данные разными способами:
*   Запись в элемент HTML с использованием innerHTML.
*   Запись в вывод HTML с использованием document.write().
*   Запись в окно оповещения с использованием window.alert().
*   Запись в консоль браузера с помощью console.log().
 ```html 
 <!DOCTYPE html>
<html>
    <body>
        <h1>My First Web Page</h1>
        <p>My First Paragraph</p>

        <p id="demo"></p>
        <script>
            document.getElementById("demo").innerHTML = 5 + 6;
        </script>
    </body>
</html>
 ```
 [try it ](https://www.w3schools.com/js/tryit.asp?filename=tryjs_output_dom)

 Изменение свойства innerHTML элемента HTML — распространенный способ отображения данных в HTML.

 Использование a