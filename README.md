# Capgemini_Experienced_Frontend_Interview_Questions
## HTML 

 ### 1. What is the difference between block and inline elements in HTML?
Block elements (e.g. <div>, <p>, <section>, <article>) always start on a new line and occupy the full available width of their parent container. They can contain both block and inline elements.
Inline elements (e.g. <span>, <a>, <strong>, <em>) do not start a new line, occupy only as much width as their content, and cannot contain block elements.
Why it matters: Knowing the difference helps control layout flow and spacing before applying CSS.

### 2. What is the purpose of the alt attribute in an <img> tag? Why is it important for web accessibility?

The alt attribute provides alternative text describing the image’s content or purpose.
It is critical for accessibility, because:
Screen readers announce it for visually impaired users.
It’s displayed if the image fails to load.
Search engines use it for SEO and context indexing.
Best practice: Always write descriptive, meaningful alt text. If the image is purely decorative, use alt="" to ensure it’s ignored by assistive technologies.

### 3. What is the difference between <div> and <section> elements in HTML?
<div> is a generic container with no semantic meaning — used for grouping and styling via CSS or scripting.
<section> is a semantic element that represents a thematically grouped content block (e.g., a chapter, article section, or group of related content with a heading).
Why it matters:
<section> improves document structure and accessibility (navigable landmarks).
<div> should only be used when no more specific semantic tag fits.
  
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
Here’s a **senior-level HTML question set** — the kind interviewers use to test *depth, reasoning, and practical experience* (not trivia).

---

## 🔹 Advanced HTML Questions for 5+ Years Frontend Experience

### **1. Explain semantic HTML and why it’s important.**

Tests: understanding of structure, SEO, and accessibility.
👉 Expect follow-ups like *“When would you use `<article>` vs `<section>`?”* or *“Why avoid excessive `<div>`s?”*

---

### **2. How does HTML5 improve accessibility and SEO?**

Key points: semantic tags, ARIA roles, microdata/schema.org, better heading structure.

---

### **3. What is the difference between `<article>`, `<section>`, `<aside>`, and `<main>`?**

Tests nuanced understanding of semantic structure.

---

### **4. Explain the role and behavior of the `<meta>` viewport tag.**

Expect details on `width=device-width`, `initial-scale`, and mobile rendering.

---

### **5. How does the browser parse and render an HTML page?**

Tests performance insight. Mention DOM construction, render tree, CSSOM, and reflows/repaints.

---

### **6. What are web components, and what problems do they solve?**

Tests modern HTML knowledge. Mention custom elements, Shadow DOM, templates.

---

### **7. What is the difference between `async` and `defer` in script loading?**

Tests performance and rendering optimization knowledge.

---

### **8. What’s the difference between `data-*` attributes and ARIA attributes?**

Shows understanding of semantics vs data storage.
`data-*` → custom JS data; `aria-*` → accessibility roles/labels.

---

### **9. How would you make an HTML page fully accessible?**

Expect details: correct semantics, alt text, keyboard navigation, ARIA roles, focus management.

---

### **10. What are contenteditable and spellcheck attributes?**

Tests awareness of native browser features.

---

### **11. Explain lazy loading of images (`loading="lazy"`) and its benefits.**

Performance optimization, network efficiency, and Core Web Vitals.

---

### **12. Difference between `<link>` and `<@import>` for CSS.**

`<link>` loads faster, allows preloading; `@import` blocks render and is discouraged.

---

### **13. What are microdata and schema.org used for?**

Structured data for SEO and rich snippets.

---

### **14. How does HTML handle forms and validation?**

Talk about built-in constraints (`required`, `pattern`, `type=email`), `novalidate`, custom validation.

---

### **15. What’s the difference between `<script type="module">` and normal scripts?**

Modules are deferred, scoped, and support import/export syntax.

---

### **16. What are shadow DOM and custom elements?**

Deep dive into component encapsulation and reusability.

---

### **17. How do you ensure cross-browser compatibility in HTML markup?**

Testing, using feature detection, progressive enhancement, avoiding deprecated tags.

---

### **18. Explain `rel="noopener noreferrer"` in `<a>` tags.**

Prevents security risks (tabnabbing) when using `target="_blank"`.

---

### **19. What is the purpose of the `<base>` tag?**

Sets a base URL for all relative links and assets.

---

### **20. How do you optimize HTML for performance?**

Minify HTML, preload key assets, defer scripts, lazy-load media, reduce DOM depth.

---

### 🧠 Bonus “Discussion-Type” Questions

* How do you approach **HTML architecture** in large projects?
* What’s your opinion on using **BEM/OOCSS** naming conventions?
* How do you balance **semantic purity vs developer productivity** (e.g., in React)?
* Have you ever built a **design system** or **component library** with accessibility in mind?

---

**a.** Want me to write **answers for the top 10 of these** (with senior-level reasoning)?
**b.** Or prefer a **categorized PDF sheet** (Basics / Semantics / Accessibility / Performance / Modern APIs) for interview prep?

