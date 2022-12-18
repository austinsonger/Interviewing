# Explain what happens when you type domain in the browser and press enter

* Resolve IP address of the URL via DNS
* Generate an HTTP request with headers (`accept`, `user-agent`, `cookie`, etc)
* Open an HTTP connection to the resolved IP address
* Send the request to the server
* Receive the response from the server
* Parse response headers
* Depending on the response headers, perform additional operations
* Decompress the response body if it's compressed (e.g. gzipped)
* Parse the HTML code inside the response body
* Resolve any additional resources (images, stylesheets, scripts, etc)
* Start loading those resources via their URLs using the same steps
* Render the HTML as soon as required resources are loaded, continue loading remaining resources in background
* When all the resources are loaded, close the HTTP connection
