<table>
  <tr>
    <td>
      <h1>
        <strong>HTML Tutorial</strong>
      </h1>
      <p>HTML is the code used to display a website.</p>
    </td>
    <td>
    <img src="https://github.com/user-attachments/assets/6d16b691-4a68-49e9-b2b0-498a5bb75294">
    </td>
  </tr>
</table>

----
## Example of a HTML
Here is a example of how a html code will be like.
````html
<!DOCTYPE html>
<html>
  <head>
    <title>HTML website</title>
  </head>
  <body>
    <h1>Hello!</h1>
    <hr>
    <p>This is a simple website</p>
  </body>
</html>
````
----
## Head
### Title
````html
<title>Title</title>
````
|The word in the title tag will be display in the browser tap|![TTitle](https://richardliucode.github.io/richardcode/external/gRIYaScdCyOOgPBNKNyWwWlKYbPnXFazqNoNRUWRdnSeofSUPbKWyphgsjSytEBKvrpxBY.png)|
|-|-|
### Link
| HTML | Description |
|-|-|
|````<link rel="icon" href="favicon.png">````| Set the favicon |
|````<link rel="stylesheet" href="style.css">````| Load the Css |
### Meta 
| HTML | Description |                                                                   
| ---------------------------------------------------------------------------- | --------------------------------------------- |
| `<meta name="author" content="Richard">`                                     | Defines the author of the document            |
| `<meta name="description" content="This is a website that talk about html">` | Provides a brief summary for SEO              |
| `<meta charset="UTF-8">`                                                     | Sets character encoding to UTF-8              |
| `<meta http-equiv="refresh" content="5;url=https:example.com">`              | Redirects page to another URL after 5 seconds |
| `<meta name="viewport" content="width=device-width, initial-scale=1.0">`     | Makes the site responsive on mobile devices   |
----
## UI Element
### Parameter Inside UI Element Tag
|parameter|description|available tag|
|-|-|-|
|id| The only id for a element, and can be use to call in css/javascript | All UI Element Tag |
|class| The class is for a group element to use a style like ````.btn{...}```` in css| All UI Element Tag |
|href | Hyper link, like ````href="https://github.com"````|[````<a>````](https://github.com/RichardLiuCode/HTMLtutorial/#hyper-link), [````<link>````](https://github.com/RichardLiuCode/HTMLtutorial/blob/main/README.md#link)|
|src| The source of a url that load for an element. |[````<img>````](https://github.com/RichardLiuCode/HTMLtutorial/#image), [````<audio>````](https://github.com/RichardLiuCode/HTMLtutorial/#audio), [````<video>````](https://github.com/RichardLiuCode/HTMLtutorial/#video), [````<iframe>````](https://github.com/RichardLiuCode/HTMLtutorial/#iframe), [````<script>````](https://github.com/RichardLiuCode/HTMLtutorial/#javascript)|
### Heading 
| # | HTML |
| - | - |
|1| ````<h1>This is a first heading</h1>```` |
|2| ````<h2>This is a second heading</h2>```` |
|3| ````<h3>This is a third heading</h3>```` |
|4| ````<h4>This is a fourth heading</h4>```` |
|5| ````<h5>This is a fifth heading</h5>```` |
|6| ````<h6>This is a sixth heading</h6>```` |

### Paragraph
````html
<p>This is a paragraph</p>
````

### Line Break
````html
<br>
````

### Dividing Line
````html
<hr>
````

### Hyper Link
````html
<a href="https://github.com">GitHub</a>
````

### Textarea
````html
<textarea>
Long text
</textarea>
````
### List
- Order List
````html
<ol>
  <li>Orange</li>
  <li>Banana</li>
  <li>Apple</li>
  <li>Strawberry</li>  
</ol>
````
<table>
  <tr>
    <td>Order list is a list that <br>with number for index</td>
    <td>
      1. Orange
      <br>
      2. Banana
      <br>
      3. Apple
      <br>
      4. Strawberry
    </td>
  </tr>
</table>

- Unorder List
````html
<ul>
  <li>Orange</li>
  <li>Banana</li>
  <li>Apple</li>
  <li>Strawberry</li>  
</ul>
````
<table>
  <tr>
    <td>Unrder list is a list that <br>with "•" for index</td>
    <td>
      • Orange
      <br>
      • Banana
      <br>
      • Apple
      <br>
      • Strawberry
    </td>
  </tr>
</table>

### Input
````html
<input>
````
| HTML | Type | Description |
| - | - | - |
| ````<input type="text">```` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;| Text | The input can type any type of text. |
| ````<input type="search">````| Search | The text input that the user can click the "×" to clear all the text in the input when they need to reset the text input to type another things. |
| ````<input type="number"````| Number | The input can only type number. |
| ````<input type="url">````| URL |The input field for web URL, but it can still enter any type of text. |
| ````<input type="date">```` | Date | The input field will automatically convert the input text into date format, the user can use a calendar to select the date. |
| ````<input type="time">```` | Time | The input field will automatically convert the input text into time format, the user can use a clock to select the date. |
| ````<input type="email">```` | Email | The input field for email, but it can still enter any type of text. |
| ````<input type="tel">```` | Telephone | The input field for phone number, but it can still enter any type of text. |
| ````<input type="password">```` | Password | The input field will automatically convert the input text into dots filler to hide the password |
| ````<input type="file">```` | File | The input looks like a button, when the user click the input, and the file explorer will be open let the user select to upload. When you use this input, you need to add the filereader is the javascript code  |
| ````<input type="color">```` | Color | The input looks like a button, when the user click the input, and it will open a color menu like a rainbow to let the user to select a color |
| ````<input type="checkbox">```` | Checkbox | A checkbox that can be check or blank |
| ````<input type="radio">```` | Radio | A button that can only be select one in the same group id, just like multiple choice. |


### Button
````html
<button>Click Me</button>
````

### Dropdown 
````html
<select>
  <option disabled selected> Choose your code language</option>
  <option>HTML</option>
  <option>Css</option>
  <option>Javascript</option>
  <option>Python</option>
</select>
````
|Special Parameter| Description |
|-|-|
|disabled selected|To make an option in the dropdown that can only be display and cannot be select.|

### Image
````html
<img src="image.png">
````

### Audio
````html
<audio controls>
  <source src="audio.mp3">
</audio>
````
|Special Parameter| Description |
|-|-|
|controls| To show the controler of the player |

### Video
````html
<video controls>
  <source src="video.mp4">
</video>
````
|Special Parameter| Description |
|-|-|
|controls| To show the controler of the player |

### Iframe
````html
<iframe src="https://somethings.com"></iframe>
````
|Special Parameter| Description |
|-|-|
|sandbox|Block some permissions to for the iframe tag, Especially when you don't trust the website you embeded in the iframe tag.|
|allow| Allow some permission in the iframe tag when needed and you trust the website is save. |
|allowfullscreen|Allow the embedded website can be go to full screen mode.|
- Remember! Some website has x-frame-option, that kind of website cannot be embeded into an iframe.
----

## Embeded Css/Javascript
### Css
````html
<style>
  body{
    background-color:skyblue;
  }
</style>
````

Embeded external
````html
<link rel="stylesheet" href="style.css">
````

### Javascript
````html
<script>
  console.log("message")
</script>
````
Embeded external
````html
<script src="script.js"></script>
````
----
# How to view page's source on a website
4 way to view page source
- You can click ````Ctrl```` + ````U```` on browser when you want to view the source code of the website you current open
- Or add the words ````view-source:```` before the URL, like if you want to view the source code of ````https://examole.com````, type ````view-source:https://examole.com```` on the browser.
- Or click ````F12```` or ````Ctrl```` + ````Shift```` + ````I```` to open the developer tool, then go to "Element", then you will see the source code
- You can also use tool like [https://www.view-page-source.com](https://www.view-page-source.com/), enter the URL that you want so view source, then it will display the source code, you can also download then as a html file.
# Other HTML tutorial document
- [https://studio.code.org/docs/ide/weblab](https://studio.code.org/docs/ide/weblab)
- [https://www.w3schools.com/html/default.asp](https://www.w3schools.com/html/default.asp)

