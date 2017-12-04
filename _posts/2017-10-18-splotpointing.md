---
ID: 5162
post_title: SPLOTpointing
author: Colin
post_excerpt: >
  That time I used SPLOTpoint for a
  presenation...
layout: post
permalink: >
  http://merelearning.ca/education/splotpointing/
published: true
post_date: 2017-10-18 09:19:50
---
I was privileged to be able to present at the <a href="http://onlinelearning2017.ca/en/">ICDE World Conference for Online Learning</a> earlier today. It was unfortunate that I couldn't be there in person, but my friend and colleague, Ken Monroe from TRU was on the ground to manage the bulk of the logistics of the presentation. I had 10 minutes in a 50-minute session shared with 3 other presenters, so there wasn't any time to fiddle-faddle around.

Knowing that the default information projector is PowerPoint but that there are far cooler tools available, made me want to try something a little different this time around.

One of the things with PPT is that your slides are a static resource after the presentation, and it is generally useless to have a list of bullet points (even if they are animated) in a file somewhere. Fortunately, <a href="https://cog.dog/">@cogdog</a> exists; not only the site, but also the guy who barks and growls on that site. Alan is one of the most generous people on the web, and one of his gifts to us is SPLOTpoint; an alternative to the one from Redmond.

SPLOTpoint (<a href="http://splot.ca/">based on the SPLOT idea</a>) is a modified WordPress theme (Intergalactic) set up to create a click-through site for you to host your presentation. Remember that thing with PowerPoint, about it being a static resource after you are done? Well, SPLOTpoint allows you to create an open repository of all your presentations that anyone can access both during and after your spiel, and they can leave comments, ask questions, seek clarification, and share their own ideas because the whole thing is just another WordPress site.

Alan has made SPLOTpoint open and super easy to install on your own site, at least if you roll your own WP install. It's not going to work on wordpress.com. Just head over to the <a href="https://github.com/cogdog/splotpoint">repo on Github </a>and click the green 'Clone or download' button to download the .zip, then upload it to your theme folder or use the automatic theme installer to upload. You'll have to ensure that you have the Intergalactic theme installed before you activate SPLOTpoint because SPLOTpoint is a child theme of Intergalactic. From there, you create your presentation in a more bloggy format than a typical PPT slide deck, and you can style your site with huge header pics with text below, or just use the header pics as your complete slide and off you go.

Alan's GitHub repo includes detailed instructions for getting the theme set up, so I encourage you to do so. It is worth noting that if you are reading this and you have a site at create.twu.ca, SPLOTpoint is installed and ready to go!

I did encounter one difficulty, predictably about 45 mins before I was set to present. I made a small edit to one of my slides, saved it, and went back to check that everything still worked (always check!), and something had borked. When I tried to navigate to that particular slide, the presentation went back to the homepage of the site. Obviously, this wouldn't do for a presentation that had to run smoothly with such limited time. I couldn't see anything wrong with the URL or with the sort order of the slides. Updating, logging out, and other such things that sometimes reorient the web ferrets didn't work.

Knowing that there was a reason that this was happening, I decided to change one of the variables just to see what would happen. Changing the sort order would be silly, because that would ruin the flow of the presentation, so I decided to change the name of the slide and the URL. I don't know which one of those things worked (oops...confounding variables going uncontrolled), but it did.

All in all, I'm really pleased with SPLOTpoint as I now have a super easy way to share my presentation that doesn't require me to upload it to SlideShare, I can display it as it was intended to be displayed, I can link to it from my other domains, and I can update it as needed.

<a style="background-color: black; color: white; text-decoration: none; padding: 4px 6px; font-family: -apple-system, BlinkMacSystemFont, 'San Francisco', 'Helvetica Neue', Helvetica, Ubuntu, Roboto, Noto, 'Segoe UI', Arial, sans-serif; font-size: 12px; font-weight: bold; line-height: 1.2;" title="SPLOT by @cogdog" href="https://github.com/cogdog/splotpoint" target="_blank" rel="noopener"><span style="padding: 2px 3px;">Featured Image Credit: @cogdog</span></a>