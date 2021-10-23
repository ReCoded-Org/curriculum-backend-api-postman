# Testing APIs with Postman
So what exactly is Postman and how helpful can it be for us to explore APIs? the learning objectives of this lesson are:
1. Understanding how to work with Postman
2. Exploring a public API
3. Understanding how helpful it can be while developing

What is Postman?
Postman is an API platform for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs—faster.

![postman](/assets/postman-pat.gif)

It helps us to test our APIs while building them and test other public APIs before using them for us to see how the data format that we are receiving and deal with it accordingly in our application.

Now let's start with downloading [Postman](https://www.postman.com/downloads/).

After downloading and installing it successfully u should see something similar to this:
<img src="./assets/postman.jpg">

Here's a video for [the basics of using postman for API testing](https://www.youtube.com/watch?v=t5n07Ybz7yI)

After watching the video please make sure to play around with the tool to get yourself familiar with it.

Using this API URL: https://jsonplaceholder.typicode.com

Try these end points:
- GET /posts
- GET /posts/1
- GET /posts/1/comments
- GET /comments?postId=1
- POST /posts
- PUT /posts/1
- PATCH /posts/1
- DELETE /posts/1


This is the [JSON placeholder API](https://jsonplaceholder.typicode.com/) that was used in the video to test other different requests.

You can also take a look at a new emerging [Thunder Client](https://www.thunderclient.io/) extension, which can run similar requests on VS code directly without the need for an app 

### Resources

- https://www.postman.com/home
- https://www.thunderclient.io/
- https://dzone.com/articles/postman-for-api-testing-pros-cons-and-alternative