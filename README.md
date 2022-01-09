# SNOW-AJAX
AJAX stands for Asynchronous JavaScript and XML. 
- AJAX is a technique for creating better, faster, and more interactive web applications with the help of XML, HTML, CSS, and Java Script.
- Ajax uses XHTML for content, CSS for presentation, along with Document Object Model and JavaScript for dynamic content display.
- AJAX is a web browser technology independent of web server software.
-With AJAX, when you hit submit, JavaScript will make a request to the server, interpret the results, and update the current screen.
- In the purest sense, the user would never know that anything was even transmitted to the server.

## XMLHttpRequest (XHR)
- XMLHttpRequest (XHR) is an API that can be used by JavaScript, JScript, VBScript, and other web browser scripting languages
-  to transfer and manipulate XML data to and from a webserver using HTTP, establishing an independent connection channel between a webpage's Client-Side and Server-Side.
- The data returned from XMLHttpRequest calls will often be provided by back-end databases.
- Besides XML, XMLHttpRequest can be used to fetch data in other formats, e.g. JSON or even plain text.

## XMLHttpRequest Methods
- abort()
Cancels the current request.
- getAllResponseHeaders()
Returns the complete set of HTTP headers as a string.
- getResponseHeader( headerName )
Returns the value of the specified HTTP header.
- send( content )
Sends the request.
- setRequestHeader( label, value )
Adds a label/value pair to the HTTP header to be sent.

## XMLHttpRequest Methods
- open( method, URL )
- open( method, URL, async )
- open( method, URL, async, userName )
- open( method, URL, async, userName, password )


- Specifies the method, URL, and other optional attributes of a request.
- The method parameter can have a value of "GET", "POST", or "HEAD". Other HTTP methods such as "PUT" and "DELETE" (primarily used in REST applications) may be possible.
- The "async" parameter specifies whether the request should be handled asynchronously or not.
-  "true" means that the script processing carries on after the send() method without waiting for a response, and
-   "false" means that the script waits for a response before continuing script processing.

## XMLHttpRequest Properties
- onreadystatechange

An event handler for an event that fires at every state change.

readyState

The readyState property defines the current state of the XMLHttpRequest object.

The following table provides a list of the possible values for the readyState property −

## State	Description
- 0	The request is not initialized.
- 1	The request has been set up.
- 2	The request has been sent.
- 3	The request is in process.
- 4	The request is completed.


- readyState = 0 After you have created the XMLHttpRequest object, but before you have called the open() method.
- readyState = 1 After you have called the open() method, but before you have called send().
- readyState = 2 After you have called send().
- readyState = 3 After the browser has established a communication with the server, but before the server has completed the response.
- readyState = 4 After the request has been completed, and the response data has been completely received from the server.


- responseText
Returns the response as a string.
- responseXML
Returns the response as XML. This property returns an XML document object, which can be examined and parsed using the W3C DOM node tree methods and properties.
- status
Returns the status as a number (e.g., 404 for "Not Found" and 200 for "OK").
- statusText
Returns the status as a string (e.g., "Not Found" or "OK").

JSON with AJAX
- According to the AJAX model, web applications can send and retrieve data from a server asynchronously without interfering with the display and the behavior of the existing page.
- Many developers use JSON to pass AJAX updates between the client and the server.
- Any data that is updated using AJAX can be stored using the JSON format on the web server. AJAX is used so that javascript can retrieve these JSON files when necessary, parse them, and perform one of the following operations −
Store the parsed values in the variables for further processing before displaying them on the webpage.
-It directly assigns the data to the DOM elements in the webpage, so that they are displayed on the website.

