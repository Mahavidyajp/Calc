# Ex.08 Design of a Standard Calculator
## Date:21.12.23

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
calculator.html

<html>
    <head>
        <title>Calculator</title>
        <style>
            *{
                font-family:cursive;
            }
            .box{
                width: 400px;
                height: 520px;
                background-color:plum;
                border-radius: 15px;
                border-color: black;
                border-style:double;
                box-shadow:5px 5px 2px grey;
                
            }
            .mainbox{
                margin-top: 40px;
                width: 350px;
                height:60px;
                border-radius: 5px;
                background-color:white;
                color:darkblue;
                font-size: 40px;
                border-style:ridge;
                border-width: 5px;
            }
            table{
                text-align: center;
                margin:5px;
            }
            .button{
                width: 55px;
                height:55px;
                background-color:transparent;
                border-radius: 5px;
                box-shadow: 5px 5px 2px purple;
                font-size: larger;
            }
            h1{
                margin-top: 10px;
                color:darkblue;
                font-size: 50px;
            }
            footer{
                background-color: darkblue;
                color: yellow;
                bottom: 0;
                width: 100%;
                height:21px;
                margin-top: 36px;
                
                
            }
            
        </style>
    </head>
    <body style="background-color:mediumpurple;">
        <center>
        <h1>CALCULATOR</h1>
        <div class="box">
            <form name="f">
                <input class="mainbox" id="mb" name="m">
                <table cellspacing="20">
                    <tr>
                        <td><input type="button" value="1" class="button" onclick="f.m.value+='1'"></td>
                        <td><input type="button" value="2" class="button" onclick="f.m.value+='2'"></td>
                        <td><input type="button" value="3" class="button" onclick="f.m.value+='3'""></td>
                        <td><input type="button" value="+" class="button" onclick="f.m.value+='+'"></td>
                    </tr>
                    <tr>
                        <td><input type="button" value="4" class="button" onclick="f.m.value+='4'"></td>
                        <td><input type="button" value="5" class="button" onclick="f.m.value+='5'"></td>
                        <td><input type="button" value="6" class="button" onclick="f.m.value+='6'"></td>
                        <td><input type="button" value="-" class="button" onclick="f.m.value+='-'"></td>
                    </tr>
                    <tr>
                        <td><input type="button" value="7" class="button" onclick="f.m.value+='7'"></td>
                        <td><input type="button" value="8" class="button" onclick="f.m.value+='8'"></td>
                        <td><input type="button" value="9" class="button" onclick="f.m.value+='9'"></td>
                        <td><input type="button" value="*" class="button" onclick="f.m.value+='*'"></td>
                    </tr>
                    <tr>
                        <td><input type="button" value="%" class="button" onclick="f.m.value+='%'"></td>
                        <td><input type="button" value="0" class="button" onclick="f.m.value+='0'"></td>
                        <td><input type="button" value="." class="button" onclick="f.m.value+='.'"></td>
                        <td><input type="button" value="/" class="button" onclick="f.m.value+='/'"></td>
                    </tr>
                    <tr>
                        <td><input type="button" value="AC" class="button" onclick="f.m.value=''"></td>
                        <td><input type="button" value="00" class="button" onclick="f.m.value+='00'"></td>
                        <td><input type="button" value="=" class="button" onclick="f.m.value=eval(f.m.value)"></td>
                        <td><input type="button" value="^" class="button" onclick="f.m.value+='^'"></td>
                </table>
            </form>
        </div>
        <footer>
            <p>Designed by Maha Vidya (23013441)</p>
        </footer>
        </center>
        
    </body>
</html> 

```

## OUTPUT:

![Alt text](cal(1).png)
![Alt text](cal(2).png)

## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
