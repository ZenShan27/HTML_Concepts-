# 🏷️ HTML Head Tag Guide

## ✅ Introduction  
This document provides an overview of the most essential HTML tags used inside the `<head>` section of a webpage. These tags help define metadata, link stylesheets, load scripts, and more.

---

## 📄 1. `<!DOCTYPE>`

- **Description:** Declares the document type and version of HTML.
- **Usage:** Ensures the browser uses the correct rendering mode for HTML5.

```html
<!DOCTYPE html>
🌐 2. <html>
Description: Root element that wraps the entire HTML document.

Attribute:

lang: Specifies the language of the document (e.g., en for English)

html
Copy
Edit
<html lang="en">
  <!-- Head and body tags go here -->
</html>
🧠 3. <head>
Description: Contains metadata and links to scripts, styles, and other resources.
It does not display content on the page.

html
Copy
Edit
<head>
  <title>My Web Page</title>
</head>
🧾 4. <meta>
Description: Provides metadata such as character set, page description, keywords, author, and viewport settings.

Common Attributes:

charset

name

content

http-equiv

html
Copy
Edit
<meta charset="UTF-8">
<meta name="description" content="A professional README on HTML head tags.">
<meta name="keywords" content="HTML, meta, head tags">
<meta name="author" content="CodeWarrior">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
🏷️ 5. <title>
Description: Sets the title of the web page (shown on browser tab and search results).

html
Copy
Edit
<title>My Awesome Website</title>
🧭 6. <base>
Description: Sets a base URL for all relative URLs in the document.

html
Copy
Edit
<base href="https://www.example.com/">
🔗 7. <link>
Description: Links external resources such as stylesheets, favicons, and fonts.

Common Uses:

rel="stylesheet"

rel="icon"

html
Copy
Edit
<link rel="stylesheet" href="styles.css">
<link rel="icon" href="favicon.ico" type="image/x-icon">
🎨 8. <style>
Description: Embeds internal CSS into the HTML document.

html
Copy
Edit
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
  }
</style>
🧩 9. <script>
Description: Embeds JavaScript code or links to external JavaScript files.

html
Copy
Edit
<!-- Internal Script -->
<script>
  console.log("Hello, World!");
</script>

<!-- External Script -->
<script src="app.js"></script>
🚫📜 10. <noscript>
Description: Provides fallback content if the browser does not support JavaScript or it is disabled.

html
Copy
Edit
<noscript>
  JavaScript is disabled in your browser. Please enable it for a better experience.
</noscript>
📚 Summary Table of Tags
Tag	Purpose	Common Attributes
<!DOCTYPE>	Declares HTML version (HTML5)	–
<html>	Root element of HTML	lang
<head>	Metadata container	–
<meta>	Metadata definition	charset, name, content
<title>	Page title	–
<base>	Base URL for links	href, target
<link>	External resources (CSS/icon)	rel, href
<style>	Internal CSS	–
<script>	JavaScript (inline or external)	src, type
<noscript>	Content if JS is disabled	–
📌 Conclusion
The <head> section of an HTML document contains vital information for the browser and search engines. Understanding and properly using these tags ensures:

✅ SEO optimization

✅ Responsive design

✅ Better performance

✅ Clean, structured code

