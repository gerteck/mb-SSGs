<frontmatter>
  title: Scully SSG
</frontmatter>

<br>

## Introduction to Scully

Scully is a static site generator for Angular projects looking to embrace the Jamstack.


# What is Scully?

Scully pre-renders each page in your app to plain HTML & CSS. To do this, Scully uses guessjs to find
all of the routes in your project. Scully then visits each route, rendering the view and saving it to an HTML file.

You can then ship all of those HTML files to production. Each view in your app can now be delivered to your users in just
a few KBs, as opposed to the hundreds/thousands of KBs require to download your entire Angular app.

Your app appears INSTANTLY on any device (including mobile 3G).

Once the fully-rendered HTML arrives/appears on the user's view, your Angular app will then load and bootstrap on top of
the existing view. This means that Scully gives you the best of both worlds:

1. The ability to pre-render your entire app to the most base form of HTML & CSS.
2. The ability to still have a full powered SPA written in Angular.

When your app is pre-rendered, users no longer wait until all the JavaScript has downloaded, parsed and executed before
they can see and interact with your website. They can immediately begin to see and interact with the page. When your page
is IMMEDIATELY available, you will have less abandoned sessions and a much higher conversion rate on your website.

This also means that you may not need to ship your backend to production. Because the view is pre-rendered and the
data is fetched at build time, all views that can run without the backend in prod CAN run without the backend in prod.
The security and cost implications to that fact can be mind blowing when you think about them.

For those wanting to know more about this process, please read the [Getting Started](https://scully.io/docs/learn/getting-started/requirements/) guide. For
those who want to know more about the theory behind pre-rendering JavaScript SPAs, our friends at [Netlify](https://netlify.com)
wrote a [free book about the Jamstack](https://www.netlify.com/pdf/oreilly-modern-web-development-on-the-jamstack.pdf).
Check that out today.