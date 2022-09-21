# 100DaysOfCode
Learn Full Stack in just 100 Days


## Day 4
### Let's start CSS.
- CSS means Cascading Style Sheets.
  - HTML create structure for our website.
  - CSS helps us to make boring webpages to good looking webpages.
  - You can build your website without CSS, but it's impossible to create website wuthout HTML.

- Let's look some popular websites without CSS.
  
  -  [Netflix](https://www.netflix.com/in/) 
     -  With CSS
        -  <p align="center"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/netflix.png?raw=true"></p>
     -  Without CSS
        -  <p align="center"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/netflixnocss.png?raw=true"></p>  
  -  [Google](https://google.com/) 
     -  With CSS
        -  <p align="center"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/google.png?raw=true""></p>
     -  Without CSS
        -  <p align="center"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/googlenocss.png?raw=true""></p>  
  -  [YouTube](https://youtube.com/) 
     -  With CSS
        -  <p align="center"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/youtube.png?raw=true""></p>
     -  Without CSS
        -  <p align="center"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/youtubenocss.png?raw=true""></p>  
  -  [Amazon](https://amazom.com/) 
     -  With CSS
        -  <p align="center"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/amazon.png?raw=true""></p>
     -  Without CSS
        -  <p align="center"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/amazonnocss.png?raw=true""></p>  

  - I use Web Developer Chrome Extension to disable all styles.
  - Now, you understand the importance of CSS.
  - We only spend 5% of our time to write HTML structure and 95% to write CSS.

### Versioning of CSS
- 1996 : CSS1
- 1998 : CSS2
- 1998 : CSS3 (Current Version)
  - We will never get CSS4, because CSS3 updated time to time.
  - Module based.

### Different ways to apply CSS
- First create a index.html file.
 ```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diffrernt ways to apply CSS</title>
</head>
<body>
    
</body>
</html>
 ```
- 1st way (Inline CSS)
- Inside body tag, write some HTML code.
- Use style attribute
```html
<body>
    <h1 style="color: orange;">I am Ashwani</h1>
</body>
```
  
- 2nd way (Internal CSS)
- Use style tag, in the head tag.
```html
<head>
    ...
    <title>Diffrernt ways to apply CSS</title>
    <style>
        h1{
            color: aqua;
        }
    </style>
</head>
```

- 3rd way (External CSS)
- Create new CSS file, write css code in it and link it with HTML in Head tag.
```html
<head>
    ...
    <link rel="stylesheet" href="style.css">
    <title>Diffrernt ways to apply CSS</title>
</head>
```

**Try Out:** Apply all different types of CSS and see the change.

<div align="center">
    <h3>Don't forget to ⭐ this repo</h3>
    <h5>Building with the COMMUNITY for the COMMUNITY ❤️</h5>
</div>