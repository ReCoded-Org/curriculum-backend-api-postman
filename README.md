# Testing APIs with Postman
So what exactly is Postman and how can it help us to explore APIs? The objectives of this assignment are:
1. Understanding how to work with Postman.
2. Exploring a public API using Postman.

## What is Postman?
As per [their website](https://www.postman.com/) -- Postman is an API platform for building and using APIs. Postman simplifies each step of the API lifecycle and streamlines collaboration so you can create better APIs—faster.

<img src="./assets/postman-pat.gif">

Postman helps us to test our own APIs while building them and test other APIs before using them for us to see the API response formats and data that we are receiving so that we can deal with it accordingly in our application. It is used by many developers and many tech companies across the world.

So let's start by [downloading Postman](https://www.postman.com/downloads/).

After downloading and installing it successfully you should see something similar to this:

<img src="./assets/postman.jpg">

## Using Postman

Here's a quick 10 minute video for [the basics of using postman for API testing](https://www.youtube.com/watch?v=t5n07Ybz7yI).

Please note: The video is about 4 years old, so it is possible the UI of Postman might have some slight changes but overall it should still help you learn to use the tool.

### Explore on your own

After watching the video, please make sure to play around with the tool to get yourself familiar with it.

Use this API URL: https://jsonplaceholder.typicode.com

And try out these end points on Postman:
- `GET /posts`
- `GET /posts/1`
- `GET /posts/1/comments`
- `GET /comments?postId=1`
- `POST /posts`
- `PUT /posts/1`
- `PATCH /posts/1`
- `DELETE /posts/1`

Note: You can refer to the [JSONPlaceholder API guide](https://jsonplaceholder.typicode.com/guide/) to check the requirements of POST, PUT and PATCH requests.

If you're interested, you can find more endpoints to explore on their guide. You can also try exploring any other open source API if you like.

### Further Reading
Throughout the course, we will be using Postman quite often to test our APIs. So hopefully this initial exploratory practice was helpful for you. As we move into advanced topics, we will also explore advanced features of Postman such as sending authenticated API requests.

If you're fascinated by cool tech products and the history behind their creation, you can read [this blog post](https://blog.postman.com/how-we-built-postman-product-and-company/) called "How We Built Postman—the Product and the Company" by one of the co-founders of Postman.

You can also take a look at a new emerging tool called [Thunder Client](https://www.thunderclient.io/), which is an extension that can run API requests on VSCode directly without the need for an app.

### Submission
Since this is just an exploratory assignment and there is no code work, you can mark your assignment as submitted by following these simple steps:
1. Click on the blue button that says "Start Assignment".
2. Copy and paste the API response of the endpoint `PUT /posts/1` in the text box provided.
3. Click on "Submit Assignment".

---
## References
- https://www.postman.com/home
- https://www.thunderclient.io/
- https://dzone.com/articles/postman-for-api-testing-pros-cons-and-alternative