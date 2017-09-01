# Dev Portal Elements 

The YaaS documentation's Cascading Style Sheet (CSS) and other plug-ins control elements such as note panels and certain headings. These are the guidelines for using these styled elements. For information on using the HTML or MD syntax itself, see the <a href="/tools/documentationsdk/index.html#About">Syntax</a> section of the Documentation SDK.

## Headings

Ideally, headings fit onto one line in the generated output, but balance brevity with a heading that adequately describes the main point of the document, section, or topic. Follow these guidelines when writing headings:

* Write headings within a document in sentence case. For example, **Create a product category**.
* In the Dev Portal, use present tense verbs in headings. For example, **Add a document type**.
* While gerunds are acceptable in body-level content, DO NOT use gerunds in headings, as in **Creating a storefront**.
* Avoid stacked headings, which are headings without body-level content in between. For example, DO NOT use a Heading 3 (H3) to introduce one or more H4s. Instead, add a paragraph after the H3 that describes the main idea of the content in the headings that follow.

<div class="panel warning">
Do not use the first and second heading levels because they are reserved in the style sheets for the following uses:
<ul>
<li>Heading 1 displays the name of a service, tool, or other main topic.</li>
<li>Heading 2 displays the title of a document or section.</li>
</ul>
This means that if you use H1 or H2 inside your documents, the heading is too large in comparison to the overall navigation and separation of sections within the documentation. Start your headings with H3, and increase the numbering from there to decrease the heading size.
</div>

## Partials
If you have content that you can use in multiple places, use **partials**. For instance, create a partial for your service URL, then use the partial in all your documentation. When your service URL updates to a new version, you only have to update the partial, not every piece of documentation.

#### Tooltips
You can use partials as tooltips. For example, in an API Glossary document. When you define a glossary term in the template provided, and use that partial in your document, the definition of the term appears when the reader's cursor hovers over the term. For example, <%- @partial('generalterm_yaas') %>. Use this feature to make it easier for your readers to understand your content, and follow these guidelines:
* Define terms that the average person is not familiar with, or is unique in your usage.
* Don't define terms that are commonplace.
* Use a tooltip on the first instance of the term on a page, not every time the term appears in the document.

For information on reusing content, see the <a href="/tools/documentationsdk/index.html#ReuseContent">Reuse Content</a> section of the Documentation SDK.

## Panels
You can highlight important information such as **Note**, **Warning**, **Find Out More**, and **Tip** content in special panels with different colors. For information on using the panel HTML or MD syntax, see **Panels** in the <a href="/tools/documentationsdk/index.html#About">Syntax</a> section of the Documentation SDK.

Use panels sparingly so that they make an impact. Multiple panels within one page view interrupts the content flow. Also, do not use panels as the first content in a document. Always precede panels with body-level text and use the panel to call attention to the preceding text. For example:
<div class="panel tip">Use different colored panels to highlight certain information in your documentation.
</div>
