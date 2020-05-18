# Question2 #
## Visual design ##
![vowel](vowel_counter.JPG)

## HTML, CSS code ##
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Question2</title>
    <style>
       .serif {
           font-family: Serif;
       }
        #h1 {
            font-weight: bold;
            font-family: Helvetica,serif;
        }

    </style>
</head>
<body>
    <h1>Vowels Counter</h1>
    <h3 class="serif">Enter a sentense below:</h3>
    <h3 class="serif"><strong>Input</strong></h3>
    <input type="text" id="input_message" value="">
    <input type="button" onclick="func2()" value="count">
    <h3 class="serif">Number of vowels</h3>
    <h4>A:</h4><div id="output_a"></div>
    <h4>E:</h4><div id="output_e"></div>
    <h4>I:</h4><div id="output_i"></div>
    <h4>O:</h4><div id="output_o"></div>
    <h4>U:</h4><div id="output_u"></div>
    <div id="output_b">

    </div>

```.py



