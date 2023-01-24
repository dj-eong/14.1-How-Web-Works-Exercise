# 14.1-How-Web-Works-Exercise

HTTP stands for Hypertext Transfer Protocol. It is the set of rules and guidelines that browsers and servers use to communicate.

URL is short for Uniform Resource Locator. It is the address for a website.

DNS stands for Domain Name System. It is the phonebook of the Internet; it translates IP addresses to readable URLs and vice versa.

A query string is a key value pair that you can pass into the URL.

2 HTTP verbs:
GET gets data from the server without altering any server data.
POST sends data to the server and changes some data in the server.

An HTTP request is a request from a browser to a server that follows the HTTP protocol.

An HTTP response is the server response to an HTTP request.

An HTTP header gives additional info about the request or response. Some examples include content-type, accept, etc.

When you type a URL into the browser and press enter, your browser uses DNS to change it into an IP address. It then makes an HTTP request to that IP address, including headers. The server responds with a status code and the requested data. The browser takes that data and makes a DOM of it, creating the webpage that you see. The browser makes any additional necessary requests for other specific resources asynchronously (such as images, CSS, scripts) and updates the DOM with each response.
