**HTML:** HTML stands for Hyper Text Markup Language.

- HTML is a markup language thet web developers use to structure and describe the content of a web page. because we use
  it to describe something.
- HTML consists of elements that describe different types of contents: paragraphs, links, headings, images, video etc.
- Web browsers understand HTML and render HTML code as websites.

* Every web element mainly consist of three parts:
  `<p?> HTML is a markup language</p>`
  1 Opening Tag: Name of the element, wrapped in < and >
  2 Content: Content of the element, in this example text. But it might be another element (Child element). Some elements
  have no content (e.g. `<img>`) at all and have only opening tag.
  3 Same as opening tag, but with a /. When element has no content, it's omitted.

  **HTML Document structure:**

  - Every html element starts with html tag `<html></html>`
  - Then one header and one body within the `<html>`
  - head element is not visible in the browser window. caontains page title, some additional information about the page,
    link to CSS file or other things.

**Headings:** Usually the goal of headings is to break up big blocks of text into more logical sections, and basically add a title to each of these sections.

**Bold:** `[<b>, <strong>]` Using `<b>` tag to make content bold is not a good practice. So B is actually an older HTML element. And Starting in HTML5, we should always use the strong element instead of B. Because B element doesn't have any so-called semantic meaning.means b is an element but without a specific meaning. While on the other hand, the strong element means that this is literally an important element that we want to standout from the page.

**Italic:** `[<i>, <em>]` Using `<i>` tag to make content bold is not a good practice because there is no semantic meaning. Instead we have to use <em> meaning emphasize.
