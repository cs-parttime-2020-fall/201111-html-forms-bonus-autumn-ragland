# 20-11-11 CSS HTML Forms Bonus

### Set Up
1. copy the assignment git url in github after accepting the assignment
1. clone the assignment in the `html-css-basics` directory using `git clone COPIED URL`
1. open the assignment in VSCode

### Linking files
1. create an html file called `index.html` and use the `html:5` shortcut to generate the html, head, and body elements
2. create a css file called `style.css`
3. link the css file to the html file using the `link` tag in the `head` - set the `rel` attribute to `stylesheet` and the `href` attribute to the css file path
```html
 <link rel="stylesheet" href="style.css">
```
4. check that the file is linked by setting the `background-color` property of the body to any color other than white/gray and open the HTML file using `ctrl o` in the browser

### Assignment
Recreate the wireframe image included following the steps below. When the form is submitted the search input value should submit to `google.com/search`

#### Content
1. add a heading with the text `20 11 11 HTML Forms Bonus - Google Search`
1. add an HTML `form` element below heading - following elements will be nested in the form element
1. set the form elements `action` attribute to `https://google.com/search` - this will submit the form to google's search page
1. create an input of type text with a placeholder with the text `Search Anything...` and the `name` attribute set to `q`  - `q` is the accepted query parameter for a google search
1. create a button of type submit

#### Styling
1. center align all text in the body
1. optionally style the heading with a google font - the font used in the wireframe is `Press Start 2P`
1. give the input element a gray rounded border, padding, and set the width to 80% of the form element
1. give the submit button a rounded blue border and blue background, padding equal to the input field, and white text
 
### Push File Changes in the Terminal
1. `git status` : check if file changes have been made
1. `git add -A` : stage changes for commit
1. `git commit -m "meaningful message"` : commit changes with appropriate message
1. `git push` : reflect local changes remotely 

### Resources
[Concept Documentation on HTML + CSS](https://github.com/cs-parttime-2020-fall/part-time-program-syllabus/blob/master/htmlCSS.md)
