1. Make a page that has a menu navbar of list
2. the page should have a list and maybe a nested list
The page should use at least three <h> tags and paragraph tags
the page should have links off the type: a tag,
  link to another page
  link to page on same site
  link to different location on same page
  open page in new browser/tab
  compose a email

 INFO
     <!-- create diffrent list Li ul dl
    ul = unordered list, all items are placed on the same line.
    ol= numbered lists
    li= List item, puts list in different lines
    dl = description list
  -->
------------------------
  BasicsStructionV1
------------------------

SEMANTIC ELEMENTS ---important!

Making semantic content
semantic markup is importent for users who are blind that uses a bot to read the page.

create a header with title, logo and navbar
create a footer with some contact info and copyright
create a few sections (section should start with a h2 tag, ex. contact, about, blogposts.. io group related content)

CONTENT SECTION ELEMENTS
<ARTICLES> https://developer.mozilla.org/en-US/docs/Web/HTML/Element/article
Elements that is an standalone article. that can be taken out of context and still make sense based on heading and paragraphs.

the <article> section element - describes self contained pices of content, like blogposts.

<NAV> https://developer.mozilla.org/en-US/docs/Web/HTML/Element/nav
is used for every major link elements like in the header and footer

<ASIDE> https://developer.mozilla.org/en-US/docs/Web/HTML/Element/aside
Like sidebar, not directly related to the main content but it holds content that is related to the entire page.

Use quote tags <q></q>

Then link the blopost to the main page

MAIN is refered to where the main content is wich is importent for screen reader programs.
Main should only be used once per page, and shoulnd be content that is cpoied or used in header, nav, sidebar or footer.

Use DIV elements for page wrapper and elements that dosent apply to article, nav aside or header.

Use blockquote ande cite tags

FOOTER
Footer can be used as credit to authur or publish date.

HEADER
You can use multiple headers for title authur and date and category.


IMAGES
figcaption shows a caption of the image. By default it indents the content.
<figure>
  <figcaption></figcaption>
</figure>

HR <hr> makes a line, this is not used for estetics but to indicate to the browser a end of a section and a start of another, like a footer or header.

TEXT LEVEL ELEMENTS
<strong> – Gives bold
<em> – displays in italics
<small> – Smaller like copyright or cite
<span> – it has no semanic ability but can be  used with CSS when no other text element can be used. Like div tag.
span are inline element so it dosent give a space around it.

#LINKING
id=about
a href="#about"
a href="about.html#about"

MAILTO;
Cool feature is addign subject
mailto:my@mail.com?subject=subjet
