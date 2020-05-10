# week 33 #
This time, I used the platform below:
https://www.w3schools.com/html/tryit.asp?filename=tryhtml_default

**link to my website(demo)**
https://www.w3schools.com/code/tryit.asp?filename=GENTEZT5II2E

**Code for my webpage**
```
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Fuma's personal webpage</title>
<style>
	
body {
	background-color: rgb(255, 255, 255)
    }
    #hello {
  position: relative;
  display: inline-block;
  margin-bottom: 1em;
}
#hello:before {
  content: '';
  position: absolute;
  bottom: -15px;
  display: inline-block;
  width: 60px;
  height: 5px;
  left: 50%;
  -webkit-transform: translateX(-50%);
  transform: translateX(-50%);
  background-color: black;
  border-radius: 2px;
}
#hello {
	font-family: impact
    }
    
    
    h1 {
  position: relative;
  padding: 0.25em 1em;
  border-top: solid 2px black;
  border-bottom: solid 2px black;
}
h1:before, h1:after {
  content: '';
  position: absolute;
  top: -7px;
  width: 2px;
  height: -webkit-calc(100% + 14px);
  height: calc(100% + 14px);
  background-color: black;
}
h1:before {
  left: 7px;
}
h1:after {
  right: 7px;
}
 h1{
 	text-align: center
    }
 h1{
 	font-family: serif
    }
 h1{
 	font-size: 60px
    }
p {
	font-family: tahoma
   }
#isak {
	color: rgb(255, 99, 71)
    }
 #first {
 	color: rgb(255, 99, 71)
    }
 #history {
 	font-family: serif
    }
 ul {
 	font-family: serif
    }
 	
    
 
</style>
</head>
<body>

<h2 id="hello">Hello, world!</h2>
<h1>I'm Fuma.</h1>

<p>I'm attending <strong id="isak">UWC ISAK Japan</strong>. At the moment, I'm learning computer science as a part of IB diploma.
<br>
<br>This is the <strong id="first">first</strong> website for me to create with HTML and CSS!</p>
<h2 id="history">My Personal History:</h2>
<ul>
	<li>'03: I was born inTokyo
   <li>'10: Start of elementary school
   <li>'10: Found an enjoyment of soccer
   <li>'12: Move to Hiroshima due to great earthquake
   <li>'13: Move to Kyoto which is my lovely hometown
   <li>'16: Move to Kanagawa where I live in now
   <li>'16: Start of junior high school
   <li>'18: Decided to be a member of ISAK communiy
   <li>'18: Start of spectacular high school life!!
</ul>

</body>
</html>
```


