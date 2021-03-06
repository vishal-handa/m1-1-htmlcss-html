# HTML Comprehension Questions

## Q1 - For each of the following HTML documents, is the HTML valid?

Type true/false in the provided [ ].

a) [False] `<div><span>hello</div></span>` _First-in first-out technique._

b) [False] _Can't use a closing tag for <ol> when it wasn't used to begin with_

```html
<ul>
<li>one</li>
</ol>
```

c) [True] `<ul></ul><img/><ol><li>one</li></ol>` 

## Q2 - What is a screenreader and why should we care about them?

_Feel free to use the powers of Google here, but please provide link(s) to your source(s)_
_Screen readers are the softwares or browser extensions that read the text from the computer screen. The reader can read from any webpage to an empty screen. Common examples are NVDA, JAWS and ReadAloud. Screen readers allow people with visual impairment to have access to the same technology easily that people without impairments use. It is an accessibility and equal opportunity issue that we all should care about._

## Q3 - For each of the following cases, which tags will be needed?

a) You want to create a webpage with the photos from your latest vacation
_<img> tag is used to add the images._

b) You want to create a website that lists all the art gallery websites in your city and links to their website.
_<a href> tag is used to link the websites to the sources, <ul> or <ol> is used to define lists and <li> is used for individual list members._

c) You want to sell designer hats. You need to receive orders from the user.
_To start with <form></form> is used, and within form tag the page will use <label> tag and <input> tag for various entries in various formats (types texts, checkboxes, radio buttons). Finally for submission <input> with type button will be used._

## Q4 - Can a `button` be a child of a `button`? Explain your reasoning
_The button tag cannot be a child of another button tag. Nested buttons are not supported by HTML alone as it was tested, and it lost the functionality._

## Q5 - What is the most generic tag you can use? 
_html, body, p, a_

## Q6 - What do the following achronyms stand for?

a) `a`
_anchor_

b) `ol`
_ordered list_

c) `ul`
_unordered list_

d) `li`
_list_
e) `tr`
_table row_
f) `th`
_table header_

g) `td`
_table cell_

## Q7 - Usually, `td` elements are children of what kind of elements?
_'td' elements are children of 'tr' element_

## Q8 - What is the difference between td and th?
_They are almost the same but th is used for table header and td is used for filling in the value for a particular cell._

## Q9 - Which tag makes the text appear bigger: h1 or h3?
_h1_
## Q10 - In which situation can you use self closing tags?
_Self closing tags can be used when there is a lack of content between an opening and closing tag_

## Q11 - What is autofilling and why is it important?
_Assumption is made for Autocomplete because there is no attribute or tag named as autofill in HTML. Autocomplete is an attribute applied to the input text fields where the information entered by the user is available to be filled automatically in the similar text fields. It is important because it helps a user to quickly fill in similar information in a field._

## Q12 - Which attributes are always present in an img element?
_src to dictate the source of the image. height and width to dictate the size of the image._

## Q13 - Which attribute is always present for an anchor tag?
_href is always present for an anchor tag._