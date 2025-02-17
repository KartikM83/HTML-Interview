
# 😊HTML Interview Questions

1. **What is HTML?**  
HTML (HyperText Markup Language) is used to structure web pages using elements like headings, paragraphs, links, images, and more. It defines the content but does not handle styling (CSS) or functionality (JavaScript).

---

2. **Difference between HTML and HTML5**  
HTML5 introduced new semantic elements (`<section>`, `<header>`, `<footer>`, `<nav>`, `<article>`), better multimedia support, new form input types, and APIs like Web Storage and Canvas. It also improved browser compatibility.

---

3. **What are semantic elements?**  
Semantic elements clearly describe their meaning to both the browser and developers, improving readability, accessibility, and SEO. Examples include `<header>`, `<footer>`, `<article>`, `<section>`, and `<nav>`.

---

4. **What is the purpose of the `<meta>` tag?**  
The `<meta>` tag provides metadata about an HTML page, such as character encoding, viewport settings, keywords, and description. It is crucial for SEO and browser behavior.

---

5. **Difference between `<div>` and `<span>`**  
- `<div>` is a block-level element that takes up the full width and is used for layout and grouping content.  
- `<span>` is an inline element that only takes up as much space as needed and is used for styling small parts of text.  
Example:  
```html
<div>This is a div.</div>
<span>This is a span.</span>
```
---

6. **Types of Lists in HTML**  
There are three types of lists in HTML:
- **Ordered List (`<ol>`)** – Items are arranged with numbers (1, 2, 3, etc.).
- **Unordered List (`<ul>`)** – Items are arranged with bullet points (•).
- **Description List (`<dl>` with `<dt>` and `<dd>`)** – Used for key-value pairs, where `<dt>` is the term and `<dd>` is the description.

---

7. **How does the `<iframe>` tag work?**  
The `<iframe>` tag is used to embed another webpage inside the current page. It allows displaying external content like videos, maps, or other websites.  
Example:  
```html
<iframe src="https://www.example.com" width="600" height="400"></iframe>
```
---
8. **Difference between Absolute and Relative URLs**  
- **Absolute URL** – Contains the full path, including protocol (http:// or https://), domain name, and file path. It is used for external sources.  
  Example: `https://www.example.com/images/photo.jpg`
  
- **Relative URL** – A URL that is relative to the current page.  
  Example: `images/logo.png` (if the image is inside a local "images" folder).

---

9. **How does the `<form>` element work?**  
Forms collect user input and send it to a server using the `action` and `method` attributes.  
Example:  
```html
<form action="submit.php" method="POST">
  <input type="text" name="username" placeholder="Enter your name">
  <input type="submit" value="Submit">
</form>
```
-   The `action` specifies where the form data is sent.
-   The `method` can be **GET** (visible in URL) or **POST** (hidden from URL).
---
10.  **Difference between `id` and `class`**

-   `id` is unique and used for a single element (`id="header"`).
-   `class` can be assigned to multiple elements (`class="button"`).  
```html
<div id="main-container">This has an ID</div>
<p class="text">This paragraph has a class</p>
<p class="text">Another element with the same class</p>

```
---
11.  **What is the difference between localStorage, sessionStorage, and cookies?**

-   **localStorage** stores data permanently until manually deleted. It has a storage limit of 5MB and is accessible only from the same domain. It's commonly used for saving user preferences like themes or settings.
    
-   **sessionStorage** stores data only until the browser tab is closed. It also has a 5MB limit and is used for temporary data like form inputs.
    
-   **Cookies** store small pieces of data (up to 4KB) and can have an expiration date. Cookies are sent with every HTTP request, making them useful for authentication (e.g., storing login sessions).
- --
12. **What are Web Components in HTML?**  
💡 Web Components allow developers to create reusable custom elements in HTML.  
- **Custom Elements** – Define new HTML tags.  
- **Shadow DOM** – Encapsulated styles/scripts.  
- **HTML Templates** – Reusable code blocks.

---

13. **How to optimize an HTML page for better performance?**  
- Minimize HTML, CSS, and JavaScript files (remove unnecessary spaces/comments).
- Use lazy loading for images (`loading="lazy"`).
- Use Content Delivery Networks (CDN) for assets like images, CSS, and JS.
- Enable Gzip Compression to reduce file size.
- Reduce HTTP Requests by combining CSS & JS files.

---

14. **What is lazy loading?**  
Lazy loading loads images or resources only when needed, improving performance.  
Example:  
```html
<img src="image.jpg" loading="lazy" alt="Lazy Load Image">
```
---

15.  **Difference between `<script defer>` and `<script async>`**

-   **async** allows your script to run as soon as it's loaded, without blocking other elements on the page.
-   **defer** means your script will only execute after the page has finished loading.

```html
<script defer src="script.js"></script>
<script async src="script.js"></script>
```
---
