# HTML

![HTML Tutorials](https://github.com/pour68/html-tutorials/blob/master/images/html-header.jpg "HTML Tutorials")

## History

- founder: Tim Berners-Lee (is an English computer scientist best known as the inventor of www)
- birthdate: 1993
- story: The first version of HTML was written by Tim Berners-Lee in 1993 that is extension of SGML, since then, there have been many different versions of HTML. The most widely used version throughout the 2000's was HTML 4.01, which became an official standard in December 1999, Another version, XHTML, was a rewrite of HTML as an XML language became an official standard in 2000 and then HTML5 became an latest HTML standard in 2011 till now.
- goals: HTML code ensures the proper formatting of text and images for your Internet browser. Without HTML, a browser would not know how to display text as elements or load images or other elements. HTML also provides a basic structure of the page, upon which Cascading Style Sheets are overlaid to change its appearance.
- GML(1969)(Charles Goldfarb, Edward Mosher and Raymond Lorie) -> SGML(1986)(IBM) -> XML(1990)(W3C) -> HTML(1993)(W3C & WHATWG)

![Tim Berners-Lee](https://i.guim.co.uk/img/media/78d8b6633929f6f931bf16f00057c3817c82ec76/0_0_5098_3059/master/5098.jpg?width=620&quality=85&fit=max&s=4805969f026815bd52a888fdb7b225e0 "Tim Berners-Lee")

---

## Why HTML?

HTML is markup language for building web pages its also called language of tags.

---

## HTML definition

HTML stands for HyperText Markup Language.

---

## HTML file extensions

- .htm - .html

---

## HTML file structure

``` <!DOCTYPE html> ```
``` <html> ```
``` <head> ... </head> ```
``` <body> ... </body> ```
``` </html> ```

---

## head tag application

``` head tag is a container for meta data ```

---

## body tag application

``` body tag is a container for visible part of the page ```

---

## Setting up your development environment

- TextEditor: Notepad(windows) - TextEdit(macos) - vim(linux)
- Advance TextEditor: VSCode - Atom - ...
- IDE: Visual studio - ...

---

### VSCode extensions

- Live server
- Auto close tag
- Auto rename tag
- Indent rainbow
- Material icon theme
- Prettier

---

## UI & UX

UI: User interface of application.
UX: User experience of user based on the application.

---

## UI sections

- Typography
- Color
- Container
- HyperLink
- Table
- List
- Figure
- Multimedia
- Form

---

## UX sections

- Experience strategy
- User research
- Information architecture
- Interaction design

---

## HTML analogy

- human-body skeleton
- skeleton of building

---

## Comment

- ``` <!-- comment --> ```

### Types

- single line
- multiline

---

## Sketch, wireframe, prototype apps

- figma
- adobe xd

---

## HTML tag types

- empty tag
``` e.g: <br /> - <hr /> ```
- pair tag
``` e.g: <p> plain text </p> ```

---

## Difference between plaintext and content

- plaintext
``` e.g: <p> plain text </p> ```
- content
``` e.g: <p> plain text <br /> </p> ```

---

## Paragraph tag

- ``` <p> paragraph tag </p> ```
- HTML category: Pair tag
- UI category: Typography
- Paragraph tag is suitable for plain text and content.

---

## Headings

- h1 - h2 - h3 - h4 - h5 - h6
- ``` <h1> heading 1 tag </h1> ... <h6> heading 6 tag </h6> ```
- HTML category: Pair tag
- UI category: Typography
- Heading tags is suitable for plain text and content.

---

## What is emmet?

high-speed markup language tag generator.

---

## emmet method

``` e.g.: ! !!! doc ```
``` e.g.: p*2 ```
``` e.g.: h${Heading $}*6 ```
``` e.g.: h${Heading $$}*6 ```
``` e.g.: p[title="paragraph"] ```
``` e.g.: (header.header#header>nav.nav>ul.nav__list>li.nav__item*6>a.nav__link)+main+footer ```
``` e.g.: header.header#header>nav.nav>ul.nav__list>li.nav__item*6>a.nav__link^main+footer ```
``` e.g.: form:post>(.group>label+input:text)+(.group>label+input:number) ```

---

## Formatting elements

- b - strong - i - em - del - ins - mark - sub - sup
- ``` <mark> highlighted tag </mark> ```
- HTML category: Pair tag
- UI category: Typography
- formatting tags is suitable for plain text and content.

---

## HTML tags behavior

- inline-level
- block-level

---

## Attributes

key/value paired data that defines on start tag of html tags and control the behavior of that tag.

- ``` <p title="paragraph">paragraph</p> ```
- ``` <p id="description">paragraph</p> ```
- ``` <h1 class="heading" id="heading">paragraph</h1> ```

- [language code](https://www.w3schools.com/tags/ref_language_codes.asp)
- [country code](https://www.w3schools.com/tags/ref_country_codes.asp)

---

## Anchor element

- a
- ``` <a href="address" target="_blank"> Link </a> ```
- HTML category: Pair tag
- UI category: HyperLink
- Link

---

## Quotation elements

- q - abbr - address - blockquote - cite - bdo
- ``` <q> quotation element </q> ```
- ``` <abbr> abbreviation </abbr> ```
- ``` <address> address </address> ```
- ``` <blockquote cite="url"> quote </blockquote> ```
- ``` <cite> artwork </cite> ```
- ``` <bdo dir="ltr"> bi-directional override </bdo> ```
- HTML category: Pair tag
- UI category: Typography

---

## Computer code

- code - kbd - samp - pre - var
- ``` <code> computer code </code> ```
- ``` <kbd> keyboard input </kbd> ```
- ``` <samp> sample output </samp> ```
- ``` <pre> preformatted text </pre> ```
- ``` <var> variable </var> ```
- HTML category: Pair tag
- UI category: Typography

---

## image

- img
- ``` <img src="address" alt="text" /> ```
- HTML category: Empty tag
- UI category: Figure
- Image

---

## image map

- ``` <img src="table.jpg" alt="workshop table" usemap="#workmap" /> ```

- ``` <map name="workmap"> ```
- ``` <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm" /> ```
- ``` <area shape="rect" coords="290,172,333,250" alt="Phone" href="phone.htm" /> ```
- ``` <area shape="circle" coords="337,300,44" alt="Coffee" href="coffee.htm" /> ```
- ``` </map> ```

- [image map generator](http://image-map.weebly.com/)

---

## picture

- ``` <picture> ```
- ``` <source media="(min-width:650px)" srcset="img_pink_flowers.jpg" /> ```
- ``` <source media="(min-width:465px)" srcset="img_white_flower.jpg" /> ```
- ``` <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;" /> ```
- ``` </picture> ```
- HTML category: Pair tag
- UI category: Figure
- Picture

---

## Meta tags

- ``` <meta charset="UTF-8" /> ```
- ``` <meta name="description" content="Free Web tutorials" /> ```
- ``` <meta name="keywords" content="HTML, CSS, JavaScript" /> ```
- ``` <meta name="author" content="Pouria Nayeb" /> ```
- ``` <meta http-equiv="x-ua-compatible" content="ie=edge" /> ```
- ``` <meta name="viewport" content="width=device-width, initial-scale=1.0" /> ```
- ``` <meta http-equiv="refresh" content="30" /> ```
- ``` <base href="https://www.w3schools.com/" target="_blank" /> ```
- ``` <link rel="shortcut icon" href="favicon.ico" type="image/x-icon" /> ```
- For SEO & Technical purposes.

- [meta tags](https://htmlcheatsheet.com/)
- [image splitter](https://pinetools.com/split-image)
- [convert png to ico](https://www.freeconvert.com/png-to-ico)

---

## Style & Script

``` <link rel="stylesheet" href="url" /> ```
``` <script src="url"></script> ```

---

## Browser JavaScript engines

- Safari v8
- IE/Edge Chakra
- FF Spider Monkey
- Apple Javascript Core Webkit

---

## Container elements

- div - span
- ``` <div> <h1> Heading 1 </h1> <p> Paragraph </p> </div> ```
- HTML category: Pair tag
- UI category: Container
- Container tags can be a container for all html tags.

---

## Semantic elements

- main - header - footer - section - article - aside - figure - figcaption - time - details - summary - dialog - ruby - rt - rp
- ``` <article> <h1> Heading 1 </h1> <p> Paragraph </p> </article> ```
- ``` <dialog open>This is an open dialog window</dialog> ```
- ``` <details> <summary>Epcot Center</summary> <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p> </details> ```
- ``` <ruby> 漢 <rt> ㄏㄢˋ </rt> </ruby> ```
- ``` <ruby> 漢 <rp>(</rp><rt>ㄏㄢˋ</rt><rp>)</rp> </ruby> ```
- HTML category: Pair tag
- UI category: Container
- Container tags can be a container for all html tags.

---

## Entities, Symbol and emojis

- [HTML entities](https://www.w3schools.com/html/html_entities.asp)
- [HTML symbol](https://www.w3schools.com/html/html_symbols.asp)
- [HTML emojis](https://www.w3schools.com/html/html_emojis.asp)

---

## table elements

- table - caption - tr - th - td - thead - tbody - tfoot
- ``` <table> <tr> <th> ID </th> <th> Name </th> </tr> <tr> <td> 1 </td> <td> Pouria </td> </tr>  </table> ```
- HTML category: Pair tag
- UI category: Table
- Table tag can be a container for all tabular data.

---

## List elements

- ul - ol - dl - li - dt - dd
- ``` <ul> <li>Mango</li> <li>Milk</li> </ul> ```
- HTML category: Pair tag
- UI category: List
- List tag can be a container for all list items.

---

## Iframe element

- iframe
- ``` <iframe href=""></iframe> ```
- HTML category: Pair tag
- UI category: Multimedia
- Iframe tag can be used to as tool to display a website inside another one.

---

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

---

## Graphic elements

- svg - canvas
- ``` <svg width="100" height="100"> <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" /> </svg> ```
- ``` <canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;"> Your browser does not support the HTML canvas tag. </canvas> ```

---

## Form elements

- form - input - label -  select - textarea - button - fieldset - legend - datalist - output - option - optgroup - datalist - output - progress - meter

---

## URL encoding/decoding

- [URL encoding/decoding](https://meyerweb.com/eric/tools/dencoder/)

---

## HTML validator

- [W3 HTML validator](https://validator.w3.org/)

---

## HTML vs XHTML

- [XHTML vs HTML](https://www.w3schools.com/html/html_xhtml.asp)

---

## HTML accessibility

- role attribute
- aria-* attribute

- [Aria attribute helper](https://www.w3.org/TR/html-aria/)

---

## HTML API

- GeoLocation
- Drag/Drop
- Web storage
- Web workers
- SSE
