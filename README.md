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
        -  <p align="justify"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/netflix.png?raw=true" width=360px height=200px></p>
     -  Without CSS
        -  <p align="justify"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/netflixnocss.png?raw=true" width=360px height=200px></p>  
  -  [Google](https://google.com/) 
     -  With CSS
        -  <p align="justify"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/google.png?raw=true" width=360px height=200px></p>
     -  Without CSS
        -  <p align="justify"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/googlenocss.png?raw=true" width=360px height=200px></p>  
  -  [YouTube](https://youtube.com/) 
     -  With CSS
        -  <p align="justify"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/youtube.png?raw=true" width=360px height=200px></p>
     -  Without CSS
        -  <p align="justify"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/youtubenocss.png?raw=true" width=360px height=200px></p>  
  -  [Amazon](https://amazom.com/) 
     -  With CSS
        -  <p align="justify"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/amazon.png?raw=true" width=360px height=200px></p>
     -  Without CSS
        -  <p align="justify"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/amazonnocss.png?raw=true" width=360px height=200px></p>  

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

**Note**
- We'll use External CSS.
- Inline CSS has the highest priority, then comes Internal/Embedded followed by External CSS which has the least priority.

### CSS Fonts
```html
<body>
    <h1>I am Ashwani</h1>
    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Magnam rerum et nihil consectetur laborum blanditiis,
        consequatur, saepe ratione, nisi id eligendi dignissimos. Nesciunt, corrupti numquam provident quas beatae
        deserunt facilis explicabo quia ducimus tenetur nostrum maxime dolores deleniti dolore ad vel recusandae
        molestias atque dolorum repudiandae sequi ea, saepe exercitationem animi. Qui, aperiam accusamus aut expedita
        neque placeat corrupti illo tempore eius porro recusandae laudantium voluptas at sequi excepturi numquam illum
        ut eligendi rerum accusantium! Vitae rem, ipsa sint modi soluta, harum cumque magni sunt atque inventore autem?
        Autem quia ad illum natus, magnam, accusantium nemo non minus error placeat voluptas dolorem cum suscipit
        perferendis? Architecto dolorem dolor fuga voluptas facilis labore quaerat ab veritatis enim at consequatur
        maiores nihil quia vel, velit assumenda harum placeat odio commodi totam nobis beatae blanditiis. Consectetur
        molestias laborum soluta ut possimus delectus asperiores quod hic a distinctio voluptates qui non exercitationem
        repellat quisquam, corporis optio tempore nulla? Doloribus error magni, dignissimos autem nulla quas mollitia
        ratione cum ad hic itaque sequi est fugiat porro et qui sed doloremque. Aperiam eum distinctio fuga ea unde
        voluptas veritatis pariatur odit totam natus voluptatem, esse quisquam aliquid deserunt laudantium est sequi
        nostrum nulla quasi non dicta.</p>
</body>
```
- By Default, browser font is Sans-serif font.
- In Modern Websites, we use Serif font.


<div align="center">
    <h3>Don't forget to ⭐ this repo</h3>
    <h5>Building with the COMMUNITY for the COMMUNITY ❤️</h5>
</div>