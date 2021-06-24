# Census Data in R

This workshp provides an introduciton to working with census data in R using the `tidycensus` package. This is the repository for D-Lab's Census Data in R. Laptop, Internet connection, and Zoom account required.

# Workshop Goals 
Since 1790, the US Census has been THE source of data about American people, providing valuable insights to social scientists and humanists. Mapping these data by census geographies adds more value by allowing researchers to explore spatial trends and outliers. This workshop will introduce three key packages for streamlining census data workflows in R: tigris, tidycensus and tmap.  Participants will learn how to download census tabular data for one or more geographic aggregation units or years, download the associated census geographic data and then join these data for analysis and mapping.

Prerequisites: D-Lab R Fundamentals Parts 1-4 or equivalent knowledge. Basic knowledge of census data and geospatial data will be very helpful.

# Installation Instructions

In preparation for the upcoming workshop you will need to install R, RStudio, the necessary libraries, and the workshop materials.

1. Install R

Download R by clicking the link here: https://cloud.r-project.org/

Select your operating system and then click "base" (Windows users) or "R-4.0.3.pkg". Double-click this file once it has finished downloading and follow the instructions to install it.

2. Install RStudio

Download RStudio by visiting this link: https://rstudio.com/products/rstudio/download/

Scroll down and click the Download button beneath "RStudio Desktop - Open Source License - Free". Double-click this file once it has finished downloading and follow the instructions to install it.

3. Install the necessary packages

Install the following packages by typing:
install.packages(c(‘sp’, ‘sf’, ‘rgdal’, ‘rgeos’, ‘raster’, ‘ggplot2’, ‘tmap’, ‘tigris’, ‘tidycensus’))
Then check to ensure that you’re able to load them by typing
library(sp)
library(sf)
etc.

sp, sf, rgdal, rgeos, raster, ggplot2, and tmap, tigris and tidycensus. 

4. Download the workshop materials

Download the workshop materials by visiting the GitHub repository: https://github.com/dlab-berkeley/Census-Data-in-R

To download the repository, click the green button in the top right hand corner that says "Code" and then select "Download ZIP". You can then unzip the contents of the downloaded folder somewhere accessible on your local computer (we recommend your Desktop).

We will take a few minutes at the start of the workshop to make sure everyone has R and RStudio installed and the workshop materials downloaded. Please feel free to email dlab-frontdesk@berkeley.edu or visit our help desk at https://dlab.berkeley.edu/frontdesk if you have any questions.

If you are a Git user, simply clone this repository by opening a terminal and typing: “git clone https://github.com/dlab-berkeley/Census-Data-in-R.git”.

# Is R or RStudio not working on your laptop?
Attend the workshop anyway, we can provide you with a cloud-based solution (DataHub or Binder) until you figure out the problems with your local installation. 

If you have a Berkeley CalNet ID, you can run these lessons on UC Berkeley's DataHub by clicking this [link](https://datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FAverysaurus%2FCensus-Data-in-R&urlpath=rstudio%2F&branch=master). By using this link, you can save your work and come back to it at any time. When you want to return to your saved work, just go straight to DataHub (https://datahub.berkeley.edu), sign in, and you click on the Census-Data-in-R  folder.
If you don't have a Berkeley CalNet ID, you can still run these lessons in the cloud, by clicking this [Binder button](https://mybinder.org/v2/gh/Averysaurus/Census-Data-in-R/HEAD?urlpath=rstudio). By using this button, you cannot save your work unfortunately. 

**NOTE: D-Lab workshops normally start 10 minutes after the scheduled start time (“Berkeley Time”). We recommend you log on at the start time to join the waiting room where hosts will message you further information.**


# Run the code!
* Requesting a Census API key

The tidycensus package, and any R package that accesses the Census APIs, requires you to first get a Census API key
Get one now if you don’t have one yet here: (just takes a minute): https://api.census.gov/data/key_signup.html
**COME UP WITH SOMETHING**

# How to get help?
* You can download the repo and work through the tutorial by following along with the [slides](https://dlab-berkeley.github.io/Census-Data-in-R/Rcensus_data_maps-slides.html#1)
**FIND RESOURCES**


# Resources
**FIND RESOURCES**

# About the UC Berkeley D-Lab
D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops such as R Fundamentals, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](http://dlab.berkeley.edu/) to learn more about us. View our [calendar](http://dlab.berkeley.edu/calendar-node-field-date) for upcoming events, and also learn about how to utilize our [consulting](http://dlab.berkeley.edu/consulting) and [data](http://dlab.berkeley.edu/data-resources) services. 

IOKN2K! is an acronym and it stands for It’s OK Not To Know!  And like every other meme, it means more than its acronym. IOKN2K! means is that D-Lab is a place to feel comfortable asking questions; D-Lab is a place to learn the skills that you don’t have yet. Bring your wonder to D-Lab. IOKN2K!

# Other D-Lab R workshops
 
### Basic Competency
* [Fast-R]()
* [R Data Wrangling]()
* [R Graphics with ggplot2]()
* [R Functional Programming]()
* [Project Management in R]()
* [Geospatial Fundamentals in R with sf]()
* [Census Data in R]()

### Intermediate/Advanced Competency
* [Advanced Data Wrangling in R]()
* [Introduction to Machine Learning in R]()
* [Unsupervised Learning in R]()
* [R Machine Learning with tidymodels]()
* [Introduction to Deep Learning in R]()
* [Fairness and Bias in Machine Learning]()
* [R Package Development]()

## Contributors:  


---
<div style="display:inline-block;vertical-align:middle;">
<a href="https://dlab.berkeley.edu/" target="_blank">
<img src ="https://dlab.berkeley.edu/sites/default/files/logo.png" width="60" align="left" border=0 style="border:0; text-decoration:none; outline:none">
</a>
</div>
<div style="display:inline-block;vertical-align:middle;align:left">
    <div style="font-size:larger">D-Lab @ University of California - Berkeley
    </br>
    <a href="https://dlab.berkeley.edu" target="_blank">https://dlab.berkeley.edu</a>
    </br>
    &nbsp;
    </div>
</div>
