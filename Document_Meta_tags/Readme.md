🏷️ Tag Descriptions and Examples
1. <!DOCTYPE>
Description: Declares the document type and version of HTML.

Usage: Ensures the browser correctly renders the page using HTML5 standards.

Example:

html
Copy
Edit
<!DOCTYPE html>
2. <html>
Description: The root element that wraps the entire HTML document.

Attributes: lang for language specification.

Example:

html
Copy
Edit
<html lang="en">
</html>
3. <head>
Description: Contains metadata, links to stylesheets, scripts, and other non-visible elements.

Example:

html
Copy
Edit
<head>
  <title>My Web Page</title>
</head>
4. <meta>
Description: Provides metadata about the HTML document (character set, viewport settings, SEO, etc.).

Common Attributes: charset, name, content, http-equiv

Example:

html
Copy
Edit
<meta charset="UTF-8">
<meta name="description" content="A professional README on HTML structure.">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
5. <title>
Description: Sets the title of the page (displayed on the browser tab).

Example:

html
Copy
Edit
<title>My Awesome Website</title>
6. <base>
Description: Sets a base URL for all relative URLs in the document.

Example:

html
Copy
Edit
<base href="https://www.example.com/">
7. <link>
Description: Links external resources like stylesheets or icons.

Common Uses: rel="stylesheet", rel="icon"

Example:

html
Copy
Edit
<link rel="stylesheet" href="styles.css">
<link rel="icon" href="favicon.ico">
8. <style>
Description: Embeds internal CSS styles within the HTML document.

Example:

html
Copy
Edit
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
  }
</style>
9. <script>
Description: Embeds or references JavaScript code.

Usage: Can be placed in the <head> or just before </body> for better performance.

Example:

html
Copy
Edit
<script>
  alert('Hello, World!');
</script>

<!-- External Script -->
<script src="main.js"></script>
10. <noscript>
Description: Defines alternate content for users who have disabled JavaScript.

Example:

html
Copy
Edit
<noscript>
  Your browser does not support JavaScript or it is disabled.
</noscript>
📚 Summary Table
Tag	Purpose	Common Attributes
<!DOCTYPE>	Declares HTML version (HTML5)	-
<html>	Root element of the HTML document	lang
<head>	Contains metadata and links	-
<meta>	Defines metadata	charset, name, content
<title>	Sets the page title	-
<base>	Base URL for all relative links	href, target
<link>	Links external resources	rel, href
<style>	Defines internal CSS	-
<script>	Adds JavaScript	src, type
<noscript>	Shown when JS is disabled	-
