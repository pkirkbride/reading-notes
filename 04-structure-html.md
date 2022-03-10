# Structure web pages with HTML - Read 04

## Wireframe and design

Designing a website usually starts with developing a wireframe. Wireframes are high-level plans for how the information will be displayed on a website or app. This step helps you consider what is important enough to be the first thing a user sees and what can go *below the fold*.

It is a good idea to work with hand-drawn wire frames initially because they are easy to change and can be used right away to get user feedback. Once the design is largely established, then switching to a software wireframe could make sense to track more minute changes.

Another key step is to map out user flow so that you know where the users are coming from and where they are going on the site. This step will help define how many different pages you need, what content they should have, and how they are related.

Now it's time to complete a draft. Don’t get too lost in the details (e.g. colors, aesthetics) at this point. Only after the draft is complete should you make decisions on formatting. This method will help keep you from getting bogged down in the process.

## HTML Basics

The function of HTML is to structure web pages and their content. While it will influence how they look, those details will actually be handled by cascading style sheets \(CSS)\--more on those later.

Most HTML consists of opening and closing tags like the example below.

```(html)
<p>Here's the text that will appear on the web page.</p>
```

To see more examples and get a better understanding of how to compose HTML, I suggest taking a look at [MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics).

Semantics plays an important role in writing code for HTML pages. In this context, semantics refers the meaning of the tags used in the code. For example, you could specifiy all of the details \(e.g. typeface, font, line breaks)\ about how an address should look displayed on the page every time an address is displayed. Alternatively, if you use the `<address>` tag, not only can the style be defined once on the CSS, it will influence search engine rankings based on the tags on the page.
