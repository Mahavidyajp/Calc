# Ex.08 Design of a Standard Calculator
## Date:22.12.23

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
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-Compatible" content="ie=edge">
        <link rel="stylesheet" href="calculator.css">
        <title>Calculator</title>
    </head>
    <body style="background-color:mediumpurple;">
        <center>
        <h1>CALCULATOR</h1>
        <p>Maha Vidya (23013441)</p>
        <div class="box">
            <input class="screen" id="screen">
                <table cellspacing="20">
                    <tr>
                        <td><button class="color">(</button></td>
                        <td><button class="color">)</button></td>
                        <td><button class="color"> C </button></td>
                        <td><button class="color">%</button></td>
                    </tr>
                    <tr>
                        <td><button> 7 </button></td>
                        <td><button> 8 </button></td>
                        <td><button> 9 </button></td>
                        <td><button class="color"> * </button></td>
                    </tr>
                    <tr>
                        <td><button> 4 </button></td>
                        <td><button> 5 </button></td>
                        <td><button> 6 </button></td>
                        <td><button class="color"> - </button></td>
                    </tr>
                    <tr>
                        <td><button> 1 </button></td>
                        <td><button> 2 </button></td>
                        <td><button> 3 </button></td>
                        <td><button class="color"> + </button></td>
                    </tr>
                    <tr>
                        <td><button> 0 </button></td>
                        <td><button class="color"> . </button></td>
                        <td><button class="color"> / </button></td>
                        <td><button class="color"> = </button></td>
                </table>
            </form>
        </div>
        </center>        
    </body>
    <script src="calculator.js"></script>
</html> 

calculator.css


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
.screen{
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
button{
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
p{
    margin-top: 10px;
    color:darkblue;
}

```

## OUTPUT:

![Alt text](sc(1).png)
![Alt text](sc(2).png)

## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
