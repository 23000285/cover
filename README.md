# Ex.06 Book Front Cover Page Design

## Date: 20/04/2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
    <head>
        <link rel="stylesheet" href="{% static 'css/index.css' %}">
        <style>
            body
            {
                color:rgb(255, 255, 255);
                font-family: Helvetica, sans-serif;
            }
            .book
            {
                width: 726px;
                height:990px;
                margin:auto;
                /*position: relative;*/
                background-image: url(bookcover1.jpg);
                background-repeat: no-repeat;
                background-size:cover;
                /*background-position: bottom 2px center;*/
            }
            #top
            {
                border-bottom:7px solid #f47027;
                padding:10px 0px 5px 30px;
                color:rgb(255, 255, 0);
                font-weight:bold;
            }
            h1
            {
                text-align: center;
                font-size:50px;
                margin:50px;
                
                color:rgb(249, 133, 0);
                font-family: Copperplate, Papyrus, fantasy;

            }
            ol
            {
                font-size:30px;
                margin:50px ;
                width:500px;
                height:5px;
                color:rgb(0, 213, 255);             
            }
            .photo
            {
                position: relative;
                top: 10px;
                left: 550px;
                width: 140px;
                height: 150px;
                background-size: cover;
                background-image:url(photo.jpg);
            }
            #bottom
            {
                border-bottom:10px solid #00fbff;
                padding:0px 0px 17px 10px;
                margin:3px;
                margin-bottom:0px;
            }
            h3
            {
                font-size: 20px;
                text-align:right;
                padding:0px 30px 0px 30px;
                color:rgb(111, 248, 14);
            }
            .h4
            {
                font-size:20px;
                color:rgb(221, 255, 0);
                padding-top: 80px;
                padding-right: 0px;
                padding-bottom: 0px;
                padding-left: 75px;
                width:600px;
                text-align:center;
                margin-top:100px;
                font-weight: bold;
            }   
            .author 
            {
                display: inline;
                color: rgb(0, 255, 13);
                margin:12px;
                top: 19px;
                font-family: Georgia;
                font-size: 20px;
                font-weight:bold;
            }
            h2
            {
                margin:0px 0px 90px 40px;
                position: absolute;
                bottom:220px;
                font-size: xx-large;
                font-weight:10px;
                font-family:Verdana, Geneva, Tahoma, sans-serif;
                color:#00fdbe;
            }
            
            
        </style>
    </head>
    <body>
        <section class="book">
            <br><br>
        <div class="box"></div>
        <div id="top">INNOVATORY</div>
        <h1>HUMAN COMPATIBLE</h1>
        <ol type="a">
            <li>Superintelligence Risk</li>
            <li>Value Alignment Problem</li>
            <li>Control Problem</li>
            <li>Beneficial AI</li>
            <li>Policy Recommendations</li>
        </ol>
        <div class="h4">"A strong foundation in algorithms and applied math.
            A good grasp of probability and statistics.
            A nuanced understanding of programming languages.
            Well-versed in cognitive learning theory, language processing, and mechanics.
            Critical thinking abilities with a curious mind."</div>
        <div class="photo"></div>
        <div id="bottom"></div>
        <div class="author"><pre>  VENKATANATHAN P R
    212223240173</pre></div>
        <h3>SEC SQUAD</h3>
        <h2>PUBLICATION</h2>
        </section>
    </body>
</html>
```

## OUTPUT:

![alt text](<exp 6 c-s.png>)

![alt text](<exp 6.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
