# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [F] `<div><span>hello</div></span>`

b) [F]

```html
<ul>
<li>one</li>
</ol>
```

c) [F] `<ul></ul><img/><ol><li>one</li></ol>`

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_

Screen reader is a software program designed for visiually impaired users to read text out loud.

https://www.afb.org/blindness-and-low-vision/using-technology/assistive-technology-products/screen-readers

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation

<img src="https://exclaim.ca/images/garfield_2.jpg">, 

b) You want to create a website that lists all the art gallery websites in your city and links to their website.

<ol>
<li>
<a href="https://www.station16gallery.com/collections/stikki-peaches">Stikki Peaches</a>
<a href="https://www.mbam.qc.ca/en/">MBAM</a>
</li>
</ol>

c) You want to sell designer hats. You need to receive orders from the user.

<input>, <form>, <label>, <text>

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning

No, a button is an inline element and it will appear on the same line

## Q5 - What is the most generic tag you can use?

<div> (but we don't like this one)

## Q6 - What do the following achronyms stand for?

a) `a`

Hyperlink

b) `ol`

Ordered List

c) `ul`

Unordered Lists

d) `li`

List element within the list

e) `tr`

Table

f) `th`

Table Head

g) `td`

Table Data

## Q7 - Usually, `td` elements are children of what kind of elements?

<TABLE> // Block level elements

## Q8 - What is the difference between td and th?

TH are Table Headers for the cells, TD is table data within the cells

## Q9 - Which tag makes the text appear bigger: h1 or h3?

h1

## Q10 - In which situation can you use self closing tags?

<area> , <base> , <br> , <col>, <embed> , <hr> , <img> , <input> , <link> , <meta>, <param> , <source> , <track> , <wbr>

## Q11 - What is autofilling and why is it important?

Provides an easy way to fill out and submit information online, it's important as it can be considered as an ease of access, and it can store sensitive data in the user's browser cache 

Source: https://www.netsparker.com/blog/web-security/impact-autocomplete-feature-web-security/#:~:text=The%20HTML%20autocomplete%20attribute%20allows,in%20the%20user's%20browser%20cache.

## Q12 - Which attributes are always present in an img element?

src & alt

## Q13 - Which attribute is always present for an anchor tag?

href

