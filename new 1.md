# **How Web Works Exercise**

## **Part One: Solidify Terminology**

### 1. What is HTTP?
HTTP (Hypertext Transfer Protocol) is the protocol used for transferring data on the web, enabling communication between clients (like browsers) and servers.

### 2. What is a URL?
A URL (Uniform Resource Locator) is the address used to access resources on the web, including the protocol, domain, path, and optionally, query strings and fragments.

### 3. What is DNS?
DNS (Domain Name System) translates human-readable domain names into IP addresses, allowing browsers to locate the correct server.

### 4. What is a query string?
A query string is part of a URL that contains key-value pairs, providing data to be sent to the server, often used in forms or filtering.

### 5. What are two HTTP verbs and how are they different?
- **GET**: Requests data from a server; data is sent in the URL.
- **POST**: Sends data to the server; data is included in the request body.

### 6. What is an HTTP request?
An HTTP request is a message sent by a client to a server, asking for a resource or performing an action.

### 7. What is an HTTP response?
An HTTP response is a message sent by a server back to the client, containing the requested resource or status information.

### 8. What is an HTTP header?
An HTTP header is a key-value pair in a request or response, providing additional information such as `Content-Type` or `User-Agent`.

### 9. What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
1. DNS lookup to find the IP address.
2. TCP connection establishment.
3. HTTP GET request is sent.
4. Server processes the request.
5. Server sends an HTTP response.
6. Browser renders the page.

## **Part Two: Practice Tools**

### 1. Using `curl` to make a GET request
Run the following command in your terminal:
```bash
curl "https://icanhazdadjoke.com/search?term=pirate" -H "Accept: application/json"
