# Introduction

## The complete web

*

## Course outline

* Intro to web fundations
* HTML 5
* CSS - CSS advance
* Boostrap and template
* CSS grid
* Careers 
* Javascript
* development environment
* git 
* profile NPM/NPM Scripts
* react.js
* node.js
* databases

in video notes 

#html-and-css
#github
#javascript
#react
#node-and-deno
#databases

## Understanding your video player (notes, video, etc)

Chrome extension recommended 

Sidebar Toggle 🚄
Darkmode 🌒


## Set your learning streak goal

set 100 day coding

## Browsing the web

For performance and optimization we need to learn about the web

laptop > web browser > google > ISP (internet service) > DNS (phonebook of list of URL)

Return: 

DNS > ISP > Google servers (computer or computer farm) text file (Hmtl, css and JS) that is sent  > web browser on computer. 

## Breaking Google 

Developer tools

We can inspect a google web page by using inspect and element to modify google page. 

The brower is a piece of software that can recieve files from servers and translate it (make it pretty) in the world. 

## The internet backbone

computer is a network of computers

## Traceroute 
command prompt
Traceroute can map the locations that the data of a website was pass thru. 


A traceroute provides a map of how data on the internet travels from its source to its destination.

What is traceroute used for? 

* figuring out the routing hops data has to go thru

* trace response delays, trace location, points of failure, full visual representation of each hop.

        How To Run a Traceroute,

        MAC

        Open up an instance of Terminal.
        Type in the phrase “traceroute [hostname]” and press enter.

        Windows

        Go to the Start menu.
        Select Run.
        Type in “cmd” and then hit “OK.” This initiates a command prompt.
        Type in “tracert [hostname]” and press enter.
        The term “hostname” or host is the website you are interested in or the IP address of a server, router, or device. The traceroute reports on this destination point. After the traceroute is done, it terminates on its own.

Syntax in command prompt: 
> tracert -4 google.com


Summary: To located how many locations or computer a file has to hop before it gets to our browser we use command prompt > traceroute or tracert to request the list of destinations. The map can help with browser technical 

## Developer Fundamental

Website Performance: 
> location of server, how many trips and size of files.

location of server if the server is close to you, the hop  makes it faster to load

how many trips - the less trip, the faster it loads

size of files - for ex. 100 megabyes slower vs kilobytes. 

## What does a developer do? 

Frontend developer - website visual
Backend developer - backend 
> frontend + backend = full stack developer

## WWW vs Internet

The history of the world wide web (WWWW). 
[Tim Berners-Lee](/img/tim.png)

Tim Berners-Lee first web developer, created the browser and server and the first website in 1969 basically as a military project where it connects some university thru the 70s to the 80s to share academic documents faster pace. There was already computer. 

A decentralized program. 

## HTML, CSS, JS

website that links

HTML === text === Element tab
CSS === visual === style tab
JS === interactive === console

## Developer fundamental: II

multiple web broswers === broswer wars

chrome vs. e vs firefox vs sarif
phone screen size vs computer screen size
web are created to share document amongst each other

standards: 

website fit browser for code. 
test each browser. 


## Developer do? 

Frontend - user see (html, css, JS + react)
Backend - Server technology uses (node.js and express.js) and database (postgreSQL, MongoDB)


## Developer History 

Full stack Dev. in the old days

Front-end developer (html, css, js + jquery)

Back end developer aka lamp stack- Apache Server (php), Database (mySQl)

## Build your first website


text editor allow us to write codes

use sublime

## Developer fundamentals: III

developer === problem solving

What is Doctype? 

doctype tell the browser that it is html 5 it has more syntax and tags. 

## how to ask questions

1. (https://rubberduckdebugging.com/)
2. (https://stackoverflow.com)
3. (https://discord.com)

HTMl tags

heading tags <h1>
paragraph tags <p>
lorem tab 
lorem 50 tab - creates 50 words.

tags vs elements

tag is just <h1>
element includes opening and closing  <h1></h1>

strong and em due to semantic. DO not use Italic or bold.

order list > number > we can nest it
unorder list > bullet

self closing html 
<br> break
<h> horizontal line
<img> image tag

attribute = special attrible has value 

> src="img/tim.png" 

alt alternative text for screen reading

Anchor Tag

link to other docs.

attribute is href="link"

<span> <div> are deprecated 
inline 

## HTML vs HTML 5

HTML start in 1991 does not have establish tags 

HTML 5 has more feature, does not affect old website support backward compatible by introducing semantic elements (making website more descriptive). 

## copy a website

css propert css trick website, unsplash.com

-border, background-image

## CSS rules

class attribute group elements
id attribute only use once for an element
star means selecting all elements
element <> its inside a open/close tag
element, element
element > element h2 > p I want to select all parent of p of h2
element + element I want two element next to each other immediate neighbor
Pseudo class vs. pseudo element
:hover
:last-child
:first child
!important (not recommend) override any css rule

> specificity

(https://specificity.keegan.st/)

 # Need to read mdn css

https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Cascade_and_inheritance


## css game

https://css-diner.netlify.app/


text and font

lorem tab

text 
line-height
font-wieght
font-size
font-family

## image

float: right always use he clear on footer 
> need to learn float and clear

image tage need source, width and height


box model:  content, padding (space bt content),border, margin (outside), 

## absolute units and relative units

Absolute units are units that are static or fixed and does not change based on any element or device
> Px
Relative units great for responsive website due to "scale up or down according to device" 
>em, rem, %, vw, vh

https://elementor.com/help/whats-the-difference-between-px-em-rem-vw-and-vh/

## Critical Render Path

Optimizing the critical render path improves render performance, ensure user interactions.



Looking under the hood. 
>web page/broswer request HTML file > parsing dom tree > constructs css object model, 
browser request html file and request from server 
render means that its display 

you can not render a website until css file is render. 

you want to minify the css file. It makes a css file samer

https://www.cleancss.com/css-minify/

When a web page is loaded, the browser reads the HTML code and builds a structure called the Document Object Model (DOM). Think of it like a tree, with each part of the HTML code being a branch or leaf on that tree.

The process of building this tree is incremental, meaning it happens step by step. First, the HTML response from the server is turned into tokens, which are like building blocks of the DOM. These tokens represent different parts of the HTML code, like tags and content.

These tokens are then used to create nodes, which are like containers that hold information about each part of the HTML code, such as the tag type and attributes. Each node represents an element in the HTML code.

Nodes are connected together based on the hierarchy of the HTML code. For example, if one element is inside another element in the HTML code, the corresponding nodes in the DOM tree are also nested inside each other.

## Flexbox






