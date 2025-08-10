<table>
  <tr>
    <td>
      <h1>
        <strong>HTML Tutorial</strong>
      </h1>
      <p>HTML or Hyper Text Markup Language is the code used to display a website.</p>
    </td>
    <td>
    <img src="https://github.com/user-attachments/assets/6d16b691-4a68-49e9-b2b0-498a5bb75294">
    </td>
  </tr>
</table>

----
## Example of a HTML
Here is an example of how a html code will be like.
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
## DOCTYPE html
````html
<!DOCTYPE html>
````

<p>Type this at the very top of your HTML code</p>

----
## Head
### Title
````html
<title>Title</title>
````
|The text inside the title tag will be displayed in the browser tab|![TTitle](https://richardliucode.github.io/richardcode/external/gRIYaScdCyOOgPBNKNyWwWlKYbPnXFazqNoNRUWRdnSeofSUPbKWyphgsjSytEBKvrpxBY.png)|
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

<table>
  <tr>
    <th>#</th>
    <th>HTML</th>
  </tr>
  <tr>
    <td>1</td>
    <td>
      <pre>&lth1&gtThis is a first heading&lt/h1&gt</pre>
    </td>
  </tr>
  <tr>
    <td>2</td>
    <td>
      <pre>&lth2&gtThis is a second heading&lt/h2&gt</pre>
    </td>
  </tr>
  <tr>
    <td>3</td>
    <td>
      <pre>&lth3&gtThis is a third heading&lt/h3&gt</pre>
    </td>
  </tr>
  <tr>
    <td>4</td>
    <td>
      <pre>&lth4&gtThis is a fourth heading&lt/h4&gt</pre>
    </td>
  </tr>
  <tr>
    <td>5</td>
    <td>
      <pre>&lth5&gtThis is a fifth heading&lt/h5&gt</pre>
    </td>
  </tr>
  <tr>
    <td>6</td>
    <td>
      <pre>&lth6&gtThis is a sixth heading&lt/h6&gt</pre>
    </td>
  </tr>
</table>

### Paragraph
````html
<p>This is a paragraph</p>
````

### Line Break
````html
<br>
````

<table>
  <tr>
    <td colspan="2">Sample</td>
  </tr>
  <tr>
    <td>
      <pre>&ltp&gtThis is the first line &ltbr&gt This is the second line&lt/p&gt</pre>
    </td>
    <td>
    This is the first line
    <br>
    This is the second line
    </td>
  </tr>
</table>

### Dividing Line
````html
<hr>
````

<table>
  <tr>
    <td>
      <pre>This is the first line<br>&lthr&gt<br>This is the second line</pre>
    </td>
    <td>
    This is the first line
    <hr>
    This is the second line
    </td>
  </tr>
</table>

### Comment
````html
<!-- This is a comment-->
````

- A comment is for label the code and will not be display in the website.
### Hyper Link
````html
<a href="https://github.com">GitHub</a>
````
<table>
  <tr>
    <td>Sample<br>(The blue text is the hyper link.)</td>
    <td>
      Example Sentence: <br>You can go to <a href="https://github.com" target="_blank">GitHub</a> to host your website
    </td>
  </tr>
</table>

### Textarea
````html
<textarea>
Long text
</textarea>
````

### Div
````html
<div></div>
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
    <td>Sample<br>An ordered list is a list with numbers as indexes.</td>
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
    <td>Sample<br>Unorder list is a list that <br>with "•" for index</td>
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

### Table
````
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Tom</td>
    <td>11</td>
  </tr>
  <tr>
    <td>Sam</td>
    <td>13</td>
  </tr>
</table>
````
<table>
  <tr>
    <td>Sample</td>
    <td>
      <table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Tom</td>
    <td>11</td>
  </tr>
  <tr>
    <td>Sam</td>
    <td>13</td>
  </tr>
</table>
    </td>
  </tr>
</table>

### Details
````
<details>
  <summary>Title</summary>
  Description
</details>
````
<table>
  <tr>
    <td>Sample<br>(Click the ">")</td>
    <td>
      <details>
      <summary>Title</summary>
        Description
      </details>
    </td>
  </tr>
</table>

### Form
````html
<form action="https://example.onrender.com/api">
  <input type="text" name="q" placeholder="Enter your message">
  <br>
  <input type="submit" value="Submit">
</form>
````

### Input
````html
<input>
````

<table>
  <tr>
    <td>Sample</td>
    <td>
      <br>
      <table>
        <tr>
          <td>_ Enter your name ____________</td>
        </tr>
      </table>
      <br>
    </td>
  </tr>
</table>

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

|Special Parameter| Description |
|-|-|
|placeholder|To label the text input before the user type any text.|

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

<table>
  <tr>
    <td>Sample</td>
    <td>
      <img src="https://richardliucode.github.io/richardcode/external/cdafuvjerbufernvbuefrvnbfeuvneut23458934285-cercv-v-UwokTTaAldAGSVRIXgseQRbfWvOtmiKPVmRJLHtrbtn-Screenshot-2025-08-07-130623.png">
    </td>
  </tr>
</table>

|Special Parameter| Description |
|-|-|
|disabled selected|To make an option in the dropdown that can only be display and cannot be select.|

### Image
````html
<img src="image.png">
````

|Special Parameter| Description |
|-|-|
| alt | To label the image if the image cannot display. |
### Audio
````html
<audio controls>
  <source src="audio.mp3">
</audio>
````
<table>
  <tr>
    <td>
      Sample
    </td>
    <td>
     <img src="https://richardliucode.github.io/richardcode/external/vbndferjvnberujvnerujvendskvmasekmrvekivmrseikajmvesakirfvmeaslvrkmvghghgbgbntlrkv43534534543Screenshot%202025-08-10%20003814.png">
    </td>
  </tr>
</table>

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
|srcdoc|Embeded plain text as html in iframe |
|sandbox|Block some permissions to for the iframe tag, Especially when you don't trust the website you embeded in the iframe tag.|
|allow| Allow some permission in the iframe tag when needed and you trust the website is save. |
|allowfullscreen|Allow the embedded website can be go to full screen mode.|
- Remember! Some website has x-frame-option, that kind of website cannot be embeded into an iframe.
----

## Embeded Css/Javascript
### CSS
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
# Where can you write HTML
## Online
These are some website that you can write HTML code online
- [Code.org WebLab](https://studio.code.org/projects/weblab/new)
- [Visual Studio code Online](https://vscode.dev/)
- [W3 School](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_editor)
- [https://onecompiler.com/html](https://onecompiler.com/html)
- [https://htmlcodeeditor.com/](https://htmlcodeeditor.com/)
- [HTML editor made by Richard Liu](https://richardliucode.github.io/htmleditor/v1.3/)

## Download Visual Studio Code

You can download the Visual Studio Code to write and edit HTML
- [Download Visual Studio](https://code.visualstudio.com/download)
- [Download on Microsoft Store](https://apps.microsoft.com/detail/xp9khm4bk9fz7q?hl=zh-TW&gl=US)
## Notepad
You can also write html code in notepad

Steps:
1. Click ````Win```` + ````R````
2. Enter "notepad"
3. Type your HTML code
4. Click "File"
5. Select "Save as"
6. Type your project's name but ended with ".html"
7. Select the "Save as type" to "All files"
8. Open the file you just save in the file explorer
# How to view html source code on a website
4 way to view page source
- You can click ````Ctrl```` + ````U```` on browser when you want to view the source code of the website you current open
- Or add the words ````view-source:```` before the URL, like if you want to view the source code of ````https://examole.com````, type ````view-source:https://examole.com```` on the browser.
- Or click ````F12```` or ````Ctrl```` + ````Shift```` + ````I```` to open the developer tool, then go to "Element", then you will see the source code
- You can also use tool like [https://www.view-page-source.com](https://www.view-page-source.com/), enter the URL that you want so view source, then it will display the source code, you can also download then as a html file.
----
# Other HTML tutorial document
- [https://studio.code.org/docs/ide/weblab](https://studio.code.org/docs/ide/weblab)
- [https://www.w3schools.com/html/default.asp](https://www.w3schools.com/html/default.asp)
- [https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements)

