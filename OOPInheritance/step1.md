### No Inheritance
If we were to use classes without inheritance for the following example the classes might look like this:
<pre>
class grocery:
    description = ""
    price = 0.0
    weight = 0.0
    
class mineral:
    description = ""
    price = 0.0
    volume = 0.0
    
class newspaper:
    description = ""
    price = 0.0
    publisher = ""
    
</pre>Copy to {{copy}}

<pre class="file" data-filename="app.js" data-target="replace">var http = require('http');
var requestListener = function (req, res) {
  res.writeHead(200);
  res.end('Hello, World!');
}

var server = http.createServer(requestListener);
server.listen(3000, function() { console.log("Listening on port 3000")});
</pre>

<pre class="file" data-target="clipboard">Test</pre>