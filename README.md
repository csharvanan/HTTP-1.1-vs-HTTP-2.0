# HTTP
## What is HTTP
- The Hypertext Transfer Protocol (HTTP) is designed to enable communications between clients and servers. 
- HTTP works as a request-response protocol between a client and server.
- HTTP was originally proposed in 1989 by Tim Berners-Lee.

### Example:
- A client (browser) sends an HTTP request to the server; then the server returns a response to the client.

## Versions Of HTTP
- HTTP/0.9–1991-Obsolete
- HTTP/1.0–1996-Obsolete
- HTTP/1.1–1997-Standard
- HTTP/2–2015-Standard
- HTTP/3–2022-Standard

# HTTP 1.1 vs HTTP 2.0

## 1. HTTP 1.1
- To address the limitations of HTTP 1.0, the next version, HTTP 1.1, was introduced in 1999. HTTP 1.1 introduced several key features that improved its performance and security.
- HTTP 1.1 also introduced several security enhancements, including support for SSL/TLS encryption and the use of authentication and access control mechanisms.

## 2. HTTP 2.2
- HTTP version 2.0 was officially released in 2015, about eighteen years after the HTTP 1.1. Particularly, HTTP 2.0 focused on improving the protocol performance.

## Key Difference
- HTTP 1.1 is speaking in ***plain text*** “Hi dude How are you” but with HTTP 2 it is using like a secret code a compact, efficient set of signals that convey the same message . ***HTTP 2 uses a binary framing layer***

- HTTP 1.1 is a sequential protocol. So, we can send a single request at a time. HTTP 2.0, in turn, allows to send requests and receive responses asynchronously. In this way, we can do multiple requests at the same time using a single connection

## Multiplexing Difference (Image View)

![Multiplexing Image View](images/http1%20vs%20http2.png)

## Response Time Difference (Image View)

![Response_Time HTTP 1.1 vs HTTP 2.0 Image View](images/http1%20vs%20http2%20responce%20time.png)

For More Click => [HTTP 1.1 vs HTTP 2.0] (https://medium.com/@csharvanan/http-1-1-vs-http-2-4e91bc0704bc)