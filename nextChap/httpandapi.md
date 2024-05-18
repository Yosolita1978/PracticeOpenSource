# Introduction to APIs and HTTP

### Projected Time

15 minutes: 
* Lesson: 10 minutes
* Guided Practice: 5 minutes

## Prerequisites

Before diving into this lesson, you should have a basic understanding of:

* [Git version control](https://www.freecodecamp.org/news/what-is-git-and-how-to-use-it-c341b049ae61/)
* [How the Internet works](https://www.freecodecamp.org/news/how-does-the-internet-work/)
* [What is a server?](https://www.freecodecamp.org/news/server-definition/) 

### Motivation

Understanding APIs and HTTP is essential for modern web development. APIs (Application Programming Interfaces) are how different software systems communicate with each other. HTTP (HyperText Transfer Protocol) is the foundation of data communication on the web.

This knowledge will help you:

* Understand how web applications function under the hood.
* Be prepared for more advanced topics in web development.
* Path your knowledge to be a Full-Stack Software Engineer.

## Objectives

By the end of this lesson, you should be able to:

* Understand what an API is.
* Understand the basics of HTTP.
* Make a simple HTTP request using a tool like Postman.

### Lesson

* What is an API?

An API, or Application Programming Interface, allows different software systems to communicate with each other. Think of it as a restaurant menu. When you visit a restaurant, you use the menu to order food. The menu provides a list of dishes you can order and the ingredients in each dish. You don't need to know how to cook the dishes; you just need to know how to read the menu and place an order.

Explanation:

* The menu represents the API documentation.
* Ordering a dish represents making a request to the API.
* The kitchen is the server that processes your order.
* The waiter is the API that takes your request to the kitchen and brings back your order.

![](https://raw.githubusercontent.com/Yosolita1978/screenshoots/b0f380e56e5be66c1d8765ad904fa4fa47bd08a2/2024/Workshops/Screen%20Shot%202024-05-18%20at%202.27.54%20PM.png)
<span  style="font-size:0.5em;">[Image by [Pawan Yadav](https://medium.com/@pawan329/what-is-an-api-a-step-by-step-guide-e6858b6e1016)]</span>

* What is an HTTP Protocol?

HTTP, or HyperText Transfer Protocol, is the protocol used for transferring data on the web. It defines how messages are formatted and transmitted, and how web servers and browsers should respond to various commands.

Key HTTP Concepts

* Request and Response: When you visit a website, your browser sends an HTTP request to the server, and the server sends back an HTTP response.
* Methods: The most common HTTP methods are:
    * GET (to retrieve data)
    * POST (to send data).
    * DELETE (to delete data)
    * PUT (to update data)

* Status Codes: HTTP responses include status codes that indicate whether a request was successful (e.g., 200 OK) or if there was an error (e.g., 404 Not Found). For a complete list of HTTP response status codes, review the [official documentation](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status)


## Guided Practice

A software called POSTMAN developed a user-friendly interface that allows users to easily construct and send HTTP requests without needing to write code. This makes it accessible to developers of all skill levels. We will use [POSTMAN](https://learning.postman.com/docs/getting-started/first-steps/sending-the-first-request/) for our practice

#### Step 1: Install and Open Postman
* If you haven't already installed Postman, [download it from Postman's official website and install it on your computer](https://www.postman.com/downloads/).

* Launch the Postman application on your computer.

#### Step 2: Create a New Request
* In the upper-left corner of the Postman interface, click on the "New" button.
* From the dropdown menu, select "Request". This will open a new request tab.

#### Step 3: Set Up the GET Request

* In the "Save Request" dialog that appears, enter a name for your request, such as `Simple GET Request`. You can also add a description if you like.
* In the request tab, you will see a field where you can enter the URL. Type in the following URL:
`https://jsonplaceholder.typicode.com/posts/1`
* To the left of the URL field, there is a dropdown menu for selecting the request type. Make sure it is set to "GET" (which is the default).

#### Step 4: Send the Request
* Once the URL is entered and the request type is set to GET, click the "Send" button located on the right side of the URL field.

#### Step 5: View the Response
* After clicking "Send", you should see the response from the server in the lower part of the Postman interface.
* The response will include various details such as status code, time taken, and size. You will also see the response body, which contains the data returned by the API.

Example Response:

```json

{
  "userId": 1,
  "id": 1,
  "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
  "body": "quia et suscipit\nsuscipit...
}
```
* Status Code: 200 OK (indicates that the request was successful)
* Response Body: Contains the data of the post with ID 1.

#### Step 6: Conclusion

You have successfully made a GET request using Postman! Feel free to experiment with the [Postman Academy to learn more about HTTP requests](https://academy.postman.com/).

## More resources

##### Online Courses

1. **[APIs and Web Services - Coursera](https://www.coursera.org/learn/apis)**
   - A comprehensive course that covers the basics of APIs, RESTful APIs, and web services. It includes practical exercises and real-world examples. Free

##### Books

1. **[REST API Design Rulebook by Mark Masse](https://www.oreilly.com/library/view/rest-api-design/9781449317904/)**
   - A practical guide to designing and developing RESTful APIs with best practices and design principles. Free trial

##### Blogs and Articles

1. **[What is an API? (A Simple Explanation) - FreeCodeCamp](https://www.freecodecamp.org/news/what-is-an-api-in-english-please-b880a3214a82/)**
   - A beginner-friendly article that explains what an API is in simple terms.

2. **[The REST API Handbook - Toptal](https://www.toptal.com/api-developers/10-most-common-rest-api-mistakes)**
   - An in-depth article on common mistakes and best practices in REST API development.

##### Videos and Webinars

1. **[APIs for Beginners - FreeCodeCamp YouTube](https://www.youtube.com/watch?v=GZvSYJDk-us)**
   - A beginner-friendly video tutorial that explains what APIs are and how to use them.

2. **[HTTP Crash Course - Traversy Media YouTube](https://www.youtube.com/watch?v=iYM2zFP3Zn0)**
   - A crash course on HTTP, covering all the essential concepts in an easy-to-understand format.

