# Web Scraping with R rough notes only Didi can understand

Today only look at Élements in the selector.

## Intro
Web scraping - in the past people just view page source code of the website  
<ol type="1"style="list-style-position:inside;">
1. Pick a page
  
2. Load a page

3. Look at page

4. Determine where the info was

5. Select it

6. Copy

7. New file

8. Paste

9. Save  

## Tools
Download Chrome CSS Gadget Selector

We are coding between no.4 and no.5 in which where we need to CODE.  

CSS - is a different language to   
CSS Selectors: Can practice at flukeout.github.io  

## Example 1

houstontx.gov/departments.html
Right click and 'Inspect'.  
Open Selector Gadget, click the ones you want and unselect the ones you do not want  
.table150 a:nth-child(3) , .table150 a:nth-child(1)  
.table150 a:first-of-type  
<a> </a> elements with opening and closing tag  

### RStudio  
Now we need to code for it to 'load the page'and then code to determine the information and select it.

## Example 2
espn.com/nba/attendance
Class selector .tablehead for 2017  
Environment tab > Global Environment > Data > nba_attendance > click the datasheet button  

But I want to get all years?  
Write sequence of numbers, OR use selector gadget?  

p/s: Selenium - a web simulator for R  

## Example 3 (future)
https://www.governmentjobs.com/careers/houston
When you load the website, you notice that the jobs only come out at a slightly later time - this may present a problem. as you 'inspect' you realize that it is a separate java. One thing to note is that the Inspect button is only able to view it at it is aat that time. View Source and you çtrl+f and cannot find what the jobs are meaning it's run on JAVASCRIPT.  
Can click on Console, Sources, Network, Memory etc but it's a whole new website understanding workshop.  

