# Today I Learned HTML-CSS-JS by [Diego Aaron Figueroa Campos]

## Week 1

### Saturday, Apr 17 2021 [Index and its basic structure]  

#### Why "index.html"  
By default, servers search an **"index.html"** file to render it as the initial page, if it doesn't exist we would have to tell the server which will be the file name considered as the initial page. If we don't do that, our project structure will be **publicly visible**.

#### How to tell the navigator that the code is HTML5  
```html
<!DOCTYPE html>
```

#### How to tell the navigator the language content  
Sometimes, when you enter a website you get an alert saying "do you want to translate this page", this is thanks to the **lang attribute** in the **HTML tag**  
```html
<html lang="en">
</html>
```  

#### Identation importance  
Identation is crucial in any programming code, because it let to other developers identify and understand the code.
```html
<!DOCTYPE html>
<html lang="en">
  <head>
  </head>
  <body>
  </body
</html>
```   

#### Head tag  
This tag content is not visible to the end user. Here goes all important things to make posible the project execution in the way we want, for example:  
- Fonts
- Dependences
- Extern libraries
- Cascade StyleSheets  

**Meta tags**  
These are typically used to specify character set, page description, keywords, author of the document, and viewport settings.  

**Meta Charset**  
This attribute help us to include special characters and emojis in our page.
```html
<head>
  <meta charset="UTF-8" />
</head>
```  
**Meta description**  
This attribute shows a website description in the search engines and benefits the website SEO.  
```html
<head>
  <meta name="description" content="A simple guide and " />
</head>
``` 

**Meta robots**  
This attribute tells the navigator robots that track our page and show it in the user searches.  
```html
<head>
  <meta name="robots" content="HTML, CSS, JS" />
</head>
```  

**Meta viewport**  
This attribute help us to work with responsive pages.  
```html
<head>
  <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
</head>
```  

**Title**  
This tag is the title displayed in the browser tab.  
```html
<head>
  <title>Today I Learned HTML-CSS-JS</title>
</head>
```  

**Link**  
This tag links an external resource into our page.
```html
<head>
  <link rel="stylesheet" href="style.css">Today I Learned HTML-CSS-JS />
</head>
```  

### Sunday, Apr 18 2021 [Index and its basic structure]   

#### Body tag  
Here goes the visible content to the end user  
```html
<body>
</body>
```  

##### Container tags  
**Header**  
It's is the page header, It usually contains a navigation menu.  
```html
<header>
  <nav>
    <ul>
      <li>Home</li>
      <li>About</li>
      <li>Contact</li>
    </ul>
  </nav>
</header>
```  

