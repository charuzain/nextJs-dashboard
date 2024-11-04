## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.


### Global Styles
Inside the /app/ui folder, we have global.css. We can use this file to add CSS rules to all the routes in our application - such as CSS reset rules, site-wide styles for HTML elements like links, and more.

We can import global.css in any component in our application, but it's usually good practice to add it to top-level component. In Next.js, this is the root layout

- Tailwind
Tailwind is a CSS framework that speeds up the development process by allowing you to quickly write utility classes directly in your TSX markup.
When you use create-next-app to start a new project, Next.js will ask if you want to use Tailwind. If you select yes, Next.js will automatically install the necessary packages and configure Tailwind in your application.

### CSS Modules
If you prefer writing traditional CSS rules or keeping your styles separate from your JSX - CSS Modules are a great alternative.

CSS Modules allow you to scope CSS to a component by automatically creating unique class names, so you don't have to worry about style collisions as well.

Tailwind and CSS modules are the two most common ways of styling Next.js applications. Whether you use one or the other is a matter of preference - you can even use both in the same application!



## Quiz
What is one benefit of using CSS modules?
Ans. Provide a way to make CSS classes locally scoped to components by default, reducing the risk of styling conflicts.