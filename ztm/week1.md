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

Week 2
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

Best practice:
        1. Minimize and optimize CSS
        2. Optimize JS Use async and defer attributes for non-critical scripts, and minify and concatenate JavaScript files.
        3. Inline critical CSS 
        4. Prioritiz Visible Content - load critical content for immed. visual to user
        5. lazy Load non-critical resource: defer not needed 
        6 Optimized Images- use lazy loading and appropriately size
        7. reduce server response time- using caching and reducing database 
        8. CDNs use for reducing latency and improving load timing. 
        9. Minimize redirects
        10.Use Browser Caching

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

https://flexboxfroggy.com/

## https://darekkay.com/flexbox-cheatsheet/

## css 3

css browser support reference. 

transition: all 1s; 

 this means that I want to transition all element for 1 sec is like hover 
if an element is not impliment into the browser you will have to add. need to add prefix so that the css will work on the browser. 
        -moz-box-shadow: (mozilla broswer )
        -ms-box-shadow (internet explorer)
        -webkit-box-shadow (safari and chrome)
        -o-box-shadow (opera broswer)
        

https://shouldiprefix.com/

> css transitions and transforms == simple and valuable not distracting from interaction for user

div {
  transition: [property] [duration] [timing-function] [delay];
}

linear, ease, ease-in, ease-out, and ease-in-out.


# transition and transforms need to master it

https://thoughtbot.com/blog/transitions-and-transforms


## Responsive UI

responsive means that websit is responsive to different screen size. It is priority when building websit. 

## Evolving technology

technology is moving fast
always keep up with latest trend
backward compatibility
developer maintain or improve 
xz securly. CDN will place servers at the exchange points of different networks. 

IXPs stands for internet exchange points

TLS stands for Transport Layer Security == secuirty protocol designed to facilitate privacy and data security for communications over the internet. 
TLS encryption helps protect web app from data breaches and other attacks.

SSL - secure sockets layer 

> TLS and SSL are sometimes used interchaneably

> TLS encrypt communication such as email, messaging and voic over ip 

>TLS === encrption, authentication, integrity

## startup landing page

meta tags for responsive meta tag that allows the browser to know that it should work on mobile device or touching moving screen, 

Responsive meta tag: 

>meta charset="utf-g"
>meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit="no">

to make an image cover the website code is 

        html {
                background: url(img.png) no-repeat center center fixed;
                background-size: cover;
        }


what is mailchimp? 

a service company its a embedded signup form to your website

link to read https://mailchimp.com/en/help/add-a-signup-form-to-your-website/


publish website for free on github by using 
name.github.io


What is animate.css? 

https://animate.style/


        <head>
        <link
        rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"
        />
        </head>

## Developer fundamentals: IV

Try to use components that is already created to make website at a faster pace. instead of creating your own. 

Two website that is suggested are 
animate.style and creative tim (https://creative-tim.com)

Free resource for template: 

        My new favourite: https://html5up.net/
        Creative Tim Templates
        Portfolio Templates
        Free CSS Templates
        TemplateMo
        Bootstrap Templates 0
        Bootstrap Templates 1
        Bootstrap Templates 2
        Animate.css

## section Overview

layout foundation for responsive webpage

css grid and flexbox and bootstrap


grid and flexbox compliment each other for layout

Best practice

> Flex box > one dimensional > columns or row (layout main, footer and header)
> Grid > two dimensional layout

most of the web is moving to to css grid, flex box is most supported by browser due to its being older. 


grid-gap is now called gap



what does 1fr mean 1 fraction i get one item
1fr 1fr mean that I want two item one fraction

grid best practice 

> 1fr or fraction

syntax: 

        display: grid;
        display: inline-grid;

        grid-template-columns
        grid-template-rows

        tracks






