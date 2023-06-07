# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:

Write your own steps here.
### Step 2:

Make a new folder templates inside your app and create a html and map them using views and url.
### Step 3:

Write down the code for book cover using HTML and CSS.
### Step 4:

Add images and other contents using CSS record a screenshot of it.


## Code:
cover.html
```
<!DOCTYPE html>
html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/book.png);
            background-size: cover;
        }
            

        .toptext{
            color:white;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            color:lightblue;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
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
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>WINGS OF FIRE</h1></div>
            <div class="subtitle">
                 Abdul Kalam and  his efforts and his courage to chase his dreams
            </div>
            <div class="photo">
                <img src="/static/images/apj.png" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>HARINI</b></p>
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

```

## Output:

### CLient output:
![Screenshot (198)](https://github.com/Harinimuthu17/cover-page-design/assets/130278614/de1e9f9f-242e-43d8-827d-17b7e7d81b44)


### Server output:
![Screenshot (200)](https://github.com/Harinimuthu17/cover-page-design/assets/130278614/16a72a74-f24f-468b-93bd-06d4c0780f78)


### Html Validator:
![Screenshot (199)](https://github.com/Harinimuthu17/cover-page-design/assets/130278614/e5460fe1-bf59-48bf-af4b-10029c85b282)




## Result:
Thus a website to display the cover page design of a book was successfully created.
