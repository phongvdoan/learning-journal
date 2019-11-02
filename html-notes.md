# HTML & CSS - Process & Design
## Who is the site for
### Target Audience: Individuals
- What is the age range of your target audience?
- Will your site appeal to more women or men? What is the mix? - Which country do your visitors live in?
- Do they live in urban or rural areas?
- What is the average income of visitors?
- What level of education do they have?
- What is their marital or family status?
- What is their occupation?
- How many hours do they work per week?
- How often do they use the web?
- What kind of device do they use to access the web?
### Target Audience: Companies
- What is the size of the company or relevant department?
- What is the position of people in the company who visit your site?
- Will visitors be using the site for themselves or for someone else?
- How large is the budget they control?
## Why people visit your website
- Key Motivations
    - Are they looking for general entertainment or need to achieve a specific goal?
    - Is it a professional or personal goal?
    - Is it essential or luxury?
- Specific Goals
    - General information/ research
    - Are they familiar or do they need introduction?
    - Looking for time sensitive information?
    - Do they need to contact you?
## What information your visitors need
- Will visitors be familiar with your brand?
- Will they be familiar with the product?
- What are the most important features of the product?
- What is different then the competitors?
- What are the common questions people ask of the subject area?
## How often people will visit your site
- How many returning customers?
- How often is your stock updated or service changed/updated?
## Site Maps
- A diagram of the pages that will be used to structure the site.
- Use **card sorting** by placing each piece of information that a visitor need to know in groups
- Begins with the homepage
## Wireframes
- A sktech of the key information that needs to go on each page of a site.
- http://gomockingbird.com
## Getting your message across using design
Designer needs to organize and prioritize information and the help users find what they need. Make parts of the page distinct from surrounding content. And group related content into blocks or chucks to make it simple. 
- Larger elements and ones with different style will grab users' attention first just as foreground and background color can do so with bright colors.
## Designing Navigation
Site navigation should be concise, clear, selective, provides context, interactive, and consistent.

# HTML5
- `<header>` and `<footer>` elements can be used as the main header or footer at the top or bottom of each page, or it can be used in each section within the page.
- `<nav>` is used to contain the major navigational blocks on the site.
- If `<aside>` is used inside an `<article>` element, should contain information that is related to the article but not essential to its overall meaning like a glossary. If its used outside, it acts as a container for content that is related to the page.
- `<section>` element groups related content together with own heading. It may contain several `<article>` elements.
- `<hgroup>` element groups `<h1>` to `<h6>` elements.
- `<figure>` element is used to contain any content that is referenced from the main flow of an article. `<figcaption>` provides a text description for the content.
- `<div>` element is used to group together related elements.
- `<a>` element can be placed around a block level element that contains child elements which allows the block to be a link.
## Extra Markup

- HTML5
```
<!DOCTYPE html>
```

- HTML 4
```
<!DOCTYPE html PUBLIC
"-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
```
- Transitional XHTML 1.0
```
<!DOCTYPE html PUBLIC
"-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/
xhtml1-transitional.dtd">
```
- Strict XHTML 1.0
```
<!DOCTYPE html PUBLIC
"-//W3C//DTD XHTML 1.0 Strict//EN" "http://www.w3.org/TR/xhtml1/DTD/
xhtml1-strict.dtd">
```

- XML Declaration
```
<?xml version="1.0" ?>
```

- Comments in HTML
```
<!-- *insert comment* -->
```
- Use *id* and *class* attributes to identify elements.
- Block level elements include `<h1>`, `<p>`, `<ul>`, and `<li>` which starts a new line.
- Inline elements include `<a>`, `<b>`, `<em>`, and `<img>` which appear to continue on the same line as their neighboring elements.
- Using `<span>` to contain a section of text where there is no other suitable element to differentiate it from its surrounding text or to contain multiple inline elements.
- `<iframe>` is a little window that has been cut into your page to view another page. Attributes include `src`, `height`,  `width`, `scrolling`, `frameborder`, and `seamless`.
- `<meta>` inside the `<head>` element contains information about the webpage used by search engines. With attributes of `description`, `keywords`, `robots`, `author`, `pragma`, and `expires`.

