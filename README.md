# MIST 353 Assignment 2: Prototype Development and Research for Web Application

## Complete a Competitive Analysis
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
- [Weather Underground / Wunderground](https://www.wunderground.com) 
	- I came across this website while searching google for "event planning weather web apps" and it also looks like it accomplishes something similar to our TravelSite web app from in class. 
	  The site immediately displayed the weather for my current location, shows the weather data for "popular cities," and provided a search bar to change locations. Right off the bat I noticed 
	  that the elements on the top-taskbar of the site all illuminate when hovering over them with the cursor which I think is a nice touch on the user-end. The site includes a "Map & Radar" section 
	  which I like a lot and will possibly implement through an API for interactive map. The source code for this website includes no comments and way more (`<script>`) and (`<noscript>`) tags that I 
	  would have ever guessed. After inspection I am still unsure what many of the scripts do besides the few that are responsible for changing text when hovering over it

## Complete Github Repository Research
- [U-Weather](https://github.com/uchechukwuekemezie/u-weather-app?trk=article-ssr-frontend-pulse_little-text-block)
	- This repository is for a weather app that allows for users to check the current weather in a specific location/city they can search for. This repo has a nicely organized README and includes a description of the web app and lists the current features of the app. It even includes details near the bottom on how to contribute to the project if anyone would like which I found pretty interesting. 
- [Weathque](https://github.com/tortamque/Weathque)
	- This repository explains that it's a dynamic weather application that provides users with real-time weather data as well as a 5-day forecast. This repository has the most detailed / clean-looking README of any of the READMEs I have looked at, it provides photos that depict the architecture for the API calls and the Storage calls which I haven't seen before. This README even shows a handful of screenshots of the web app in use on a mobile device with different background themes enabled. I am definitely going to be returning to this README after more ammendments are made to this project.  

## Develop a Prototype
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
	- Through [Bootswatch](https://bootswatch.com/solar/), I was able to find a theme that I liked and applied it to my project. Within the theme I also implemented a button that shows a shadow when you hover over it.
- Custom CSS - Write CSS for HTML classes in css/site.css, with at least 3 properties, 2 of which that have not been taught in class (as of 1/18). This should
accomplish something that CANNOT be done using Bootstrap classes.
	- Within my site.css I wrote four custom classes, while I think only three accomplish tasks that cannot be done through Bootstrap. While the first two are basic, I played with the css animation for a little while with the help of [w3schools](https://www.w3schools.com/css/css3_animations.asp). 
		1. TextAlign
		- Simply centers text, used in my alert at top of page
		2. TextFont
		- Simply changes font to "fantasy", used in the title under the alert
		3. Rotate 
		- Makes an element rotate on its x-axis 360 degrees
		4. Title
		- Allows for the animation to be applied to an element as well as changes to be made to the duration of the animation.  
- JavaScript - Implement a small custom JavaScript.
	- I found a simple in-line js script that displays the current date and time when clicked on through [w3schools](https://www.w3schools.com/html/html_scripts.asp). 

## Project Summary  
- Project Overview 
	-  This event planning weather web app is designed to provide useful weather data to anyone who is attempting to plan any event that may be influenced by the weather; (Food trucks, Weddings, Concerts, etc.). Also will allow for the viewing of multiple location's weather side-by-side for those who are coordinating multiple events occurring at the same time. This project is still in a developmental phase and does not yet include all planned functionality.
- Page Descriptions
	- Conceptually, the index page will later include a search bar or form that will read provided locations from users and then display the corresponding weather data. I would like to have it so that users can search for a location and then save / pin it somewhere so that users could see the weather data for multiple different locations without having to switch pages. 
	- Technically, at this point in time this project has extremely limited functionality and almost zero real-world application besides accessing the current date and time which could be done a plethora of easier ways.
- Research Summary 
	- After finding three relevant websites and two relevant github repositories, I honestly did not find them super useful for finding new features / functionality compared to the video you had uploaded. While it was helpful to see examples of similar web apps as well as README's, I think it was most useful for identifying details that I would want to omit from my project. For example the sites all used dated-looking layouts and formatting which makes me want to put more time into the app to make sure it looks professional to the end-user. 
- Future Enhancements
	- While there are many future enhancements in mind, the most significant enhancement will be the implementation of the [NOAA Climate Normals](https://www.ncei.noaa.gov/products/land-based-station/us-climate-normals) API so that the web app can actually return weather data to users based on their input. 
	- For the front-end however, there needs to be some sort of form added to the Index page with a field that allows for the user to search for a location to view weather data from. 
- Reflection on Resources
	- When first looking over the rubric for this assignment I was very worried going into the project with my little bit of HTML knowledge, however it went much smoother than I was anticipating. The video you had posted was easily the most helpful of any resource though, it even discussed how and where to implement certain items that would satisfy the requirements of the project.  
	- W3Schools had the answer to almost every question I had, and if it didn't, I had just not looked hard enough as there's so much useful information packed into that one website. One of the only hiccups I ran into was with implementing a little bit of javascript, which is when I asked Chat GPT for some assistance with creating an animation. 
## References 
To construct the javascript element of this project I used [Chat GPT 3.5](https://chat.openai.com) with the following prompt:

> "What is a basic animation that I could write in my site.css that will effect some text in my index.cshtml page? Perhaps for my title text?"

The response I got was similar to something we would see on w3schools and gave an example of a fadeIn animation, but I was looking for a little bit more detail on how exactly the code worked and what other animations were possible, so I followed up with the following prompt:

> "What causes this animation to start? Will it simply play once when the website is first launched or is this repeatable? Also are there any other basic animations I could use besides fadeIn?"

This output was much more helpful but required a few changes that had to be done manually to get the result I was looking for. 

I used the [Quickstart for writing on Github](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github) for Markdown ideas.

All other references are linked throughout this document.