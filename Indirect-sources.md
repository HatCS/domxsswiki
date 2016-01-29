(TBA)

## Storage Object
HTML 5 Storage objects [ [1], [2], [3] ] can be considered an indirect source, since they can be used to store values from direct sources and use them later insecurely.

Indirect source objects are:
 * localStorage
 * sessionStorage
 * IndexedDB (mozIndexedDB, webkitIndexedDB, msIndexedDB)
 * Database (Safari Only)

## Server Response Sources
Previously server side stored data could be used by an attacker to send untrusted input to JavaScript.

(TBF)


[1]: http://dev.w3.org/html5/webdatabase/	"Web SQL Database"
[2]: https://html.spec.whatwg.org/multipage/webstorage.html "W3C WebStorage"
[3]: https://msdn.microsoft.com/en-us/library/bg142799(v=vs.85).aspx  "Microsoft's Introduction to WebStorage"
