# ***React 3***

## NEXT.JS

### Assets
Next.js can serve static assets, like images, under the top-level public directory. Files inside public can be referenced from the root of the application similar to pages.

The public directory is also useful for robots.txt, Google Site Verification, and any other static assets. Check out the documentation for Static File Serving to learn more.

let's retrieve your profile picture.


* Download your profile picture in .jpg format (or use this file).
* Create an images directory inside of the public directory.
* Save the picture as profile.jpg in the public/images directory.
* The image size can be around 400px by 400px.
* You may remove the unused SVG logo file directly under the public directory.

### Metadata
What if we wanted to modify the metadata of the page, such as the title HTML tag?

```
<Head>
  <title>Create Next App</title>
  <link rel="icon" href="/favicon.ico" />
</Head>
```
Notice that Head is used instead of the lowercase head. Head is a React Component that is built into Next.js. It allows you to modify the head of a page.

You can import the Head component from the next/head module.

Adding Head to first-post.js

We haven't added a title to our /posts/first-post route. Let's add one.

Open the pages/posts/first-post.js file and add an import for Head from next/head at the beginning of the file:


```
import Head from 'next/head'
```
Then, update the exported FirstPost component to include the Head component. 

### CSS Styling

Let’s now talk about CSS styling.

As you can see, our index page (http://localhost:3000) already has some styles. If you take a look at pages/index.js, you should see code like this:
```
<style jsx>{`
  …
`}</style>
```
This page is using a library called styled-jsx. It’s a “CSS-in-JS” library — it lets you write CSS within a React component, and the CSS styles will be scoped (other components won’t be affected).

Next.js has built-in support for styled-jsx, but you can also use other popular CSS-in-JS libraries such as styled-components or emotion.

## React Context for Beginners 
React context is an essential tool for every React developer to know. I lets you easily share state in your applications.

## What is React context?
React context allows us to pass down and use (consume) data in whatever component we need in our React app without using props.
## When should you use React context?
React context is great when you are passing data that can be used in any component in your application.

These types of data include:

* Theme data (like dark or light mode)
* User data (the currently authenticated user)
* Location-specific data (like user language or locale)

## How do I use React context?
There are four steps to using React context:

* Create context using the createContext method.
* Take your created context and wrap the context provider around your component tree.
* Put any value you like on your context provider using the value prop.
* Read that value within any component by using the context consumer.