![image](https://user-images.githubusercontent.com/45472379/115162995-4b968580-a06c-11eb-9739-bd08b8f68e63.png)  

**Nav**
It usually is inside header tag, its purpose is provide navigation links.  
```html
<nav>
  <ul>
    <li>About</li>
    <li>Plans</li>
    <li>Pricing</li>
  </ul>
</nav>
```  

![image](https://user-images.githubusercontent.com/45472379/115162987-3f122d00-a06c-11eb-8003-492ecfdc7b8f.png)  

**Main**  
It represents the main body content, this should be unique.  
```html
<main>
  <aside>
    <article>
      <h2>Diego Figueroa</h2>
    </article>
  </aside>
  <section>
    <h2>My projects<h2>
  </section>
</main>
```  

![image](https://user-images.githubusercontent.com/45472379/115162980-33bf0180-a06c-11eb-9c9d-0a8ba68c1db1.png)  

**Section**    
It represents generic sectioning element, and should only be used if there isn't a more specific element to represent it, it typically by including a heading. 
```html
<section>
  <h2>My projects<h2>
  <p>Pimglo</p>
</section>
```  

![image](https://user-images.githubusercontent.com/45472379/115162968-1f7b0480-a06c-11eb-9a39-e76d822436eb.png)  

**Articlee**  
It represents a self-contained composition which is intended to be independently distributable or reusable.  
```html
<article>
  <h2>Diego Figueroa</h2>
  <p>Front-end developer</p>
</article>
```  

![image](https://user-images.githubusercontent.com/45472379/115162952-0b370780-a06c-11eb-854a-1f0ff1b15410.png)  

**Ol**  
It represents an ordered list of items, typically rendered as a numbered list.  
```html
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>JS</li>
  <li>GIT</li>
</ol>
```  

![image](https://user-images.githubusercontent.com/45472379/115163071-ad56ef80-a06c-11eb-90bc-4e54f5356c1d.png)  

**Ul**  
It represents an unordered list of items, typically rendered as a bulleted list.  

```html
<ul>
  <li>Responsability</li>
  <li>Empathy</li>
  <li>Proactive</li>
  <li>Self-taught</li>
</ul>
```  

![image](https://user-images.githubusercontent.com/45472379/115163105-d8d9da00-a06c-11eb-9e80-a10446711b7d.png)  

**Li**  
It represents an item in a list. It must be contained in a parent element  

![image](https://user-images.githubusercontent.com/45472379/115163162-1f2f3900-a06d-11eb-8875-34cc1996b691.png)  

**Footer**  
It represents a footer for its nearest sectioning content or sectioning root element  

![image](https://user-images.githubusercontent.com/45472379/115163255-c1e7b780-a06d-11eb-858b-6faf52bc2931.png)  

##### Content tag

**P**  
It represents a paragraph  

![image](https://user-images.githubusercontent.com/45472379/115163222-851bc080-a06d-11eb-8963-e77975eb3352.png)  

**H1-H6**  
It represent six levels of section headings. <h1> is the highest section level and <h6> is the lowest.

![image](https://user-images.githubusercontent.com/45472379/115163215-7af9c200-a06d-11eb-8265-0e75a85ad8d2.png)  

**a**  
This element with its href attribute, creates a hyperlink to web pages, files, email addresses, locations in the same page, or anything else a URL can address  

![image](https://user-images.githubusercontent.com/45472379/115163348-40445980-a06e-11eb-9cfe-b2d5c762e437.png)  

#### HTML5 General Semantic

![image](https://user-images.githubusercontent.com/45472379/115162253-23a52300-a068-11eb-89f7-0e1057ca4be8.png)  

### Monday, Apr 19 2021 [Challenge: Make a supermarket shopping list]  
```html
<ul>
  <li>Fruits</li>
  <ol>
    <li>Apple</li>
    <li>Apple</li>
  </ol>
  <li>Meat</li>
  <ol>
    <li>Chicken</li>
    <li>Ground beef</li>
  </ol>
  <li>Vegetables</li>
  <ol>
    <li>Lemon</li>
    <li>
      <a href="shorturl.at/gmBGK" target="_blank">Carrot<a>
    </li>
  </ol>
</ul>
<p>Created with love</p>
```
### Tuesday, Apr 20 2021 [HTML Tag Anatomy]  

![image](https://user-images.githubusercontent.com/45472379/115413441-cb326a80-a1ba-11eb-8ab1-a1ca5f35855c.png)  

#### Type of images  
**Lossy vs Lossless**
There are 2 types of images, lossless and lossy, it depends on the image format.  

**Lossless** 
It lose nothing from the original image. Lossless images are bigger than lossy ones.

**Lossy**  
It approximates the original image, reducing the file size but also the quality. Lossy images are smaller than lossless one.   

![image](https://user-images.githubusercontent.com/45472379/115417122-f9657980-a1bd-11eb-88ea-a45ede886c14.png)  

#### Images optimization  
On average, an image should weigh 70 kb  

**Tools to get a better image optimization**  
- https://tinypng.com/
- https://www.verexif.com/

**Challenge, using images in a shopping cart**  
```html
<ul>
  <li>Fruits</li>
  <ol>
    <li>Apple</li>
    <img src="https://images.pexels.com/photos/206959/pexels-photo-206959.jpeg?cs=srgb&dl=pexels-pixabay-206959.jpg&fm=jpg" width="200px" alt="apple" />
    <li>Lemon</li>
    <img src="https://images.pexels.com/photos/952360/pexels-photo-952360.jpeg?cs=srgb&dl=pexels-lukas-952360.jpg&fm=jpg" width="200px" alt="lemon" />
  </ol>
  <li>Meat</li>
  <ol>
    <li>Chicken</li>
    <img src="https://images.pexels.com/photos/1059943/pexels-photo-1059943.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" width="200px" alt="chicken food" />
    <li>Ground beef</li>
    <img src="https://images.pexels.com/photos/128401/pexels-photo-128401.jpeg?cs=srgb&dl=pexels-angele-j-128401.jpg&fm=jpg" width="200px" alt="ground beef" />
  </ol>
  <li>Vegetables</li>
  <ol>
    <li>Potato</li>
    <img src="https://images.pexels.com/photos/1059943/pexels-photo-1059943.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" width="200px" alt="potatoes" />
    <li>
      <a href="shorturl.at/gmBGK" target="_blank">Carrot<a>
    </li>
    <img src="https://images.pexels.com/photos/143133/pexels-photo-143133.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940" width="200px" alt="carrot" />
  </ol>
</ul>
<p>Created with love</p>
```
