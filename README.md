# 11056_project1

## Diving into the Content
When we were first given the site to redesign, I began by working my way through every page on the site and the content that it contained. After I felt like I had a solid understanding of all the sections that the site contains I began to copy all the text-based content into a word document where I could shuffle it around and combine sections that have similar content. This allowed me to reduce the quantity of pages and start looking at how I could simplify the IA.

## Designing the Information Architecture
It is important to have a clear and easy to navigate IA for any website, the original IA for CAB was a bit convoluted, and some of the labels were a bit unclear. 

The original navigation looked like this:
![Old Navigation](assets/images/CAB-Nav-Original.png)

The new navigation looks like this:
![Old Navigation](assets/images/CAB-Nav-New.png)

The new IA was meant to keep the navigation as simple as possible for the user.

## Creating basic pages, over and over again
Once I had the IA in mind, I began to create the HTML pages in line with the design. I started out with the home page including finishing the CSS for the header and footer in desktop view. This meant when I created all the other html files I was able to just copy paste the exsisting header and footer code and I knew it would work. I then went through and put in all the content and images for each page.

## I wish my CSS was organised better
Once I had done all the html content input, I continued with CSS to start creating the desktop versions of each page. I quickly discovered that to use grid I would have to go back into my html pages and modify them slightly, so that certain parts of the page would be children in the grid. one the grids were set up and functioning for desktop across the site, I could move onto creating media queries for a responsive site.
I got better at wrapping my head around media queries with each new page. I had three main page widths with a few extra ones for more complicated pages like 'festivals' which had a map display with a scrolling list down the side. Most of my media queries simply rearranged the grid, I really enjoyed the functionality of grid, it made my life very easy lots of times. I realised as I went along that I should have made the site a bit more 'templatey', as I had to modify every page on the site separately for every media query. 

## Using flexible images verses flexible columns
One thing I learnt a lot about as I was doing media queries, is the simply scaling down the grid works great for text but not very well for images. It is very easy to distorts images unless you use fixed values that change with each breakpoint. I found it very annoying to deal with the disported images, and I wish I realised sooner that I should be using fixed values.

## News Article and Artist Pages are not built quite up to standard
Upon reflection, I don't think the article or artist placeholder pages could handle pasting real content into them. If I were to go back and build each page in, I think that some of the longer headings or oddly sized images would break the page as it currently is.

## Festival page is a bit static
The festival page is meant to have a scrollable map, that will show you where the art piece you have selected on the right is located on the left. While I was able to have a list of artist on the right that you can scroll through, I was not able to create proper map functionality for this assignment.

## This project has taught me so much about how I WON'T set up my HTML files next time...
I found out that sectioning things out properly in HTML files makes life so much easier when doing CSS, you need a pretty clear idea of how you will do your CSS while you are doing your HTML. Especially when building a responsive site, you must think about all the different sizes the site will be in when sectioning out your HTML.

## Site is a bit ugly but happy with functionality
When designing the site, I had plans for the structure, but I didn't put much time into the design of the site. So, while I am incredibly happy with the functionality of the site, I am disappointed with the aesthetics of some of the pages, and I wish I put more time into the design early on.

