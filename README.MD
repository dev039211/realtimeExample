
<mark>🎯 Try It Yourself! </mark><br>
Create these three files (index.html, style.css, script.js).<br>

Save them in a folder.<br>

Open index.html in your browser. 🎉<br>

**🌐 What is a Request and a Response?**<br>
Request: When you ask for something from a website. (Like saying, “Hey website, give me this page!”) <br>

Response: When the website gives you what you asked for. (Like handing you a page to read.)<br>

Now, let’s see how this works in our example.<br>

🚀 Request & Response Flow in Our Example Website<br>
Step 1: Opening the Website (HTML Request)<br>
You type index.html in your browser or double-click the file.<br>

Browser sends a request to get the HTML file.<br>

Response: The browser gets index.html and starts reading it.<br>

🔹 Request: GET index.html<br>
🔹 Response: index.html is sent to the browser.<br>

Step 2: Loading Styles (CSS Request)<br>
In index.html, the browser sees:<br>

`<link rel="stylesheet" href="style.css">` <br>
The browser requests style.css to make the page look nice.<br>

Response: The server (or your computer) sends style.css.<br>

🔹 Request: GET style.css<br>
🔹 Response: The browser gets the CSS and applies styles.<br>

Step 3: Loading JavaScript (JS Request)<br>
The browser sees this in index.html:<br>
`<script src="script.js"></script>`<br>
Browser requests script.js so it can run JavaScript.<br>

Response: The server sends script.js.<br>

🔹 Request: GET script.js<br>
🔹 Response: JavaScript is loaded and ready to run.<br>

Step 4: Clicking the Button (JavaScript Action)<br>
You click the button, which calls:<br>

    function changeText() {
        document.getElementById("message").innerText = "Ta-da! 🎩✨ Button Clicked!";
    }
<br>
This happens inside the browser, so no new request is sent to the server.<br>

The browser instantly updates the text on your screen (No waiting needed!).<br>

🔹 Request: (No request to the server, JavaScript runs locally.)<br>
🔹 Response: JavaScript changes the text dynamically.<br>

🚀 Full Request-Response Summary:<br>
| Action         | Request Sent                          | Response Received            |
|---------------|--------------------------------------|------------------------------|
| Open Website  | `GET index.html`                     | Sends `index.html`           |
| Load CSS      | `GET style.css`                      | Sends `style.css`            |
| Load JavaScript | `GET script.js`                    | Sends `script.js`            |
| Click Button  | No Request (JavaScript runs in browser) | Text changes instantly     |

<br>
🤔 What If This Were Online?<br>
If this website were on a real web server (like GitHub Pages), your browser would send these requests over the internet, and a server would respond with the files.
<br>


