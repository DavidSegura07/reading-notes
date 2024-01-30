# Reading

## [What Google Learned From Its Quest to Build the Perfect Team](https://www.nytimes.com/2016/02/28/magazine/what-google-learned-from-its-quest-to-build-the-perfect-team.html)

### To what extent did psychological safety impact your previous work experience?

### How does this article inform your approach to working with others moving forward?

## How I explained REST to my brother

### Who is Roy Fielding?

Roy Fielding help write the first web server that sent documents across the internet and did a bunch of research explaining why the web works the way it does.

### Why don’t the techniques that we use in this class work well when we need to be able to talk to all of the machines in the world?

Because they weren't designed to be used like that. When Fielding and his colleagues started building the web, being able to talk to any machine anywhere in the world was a primary concern. But most of the techniques developers later used to get computers to talk to each other didn't have those requirements. You just needed to talk to a small group of machines.

### What is the HTTP protocol that Fielding and his friends created?

HTTP—this protocol Fielding and his friends created—is all about applying verbs to nouns. For instance, when you go to a web page, the browser does an HTTP GET on the URL you typed in and back comes a web page.

### What does a GET do?

GET: This method requests data from a specified resource. It is used to retrieve information from the server. GET requests can be cached and remain in the browser history. They should not be used for sensitive data because the data sent is part of the URL.

### What does a POST do?

POST: This method sends data to a server to create or update a resource. The data sent to the server with POST is stored in the request body of the HTTP request. POST requests are not cached and do not remain in the browser history. They are often used for submitting form data or uploading a file.

### What does PUT do?

PUT: This method sends data to a server to create or replace a resource. The difference between PUT and POST is that PUT requests are idempotent. This means if you call the same PUT request multiple times, the results will be the same (it will create or update the same resource). It is often used for updating a resource entirely.

### What does PATCH do?

PATCH: This method is used for partial updates to a resource. Instead of replacing the entire resource like PUT, PATCH only updates the specified fields of the resource. This is more efficient for minor changes to complex resources.

## API Keys

Request a personal API key from the following APIs. You should receive these in your email within a few hours, often within minutes. Please request these keys prior to lecture to allow adequate time because you will need them in order to complete your lab assignment. Note: do not post your API keys in the Canvas discussion or on GitHub. Save them in a secure place.
