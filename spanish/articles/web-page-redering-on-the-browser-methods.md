> - Originally published at [How Web Pages Get Rendered on the Browser - Different Methods Explained](https://www.freecodecamp.org/news/web-page- rendering-on-the-browser-different-methods/)
> - Originally Posted by [Favour C. Felix](https://www.freecodecamp.org/news/author/favour/)
> - Translated by Papaya HUANG
> - Proofreader:

! [How Web Pages Get Rendered on the Browser - Different Methods Explained](https://www.freecodecamp.org/news/content/images/size/) w2000/2022/10/fav-poster.jpg)

Today, computers and networks around the world are becoming faster and faster. This facilitates the enhancement of Web development and user experience. The possibilities that people can realize through the Internet have also taken a big step forward.

The flip side of the remarkable progress also means that there are some people who have fallen behind. In this age of digital fragmentation, the challenge is how to improve the web experience to reach more users whose networks and devices are not as well equipped.

To solve this conundrum, one must first understand that the browser is the method by which web pages are rendered.

## Terms covered in this article

Before we begin, I need to make sure you are familiar with the terms covered in this article. Some of them may be difficult for new developers to understand. If you already know this section well, you can skip it.

- **Server**: A server is a computer located at a remote location (in the Internet sense) whose job is to process and respond to requests from clients.
- **Client**: A client is a device that communicates with a server to access resources. In most cases, a client is a device that can access the network. In this article, a web browser acts as a client.
- **CDN**: Acronym for Content Delivery Network, which is "a network of interconnected servers that speeds up the loading of web pages for data-intensive applications" (quoted from [AWS](https://aws. amazon.com/what-is/cdn/)).
- **Build Time**: At build time, the application code is prepared for another environment. Most of the time another environment here means a hosting environment on the Internet.

Now let's learn the different ways of rendering a website.

## What is Client Side Rendering (CSR)?

! [csr](https://www.freecodecamp.org/news/content/images/2022/10/csr.jpg)

Client-side rendering relies entirely on JavaScript code to generate web pages in the browser. The browser pre-processes the JS code before the page content is loaded for the user to view.

JavaScript dynamically assists in defining the **architecture** of a website at the time of download. Architecture in this context refers to fetching data from the [API](https://aws.amazon.com/what-is/restful-api/), site navigation, and some simple business logic within the site.

### Client-side rendering and JavaScript frameworks

Client-side rendering has become increasingly popular with the release of JavaScript frameworks or libraries such as React, Vue, and Angular. These frameworks only take effect when a CDN is introduced at the head of the HTML page - usually these CDNs contain a lot of JS code.

Translated with DeepL.com (free version)
