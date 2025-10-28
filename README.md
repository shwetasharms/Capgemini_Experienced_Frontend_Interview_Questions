# Capgemini_Experienced_Frontend_Interview_Questions
## HTML 

### 1. What is the difference between block and inline elements in HTML?
### 2. What is the purpose of the alt attribute in an <img> tag? Why is it important for web accessibility?
#### Ans- 
### 3. What is the difference between <div> and <section> elements in HTML?
#### Ans- 
### 4. What are semantic HTML elements and why should you use them?
#### Ans. Why it matters: Shows you care about structure, accessibility, SEO, maintainability.
Strong answer: Mentions tags like <header>, <nav>, <article>, <section>, <footer>, difference vs generic <div>; explains benefits (screen-readers, style hooks, search engines).

### 5. Explain the difference between HTML and HTML5. What new features did HTML5 bring?

#### Ans. Why it matters: Senior devs should know the evolution of the web platform.
Strong answer: Talks about new semantic tags, <video>, <audio>, <canvas>, local storage APIs, web workers, etc.

### How does the <!DOCTYPE html> work? Why is it required?

Why it matters: Fundamental understanding of browser modes.

Strong answer: Explains it triggers standards-mode vs quirks mode in browsers; allows correct rendering of HTML5.

foundit
+1

### What is the role of meta tags in HTML and what are important ones you use regularly?

Why it matters: Senior devs should know document-head best practices (SEO, mobile, charset).

Strong answer: Mentions <meta charset="UTF-8">, <meta name="viewport" …>, description, keywords (maybe), theme-color, etc; explains importance.

designwithrehana.com
+1

### Explain how accessibility (a11y) is impacted by HTML markup. What practices do you follow?

Why it matters: Modern senior front-end devs must consider accessibility, not just visuals.

Strong answer: Talks about proper heading order (<h1> → <h2> …), ARIA attributes (aria-label, aria-live, etc), alt text on images, semantic HTML, roles, landmarks.



### What are void (self-closing) HTML elements and give examples.

Why it matters: Shows you know HTML syntax and fundamentals.

Strong answer: Examples: <img>, <br>, <hr>, <input>, <meta>. Explain they don’t require closing tag because no content.


### What’s the difference between <div> and <span> (block vs inline)?

Why: Basic but still asked — shows you know display & layout at markup level (even though CSS handles much).

Answer: <div> is block­level, occupies full width by default; <span> is inline, only as wide as content; use cases etc.


### How does the viewport meta tag work and why is it important for mobile/responsive design?

Why: Responsiveness and HTML markup interplay.

Strong answer: Example <meta name="viewport" content="width=device-width, initial-scale=1">; explains controlling layout-viewport vs device-width, making site mobile-friendly.


### What is the difference between id and class attributes in HTML?

Why: Basic DOM/selector knowledge still expected of seniors to articulate.

Answer: id is unique per page, used for single elements; class can be used on many elements; specificity differences; possible implications for JavaScript/CGI, CSS.


### When should you put <script> tags in HTML and what are async & defer attributes?

Why: Shows you understand performance, document loading, and markup scripting interplay.

Strong answer: Explain placing scripts at end of body vs head; async loads script asynchronously and executes as soon as possible; defer loads async but executes after the document parsing; correct usage.
