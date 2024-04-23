 #  Возможности отображения JavaScript
*   JavaScript может «отображать» данные разными способами:
*   Запись в элемент HTML с использованием innerHTML.
*   Запись в вывод HTML с использованием [document.write()](#document.write()).
*   Запись в окно оповещения с использованием [window.alert()](#window.alert())
*   Запись в консоль браузера с помощью [console.log()](#console.log());
*    [window.print()](#window.print())
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
### My Great Heading {#custom-id}

>Изменение свойства innerHTML элемента HTML — распространенный способ отображения данных в HTML.

<a id="document.write()">document.write()</a>

```html
<!DOCTYPE html>
<html>
    <body>
        <h1>My First Web Page</h1>
        <p>My first paragraph.</p>

        <script>
            document.write(5 + 6);
        </script>
    </body>
</html>
```
[try it](https://www.w3schools.com/js/tryit.asp?filename=tryjs_output_write)

> Использование document.write() после загрузки HTML-документа удалит весь существующий HTML 

Для целей тестирования удобно использовать 


### Использование  <a id="window.alert()">window.alert()</a>
Вы можете использовать окно оповещения для отображения данных:

Пример
```html
<!DOCTYPE html>
<html>
    <body>
        <h1>My First Web Page</h1>
        <p>My first paragraph.</p>
        <script>
            window.alert(5 + 6);
        </script>
    </body>
</html>
```


### Использование <a id="console.log()">console.log()</a>
В целях отладки вы можете вызвать console.log()метод в браузере для отображения данных.

Вы узнаете больше об отладке в следующей главе.

**Пример**
```html
<!DOCTYPE html>
<html>
    <body>

    <script>
        console.log(5 + 6);
    </script>

    </body>
</html>
```
[try it](https://www.w3schools.com/js/tryit.asp?filename=tryjs_output_console)

### JavaScript Печать
В JavaScript нет объекта печати или методов печати.

Вы не можете получить доступ к устройствам вывода из JavaScript.

Единственным исключением является то, что вы можете вызвать <a id="window.print()">window.print()</a> метод в браузере, чтобы распечатать содержимое текущего окна.

**Пример**
```html
<!DOCTYPE html>
<html>
    <body>

    <button onclick="window.print()">Print this page</button>

    </body>
</html>
```
[try it](https://www.w3schools.com/js/tryit.asp?filename=tryjs_output_print)