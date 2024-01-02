# Ex-08-Book-Cover-Design:

# AIM:
To develop a website to display the cover page design of a book

# Design Steps:
# Step 1:
Write down the code for book cover using HTML and CSS.

# Step 2:
Add images and other contents using CSS record a screenshot of it.

# Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Web Development Technologies</title>
        <style>
            body{
    color:rgb(255, 255, 255);
    font-family: Helvetica, sans-serif;
    background-color: #333
}

.book{
    width: 726px;
    height:891px;
    background-color:rgb(0, 0, 0);
    margin:auto;
    position: relative;
    background-image: url(image/bookpage.jpg);
    background-repeat: no-repeat;
    background-size:606px;
    background-position: bottom 150px center;
}
h1{
    font-size:70px;
    margin:60px;
    margin-bottom:0px;
}
h3{
    margin:0px 0px 90px 60px;
    position: absolute;
    bottom:0px;
    font-size: x-large;
    color: #f47027;
}
h4{
    font-size:20px;
    margin:60px;
   margin-top:10px;
   width:430px;
}
#top{
    border-bottom:2px solid #f47027;
    padding:100px 0px 5px 30px;
}
footer{
    position: absolute;
    bottom: 0px;
    border-top:2px solid #f47027;
    padding-top:10px;
    width:726px;
}
#HASH {
    display: flex;
    justify-content: space-between;
}
  #HASH span{
    margin:10px 0px 20px 60px;
    font-size: xx-large;
    font-weight: bold;
  }
  #end{
    padding-right:60px;
  }
  .photo{
    margin:210px 0px 0px 560px;
    
  }
        </style>
    </head>
    <body>
        <section class="book">
            <br><br>
        <span id="top">EXPERT INSIGHT &nbsp;&nbsp;&nbsp;</span>
            <h1>Responsive Web Design with HTML5 and CSS</h1>
            <h4>Develop future-proof responsive websites using the latest HTML5 and CSS techniques</h4>
            <h3>Third Edition</h3>
            <div class="photo">
                <img src="image/ben.jpeg" width="130" height="145" alt="">
            </div>
            <footer>
                <div id="HASH" class="blue-msg">
                    <span>Ben Frain</span>
                    <span id="end"><u>Packt></u></span>
                </div>
                
            </footer>
    </section>
    </body>
</html>


```
# OUTPUT:
![Alt text](image.png)

# RESULT:
Thus a website to display the cover page design of a book was successfully created.
