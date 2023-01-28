# HTML

![HTML Tutorials](https://github.com/pour68/html-tutorials/blob/master/images/html-header.jpg "HTML Tutorials")

## Study pattern

1. History
2. Definition
3. Settings up development environment
4. Topics
   - Basic
   - Intermediate
   - Advance

## History

- founder: Tim Berners-Lee (is an English computer scientist best known as the inventor of www)
- birthdate: 1991
- story: The first version of HTML was written by Tim Berners-Lee in 1991 that is extension of SGML, since then, there have been many different versions of HTML. The most widely used version throughout the 2000's was HTML 4.01, which became an official standard in December 1999, Another version, XHTML, was a rewrite of HTML as an XML language became an official standard in 2000 and then HTML5 became an latest HTML standard in 2011 till now.
- goals: HTML code ensures the proper formatting of text and images for your Internet browser. Without HTML, a browser would not know how to display text as elements or load images or other elements. HTML also provides a basic structure of the page, upon which Cascading Style Sheets are overlaid to change its appearance.
- GML(1969)(Charles Goldfarb, Edward Mosher and Raymond Lorie) -> SGML(1986)(IBM) -> XML(1990)(W3C) -> HTML(1993)(W3C & WHATWG)
- Mime-type: text/html

![Tim Berners-Lee](https://github.com/pour68/html-tutorials/blob/master/images/tim-berners-lee.png "Tim Berners-Lee")

## Why HTML?

HTML is standard markup language for building web pages its also called language of tags.
HTML describes the structure of a Web page.
HTML consists of a series of elements.
HTML elements tell the browser how to display the content.

## HTML definition

HTML stands for HyperText Markup Language.

## HTML file extensions

- .htm - .html

## HTML file structure

``` <!DOCTYPE html> ```
``` <html> ```
``` <head> ... </head> ```
``` <body> ... </body> ```
``` </html> ```

## head tag application

``` head tag is a container for meta data ```

## body tag application

``` body tag is a container for visible part of the page ```

## Setting up your development environment

- TextEditor: Notepad(windows) - TextEdit(macos) - Vim(linux)
- Advance TextEditor: VSCode - Atom - ...
- IDE: Visual studio - ...

## Difference ways of opening a project in vscode

## Get familiar with vscode

### VSCode extensions

- Live server
- Auto close tag
- Auto rename tag
- Indent rainbow
- Material icon theme
- Prettier

## UI & UX

UI: User interface of application.
UX: User experience of user based on the application.

- UX without UI: Brain without a body.
- UI without UX: Body without a brain.

## UI sections

UI designers make products joyful to interact with, they focus on visual hierarchy and patterns that give visual cues to users.

- Typography
- Color scheme
- Iconography
- Container
- Layout
- HyperLink
- Table
- List
- Figure
- Multimedia
- Graphic
- Form
- Animation

## UX sections

UX always puts users needs first when considering design solutions in order to enhance customer satisfaction.

- Defining a problem
- Understanding users
- Creating personas
- Generating tasks and user flows
- Creating sketches, wireframes and prototypes
- Usability testing

- Experience strategy
- User research
- Information architecture
- Interaction design

## HTML analogy

- human-body skeleton
- skeleton of building

## Comment

``` <!-- comments are not displayed by the browser, but they can help document your HTML source code --> ```

### use cases

- documentation
- notification
- reminder
- debugging
- hide content

### Types

- single-line
- multi-line

## Sketch, wireframe, prototype apps

- figma
- adobe xd

## HTML tag types

- empty tag
``` e.g: <br /> - <hr /> ```
- pair tag
``` e.g: <p> plain text </p> ```

## Difference between plaintext and content

- plaintext
``` e.g: <p> plain text </p> ```
- content
``` e.g: <p> plain text <br /> </p> ```

## Paragraph tag

- ``` <p> paragraph tag </p> ```
- HTML category: Pair tag
- UI category: Typography
- Paragraph tag is suitable for plain text and content.

## Headings

- h1 - h2 - h3 - h4 - h5 - h6
- ``` <h1> heading 1 tag </h1> ... <h6> heading 6 tag </h6> ```
- HTML category: Pair tag
- UI category: Typography
- Heading tags is suitable for plain text and content.

## What is emmet?

high-speed markup language tag generator.

## emmet method

``` e.g.: ! !!! doc ```
``` e.g.: p*2 ```
``` e.g.: h${Heading $}*6 ```
``` e.g.: h${Heading $$}*6 ```
``` e.g.: p[title="paragraph"] ```
``` e.g.: (header.header#header>nav.nav>ul.nav__list>li.nav__item*6>a.nav__link)+main+footer ```
``` e.g.: header.header#header>nav.nav>ul.nav__list>li.nav__item*6>a.nav__link^main+footer ```
``` e.g.: form:post>(.group>label+input:text)+(.group>label+input:number) ```

## Formatting elements

- b - strong - i - em - del - ins - mark - sub - sup
- ``` <mark> highlighted tag </mark> ```
- HTML category: Pair tag
- UI category: Typography
- formatting tags is suitable for plain text and content.

## Marquee element(obsolete)

```<marquee behavior="scroll|slide|alternate" bgcolor="color|hex" direction="left|right|up|down" height="" width="" loop="-1" scrollamount="6" scrolldelay="85"> content </marquee>```

- scrollamount: Sets the amount of scrolling at each interval in pixels. The default value is 6.
- scrollDelay: Sets the interval between each scroll movement in milliseconds. The default value is 85. Note that any value smaller than 60 is ignored and the value 60 is used instead, unless truespeed is specified.
- truespeed: By default,scrolldelay values lower than 60 are ignored. If truespeed is present, those values are not ignored.

## HTML tags behavior

- inline-level
- block-level

## Attributes

key/value paired data that defines on start tag of html tags and control the behavior of that tag.

- ``` <p title="paragraph">paragraph</p> ```
- ``` <p id="description">paragraph</p> ```
- ``` <h1 class="heading" id="heading">paragraph</h1> ```

- [language code](https://www.w3schools.com/tags/ref_language_codes.asp)
- [country code](https://www.w3schools.com/tags/ref_country_codes.asp)

Note:

- class used to select multiple elements in html document.
- id used to select single element in html document.
- id can be used to create bookmark in html document by the help of url fragment.

## Anchor element

- a
- ``` <a href="address" target="_blank"> Link </a> ```
- HTML category: Pair tag
- UI category: HyperLink
- Link

## Quotation elements

- q - abbr - address - blockquote - cite - bdo
- ``` <q> a short quotation </q> ```
- ``` <abbr title="description of acronym"> abbreviation </abbr> ```
- ``` <address> defines contact information for the author/owner of a document </address> ```
- ``` <blockquote cite="url"> a section that is quoted from another source </blockquote> ```
- ``` <cite> the title of a creative work </cite> ```
- ``` <bdo dir="ltr"> used to override the current text direction </bdo> ```
- HTML category: Pair tag
- UI category: Typography

## Computer code

- code - kbd - samp - pre - var
- ``` <code> computer code </code> ```
- ``` <kbd> keyboard input </kbd> ```
- ``` <samp> sample output </samp> ```
- ``` <pre> preformatted text </pre> ```
- ``` <var> variable </var> ```
- HTML category: Pair tag
- UI category: Typography

## Image

- img
- ``` <img src="address" alt="text" /> ```
- HTML category: Empty tag
- UI category: Figure
- Image

## Image map

- ``` <img src="table.jpg" alt="workshop table" usemap="#workmap" /> ```

- ``` <map name="workmap"> ```
- ``` <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm" /> ```
- ``` <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm" /> ```
- ``` <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm" /> ```
- ``` </map> ```

- [image map generator](http://image-map.weebly.com/)
- [url shortener](https://free-url-shortener.rb.gy/)

## Picture

- ``` <picture> ```
- ``` <source media="(min-width:650px)" srcset="img_pink_flowers.jpg" /> ```
- ``` <source media="(min-width:465px)" srcset="img_white_flower.jpg" /> ```
- ``` <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;" /> ```
- ``` </picture> ```
- HTML category: Pair tag
- UI category: Figure
- Picture

Note: bandwidth and format support are reasons for selecting picture over img.

- bandwidth: If you have a small screen or device, it is not necessary to load a large image file.
- format support: The browser will use the first ```<source>``` element with matching attribute values, and ignore any following ```<source>``` elements.

## Questions 1

1. What is a computer?
2. What is DNS?
3. What is IP?

### Exercise 1

1. What is os?
2. What is os ISO file?
3. What is hardware?
4. What is software?

## Meta tags

- ``` <meta charset="UTF-8" /> ```
- ``` <meta name="description" content="Free Web tutorials" /> ```
- ``` <meta name="keywords" content="HTML, CSS, JavaScript" /> ```
- ``` <meta name="author" content="Pouria Nayeb" /> ```
- ``` <meta http-equiv="x-ua-compatible" content="ie=edge" /> ```
- ``` <meta name="viewport" content="width=device-width, initial-scale=1.0" /> ```
- ``` <meta http-equiv="refresh" content="30" /> ```
- ``` <base href="https://www.w3schools.com/" target="_blank" /> ```
- ``` <link rel="icon" href="favicon.ico" type="image/x-icon" /> ```
- For SEO & Technical purposes.

- [meta tags](https://htmlcheatsheet.com/)
- [image splitter](https://pinetools.com/split-image)
- [image cutter](https://www.imgonline.com.ua/eng/cut-photo-into-pieces.php)
- [convert png to ico](https://www.freeconvert.com/png-to-ico)

Note: link element defines the relationship between a document and an external resource.

## Style & Script

``` <link rel="stylesheet" href="url" /> ```
``` <script src="url"></script> ```
``` <noscript>Your browser does not support JavaScript</noscript> ```

## Question 2

1. What is CDN?
2. What is deep and dark web?
3. What is device mac-address?
4. what is difference between static and dynamic webpages?

### Exercise 2

1. What is driver?
2. How to access windows charset?
3. How to access windows emojis?

## Browser JavaScript engines

- Safari V8
- IE/Edge Chakra/V8
- FireFox Spider Monkey
- Apple Javascript Core Webkit

## Container elements

- div - span
- ``` <div> <h1> Heading 1 </h1> <p> Paragraph </p> </div> ```
- HTML category: Pair tag
- UI category: Container
- Container tags can be a container for all html tags.

## Semantic elements

- main - header - footer - nav - section - article - aside - figure - figcaption - time - details - summary - dialog - ruby - rt - rp
- ``` <article> <h1> Heading 1 </h1> <p> Paragraph </p> </article> ```
- ``` <dialog open>This is an open dialog window</dialog> ```
- ``` <details> <summary>Epcot Center</summary> <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p> </details> ```
- ``` <ruby> 漢 <rt> ㄏㄢˋ </rt> </ruby> ```
- ``` <ruby> 漢 <rp>(</rp><rt>ㄏㄢˋ</rt><rp>)</rp> </ruby> ```
- HTML category: Pair tag
- UI category: Container
- Container tags can be a container for all html tags.

## HTML validator

- [W3 HTML validator](https://validator.w3.org/)

## HTML vs XHTML

- [XHTML vs HTML](https://www.w3schools.com/html/html_xhtml.asp)

## Entities, Symbol and emojis

- [HTML entities](https://www.w3schools.com/html/html_entities.asp)
- [HTML symbol](https://www.w3schools.com/html/html_symbols.asp)
- [HTML emojis](https://www.w3schools.com/html/html_emojis.asp)

## Table elements

- table - caption - tr - th - td - thead - tbody - tfoot - colgroup - col
- ``` <table> <tr> <th> ID </th> <th> Name </th> </tr> <tr> <td> 1 </td> <td> Pouria </td> </tr>  </table> ```
- ``` <table> <colgroup> <col span="2" style="background-color: lightblue" /> <col span="3" style="visibility: collapse" /> </colgroup> <tr> <th> MON </th> <th> TUE </th> ... </tr> <tr> ... </tr>  </table> ```
- HTML category: Pair tag
- UI category: Table
- Table tag can be a container for all tabular data.

- [HTML table generator](https://www.textfixer.com/html/html-table-generator.php)

Note: tables allow web developers to arrange data into rows and columns.

## List elements

- ul - ol - dl - li - dt - dd
- ``` <ul type="circle|square|disc|none"> <li>Mango</li> <li>Milk</li> </ul> ```
- ``` <ol type="1|A|a|I|i" start="" reversed> <li>Mango</li> <li>Milk</li> </ol> ```
- HTML category: Pair tag
- UI category: List
- List tag can be a container for all list items.

Note: lists allow web developers to group a set of related items in lists.

### types

- unordered list
- ordered list
- description list

## Iframe element

- iframe
- ``` <iframe href="" width="" height="" name=""></iframe> ```
- HTML category: Pair tag
- UI category: Multimedia
- Iframe tag can be used to as tool to display a website inside another one.

## Questions 3

1. Client/Server pattern
2. [HTTP response status code](https://www.w3schools.com/tags/ref_httpmessages.asp)
3. [HTTP methods](https://www.w3schools.com/tags/ref_httpmethods.asp)

## Multimedia elements

- video - audio - embed - object - source - track
- ``` <video src="address" controls muted autoplay></video> ```
- ``` <audio src="address" controls muted autoplay></audio> ```
- ``` <object data="address"></object> ```
- ``` <embed src="address" /> ```
- ``` <audio controls> <source src="horse.ogg" type="audio/ogg" /> <source src="horse.mp3" type="audio/mpeg" /> Your browser does not support the audio element. </audio> ```
- ``` <video width="320" height="240" controls> <source src="forrest.mp4" type="video/mp4" /> <source src="forrest.ogg" type="video/ogg" /> <track src="fg_subtitles_en.vtt" kind="subtitles" srclang="en" label="English" /> <track src="fg_subtitles_no.vtt" kind="subtitles" srclang="no" label="Norwegian" /> </video> ```
- HTML category: Both
- UI category: Multimedia
- Multimedia tags is used to display multimedia content in html document.

## Question 3

1. Computer components

### Exercise 3

1. Computer buying guide

## Graphic elements

- svg - canvas
- ``` <svg width="100" height="100"> <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" /> </svg> ```
- ``` <canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;"> Your browser does not support the HTML canvas tag. </canvas> ```

## Form elements

- form - label - input -  select - option - textarea - button - fieldset - legend - datalist - output - optgroup - datalist - output - progress - meter

### Form

- ``` <form method="get|post" action="url" enctype="multipart/form-data" autocomplete="on" novalidate> content </form> ```

### Label and input

- ``` <label for="input id">plain text</label> ```
- ``` <input type="text|password|email|search|tel|url" id="" class="" placeholder="" value="" pattern="" minlength="" maxlength=" name="" size="" required autofocus readonly disabled /> ```
- ``` <input type="hidden" /> ```
- ``` <input type="number" min="1" max="5" step="2" /> ```
- ``` <input type="range" min="0" max="50" /> ```
- ``` <input type="date" min="YYYY-MM-DD" max="YYYY-MM-DD" /> ```
- ``` <input type="month|week" /> ```
- ``` <input type="datetime-locale" /> ```
- ``` <input type="time" /> ```
- ``` <input type="checkbox" checked /> ```
- ``` <input type="radio" checked /> ```
- ``` <input type="color" /> ```
- ``` <input type="file" multiple /> ```

### Textarea

- ``` <textarea cols="" rows=""></textarea> ```

### Dropdown

- ``` <select name="cars" id="cars"> <option value="mercedes">Mercedes</option> <option value="audi">Audi</option> </select> ```

- ``` <select name="cars" id="cars"> <optgroup label="Swedish Cars"> <option value="volvo">Volvo</option> <option value="saab">Saab</option> </optgroup> <optgroup label="German Cars"> <option value="mercedes">Mercedes</option> <option value="audi">Audi</option> </optgroup> </select> ```

### Button

- ``` <input type="button|reset|submit|image" value="" /> ```
- ``` <button type="button|reset|submit"> content </button> ```

### Fieldset and legend

- ``` <fieldset> <legend> label </legend> </fieldset> ```

1. ``` The <fieldset> tag is used to group related elements in a form ```
2. ``` The <fieldset> tag draws a box around the related elements. ```
3. ``` The <legend> tag is used to define a caption for the <fieldset> element. ```

### Datalist

- ``` <label for="browser">Choose your browser from the list:</label> <input list="browsers" name="browser" id="browser" /> <datalist id="browsers"> <option value="Edge" /> <option value="Firefox" /> <option value="Chrome" /> <option value="Opera" /> <option value="Safari" /></datalist> ```

### Output

- ``` <form oninput="x.value=parseInt(a.value)+parseInt(b.value)"> <input type="range" id="a" value="50" /> + <input type="number" id="b" value="25" /> = <output name="x" for="a b"></output> </form> ```

### Progress bar

- ``` <progress value="32" max="100"> 32% </progress> ```

### Meter

- ``` <meter id="disk_c" value="2" min="0" max="10">2 out of 10</meter> ```

## Input form attribute

- ``` <form id="login"></form> <input type="text" form="login" /> ```
- ``` <form> <input type="submit" formaction="url" formenctype="multipart/form-data" formmethod="post" formtarget="_blank" formnovalidate="formnovalidate" value="" /> </form> ```

## URL encoding/decoding

- [URL encoding/decoding](https://meyerweb.com/eric/tools/dencoder/)

## Browser support

- [can I use](https://caniuse.com/)

## HTML accessibility

- role attribute
- aria-* attribute

- [Aria attribute helper](https://www.w3.org/TR/html-aria/)

## HTML API

- GeoLocation
- Drag/Drop
- Web storage
- Web workers
- SSE

## Data attribute

- data-*
- Specify attribute

``` <article id="electric-cars" data-id="3"> ... </article> ```

- Get by css

``` article::before { content: attr(data-parent); } ```

- Get by javascript

``` const article = document.querySelector('#electric-cars'); ```
``` article.dataset.id ```

## Resources

- [Pexels](https://www.pexels.com/)
- [Unsplash](https://unsplash.com/)
