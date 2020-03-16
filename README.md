# 01 HTML CSS Git: Code Refactor

## Summary 

The purpose of the assignment was to refactor an existing website using the prompt and parameters below.

```
User Story

AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```
The assignment was then graded upon the following criteria:

1. Semantic HTML
2. Logical Structure
3. Accessible Alt Attributes
4. Sequential Header Elements
5. Concise & Descriptive Title

```
Acceptance Criteria

GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Site Picture
![Site](./assets/images/code-refactor.png)

## Technologies Used
- HTML - used to create elements on the DOM
- CSS - styles html elements on page
- Git - version control system to track changes to source code
- GitHub - hosts repository that can be deployed to GitHub Pages

## Code Snippet

Below is an example of a block of code in the HTML file where I refactored the spacing and indentation as well as added semantic Header tags.

```html
  <!-- Added Header tags, removed Header class, & adjusted spacing/indentation throughout section -->
    <header>
        <h1>Hori<span id="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization
                    </a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management
                    </a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing
                    </a>
                </li>
            </ul>
        </div>
    </header>
```
Below is an example of a block of code in the CSS file where I refactored the Header class and changed redundant or removed unneccesary tags.

```css
/* <!-- Removed Header class to reference semantic tag throughout --> */
header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}

header h1 {
    display: inline-block;
    font-size: 48px;
}

/* <!-- Changed seo class to id for single item --> */
header h1 #seo {
    color: #d9dcd6;
}

header div {
    padding-top: 15px;
    margin-right: 20px;
    float: right;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 20px;
}

/* <!-- Removed unneccesary li tag --> */
header ul {
    list-style-type: none;
}

/* <!-- Removed unneccesary ul tag --> */
header li {
    display: inline-block;
    margin-left: 25px;
}
```

## Author Links

Will Gibson

[LinkedIn](https://www.linkedin.com/in/wtgibson/)

[GitHub](https://github.com/wtgibson/1-code-refactor)

Special thanks to Brad Davis, Mahisha Gunasekaran, Kerwin Hy for their input and assistance with the assignment!
