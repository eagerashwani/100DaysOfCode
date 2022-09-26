# 100DaysOfCode
Learn Full Stack in just 100 Days

- [100DaysOfCode](#100daysofcode)
  - [Day 4](#day-4)
    - [Let's start CSS.](#lets-start-css)
    - [Versioning of CSS](#versioning-of-css)
    - [Different ways to apply CSS](#different-ways-to-apply-css)
    - [CSS Fonts](#css-fonts)
    - [CSS Colors](#css-colors)
    - [CSS Selectors](#css-selectors)
  - [Day5](#day5)
    - [Some More Selectors](#some-more-selectors)
      - [Universal Selector](#universal-selector)
      - [Attribute Selector](#attribute-selector)
  - [Day 6](#day-6)
    - [CSS Specificity](#css-specificity)
    - [How to calculate specificity](#how-to-calculate-specificity)
  - [Day 7](#day-7)
    - [CSS Border](#css-border)
    - [CSS Box-Model](#css-box-model)
      - [Padding](#padding)
      - [Margin](#margin)
  - [Day 8](#day-8)
    - [Margin Collapsing](#margin-collapsing)

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
- By Default, browser font is Serif font.
- In Modern Websites, we use Sans-Serif font.
- Difference between Serif and Sans-serif font.
  
    -  <p align="justify"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/sansserifvsserif.jpeg?raw=true" width=360px height=200px></p> 
- We want to change the font from serif to sans-serif.
- In style.css
  ```css
  body{
    font-family: Arial, Helvetica, sans-serif;
    /* If Arial is not present, than Helvetica, than sans-serif */
    }
  ```
- Many different types of fonts are available in our Operating System.
- But, some fonts are available only in MacOS, some in Windows.
- To Tackle this problem, we use [google fonts.](https://fonts.google.com/)

- After selecting your font, you get something like this.
- 1st way (In HTML).
  ```html
  <head>
    ...
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;900&display=swap" rel="stylesheet">
    <title>Diffrernt ways to apply CSS</title>
  </head>
    ```

- 2nd way (In CSS).
- Paste @import in the 1st line.
```css
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;900&display=swap');
```

- You can use any way.
  
- Changes in style.css
  
```css
  body{
    font-family: 'Roboto', sans-serif;
    }
```
- We select 4 different weight types : 300, 400, 500, 900.

- Now, add font-weight and see the difference.

```css
body{
    font-family: 'Roboto', sans-serif;
    font-weight: 900;
}
```

### CSS Colors

- We have 16777216 possible colors.

- RGB
  - rgb(232, 155, 0);
  - R stands for Red (232).
  - G stands for Green (155).
  - B stands for Blue (0).
  - Value from 0 to 255.

 - Hex Code
   - #ff34d8
   - ff for Red.
   - 34 for Green.
   - d8 for Blue.
   - Value from 0 to f.
     - 0, 1, 2, 3, 4, 5, 6, 7, 8, 9, a, b, c, d, e, f

```css
h1{
    background-color: #ff0000;
    color: rgb(255,255,255);
}
```

### CSS Selectors
- index.html file looks like
  ```html
  <body>
    <div>
        <h1>Main Heading</h1>
    </div>

    <div>
        <h2>Sub Heading</h2>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officiis soluta enim ipsum quaerat iusto modi quasi
            natus nam sunt consequatur, expedita pariatur voluptatum dolorem!</p>
    </div>
  </body>
  ```
  - Now, I want to change the 2nd div.
  - If we just use div tag, than the styles apply to all div.
  ```css
  div{
    color: blue;
    background-color: #cdcdcd;
    }
  ```
  - The above selector is called Element Selector.
 - To tackle above problem, we use id and class selector.
 - Now, our HTML looks like this.
  ```html
    <body>
        <div>
            <h1 id="main-heading">Main Heading</h1>
        </div>

        <div>
            <h2 class="sub-heading">Sub Heading</h2>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officiis soluta enim ipsum quaerat iusto modi quasi
                natus nam sunt consequatur, expedita pariatur voluptatum dolorem!</p>
        </div>
    </body>
  ```
  - style.css
  ```css
    #main-heading{
        background-color: #cdcdcd;
        /* id selector */
    }

    .sub-heading{
        /* class selector */
        background-color: #efefef;
    }

    p{
        /* element selector */
        background-color: #6e6767;
    }
  ```
  - You can use same class selector in many times, but you have to use id selector only one time for one element/tag.
  - Most developers use class selector very frequently.

  - **Utility class**
  - Many times we already know, how our webpage will look.
  - Like we already know if h2 text is red and p text is in green.
  - We define, only one property in utility class.

    ```css
    .text-red{
        color: rgb(249, 95, 95);
    }

    .text-green{
        color: rgb(80, 181, 80);
    }

    .bg-color{
        background-color: beige;
    }
    ```
  - Our HTML 
    ```html
    <div>
            <h2 class="sub-heading text-red">Sub Heading</h2>
            <p class="text-green bg-color">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Officiis soluta enim ipsum quaerat iusto modi quasi
                natus nam sunt consequatur, expedita pariatur voluptatum dolorem!</p>
        </div>
    ```
  - We can give more than one class to our tag, like we done in h2 and p tag.

## Day5
### Some More Selectors
  - Here is my HTML
    ```html
    <body>
    <header>
      <p>Inside header</p>
      <h1 class="main-logo">main logo</h1>
      <ul>
          <li><a href="">Home</a></li>
          <li><a href="">About</a></li>
          <li><a href="">Contact</a></li>
      </ul>
      <p>Inside header</p>
    </header>

    <main>
      <h2>Main Content of webpage</h2>
      <section class="my-articles">
          <h2>Articles Section</h2>
          <article>
              <h2>Article Heading</h2>
              <p>Lorem ipsum dolor sit amet. </p>
          </article>
          <article>
              <h2>Article Heading</h2>
              <p>Lorem ipsum dolor sit amet. </p>
          </article>
      </section>
    </main>
    </body>
    ```
#### Universal Selector
  - Now, you want to change the entire text color, you can use **universal selector** .
      ```css
        *{
        color: royalblue;
        }
      ```
    - We not use universal selector like this and not so much, we use this to reset our CSS.
  - Here is my CSS
  
  ```css
      header{
      background-color: #ffebeb;
  }

  /* Select section which has my-articles class */
  section.my-articles{
      background-color: #ffefef;
  }

  /* Select all p tag inside header tag */
  /* Descendent Selector */
  /* We use mostly */
  header p{
      color: red;
  }

  /* change the color of all links inside list */
  li a{
      color: rgb(0, 70, 0);
  }

  /* Selects all h2 inside section tag which has my-articles class */
  /* section.my-articles h2{
      color: purple;
  } */

  /* But, I want to select only Direct child (h2) of section  */
  section.my-articles > h2 {
    color: purple;
  }

  /* Selects direct p who come after h2 */
  h2+p{
      color: rosybrown;
  }
  ```
#### Attribute Selector
   - Here is my HTML
     ```html
      <body>
        <h2>Links</h2>
        <a href="https://google.com">Google</a><br>
        <a href="https://amazon.com">Amazon</a><br>
        <a href="https://amazon.in">Amazon India</a><br>
        <a href="youtube.com">YouTube</a><br>

        <h2>Form</h2>
        <form>
          <label for="fname">First Name:</label><br>
          <input type="text" id="fname"><br>
          <label for="lname">Last Name:</label><br>
          <input type="text" id="lname"><br>
          <label for="pass">Password:</label><br>
          <input type="password" id="pass"><br><br>
          <input type="button" value="Submit">
        </form>
      </body>
      ```
   - href, type etc are attribute of their respective elements.
   - CSS file
      ```css
      input[type = "text"]{
          color: red;
      }

      input[type="password"]{
          background-color: antiquewhite;
      }

      /* Now, I want to select link that havve amazon */

      a[href *= "amazon"]{
          color: brown;
      }

      /* Now, I want to Select those link that start with https */
      a[href ^= "https"]{
          color: bisque;
      }

      /* Now, I want to Select those a that ends with .in */
      a[href $= ".in"]{
          color: rebeccapurple;
      }
      ```
## Day 6
### CSS Specificity
- class selector have more prefrence than elements/tags selector, because classes are more specific than HTML elements.
- ID selector have more prefrence than class selector.
- Inline style attribute have more prefrence than ID selector.
  ```imp
    Inline style attribute > ID selector > class selector > element selector
  ```
- Here is my HTML
   ```html
  <body>
    <h1 class="myClass" id="myId" style="color: brown;" >Hello</h1>
  </body>
  ```
 
- Here is my CSS.  
  ```css
      h1{
        color: green;
      }

    .myClass{
        color: red;

      }

      #myId{
        color : blue;
      }
  ```
- If you want to apply ID (forcefully), you can do this.
  ```css
  #myId{
    color : blue !important;
  }
  ```
  - But, its not a good practice.
- HTML
  ```html
  <body>
    <h1 class="myClass heading">Hello</h1>
  </body>
  ```
- CSS
  ```css
    h1{
      color: green;
  }

  .myClass{
      color: red;

  }

  h1.heading{
      color: magenta;
  }
  ```
  - Now, we have two classes on an element, class write after than other class have more specificity.
  - Eg : heading has more specificity than myClass, if myClass comes after heading class than text have red color.
- Here is my updated CSS.
  ```css
    h1.heading{
        color: magenta;
    }
    .myClass{
        color: red;
    }

  ```
  - h1.heading has more specifity.
  
### How to calculate specificity
- Look this picture carefully.
-  <p align="justify"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/specificity.jpg?raw=true" width=360px height=200px></p>
-  Here is my HTML.
  ```html
  <body>
  <div id="container">
    <ul class="my-style">
        <li class="fav">The Big Short</li>
        <li>Margin Call</li>
        <li>Wolf of wallstreet</li>
        <li>Wall Street : Money never sleeps</li>
    </ul>
  </div>
  </body>
  ```
- CSS
  ```css
  div#container ul.my-style li{
    color: blue;
    background: bisque;
    }

      /* Inline > ID > Class > Element */
      /* 0, 1, 1, 3 */
      /* 0 -> Inline
      1 -> ID 
      1 -> Class
      3 -> Element 
      for easy understanding, we say above style have 113 specificity */
  li.fav{
          color: bisque;
          background: blue;
      }

      /* 0, 0, 1, 1  --> 11 */
  ```
  - li.fav style not apply, because it has low specificity than above style.
  
## Day 7
### CSS Border
- Here is my HTML (himHTML shortform)
  ```html
    <body>
    <div class="header">
      <ul>
        <li class="home">Home</li>
        <li>About</li>
      </ul>
    </div>

    <h2>Our Heading</h2>

    <img src="images/amazon.png" alt="" srcset="" width="260px" height="200px">

    <p>This <span>is</span> paragraph</p>
  </body>
  ```
- Now, I want to add border arround my HTML elements.
- I can achieve this via border property of CSS.
- Here is my CSS (himCSS shortform).
  ```css
  h2, img{
      border: 5px solid red;
       /* 5px-> width of border, border style -> solid, border color -> red */
       /* This is shorthand*/
  }
  ```
- We can also use this.
- h2 takes full width, because h2 is a block level element.
  ```css
    border-width: 5px;
    border-style: solid;
    border-color: red;
  ```
- Now, I want to apply border only on top and bottom of HTML tag.
  ```css
    border-bottom: 5px solid red;
    border-top: 5px solid red;
  ```
- Our border corners are very sharp, we can round that.
  ```css
    border: 5px solid red;
    border-radius: 5px;
  ```
### CSS Box-Model
#### Padding
- <p align="justify"><img src="https://github.com/eagerashwani/100DaysOfCode/blob/main/images/box-model.webp?raw=true" width=360px height=200px></p>
- As you saw above, there is no space between Our content(h2) and border.
- We can add space with the help of padding property.
  ```css
    h2{
      border: 5px solid red;
      padding-left: 40px;
      padding-bottom: 40px;
      padding-right: 40px;
      padding-top: 40px;
    }
  ```
- The shorthand, Now, you want equal padding in every side
  ```css
   padding: 40px;
  ```
  -  add 20px in top, bottom and 40px in left,right  
  ```css
  padding: 20px 40px;
  ```
  -  Different padding in every sides.
  - Clockwise Direction -> Top, Right, Bottom, Left 
  ```css
  padding: 10px 20px 30px 40px;
  ```

#### Margin
-  Used to create space around elements, outside of any defined borders.
-  Everything same as padding, all shorthands etc.
-  Now, As you see the output, I want to reduce the width.
  ```css
  width: 500px;
  ```
- Now, I want my element in center.
  ```css
  margin: 20px auto;
  ```
- Our Background start from border edge.
  ```css
    border: 5px dotted red;
    background: lightblue;
  ```

## Day 8
### Margin Collapsing
- himHTML
  ```html
  <body>
    <div class="box1">
      <h2>this is box 1</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt earum provident debitis eaque accusamus illum nihil nam voluptatum! Praesentium, tenetur!</p>
      
    </div>
    <div class="box2">
      <h2>this is box 2</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Incidunt earum provident debitis eaque accusamus illum nihil nam voluptatum! Praesentium, tenetur!</p>
    </div>
  </body>
  ```
- himCSS
  ```css
  .box1, .box2{
    border: 2px solid black;
    padding: 10px;
  }

  .box1{
      margin-bottom: 40px;
  }

  .box2{
      margin-top: 50px;
  }
  ```
  - What you think the total margin between box1 and box2?
  - It's 50px, not 90px(40 + 50).
  








<div align="center">
    <h3>Don't forget to ⭐ this repo</h3>
    <h5>Building with the COMMUNITY for the COMMUNITY ❤️</h5>
</div>