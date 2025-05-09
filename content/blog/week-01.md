+++
title = "Week 1: Introduction / Infrastructure"
date = "2025-08-19"
description = "Notes on the first week of DCDA 30970"
tags = [
    "week notes",
]
image = ['share.webp']
[extra]
author = ["Dr. Edwards"]
+++
Welcome to the course website and blog for **DCDA 30970 - Special Topics: Digital Infrastructure and Climate Crisis**. On this site, you'll find materials related to our course, including my weekly notes, which are intended to help you with coursework, writing, and creativity. You are reading one of these [week notes](../tags/week-notes) posts right now. Be aware that these notes do **not** replace our time in class together.

You'll also be contributing to this site as the semester goes along, mostly in the form of blog posts that will appear alongside mine. More on that later. For now, let's start by getting to know each other. 

## Introduction
When I was still in elementary school, my mom got a job working at the America Online call center in Jacksonville, FL. This was the mid-1990s, when you connected to the internet by having [your modem scream into your home telephone line](https://upload.wikimedia.org/wikipedia/commons/3/33/Dial_up_modem_noises.ogg). AOL charged customers by the hour to use the internet, but we got it for free thanks to my mom's job. 

I fell in love with the internet back when you still had to use command line prompts to tell DOS to launch the Windows GUI. If you don't know what any of that means, well... it was another era. 

<img
  src="aol.jpg"
  alt="A floppy disk with a label for America Online"
  caption="This was the kind of floppy disk we used to install America Online in the mid-90s"
>

I never thought of myself as a particularly technology-focused kid. I just loved reading websites and bulletin board posts from other parts of the world, from the comfort of the desk near the windows in my grandmother's tiny dining room. Once, my mom was sitting there browsing the web when a storm brought a tree down on the roof right above her. She was fine, and the roof was fixed eventually, and I don't think the internet even went out that day. 

What's your technology origin story? Take a moment to conjure it up in your mind. Where does it take you back to? What do you see, smell, feel, hear?

I feel the flex and give of my grandmother's [Cesca-style](https://en.wikipedia.org/wiki/Cesca_chair) dining room chairs (the same chairs I fell out of as an infant, breaking my wrist in a way that never fully healed). I see the big boxy beige monitor, but also the jungle of palms and vines separating our house from our neighbors' on the dining room side. I hear the modem scream, and my granny clinking dishes in the kitchen, and my cousin letting the screen door slam as he comes over unannounced. I hear my mom calling my name from some other room of the little house. I smell the salty air of the ocean one block away. 

### How do you see the internet?
This is an activity adapted from Ingrid Burrington's *Networks of New York*, a book she wrote because, as she explains, "I wanted to know about the stuff that made the Internet work, where it lived, and how I could find it." We'll return to Burrington's work in a couple of weeks, but for now, consider all the various ways there are to answer this question.

Let's use this website as an example of one possible way to answer. To make it, I used a laptop (provided for me by work). I created the site with several pieces of software, which I downloaded from servers somewhere in the world, using my home internet. 

That internet connection arrives to my apartment through fiber optic cables, which were installed in my neighborhood less than two years ago. Those cables run underground parallel to the road, then snake into our apartment building in between the walls, up to our living room on the third floor. They end by plugging into a router installed about eight feet up our wall. The router broadcasts the wireless signal that lets my computer talk to other computers around the world.

Once I created the site, I used the internet to send the data to Github's servers, which are distributed all over the world. Assuming the data is being stored on a server nearby, the most likely place is the San Antonio area, where Microsoft (who owns Github) has acquired [at least 12 parcels of land](https://sanantonioreport.org/medina-county-farmland-data-centers-strain/) and has built something like 8 data centers in the past 9 years. Each new round of construction requires clearing both farmland and stands of oak trees. 

<img
  src="datacenter.jpeg"
  alt="An aerial image of a massive piece of land that has been cleared for construction. Two almost featureless buildings are in the middle."
  caption="Construction of a Microsoft data center near San Antonio in 2023. Credit: Scott Ball / San Antonio Report"
>

At some point, you, the person reading this, get on your computer and use your internet connection to tell the Github servers to send you the data that I sent to them, and so much of the process happens again in reverse. 

None of this would be possible without physical infrastructure—buildings, cables, computer chips, screens, wires, and much, much more. 

And it all requires electricity, which gets into our houses, dorms, and data centers through other kinds of cables, after being generated at a power station somewhere nearby. The closest to us is the [Comanche Peak Nuclear Power Plant](https://en.wikipedia.org/wiki/Comanche_Peak_Nuclear_Power_Plant). It relies on water from Comanche Creek, stored in a nearby purpose-built reservoir, for cooling. This reservoir was [renamed in 2022](https://edits.nationalmap.gov/apps/gaz-domestic/public/search/names/1863319) to remove a derogatory slur for Native American women from its name. 

## Infrastructure

So what is "infrastructure," and why are we studying it? I find this explanation helpful in answering both of those questions:

> The word “infrastructure” emerged in the early twentieth century as “a collective term for the subordinate parts of an undertaking; substructure, foundation,” and first became associated with permanent military installations (OED). Since then the term’s meanings have expanded to include electrical grids, telecommunication networks, bridges, subways, dams, sewer systems, and so on, and infrastructures have been the topic of research in fields such as Urban Studies, Communication, Geography, and Science and Technology Studies. In digital humanities scholarship, researchers have explored the topic of “networks” developing important historical and critical studies of networked technologies, institutions, corporations, and cultures. Fewer, however, have investigated the physical infrastructures through which audiovisual signals and data are trafficked. 
>
> By physical infrastructure I am referring to the material sites and objects that are organized to produce a larger, dispersed yet integrated system for distributing material of value, whether water, electrical currents, or audiovisual signals. Engineers often refer to infrastructures as “the stuff you can kick.”
>
> —Lisa Parks, "The Stuff You Can Kick"

Read through that quotation again, slowly. There are at least 2 things I want you to notice. First, that the word "infrastructure" originally applied to "permanent military installations," according to the *Oxford English Dictionary* (a reliable source for the etymology, or origins, of English words). You can access the OED online through the [TCU library website](https://libguides.tcu.edu/az.php?a=o); doing this tells me more specifically that this usage of "infrastructure" became common in the 1950s, during the Cold War. This is a thread we'll trace all semester, this relationship between military weaponry and digital culture in the decades after World War II.

Second, Parks notes above that "the stuff you can kick" is usually studied by disciplines that lean more towards science than the humanities. Or, we could say, you are more likely to encounter this stuff on the "data analytics" side than the "digital culture" side of DCDA. 

I actually think this binary division (STEM vs. liberal arts, engineers vs. poets) is incredibly harmful. It gives people permission to ignore the infrastructures that underpin the tools they use everyday, especially if they consider themselves "not a STEM person." And it gives the people who build and use these tools permission to ignore the meanings, the ethics, the consequences, of what they create.

This semester, we are going to try to get our minds past that binary way of thinking. Not an easy task, especially when we're dealing with machines whose native language is literally [binary code](https://en.wikipedia.org/wiki/Binary_code) (1s and 0s)! We're going to banish the phrase "I'm not tech saavy" from our vocabularies. We're going to write poetry about wireless routers. We're going to call out when powerful institutions are being hypocritical or otherwise foolish (like, really, it took y'all until twenty-twenty-TWO to realize stuff in this country had racist names??). We're going to think about infrastructure as both physical object and carrier of meaning. 

And above all, we are going to remember, as Black liberation poet and scholar Amiri Baraka [said](https://drive.google.com/open?id=1YV34Lsius5QIaJmMQVFwi1biIabfl85_):

> Nothing has to look or function the way it does… Machines have the morality of their inventors.