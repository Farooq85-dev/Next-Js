# Next-Js

## A short overview of next Js.

### What is Next-Js?

```
Next.js is a React Framework that provides built-in support for Server Side
Rendering, Static Site Generation, built-in routing based on file system, and many
more features!
Note:- You do not need to learn a new language or new syntax, Next.js is literally
just the same as React with plenty of unique features React itself as a library does
not provide.
Note:- Framework allows you to follow some rules and regulations yoi built something.
```

### Why use Next.js?

```
- Server Side Rendering!
- SEO Performant
- Extremely Fast
- File System Routing
- Built-in API Layer
- And Much more!
```

### Let's broke down previous concepts?

````
- You want to build a platform that can serve content fast
- Rank higher in search engines and possibly increase analytics
- You want your pages to have a fast initial load (landing pages)
- You may need an API layer but don’t want to set up a new project using
Express or Nest.js.```
````

### How can I learn Next.js?

```
- Learn React first!
- Understanding of Server Side Rendering, Static Site Generation, and Client-Side Rendering
- Understanding of Prerendering
```

## Let's Breakdown core concepts of Next Js?

### Pre-rendering

```
Next.js generates HTML for each page on the server-side. This process is called
pre-rendering and it can increase performance and SEO, which can positively
impact your application.
Pre-rendering is good since it will take care of generating all the HTML on the
server-side, rather than on the client-side.
```

### Static Generation

```
Static Generation is one of two forms of pre-rendering in Next.js.
Static Generation is when the HTML is generated during build time, and that
HTML is served upon each request.
This method of pre-rendering is great for apps that don’t change often,
e.g: Landing Pages, Portfolio Websites, Blogs, etc.
```

#### Server-Side Rendering

````
With Server-Side Rendering (SSR), the HTML is generated on each request.
If you have an application that has data changing constantly, you will want to
consider SSR over Static Generation.
This can be great for the same types of apps we mentioned earlier, assuming the
content is changing frequently.
But you can imagine, apps like e-commerce platforms can benefit with Server Side
Rendering and also have great SEO, because your products may need to appear
on Google! If you use Static Generation, you wouldn’t be able to see latest
updates to the listed product.```
````

### Note

```
Keep in mind, these concepts are NOT specific to Next.js. Everything you just
learned is transferable and goes a long way. Any framework you use or even if you
don’t use a framework, understanding these core concepts will benefit you
tremendously and help you pick the right tools you need to build an app.
```

### Client-Side Rendering

```
Client-Side Rendering is the opposite of Server-Side rendering. It just means all of
the rendering happens on the Client side, rather than the server side. The “client”
in this situation would just be the browser.
For example, when you use the useEffect hook in React to fetch data from an API,
then update some state, and then render the data in the form of JSX/TSX to the
DOM dynamically. This is client-side rendering, because the rendering happens on
the client side thanks to executed JavaScript code.
```
