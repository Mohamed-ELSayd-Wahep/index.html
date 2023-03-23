HTML:
<!DOCTYPE html>
<html>
  <head>
    <title>تهنئة رمضانية</title>
  </head>
  <body>
    <h1>تهنئة رمضانية</h1>
    <p>أهلاً بكم في موقع التهنئة الرمضانية. يرجى كتابة اسمك أدناه لتلقي التهنئة الخاصة بك.</p>
    <input type="text" id="name" placeholder="اسمك هنا">
    <button onclick="generateGreeting()">تلقي التهنئة</button>
    <div id="greeting"></div>
  </body>
</html>
CSS:
body {
font-family: Arial, sans-serif;
text-align: center;
}
h1 {
color: #FF5733;
}
input[type="text"] {
padding: 10px;
margin: 10px;
border: 2px solid #ccc;
border-radius: 4px;
}
button {
background-color: #4CAF50;
color: white;
padding: 10px 20px;
border: none;
border-radius: 4px;
cursor: pointer;
}
button:hover {
background-color: #3e8e41;
}

JavaScript:
function generateGreeting() {
var name = document.getElementById("name").value;
var greeting = "رمضان كريم " + name + "!";
document.getElementById("greeting").innerHTML = greeting;
}# index.html
