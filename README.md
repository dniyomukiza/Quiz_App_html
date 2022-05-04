# Quiz_App_html
<!DOCTYPE html>
<html>
 <head>     
    <meta charset="utf-8"/>
    <meta name="viewport" content="width=device-width,initial-scale=1"/>
    <title> Web dev</title>
    <link href="Quiz.css" rel="stylesheet" type="text/css"/>
    <script src="Quiz.js" defer></script>
    
 </head>
 <body></body>
 <div id="container">
    <div id ="heading"> Quiz </div>
    <div id ="scoreContainer"> Score:</div>
    <div id ="questionContainer"> </div>
    <ul>
        <li onclick= 'changeColor(0)'></li>
        <li onclick= 'changeColor(1)'></li>
        <li onclick= 'changeColor(2)'></li>
        <li onclick= 'changeColor(3)'></li>
    </ul>
    <div id ="scoreAndNext"> 
<button id='checkScore'>Check score</button>
<button id="next">Next</button>
    </div>
    <div id="Numbering"></div>   

</div>
   
</body>
