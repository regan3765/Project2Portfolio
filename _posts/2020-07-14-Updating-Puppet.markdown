---
layout: default
modal-id: 2
date: 2020-07-14
img: puppet/puppet.png
alt: image-alt
project-date: 
client: 
category: Web Development
description: Fixing Puppet 
---

I was trying to stop the alerts that where coming from the Nagios server as i thing there were a lot coming in but can't remember the frequency but they became annoying.


Updating the puppet module so that there are no errors show when the puppet ask for updates from the puppet master.

I can't remember why i was trying to pull the puppet master exactly but


![alt text]( img/puppet/PuppetProblem3.png ){: style="width: 800px"}
This is the error i was getting which suggested that it was expecting a '}'

![alt text]( img/puppet/puppetProblem2.png ){: style="width: 800px"}
Here is the line number from the puppet master and there is a '}' missing so i edited it in vim

<!-- ![alt text]( img/puppet/puppetProblem4.png ){: style="width: 800px"} -->
<!-- ![alt text]( img/puppet/puppetProblem5.png ){: style="width: 800px"} -->
![alt text]( img/puppet/puppetProblem6.png ){: style="width: 800px"}
Here is the puppet pulling from the puppet master and it completed without any errors.
