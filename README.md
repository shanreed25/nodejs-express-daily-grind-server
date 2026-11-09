# Basic Express.js Server

> A basic web server using Node.js and Express that can serve a home page and a contact page.

## Reflection Questions

### What is the difference between res.send() and res.sendFile()? When would you use one over the other?

#### res.send(): sends content
- send information that is in your index.js file/code
- takes the information directly
- use for short or dynaically generated responses

### res.sendFile(): sends a file
- reads a file and adds the contents of that file to the browser
- takes a file path
- use when th response is in the file

### Why is the path module necessary when serving files? What could go wrong if you just used a relative path like 'public/index.html'?
> The path module is not neede for this assignmnet

### How would you add a third page (e.g., a menu page) to this server? What steps would you take?
1. Create the file like `about.html`
2. Create a route handler to server the page
