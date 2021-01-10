---
title: shucking disks
author: '@sagrudd'
date: '2021-01-10'
slug: []
categories:
  - hardware
tags:
  - hardware
image: 'images/post_content/shucking_disks.jpg'
showonlyimage: false
type: featured
---

We are a week further into this year since the last post - so much for the
ambitions of a post a day! A load of things have happened, a week back at work
with the accompanying excitement, progress and planning for the next rounds of
awesomeness. We have committed to becoming the owners of a puppy (we'll have a
post on that once she has taken up residence ...).

For today's words we will have a quick look at `shucking disks`. Using 
[Amazon.de](https://amazon.de) as a guide, hard-disks can be purchased simply.
I have some projects to introduce in the coming weeks where we will require a
reasonable amount of not extraordinarily fast storage. My existing 
[freenas](https://freenas.org) and [unRAID](https://unraid.net) servers don't
have a lot of space. My aged Synology RS-816 is looking after backup for my
various laptops - it's time to upgrade its disks!

I would like to go with 6Tb disks - it's a compromise between space and price -
6Tb disks are about 100 EUR each so relatively affordable. 

The curious thing is that an external disk in an enclosure with power-supply and
USB cable costs **100 EUR**. A hard disk without the consumer packaging, plastic
enclosure and power supply costs between 130 and 150 EUR and a NAS approved disk
(again without any extra consumer waste) costs 175 EUR. Normally I'd just go 
with NAS approved disks - but I'm looking to live dangerously and hope to 
acquire a modest following of bioinformaticians who can shudder at these
foolish thoughts. Can we do bioinformatics on a budget?

So, as demonstrated by the picture at the head of this post, I started with four
external hard disks. Using my trusty computer repair kit, I forcibly shucked the
external cases and extracted the four 6TB disks. They are consumer grade
`compute` disks by Seagate - good enough for a side-project. Let's see how well
they last!

![](images/post_content/shucked_disks.jpg)

The image above shows the four disks ready for squeezing into caddies for their
future occupancy of the RS816 NAS. The process of shucking was trivial. I am
not happy though with the amount of cardboard, plastic and electrical waste that
has been left behind. Each of the boxes was plastic wrapped; the plastic drive
enclosure was also wrapped and a prodigious amount of cardboard was used to keep
everything safe. A nice way to save an additional 30% of cost but now feeling
dirty!

So how are the drives being setup? While a 24 (give or take) RAID-0 drive would
be magnificent; I have lost more than enough drives in my computing career -
a simple RAID-5 is good enough for me!

![](images/post_content/you_have_been_warned.png)

Synology is clearly a little concerned for my sanity - I have been warned.

![](images/post_content/you_have_been_warned.png)