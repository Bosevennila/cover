# Ex.06 Book Front Cover Page Design
## Date: 27.11.2023

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
<!DOCTYPE html>
<html>

<head>
    <title>AI</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(1234.PNG);
            background-size: cover;
        }
            
        
        .insight{
            color:azure;
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:cornflowerblue;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:azure;
            font-family: 'Courier New', Courier, monospace;
            font-size: 26px;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:200px;
            
        }
        .pub{
            color:azure;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:100px;
        
        }
        .subtitle{
            color:azure;
            font-family:unicorn;
            font-size: large;
            text-align: center;
            position: relative;
            top:60px;
        }
        .mypic{
            position: relative;
            top: 190px;
            left: 240px;
            width: 100px;
            height: 90px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                BOOK OF AI
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>ARTIFICIAL INTELLIGENCE</h1></div>
            <div class="subtitle">
                Modern Magic or Dangerous Future
            </div>
            <div class="subtitle">
                 YORICK WILKS
            </div>

            <div class="mypic">
                <img src="cutie.jpeg" width="150" height="100" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>CHANDRAPRIYADHARSHINI C</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>LIMITED EDITION</b>
            </div>
        </div>
        </body>
        

</html>

```

## OUTPUT:
![book page](https://github.com/Bosevennila/cover/assets/144870486/45f32b08-390a-4972-810c-7b3e8631cea2)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
