# Assignment-6

https://nodeserver1.netlify.app/

In this assignment,I made Node js server using built in http module.Server listen on one port and wait for client request.It checks request URL and give different HTML page for different route like /services, /about, /contact.For each route,server send response with res.writeHead() and then res.end().If user go to route not exist, server show "404 Page Not Found".This show how Node js can do routing and create simple web pages
