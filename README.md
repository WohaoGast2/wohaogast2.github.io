<!DOCTYPE html>
<html>
<head>
    <title>
      Navigator userAgent Property in HTML
    </title>
    <style>
        h1 {
            color: green;
        }
         
        h2 {
            font-family: Impact;
        }
         
        body {
            text-align: center;
        }
    </style>
</head>
 
<body>
    <h1>GeeksforGeeks</h1>
    <h2>Navigator userAgent Property</h2>
     
<p>
      For checking the browser's User-agent header name,
      double click the "Check User Agent" button:
    </p>
 
    <button ondblclick="checkua()">
      Check User Agent
    </button>
 
    <p id="header"></p>
 
    <script>
        function checkua() {
            var u =
                "User-agent header sent by the browser : "
                                     + navigator.userAgent;
            document.getElementById("header").innerHTML = u;
        }
    </script>
</body>
</html>
