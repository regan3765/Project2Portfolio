---
layout: default
modal-id: 8
date: 2020-11-05 
title: DB3 Docker Problem
img: DB3Problem/sql-server.png
alt: image-alt
description: DB3 docker problem with sql agent being disabled
---

So today i was in DB3 when Krissi our lecture told all of us of a problem that the class had as it is part of our 10% lab. 

The problem was that all of our containers(1 for each student in the class) and that the sql agent in the container which is a Microsoft sql server and to complete the task we needed to be able to create and schedule schedule a job like backing up a database but by default the sql agent is disabled by default and the fix was to run this command 


EXEC sp_configure 'show advanced options', 1
GO
RECONFIGURE
GO
EXEC sp_configure 'Agent XPs'

GO
EXEC SP_CONFIGURE 'Agent XPs',1
GO
RECONFIGURE
GO

and then Refresh the connection or the sql agent and then you could create and schedule a job

Krissi said that she had tried this before and it didn't work but I'm not sure if she refreshed it like i did.


![alt text]( img/DB3Problem/codeMessage.png ){: style="width:700px"}
so I showed her what id done sent her the code and she tried it and then refreshed and it worked


https://zarez.net/?p=2720