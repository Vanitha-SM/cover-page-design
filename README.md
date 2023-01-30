# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:
 
## Step 1:
Create a new Django project and app.
### Step 2:
Create a static file directory and mention the changes in settings.
### Step 3:
Make a new folder templates inside your app and create a html and map them using views and url.
### Step 4:
Write down the code for book cover using HTML and CSS.
### Step 5:
Add images and other contents using CSS record a screenshot of it.

## Code:

cover.html code
~~~
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:Trebuchet MS;
            margin-left: auto;
            margin-right: auto;
            padding: 25px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(cvpage.png);
            background-size: cover;
        }
            

        .toptext{
            color:rgb(65, 5, 32);

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: red;
            display: inline;
            position: relative;
            color:brown;
            top:210px;
            
            font-family:Trebuchet MS;
            font-size: medium;
        }
        .booktitle{
            font-family: Trebuchet MS;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }       
                   
        .publisher{
            font-size: medium;
            position: relative;
            top:180px;
            left:330px;
        }
        .edition{
            color:rgb(65, 5, 32);
            font-size: large;
            font-family:Trebuchet MS ;
            position:relative;
            top:67px;

        }
        .subtitle{
            font-family:Trebuchet MS;
            font-size: large;
            position: relative;
            top:40px;
            left:10px;
        }
        .photo{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: black">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
            </div>
            <div class="photo">
                <img src="photo.png" width="130" height="145" alt="">
            </div>
            
            <div class="author">
               <p><b>VANITHA S</b></p>
            </div>
            <div class="publisher">
                Packt>
            </div>
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>
~~~

## Output:
![cvoutput](/cvoutput.png)

## Result:
Thus a website to display the cover page design of a book was successfully created.
