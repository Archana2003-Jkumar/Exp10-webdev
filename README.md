# Exp10-webdev
# Gliding box using CSS animation
## Aim:
To develop a  Gliding box using CSS animation.
## Algorithm:
1. Code all the necessary Css elements.
2. And connect it with the HTML page.
3. Then execute it.
4. Display the results.
## Code:
```
HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="bgcolor.css"/>
    <title>Document</title>
</head>

<body>
    <div class="container">
       
        <center>
            <div class="box">
                <h4 style="color:white;padding-top: 10px; margin-top: 2cm;">Rainbow Stack</h4>
            </div>
        </center>
    </div>
</body>
</html>
```
```
CSS
body{
    background-color: white;
    margin-top: 100px;
    margin-left:250px;
}
.container
{
    background-color: black;
    width:1000px;
    height:500px;
    border-radius: 25px;
    display: flex;
    flex-direction: column;
    justify-content: center;
}
.box
{
    width: 200px;
    height:100px;
    box-shadow: blue 0px 0px 0px 2px inset,black 10px -10px 0px -3px, green 10px -10px, black 20px -20px 0px -3px, yellow 20px -20px, black 30px -30px 0px -3px, orange 30px -30px,black 40px -40px 0px -3px, red 40px -40px;
    cursor: pointer;
     
}
.box:hover
{
    animation: shadow-wave 1s ease infinite;
}

@keyframes shadow-wave {
    0%{
        box-shadow: blue 0px 0px 0px 2px inset,black 10px -10px 0px -3px, green 10px -10px, black 20px -20px 0px -3px, yellow 20px -20px, black 30px -30px 0px -3px, orange 30px -30px,black 40px -40px 0px -3px, red 40px -40px;
    }
    20% {
        
        box-shadow: red 0px 0px 0px 2px inset,black 10px -10px 0px -3px, blue 10px -10px, black 20px -20px 0px -3px, green 20px -20px, black 30px -30px 0px -3px, yellow 30px -30px,black 40px -40px 0px -3px, orange 40px -40px;
 
      }
    40% {
        
        box-shadow: orange 0px 0px 0px 2px inset,black 10px -10px 0px -3px, red 10px -10px, black 20px -20px 0px -3px, blue 20px -20px, black 30px -30px 0px -3px, green 30px -30px,black 40px -40px 0px -3px,yellow 40px -40px;
    }
    60% {
      
        box-shadow: yellow 0px 0px 0px 2px inset,black 10px -10px 0px -3px, orange 10px -10px, black 20px -20px 0px -3px, red 20px -20px, black 30px -30px 0px -3px, blue 30px -30px,black 40px -40px 0px -3px, green 40px -40px;
    }
    80% {

        box-shadow: green 0px 0px 0px 2px inset,black 10px -10px 0px -3px, yellow 10px -10px, black 20px -20px 0px -3px, orange 20px -20px, black 30px -30px 0px -3px, red 30px -30px,black 40px -40px 0px -3px, blue 40px -40px;
    }
    100% {
      
        box-shadow: blue 0px 0px 0px 2px inset,black 10px -10px 0px -3px, green 10px -10px, black 20px -20px 0px -3px, yellow 20px -20px, black 30px -30px 0px -3px, orange 30px -30px,black 40px -40px 0px -3px, red 40px -40px;
    }
    
}
```
## Output:
![image](https://github.com/Archana2003-Jkumar/Exp10-webdev/assets/93427594/c0cbdc06-fce4-4301-9680-3aa4798efd50)
## Result:
Thus the code has been implemented successfully.
