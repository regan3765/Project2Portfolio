---
layout: default
modal-id: 3
date: 2020-07-15
img: helpsite/helpsite1.png
alt: image-alt
project-date: 
client:
category: Web Development
description: Getting the help site up and running
---

The first step with the help site was to find the repo in our gitlab, but our gitlab had been down for quite some time so we need to get the certs up on it before we could pull it down.
Once we had got the certs up we could then pull it down.

On further inspection the readme file only had web development team names and the site. NOT very useful. After going through some of the folders i found that it was deployed by hugo which is a very fast static website generator.

The code from the previous build was old and not up to date, and that gave me grief not knowing this at all the website would not display as it should/previously. There where also other ways that we could have got the content out, which would have been to download the files directly from the server and then could have changed what we need to and then put it on the server. I didn't do this as i thought it would still be a good website to use. 
The outdated site did not show all the information from each post this, this lead to some researching more about hugo and i found that there was more or new setting that need to be add and changed so that i could display it all. With also some changes in the layout file as well to display all the posts.

To get onto the production server

![alt text]( img/helpsite/helpsite1.png ){: style="width: 800px"}
website is running on my gitlab account
![alt text]( img/helpsite/helpsite2.png )
Changes to the settings to true
![alt text]( img/helpsite/helpsite3.png ){: style="width: 800px"}
running the website locally on the production server
![alt text]( img/helpsite/helpsitecert.png ){: style="width: 800px"}
this is there certificate that was on the original site hosted on gitlab.op.ac.nz as you can see it is issued to *.op-bit.nz and it needs to be *.pages.op-bit.nz
![alt text]( img/helpsite/helpsitecert1.png ){: style="width: 900px; height=950px; float: left;"} 
I was trying to find any information about the certificate of the website that was hosted through our gitlab