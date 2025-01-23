---
  title: Home Page
  layout: default.md
  pageNav: 4
  pageNavTitle: "Topics"
---

<br>

## Static Site Generators

This site, created with MarkBind, serves as a comprehensive wiki for exploring different Static Site Generators (SSGs). Whether you're a developer deciding on the right tool for your next project or a curious learner, this guide will cover the #b#essentials##, #g#benefits##, #r#drawbacks##, and comparisons of various SSGs.

> "Static Site Generators empower you to build fast, secure, and scalable websites with ease, all while embracing simplicity and cutting-edge web performance."
> > Use MarkBind


<span class="badge bg-primary">
- Chatgpt, probably
</span>

<br/>
<br/>

<box>
<md>

### Why use SSGs?

1. **Speed and Performance** 
    - SSGs pre-generate HTML files, resulting in lightning-fast page load times. { icon="zap" }
2. **Enhanced Security**  
   - With no server-side code execution, the attack surface is significantly reduced. { icon="dagger" }
3. **Scalability**  
   - Serve static files directly via CDNs, making scaling effortless for high traffic. { icon="traffic_light" }
4. **Simplified Hosting**  
   - Host static files on cost-effective platforms like GitHub Pages, Netlify, or Vercel. { icon="traffic_light" }
5. **Developer Productivity**  
   - Focus on content and design with minimal backend configuration. { icon="airplane" }
6. **SEO Benefits**  
   - Pre-rendered HTML improves search engine crawlability and indexing. {icon="bow_and_arrow"}
7. **Version Control Integration**  
   - Content and code are managed in a single repository, enabling seamless version control. {icon="passport_control"}
8. **Flexibility with Modern Tools**  
   - SSGs integrate well with modern tools and frameworks (e.g., React, Vue, Markdown). {icon="hammer"}
9. **Better User Experience**  
   - Deliver instant page transitions with progressive enhancements. {icon="moyai"}
</md>
</box>


<box type="tip">

***Quick Tip***: 

If you're new to Static Site Generators, start by identifying your project's requirements (e.g., blogs, documentation, or portfolios) and choose an SSG that matches your preferred programming language. For a lightweight start, try Jekyll or Hugo. For more dynamic functionality, explore Gatsby or Next.js. But of course, you can start by playing around with [MarkBind](https://markbind.org/)!

Read more about Setting up your Project [here](./contents/setting-up.md)!

Read more about Choosing an SSG [here](./contents/choosing-ssg.md)!

</box>

<br/>

--- 

## What are Static Site Generators?

_Static Site Generators_ are, in short (SSGs), an application that takes plain text files and compiles them to html files, or static web pages. 

Unlike traditional web applications that depend on a backend to dynamically generate content for each request, SSGs pre-build all pages during the site generation process. This results in static web pages that can be served directly by a Content Delivery Network (CDN) or web server. They don't need a backend after site generation.

**Benefit**: Speed, process of generating HTML happens at build time. No need to run server or backend.

This is compared to something like WordPress, which is a dynamic content management system, where the HTML files are generated dynamically upon request. Read More [here](./contents/cms/wordpress.md)

<box type="info" seamless>

Some popular static site generators include Jekyll, Hugo, Eleventy, Gatsby and Next.js (and MarkBind). There are hundreds of SSGs that exist.

</box>


<br/>

<panel header="**What is MarkBind?**" type="light">

<include src="./contents/markbind.md"/>

</panel>

<br/>
<br/>

### Comparison of SSGs



| Static Site Generator | Performance | Ease of Use | <popover content="Framework integration refers to how well a static site generator (SSG) works with or depends on a specific front-end framework (like React, Vue.js, or Angular)."> Framework Integration </popover> | Customization | Remarks                     |
|------------------------|:-----------:|:-----------:|:----------------------:|:-------------:|----------------------------|
| Hugo                  | Excellent   | Easy        | Limited               | High          | Known for speed and flexibility. |
| Scully                | Excellent   | Moderate    | Angular               | Moderate      | Best suited for Angular projects. |
| Gatsby                | Very Good   | Moderate    | React                 | High          | Strong plugin ecosystem but can be slow for large sites. |
| Next.js               | Very Good   | Moderate    | React                 | Very High     | Offers both SSG and SSR, ideal for hybrid applications. |
| Jekyll                | Good        | Easy        | Limited               | Moderate      | Great for blogs, backed by GitHub Pages. |
| Nuxt.js               | Very Good   | Moderate    | Vue.js                | High          | Combines SSG, SSR, and modern Vue features. |
| MarkBind             | Awesome        | Easy        | Limited               | Moderate      | Tailored for documentation with a focus on simplicity. |

<br/>
<br/>