---
layout: default
modal-id: 7
img: cloneDeploy/cloneDeploy.jpg
title: CloneDeploy
date: 2020-11-05
category: 
description: This is a problem we got from Hamish a lecture at polytech to clone windows7
---

Hamish has assigned a task to the ops group to get images from a windows 7 pc's for the ones they are giving away to varies people/groups/organizations

We originally got the document from Hamish that had instructions about how to deploy to the machines, but no documents on how to upload a new image.

The problem that we came across after updating the machines and trying to upload them was this :

![alt text]( img/cloneDeploy/Problem1.png ){: style="width: 450px"}

after we had updated windows7 we would try to upload the image to the server, the hard drive appears to have both GPT and MBR partitions.

so then we tried to install a new copy of windows, that didn't work, then tried to delete everything on the disk with dban 
![alt text]( img/cloneDeploy/dban.png ){: style="width: 750px"}

Which is an open source linux data wiping tool. 
Then we tried installing windows again and updating then trying to upload it with the machine with the same problem.

Then I emailed our client Hamish. Who then came down and had a wee discussion with me and then we changed some of the BIOS settings then installed a windows again then we tested if it could upload and image with success then when we tried to update the windows to patch it we ran in to this error.
![alt text]( img/cloneDeploy/Problem2.png ){: style="width: 450px"}



