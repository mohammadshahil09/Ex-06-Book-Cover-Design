# Ex-06-Book-Cover-Design

Name: guntur shaik mohammad shahil

Reference Number: 23011002

Department: AIML

## AIM:

To design a book-cover-design using HTML and CSS.

## DESIGN PROCEDURE:

## STEP 1:

Start define the document type as HTML.

## STEP 2:

Open the HTML structure with necessary head and body sections. In the head section ,set
the title as Book Cover and define the styles for the bookcover.Use the CSS styles in
the code.The styles include:
background-color,
background-image,
background-position,
background-repeat,
cellpadding,
font-size,
font-family,
display,
line-height.

## STEP 3:

In the body section, create a division with the text with respective to the headings:
"World Best Seller",
"Wuthering Heights",
"Illustrated with wood engravings by Fritz Eichenberg",
"New York:Random House Publishers 1945",
"First Edition",
"Emiley Bronte".

## STEP 4:

Close the HTML structure.

## CODE:
```
<!DOCTYPE html>
<html>
    <head>
        <title>Book Cover</title>
        <style>
            h1{
                color: beige;
            }
            .bookpage{height:600px;
                width:400px;
                padding:20px; 
                background-image:url("book cover background.jpg");
                background-position: center;
                background-repeat: no-repeat;
                margin-left: auto;
                margin-right: auto;
            }
            .toptext{
                color: white;
                padding-left: 5px;
                font-size: 14px;
                font-family: Arial, Helvetica, sans-serif;
            }
            .tophr{
                color: red;
                width:200px;
            }
            hr{
                color:red;
            }
            .booktitle{
                font-family:Arial, Helvetica, sans-serif;
                padding:10px 10px 0px 10px;
                display: flex;
                align-items: center;
                justify-content:center;
                font-size: 30px;
                line-height: normal;
                margin-left: 10px;
                margin-right: 10px;
            }
            .author{
                color: white;
                display: inline;
                position: relative;
                font-family: Arial, Helvetica, sans-serif;
                display: inline;
                font-size: 20px;
                line-height: 5px;
            }
            .sub-text{
                color: beige;
                font-family: Arial, Helvetica, sans-serif;
                display: flex;
                line-height: 5px;
                font-size: 14px;
                margin-right: 10px;
                margin-left: 10px;
            }
            .footer{
                color: red;
                padding-top: 100px;
            }
            .image{
                color:red;
                font-family: Arial, Helvetica, sans-serif;
                font-size: 22px;
            }
            .bottomhr{
                color: brown;
                width: 400px;
            }
            img{
                width: 95px;
                height: 100px;
                margin-right: 20px;
                vertical-align: bottom;
            }
            .edition{
                color: red;
                font-family: Arial, Helvetica, sans-serif;
                font-size: 22px;
                line-height: bottom;
            }
            </style>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;WORLD BEST SELLER</div>
            <div class="tophr"><hr></div>
            <div class="booktitle"><h1>Wuthering Heights</h1></div>
            <h3 class="sub-text">&nbsp;&nbsp;&nbsp;Illustrated with wood engravings by Fritz Eichenberg</h3>
            <h3 class="sub-text">&nbsp;&nbsp;&nbsp;New York:Random House Publishers 1945</h3>
            <div class="footer">
                <h2 class="edition">&nbsp;&nbsp;First Edition&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<img src="emiley bronte.jpg"></h2>
                <div class="bottomhr"><hr></div>
                <div class="author"><h3>&nbsp;&nbsp;Emiley Bronte&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Thomas</h3></div>

            </div>
        </div>
    </body>
</html>
```
## OUTPUT:

![bookcover](https://github.com/mohammadshahil09/Ex-06-Book-Cover-Design/assets/145742840/d119a1fe-3289-47d6-bf59-9b7926910c2d)


## RESULT:

Thus the book-cover design has been successfully created using HTML and CSS.
