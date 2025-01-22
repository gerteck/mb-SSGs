<frontmatter>
  title: Chooing an SSG
</frontmatter>

<br>

# Choosing a Site Generator

With content managed using one or more of the techniques described in (setting up), it’s time to consider how it is transformed into production HTML.

## Evolution of Site Generators

In the beginning, site generators were almost synonymous with **Jekyll**, the first to gain significant traction. Created by **Tom Preston-Werner**, GitHub’s cofounder, Jekyll is written in Ruby. 

Today, site generators are available in many languages, including Ruby, Python, PHP, JavaScript, and Go. The website [staticgen.com](https://staticgen.com) lists over 30 languages and showcases the popularity of different generators. Most are free and open source.

Choosing a site generator can be challenging. While popularity is a factor, here are five key considerations:

---

## 1. The Type of Website

Each generator is designed with specific website types in mind:
- Complex taxonomy and thousands of pages
- Blogs
- Documentation
- Progressive Web Apps (PWAs) or highly interactive apps

**Advice:** Explore sample projects for each generator to determine compatibility with your goals.

---

## 2. The Programming Language Used

While prior programming experience isn’t always necessary, familiarity with the language can help for custom plugins and extensions.

Examples:
- **Hugo** (Go): Simple installation; no Go knowledge required.
- **Jekyll** (Ruby): Ruby installation needed but minimal language knowledge required.
- **Gatsby** (JavaScript): Requires Node.js for installation.

Choosing a generator in a language your team knows can streamline development.

---

## 3. The Templating Syntax

JAMstack development involves creating HTML templates, CSS, and JavaScript. Templating languages extend HTML functionality with reusable blocks, loops, and conditional statements.

Examples:
- **Jade/Pug**: Minimalist syntax using indentation.
- **Handlebars/Liquid**: Close to traditional HTML.

Choose a syntax that aligns with your team’s preferences.

---

## 4. Speed

Build speed becomes critical as site content grows:
- Small sites: Milliseconds to build.
- Large sites: Several minutes per build.

**Hugo** is known for its speed due to Go's multi-threaded architecture, whereas some generators (e.g., Gatsby, Nuxt) build JavaScript bundles alongside static HTML, increasing build times but optimizing site performance on CDNs.

---

## 5. Developer Tooling

Modern web development includes asset preparation, such as:
- Image compression
- JavaScript transpilation and minification
- CSS compilation (e.g., SASS, LESS)

Some generators, like **Nuxt** and **Gatsby**, include features for asset management, often leveraging tools like **Webpack**. Others rely on external utilities.

**Additional Features:**
- **Linting**: Automatically tests for errors in HTML, CSS, and JavaScript.
- **Local Testing and Hot Reloading**: Previews changes locally, with immediate browser updates upon saving.

---

## Final Thoughts

Recommending a site generator depends on:
- Personal preference
- Familiarity
- Intended use

Static site generators evolve rapidly, making it worthwhile to experiment with several options. Always explore the documentation to understand the problems each generator solves.
