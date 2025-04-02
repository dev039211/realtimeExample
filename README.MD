
🎯 Try It Yourself!
Copy these three files (index.html, style.css, script.js).

Save them in a folder.

Open index.html in your browser. 🎉

🌐 What is a Request and a Response?
Request: When you ask for something from a website. (Like saying, “Hey website, give me this page!”)

Response: When the website gives you what you asked for. (Like handing you a page to read.)

Now, let’s see how this works in our example.

🚀 Request & Response Flow in Our Example Website
Step 1: Opening the Website (HTML Request)
You type index.html in your browser or double-click the file.

Browser sends a request to get the HTML file.

Response: The browser gets index.html and starts reading it.

🔹 Request: GET index.html
🔹 Response: index.html is sent to the browser.

Step 2: Loading Styles (CSS Request)
In index.html, the browser sees:
<link rel="stylesheet" href="style.css">
The browser requests style.css to make the page look nice.

Response: The server (or your computer) sends style.css.

🔹 Request: GET style.css
🔹 Response: The browser gets the CSS and applies styles.

Step 3: Loading JavaScript (JS Request)
The browser sees this in index.html:
<script src="script.js"></script>
Browser requests script.js so it can run JavaScript.

Response: The server sends script.js.

🔹 Request: GET script.js
🔹 Response: JavaScript is loaded and ready to run.

Step 4: Clicking the Button (JavaScript Action)
You click the button, which calls:
function changeText() {
    document.getElementById("message").innerText = "Ta-da! 🎩✨ Button Clicked!";
}
This happens inside the browser, so no new request is sent to the server.

The browser instantly updates the text on your screen (No waiting needed!).

🔹 Request: (No request to the server, JavaScript runs locally.)
🔹 Response: JavaScript changes the text dynamically.

🚀 Full Request-Response Summary
| Action         | Request Sent                          | Response Received            |
|---------------|--------------------------------------|------------------------------|
| Open Website  | `GET index.html`                     | Sends `index.html`           |
| Load CSS      | `GET style.css`                      | Sends `style.css`            |
| Load JavaScript | `GET script.js`                    | Sends `script.js`            |
| Click Button  | No Request (JavaScript runs in browser) | Text changes instantly     |


🤔 What If This Were Online?
If this website were on a real web server (like GitHub Pages), your browser would send these requests over the internet, and a server would respond with the files.


