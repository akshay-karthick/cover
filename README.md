# Ex.06 Book Front Cover Page Design
## Date:02/12/2024

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
    <title>Book cover</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image: url("back.jpg");
            background-size: cover;
        }
            
        
        .insight{
            color:azure;
            font-family: Trebuchet MS;
        
        }
        
        
        .hrstyle{
            width:145px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(255, 255, 255);
            top:100px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:azure;
            font-family: 'Times New Roman', Times, serif;
            font-size: larger;
            text-align: left;
            position: relative;
            top: 10px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:100px;
            
        }
        .pub{
            color:azure;
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:rgb(132, 241, 209);
            font-size: medium;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            position:relative;
            bottom:220px;
        
        }
        .subtitle{
            color:azure;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:35px;
        }
        .subtitle1{
            color:azure;
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:60px;
        }
        .sub{
            color:azure;
            font-family:Arial, Helvetica, sans-serif;
            font-size: large;
            position: relative;
            top:250px;
        }
        .mypic{
            position: relative;
            top: 105px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        .lpic{
            position: relative;
            bottom: 100px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                Server Development
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1 style="font-family: 'Times New Roman', Times, serif; color:wheat;">Full-Stack Symphony: Mastering CSS, Java, and Python</h1></div>
            <div class="subtitle" style="text-align: left;color: rgb(189, 229, 126);">
                 Easy Steps to Build Yourself
            </div>
            <div class="subtitle1" style="color: rgb(193, 172, 133);text-align: left;">
                 REVISED CONTENT
            </div>
            <div class="sub" style="color: rgb(193, 172, 133);text-align: left;">
                A TECHNICAL BOOK TO EVOLVE
           </div>

            <div class="mypic">
                <img src="Pic.jpg" width="120" height="120" >
            </div>
            <div class="lpic">
                <img src="apple (2).png" width="90" height="90" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>AKSHAY KARTHICK ASR</b></p>
            </div>
            <div class="ed">
                <b>FULL STACK WORKSTATION</b>
            </div>
        </div>
        </body>
        

</html>

```

## OUTPUT:
![alt text](<Screenshot (37).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
