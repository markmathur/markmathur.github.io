---
layout: post
title:  "Mixed answers"
date:   2017-11-18 18:44:39 +0100
comments: true
categories: CSS
---

# Further remarks on this site

## robots.txt

This file that on puts in the root catalogue, is a message to search engines that come across 
ones URL. In this simple text document one can declare if certain parts of the site are not 
appropriate to list in search results. It can be old files that are replaced by new ones, 
files under developement and system files. 

Search engines arent't restricted from these files, it is more of an silent agreement - 
they don't want to show meaningless information just for the sake of it. 

## humans.txt

This file sounds like some kind of human equivalent to robots.txt, but it isn't (and it 
doesn't appear to be all that much used eather). Humans.txt is a simple text file where 
the humans involved in the production of the site can be listed with contact information.
Usually the client who has payed for the site don't want the progammers' names to be listed
on the site. But in case someone is really impressed by it (or has questions), this small
file off the grid comes in handy (it never is visible on the homepage, as its not HTML - 
one has to literally invoke it to see it).

## Open graph 

Facebook first developed this protocol to be able to register better whats its users were 
doing and with what, as such things were often shared in social media. Today it is controlled 
by the Open Web Foundation and is the standard for several social medias. 

Basically, adding Open graph tags to you site (or other apps and stuff that can be shared via 
social media) lets you control what a *share* would look like when a user shared its acitivity
on a social media web site. For instance, if you have connected your listening on Spotify to 
your Facebook account, Spotify can with Open graph control how that *share* is to be displayed: 
Title? Artist? Song name? The album cover? Some additional text string such as "nn is listening to"
etc. 

On my site I have chosen to communicate title, type, url, image, locale (the site is in English, but 
coming from Sweden) and description.

