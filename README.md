# Today I Learned HTML-CSS-JS by [Diego Aaron Figueroa Campos]

## Week 1

### Saturday, Apr 2021 [Index and its basic structure]  

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

**Title**
This tag is the title displayed in the browser tab  
```html
 <head>
   <meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">
 </head>
```  


    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!--Nos ayuda a trabajar en proyectos reponsive-->

    <link rel="stylesheet" href="./css/style.css">
    <!--Linkea/Enlaza archivos de estilos u otros archivos que necesitemos en nuestro proyecto-->

  </head>
