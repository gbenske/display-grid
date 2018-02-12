# Display Grid

### Eine Präsentation von German "Adonis" Benske

---


## Vorteile von Display Grid

- Einfaches Strukturieren der Inhalte |
- Keine float oder inline-block mehr nötig |
- 

---

## Nachteile von Display Grid

- Browsersupport |
  +Firefox 57+, Chrome 62+, Edge 16+, Opera
  + Safari 11+, supportet nicht alle Eigenschaften (grid-template-rows)
  + IE 11 unterstützt es nur teils, darunter nicht mehr
  + Spezielle Prefixe nötig für IE
- Neu im Webbereich |
- Nicht Anfängerfreundlich

---

## Display grid vs flex

- Grid |
 + weniger media queries
 + Positionierung der Elemente in 2 Dimensionen (columns und rows)
 + keine gescheite Navigation möglich

- Flex |

---

## Funktionsweise von Display Grid

---

@title[Grid Block]

<p><span class="slide-title">Grid</span></p>

```javascript
// Include http module.
var http = require("http");

// Create the server. Function passed as parameter
// is called on every request made.
http.createServer(function (request, response) {
  // Attach listener on end event.  This event is
  // called when client sent, awaiting response.
  request.on("end", function () {
    // Write headers to the response.
    // HTTP 200 status, Content-Type text/plain.
    response.writeHead(200, {
      'Content-Type': 'text/plain'
    });
    // Send data and end response.
    response.end('Hello HTTP!');
  });

// Listen on the 8080 port.
}).listen(8080);
```

@[1,2](You can present code inlined within your slide markdown too.)
@[9-17](Displayed using code-syntax highlighting just like your IDE.)
@[19-20](Again, all of this without ever leaving your slideshow.)

---?gist=onetapbeyond/494e0fecaf0d6a2aa2acadfb8eb9d6e8&lang=scala&title=Scala GIST

@[23](You can even present code found within any GitHub GIST.)
@[41-53](GIST source code is beautifully rendered on any slide.)
@[57-62](And code-presenting works seamlessly for GIST too, both online and offline.)

---

# Fragen?


