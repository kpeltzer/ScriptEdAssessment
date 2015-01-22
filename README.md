1. Given the following html document, which are the two required elements needed to make this a valid page? (A.HP.1.1 Student can employ HTML head tags && A.HP.1.2 Student can employ HTML body tags)
  ```html
  <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN"
    "http://www.w3.org/TR/html4/strict.dtd">
    <HTML>
      <!-- Missing element #1 -->
  
      <!-- Missing element #2 -->
    </HTML>
  ```
  * **&lt;head>**
  * &lt;title>
  * **&lt;body>**
  * &lt;div>
  * &lt;script>

2. A webpage is often broken up into multiple sections. Which block of html below best matches the output given here? (A.HP.2.1 Student can create sections and groups in HTML (divs/spans))
<br><div><span>I'm section 1!</span></div><br><div><span>I'm section 2!</span></div>

  * ```<p>I'm section 1! I'm section 2!</p>```
  * ```<title>I'm section 1!</title><span>I'm section 2!</span>```
  * ```<div><span>I'm section 1!></span></div><div><span>I'm section 2!></span></div>``` <- correct


3. How many sections are defined in the below html page? (A.HP.2.1 Student can create sections and groups in HTML (divs/spans))
  ```html
  <div class="section">
  </div>
  <div class="section">
  </div>
  <div class="section">
  </div>
  ```
  * 0
  * 1
  * 2
  * **3**
  * 4

4. In the html below, there is a list of fruits, and a list of vegetables. Which CSS rule would correctly change the color of the fruits to blue? A.HP.2.2 Student can style sections and groups in HTML accordingly using CSS.
  ```html
  <div>
    <ul>
      <li>Banana</li>
      <li>Orange</li>
      <li>Mango</li>
    </ul>
  </div>
  <div>
    <span>Broccoli</span>
    <span>Potato</span>
  </div>
  ```
  * ```body {border-color: blue;}```
  * ```span {color: blue;}```
  * ```ul {color: blue;}``` <- correct
  * ```div {color: black;}```

5. Consider the following list of book titles, printed using structure (HTML elements), and style (CSS). Which of the following attributes can be consider the *style*? (A.HP.3.1 Student can identify the separation of structure and style in the creation of web pages.
 A.HP.3.2 Student can explain the separation of structure and style in the creation of web pages.)
  <ol>
    <li>John Steinbeck's The <span style="text-decoration:underline;">Grapes</span> of Wrath</li>
    <li>Harper Lee's To Kill A Mockingbird</li>
  <ol>
  * The apostrophe in "Steinbeck"
  * The title "Grapes of Wrath"
  * **The underline underneath "Grapes"**
  * The fact that the books are on separate lines

6. What is the correct CSS rule that will change the text in the ```<span>``` below to blue? ( A.S.1.1 Student can use CSS selectors to style elements by ID.)
  ```html
  <span id="sentence">The quick brown fox...</span>
  ```
  * ```text {color:blue;}```
  * ```.sentence {color: blue;}```
  * ```#sentence {color:blue;}```

7. Given the HTML below, what will the final output look like in a web browser? (A.S.1.2 Student can use CSS selectors to style elements by class.)
  ```html
  <div>
    <p class="paragraph">Coca Cola</p>
    <p id="paragraph">Pepsi</p>
  </div>
  <style>
      .paragraph {color: yellow;}
  </style
  ```
  * "Coca-cola" will show up as yellow, and "Pepsi" will be black.
  * "Pepsi" will be yellow, and "Coca-cola" will be black.
  * Both "Coca-cola" and "Pepsi" will be black.
<br>
<br>

8. Fill in the blank in the following sentence with the correct term: "An element with a CSS rule of position:_______ will stay right where it is as the page is scrolled." A.S.2.1 Student can explain the difference between static, absolute, and fixed positioning in web pages.)
  * Static
  * Fixed
  * Absolute
