# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:

First Clone the repository to your theaid.

### Step 2:

Create a new folder named static inside the repository.

### Step 3:

Also create a project inside the repository and fill the needs.

### Step 4:

create a html folder inside statis folder and create a new file named index.html inside html folder.

### Step 5:

write your own code inside the index.html to create the calculator on website.

### Step 6:

Publish the website in the given URL.

## PROGRAM :

```
<html>
    <head>
        <script>
            function ac()
            {
                document.getElementById("res").value="";
            }
            function show(input)
            {
                document.getElementById("res").value+=input;
            }
            function cal()
            {
                var output=eval(document.getElementById("res").value);
                document.getElementById("res").value=output;
            }
        </script>
    </head>
    <body>
        <table border="1">
            <caption><h1>SIMPLE CALCULATOR</h1></caption>
            <tr>
                <td colspan="3" align="center"><input type="text" id="res"></td>
                <td align="center"><button onclick="ac()">AC</button></td>
            </tr>
            <tr>
                <td align="center"><button onclick="show('1')">1</button></td>
                <td align="center"><button onclick="show('2')">2</button></td>
                <td align="center"><button onclick="show('3')">3</button></td>
                <td align="center"><button onclick="show('+')">+</button></td>
            </tr>
            <tr>
                <td align="center"><button onclick="show('4')">4</button></td>
                <td align="center"><button onclick="show('5')">5</button></td>
                <td align="center"><button onclick="show('6')">6</button></td>
                <td align="center"><button onclick="show('-')">-</button></td>
            </tr>
            <tr>
                <td align="center"><button onclick="show('7')">7</button></td>
                <td align="center"><button onclick="show('8')">8</button></td>
                <td align="center"><button onclick="show('9')">9</button></td>
                <td align="center"><button onclick="show('*')">*</button></td>
            </tr>
            <tr>
                <td align="center"><button onclick="show('0')">0</button></td>
                <td align="center"><button onclick="show('%')">%</button></td>
                <td align="center"><button onclick="show('/')">/</button></td>
                <td align="center"><button onclick="cal()">=</button></td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT:

### Model of Calculator:

![image](./img/1.png)

### Working of caluculator:

![image](./img/2.png)

## Result:

