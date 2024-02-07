# MIST 353 Assignment 2: Prototype Development and Research for Web Application

## 1. Complete a Competitive Analysis
- [WeatherPlanner.com](https://weatherplanner.com/weather/index.php)
	- This first website I found quite quickly after searching google for an "event planning weather app" and immediately 
	  realized how similar this site looks to the travel site that we've been working on in class. After exploring their
	  website for a few minutes I noticed that they have a few more pages than we added in class, for example they have 
	  an "About" tab, as well as a "Plannability Factor" tab that lists reasons why their weather planning app is useful. 
	  I thought these two tabs provided helpful info and I'd like to include something similar in my web app in the future.
	  looking at the site's source code revealed that almost all of the pages are written in php and use css for styling 
	  but I have been able to actually *view* the code. 
- [U-Weather](https://delicate-zabaione-7701bf.netlify.app/?trk=article-ssr-frontend-pulse_little-text-block)
	- This website I found through a [LinkedIn post](https://www.linkedin.com/pulse/u-weather-web-app-uchechukwu-ekemezie) 
	  that included both the website's url as well as the github repository. The site at first glance looks fairly basic, 
	  similarly to how our site from in class, and my site, looks, but it does provide some good information. After inspecting
	  the source code I was surprised to see that there is a lot of information in the <head> unlike what I've seen in class 
	  so far. There is also a <script> tag within the index that appears to use an api to acquire the weather information from 
	  any location that's entered into the search bar. I was looking into implementing an api that would find the user's current 
	  location, similar to how we did it with the TravelSite from in class, but soon realized I was in over my head.  
- website 3 / Identify 
	- 
^^ note any ideas may want to add / include ^^


## 2. Complete Github Repository Research
- [U-Weather](https://github.com/uchechukwuekemezie/u-weather-app?trk=article-ssr-frontend-pulse_little-text-block)
	- This repository has a somewhat nicely organized README and includes a description of the web app and lists the current features of the app.
	  
- GITHUB 2
	- summarize each repository and your takeaways from the READMEs

## 3. Develop a Prototype
- Webpage Creation - Build 2 simple webpages ( .cshtml files) for your application.
	- I created two basic webpages the same way that we created our index and searchResults pages in class.
- Navigation - Implement navigation from one page to the other using an anchor
element (`<a>`) with the approriate hypertext reference (`<href>`) attribute.
	- Within the index page, I added a button that links to the searchResults page that I found while looking through [w3schools](https://www.w3schools.com/tags/tag_button.asp). 
- HTML Structure - Use proper headings including at least 1 (`<h1>`) and 3 (`<h2>`) tags
across the pages.
	- Within my index page I used an (`<h1>`) and an (`<h2>`), while on my searchResults page I only used two (`<h2>`) tags. 
- Tables - Include a table (`<table>`) element with at least 2 rows.
	- While I was trying to get around using a table by sizing down a few (`<div>`) and orienting them to sit side by side, I opted to add the table to my searchResults page for now. 
- Unique HTML Elements - Incorporate an HTML element not covered in class (as of 1/18).
	- I tried my best to kinda experiment and play around with different items and ended up adding a few HTML elements we did not discuss in class yet. 
		- Hamburger icon + different home page name displayed on the top of the browser when opened. 
		- Alert bar across the top of the index page
		- Dynamically sizing image on my searchResults page
- Bootstrap Integration - Use Bootstrap, including a custom theme from Bootswatch
and a Bootstrap class not discussed in class (as of 1/18).
	- Through [Bootswatch](https://bootswatch.com/solar/) I was able to find a theme that I liked and applied it to my project. Within the theme I also implemented a button that shows a shadow when you hover over it.
- Custom CSS - Write CSS for HTML classes in css/site.css, with at least 3
properties, 2 of which that have not been taught in class (as of 1/18). This should
accomplish something that CANNOT be done using Bootstrap classes.
- Within my site.css I wrote four custom classes, while I think only three accomplish tasks that cannot be done through Bootstrap. While the first two are basic, I played with the css animation for a little while with the help of [w3schools](https://www.w3schools.com/css/css3_animations.asp). 
	1. textAlign
		- Simply centers text, used in my alert at top of page
	2. textFont
		- Simply changes font to "fantasy", used in the title under the alert
	3. rotate 
		- Makes an element rotate on its x-axis 360 degrees
	4. title
		- Allows for the animation to be applied to an element as well as changes to be made to the duration of the animation.  
- JavaScript - Implement a small custom JavaScript.
	- I found a simple in-line js script that displays the current date and time when clicked on through [w3schools](https://www.w3schools.com/html/html_scripts.asp). 

## 4. Document with a README**
I used the [Quickstart for writing on Github](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github) for Markdown ideas.



## References 
