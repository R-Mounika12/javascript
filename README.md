#################JAVA SCRIPT Learning######################


JavaScript is  a programming language that allows you to interact with the elements in the web pages.

Within the web browsers JavaScript consists of 3 main parts
1.ECMAScript provides the core functionality
2.DOM(Document Object model) provides an interface for interacting with elements in the  web pages.
3.BOM(Browser Object Model) provides browser API to interact with the web browsers

JavaScript allows you to add interactivity to the web pages. we typically use JavaScript with HTML and CSS to enhance the web functionality,
such as validating forms, creating interactive maps and displaying animated charts.

Notable JavaScript engines are V8 in chrome, SpiderMonkey in firefox and JavaScriptCore in Safari.

JavaScript run on both servers and web browsers.
when JavaScript is used on web page, it is executed in web browsers, serving as client-side language.

popular JavaScript server side environment is Node.js.
unlike client-side JavaScript, server-side JavaScript executes on the server and allows you to access DB, file systems etc.


#########JavaScript Overview#################

To define variable

var x = 20;
var y = 30;

with ES6
let x=1;
let y=8;

it's a good practice to use 'let' keyword to declare a variables.


To declare a function

function add(a,b) {
	return a+b;
}

To call the function

let sum = add(x,y);

To log the result into the console window of the web browser or terminal(in case of node.js)
console.log(result);

To delcare an arrya
let items = [];
let numbers = [1,3,5,7];

To insert JavaScript into HTML, we should use <script> tag

there are two ways to add <script> in HTML page
1.embed the JavaScript code directly into the HTML page
2.Reference an external JavaScript code file


To modify how the browser load and execute JavaScript files, we use one of the below attributes.

1.async attribute

attribute instructs the web browser to execute the JavaScript file asynchronously. however it does not guarantee that the script files will execute in the order in which they appear.

<script async src="service.js"></script>
<script async src="app.js"></script>

The app.js file might execute before the service.js file. Therefore, you must ensure that there is no dependency between them.

2.defer attribute

The defer attribute requests the web browser to execute the script file after the HTML document has been parsed.

For a page that includes many external JavaScript files, the blank page may be displayed during the rendering phase.

To prevent this, you include the JavaScript file just before the </body> tag





 

