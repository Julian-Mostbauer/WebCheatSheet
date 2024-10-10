# Basic Web Techniques

## Reading Assignment 2: WWW and HTML

### Html

1. Name the components of html elements properly
- Attributes, child notes
2. Identify void elements and how they are denoted
- They cant have children and can be self closed <tag/>
4. Identify attributes
- ```<tag atr1="" atr2=""/> ``` used to add paramaters to html tags
6. Write down the correct ``DOCTYPE`` declaration for html 5
- ```<!DOCTYPE html>```
7. Write down syntactically correct statements for the following elements
   - Article (``<article>``)
   ```html
   <article>
      <section>
        <p>Text</p>
      </section>
    </article>
   ```
   - Body (``<body>``)
   - line break (``<br/>``)
   - Headings (``<h1>``, ...)
   - Section with meta-information (``<head>``)
   - Top level element (``<html>``)
   - Image named ``Team.jpg`` (``<img src="Team.jpg">``)
   - Paragraph (``<p>``)
   - Section (``<section>``)
   - Label appearing in the title bar (``<title>``)
   - Link to other pages (``<a>``)
     ```html 
      <a href="https://www.example.com">Example</a> 
      ``` 
   - Comment     
     ```html
      <!-- Text --> 
      ```
   - Head with title and meta elements
   ```html
   <head>
      <title>Document Title</title>
      <meta charset="UTF-8">
   </head>
   ```

## Css

1. **Components of a CSS rule:**
   - **Selector:** Defines the HTML element(s) to style.
   - **Declaration Block:** Contains one or more declarations, enclosed in curly braces `{}`.
   - **Declaration:** Composed of a **property** (e.g., `color`) and a **value** (e.g., `blue`), separated by a colon (`:`).
   - **Example:**
     ```css
     p {
       color: blue;
       font-size: 16px;
     }
     ```

2. **Combinators in CSS:**
   - **Direct Child (`>`):** Targets direct children of an element.
     ```css
     div > p {
       color: red;
     }
     ```
   - **Descendant (empty space):** Targets all descendants of an element.
     ```css
     div p {
       color: blue;
     }
     ```
   - **Adjacent Sibling (`+`):** Targets the next sibling immediately after an element.
     ```css
     h1 + p {
       color: green;
     }
     ```
   - **General Sibling (`~`):** Targets all siblings after an element.
     ```css
     h1 ~ p {
       color: purple;
     }
     ```

3. **Specify colors:**
   - **Color Names:**
     ```css
     color: red;
     background-color: blue;
     ```
   - **Hexadecimal Notation:**
     ```css
     color: #ff0000;
     background-color: #0000ff;
     ```

   - **RGB(A)**
      ```css
      color: rgb(255,120,0):
      color: rgba(255,120,0,0.5)
      ```
4. **Declarations for color and background-color:**
   ```css
   color: #333333; /* text color */
   background-color: #f0f0f0; /* background color */
   ```

5. **Pseudo-classes for the `<a>` element:**
   ```css
   a:link { color: blue; } /* unvisited link */
   a:visited { color: purple; } /* visited link */
   a:hover { color: red; } /* mouse over link */
   a:active { color: green; } /* selected link */
   ```

6. **Declaration for background image:**
   ```css
   background-image: url('image.jpg');
   ```

7. **Declaration for text alignment:**
   ```css
   text-align: left; /* or right, center, justify */
   ```

8. **Declaration for text decoration:**
   ```css
   text-decoration: underline; /* or overline, line-through */
   ```

9. **Declaration for text transformation:**
   ```css
   text-transform: uppercase; /* or lowercase, capitalize */
   ```

10. **Difference between serif and sans-serif fonts:**
    - **Serif Fonts:** Small lines or strokes on letters
    - **Sans-serif Fonts:** No extra strokes

11. **Declaration for font families:**
    ```css
    font-family: "Times New Roman", serif;
    font-family: Arial, sans-serif;
    ```

12. **Declaration for font styles:**
    ```css
    font-style: normal;
    font-style: italic;
    ```

13. **Declaration for font sizes:**
    ```css
    font-size: 16px; /* Can also use em, rem, %, or other units */
    ```

14. **Declaration for font weights:**
    ```css
    font-weight: normal; /* or bold, 100 to 900 */
    ```