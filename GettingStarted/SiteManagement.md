# Site Hosting/Creation/Management
## Overview 
<img src="/images/html5.png" height="80" weight="80"></img>   <img src="/images/css.png" height="80" weight="80"></img>    <img src="/images/javascript.png" height="80" weight="80"></img>  

- Creating your first `Hosted Pages Project`(with Github)
- Basic HTML and CSS 
    - What `HTML` is and it's syntax 
    - What `CSS` is and it's syntax 
    - Linking `CSS` to `HTML` 
- JavaScript Brief Explanation
    - What JavaScript does for a website (can do everything)


### Hosting w/ Github Pages 

Hosting with `Github Pages` has never been easier! Here is 
a step by step process on getting your first project hosted. 
#### Hosting Instructions 
1. Create a repository in your `Github`.
    - Name your repository following the example below! 
        - `youraccountname.github.io`
2. Choose whether you want your repository to be `Public` or `Private`.
3. Make sure to initialize a read me! 
4. If you choose to do your workflow with `Git` using `Git Bash` her are some example commands. 
    - `~ $ git clone https://github.com/username/username.github.io`
    - `~ $ cd username.github.io`
    - `~ $ echo "Hello World" > index.html`
    - `~ $ git add --all //these are pushing and commiting commands`
    - `~ $ git commit -m "Initial commit" //these are pushing and commiting commands`
    - `~ $ git push -u origin main //these are pushing and commiting commands`
5. You are finished in your browser you can just type in your URL as shown below. 
    - `https://yourusername.github.io` 
Other Resource (If you need it explained different): [https://pages.github.com/](https://pages.github.com/)

### Basics of HTML and CSS

#### Working w/ HMTL
The purpose of `HTML (Hypertext Markup Language)` is to serve a structure/foundation. We build on top of HTML with other technologies for example CSS and Javascript. 

Making a Basic HTML Template: 
1. Make a file under your working folder: 
    - `right click` -> `new file`
    or 
    - Hover over the main folder and click the <img src="newfile.png" height="40" width="40">
    - Naming convention for home page is `index.html` (this is what we will name our file)
2. Creating Structure 
- Here is a basic HTML structure. We can easily do this with the extension 
I had you download earlier.

```
    <!-- This is what commenting looks like in HMTL -->
    <!DOCTYPE html>           //tells the browser what document it's receiving
    <html lang="en">           //what language the doc is in 
    <head>                     //focuses on the name of the tab at the top and document resources
        <meta charset="UTF-8"> //tells us what unicode standard we will use
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>   //Holds content
    </body>
    </html> //ending tag for the html document
```

3. Types of tags we can use in HTML
- Header Tags: 
    - Range in size from largest to smallest: `h1/h2/h3/h4/h5/h6`.
    - They start at h1(being the largest) and end in h6(being the smallest).
- Anchor Tags: 
    - An anchor tag `<a></a>` holds a link to another page.
     - This can be in file format or in URL format
    - Example of finished anchor tag: 
    `<a href="https://www.youtube.com/watch?v=rz5TGN7eUcM">Funny Video</a>` 
- Text styling tags: 
    - Bold and Strong: 
        - `<b>We are Bold</b>` this makes the text bold.
        - `<strong>We are Bold as well</strong>` this also make the text bold.
        - The difference between `bold and strong` would be that strong holds greater importance. `Strong` should be used for high importance and labeling paragraphs. 
    - Underline: 
        - `<u>Underlined text</u>` this is an example of underlined text. 
    - Emphasis Element: 
        - `<em>Emphasized text</em>` this is an example of emphasized text.
        - It is typically used to represent stress on a word. (looks like italics)
- Breakline: 
    - `<br>` used like an `endl` or `\n`
- Listing HTML: 
    - Unordered list: 
        - `<ul></ul>` un ordered list tag
        - `<li></li>` list item
    - Ordered List: 
        - `<ol></ol>` ordered list tag
    ```
    <!-- Unordered List -->
      <h3>Names</h3>
        <ul>
         <li>Jim</li>
         <li>Dwight</li>
         <li>Michael</li>
        </ul>

    <!-- Ordered List -->
    <h3>Favorite Sports</h3>
        <ol>
         <li>Golf</li>
         <li>Rock Climbing</li>
         <li>Baseball</li>
        </ol>
    
    //Note: The syntax is the same, it is just convention to use in the proper context. 
    ```
- Paragraph: 
    - `<p>Lorem Ipsum</p>` this will contain entire paragraphs 
    - We can utilized the earlier text styling tags inside of this.

4. Making Content of Page 
- Here is an example of some basic content to the page. 
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8"> 
        <meta http-equiv="X-UA-Compatible" content="IE-edge">

        <title>MSU ACM Chapter</title>
    </head>
    <body> 
        <!-- Navbar -->
        <nav>
            <img></img>
            <ul>
              <li><a href="index.html">Home</a></li>
              <li><a href="about.html">About</a></li>
              <li><a href="events.html">Events</a></li>
            </ul>
        </nav>
        <!-- Title -->
        <h1 id="title-h1">Midwestern State University ACM Chapter</h1>
        
    </body>
</html>  
```
- In the provided structure we have made the start to our front page of our ACM "website". 
- It contains an unordered list inside of a `nav` tag which will be the start of our navbar for now. 



#### Working w/ CSS 
The purpose of `CSS (Cascading Style Sheets)` is to add some styling to our HTML pages. `CSS` can do a whole bunch of different things from changing `text fonts/colors/etc`, making `animations`, and `media queries`. 

