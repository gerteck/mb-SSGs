<frontmatter>
  title: FAQ
</frontmatter>

<br>

# Frequently Asked Questions 

### What exactly is Client-side rendering, Server-side rendering and Prerendering?

**Client-side rendering** is performed in the browser with JavaScript. 
* This term is not used to refer to the work that browsers do by default to render HTML documents; instead, it describes the process
by which *JavaScript is used to manipulate the Document Object Model (DOM) and dynamically manipulate what the browser displays*. 
It has the advantage of allowing user actions to immediately influence what is displayed, and it also can be very efficient in combining data from many different sources into templated views. Web browsers, though, are not as tolerant to errors found in JavaScript as
they are with HTML. Where possible, it is prudent to deliver as much content as possible already rendered into HTML on the
server, which then can be further enriched and enhanced with JavaScript in the browser.


**Server rendering** refers to the process whereby a server responds to requests for content by compiling (rendering) the required content
into HTML and delivering it on demand for the browser to display. 
* The term is often used as the antithesis of client-side rendering,
when data (rather than ready-generated HTML) is delivered into the browser where it must then be interpreted and rendered into HTML
or directly manipulate the browser’s DOM via JavaScript. (Clientside rendering such as this is common in single-page applications
[SPAs].) Server-rendering typically happens just-in-time based on what requests are being made.


**Prerendering** performs the same task of compiling views of content as we see in server rendering, but this is carried out only once and in advance of the request for the content. 
* Rather than awaiting the first request for a given piece of content before we know if the result will
be correct, we can determine this at build time. Decoupling this rendering or generation of views from the timing
(and machinery) at request time allows us to expose the risk early and tackle any unknowns of this operation far in advance of the
times a request for the content is made by a user. By the time requests for prerendered content arrives, we are in a position to simply return the prebaked response without the need to generate it each time.



<panel>

Hello There

</panel>
