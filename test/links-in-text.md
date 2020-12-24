---
title: "Links in Text (Test)"
date: 2020-10-09T21:19:59+02:00
slug: "links-in-text"
author: jh
weight: 10
draft: true
---
*This posting is intended for testing purposes only. If you have found it in a public website with regular content, the owner of the site has probably forgotten to delete it.*

An [internal link] to another page on this website. 

An [external link] to a page on a different website. 

A footnote[^1] links to the foot of the page. The note there contains a backlink at the end of the remarks.

#### Special cases

An *[internal link]*  with emphasis to another page on this website. 

An **[external link]** with strong emphasis to a page on a different website. 

[internal link]: {{< relref "list-in-text" >}} "List in Text"
[external link]: http://joerghuber.net "Jörg Huber"


[^1]: The content of the footnote can stretch over more than one paragraph, if they are separated with two backslashes.\
\
This is the paragraph with the continuation of the footnote and the final backlink at the end. 
