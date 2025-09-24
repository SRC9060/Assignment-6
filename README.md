# Assignment-6

https://nodeserver12.netlify.app/

In this assignment, I built a simple Node.js server using the built-in http module. The server runs on a specific port and waits for client requests. Based on the URL entered by the user, it sends back different HTML responses. For example, if the user goes to /, it shows the home page, while /about or /contact return their respective pages. I used res.write() and res.end() to send the responses. If someone tries to access a route that doesn’t exist, the server gives a “404 Page Not Found” message. This shows how Node.js can be used to handle basic routing and serve simple web pages even without using external frameworks like Express.
