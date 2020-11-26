# What's the Weather?

![Title](assets/images/Fig1_temp_latitude.png)

## Table of contents
* [Assignment](#assignment)
* [Data Sources](#data_sources)
* [Website Components](#components)
* [Website Design](#design)
* [Lesson Learned](#lessons)

## Assignment
Design a website with a dashboard to share data analysis. 
The final published product can be found here: https://klacerda08.github.io/Web-Design-Challenge/ 

## Data Sources
Data included the weather data obtained using through OpenWeatherMap API earlier this year (October 2020).  

To design the website, the following tools were used: 
- html coding with custom cascading style sheet (.css)
- Bootstrap css style sheet:  https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css

## Website Components

The website consisted of a dashboard with the following components: 
- Seven (7) pages
- A navigation bar with a dropdown menu, functional from each page
- Each page and the navigation bar are responsive to make the pages readable on smaller screen sizes.  

## Website Design
The website design included the following major tasks:
- The modification of a standard Bootstrap navigation bar for a customized look. 
- The use of containers and Bootstrap cards to house images and text in an organized fashion.
- The use of jupyter notebook and pandas to extract data from a csv file and export it to html.
- The use of Bootstrap styling and functionality to format the html table in a responsive way.
- Formatting with html and css.  

## Lessons Learned
On first pass, it was very hard to understand the Bootstrap classes without seeing them in a style sheet
themselves. However, the Bootstrap style sheet is very difficult to navigate.  Instead, I tried to create 
my own navigation bar with a combination of self-made classes and the Bootstrap navbar class, but it did 
not contain all the requested components (it was missing the hamburger collapsible feature upon screen 
reduction). I also encountered an issue with the navigation bar being very wide and, although I tried 
fixing several attributes (padding, border, margins, etc.), it would not reduce in size. I abandoned 
this navigation bar entirely and started from scratch, from the Bootstrap template. Having spent so much 
time troubleshooting, it was easier to understand the classes the second time around. The final product 
contains this revised navbar.  

Additionally, in the first navbar, I encountered an issue where the dropdown menu worked on the home
page, but did not work on the other pages. I realized that I had not copied the javascript code from the 
home page to the other pages.  

Final thoughts: I always knew a lot went into designing webpages, and I have a new appreciation for 
professionals who work with html and css to create websites that are both visually appealing and functional 
for the user.  

