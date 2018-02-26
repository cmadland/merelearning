---
ID: 5313
post_title: Am I in sync?
author: Colin
post_excerpt: "I've previously written about the learning design workflow that I've worked out for TWU. In short, we need a highly streamlined process..."
layout: post
permalink: >
  http://merelearning.ca/technology/am-i-in-sync/
published: true
post_date: 2018-02-25 18:43:56
---
I've previously written about the learning design workflow that I've worked out for TWU. In short, we need a highly streamlined process (because we don't have the staff to manage a complex process) that is forkable and version controlled and which results in portable and relatively simple markdown files that can be deployed in a wide variety of environments.

GitHub allows us to meet all of those requirements, but with the caveat that the GH interface for composing content is less-than-intuitive, especially for anyone not accustomed to it.

That's where GitBook came into the picture. GitBook is a git-based service that has a nice simple WYSIWYG editing interface and it's built for composing text, rather than code. Further, GB connects easily to GH repositories for backup as well as project management tools.

What we've found though is that GB seems to have a difficult time with large files and, for some reason, leads to inconsistent results, especially when displaying tables or nested lists.

These glitchy things can be worked around, but work-arounds tend to lead to more workarounds, and eventually you get to the point that the costs of using free software are too great. Too much time. Too much frustration. Too many steps between design and front-end experience.

So, it was time for a better solution.

One of the solutions that I discovered in looking for ways to connect github with WordPress (our front end) is a plugin called 'WordPress - GutHub Sync' (WPGHS). Sounded promising, but at the time, I didn't like the fact that it was a sync, not embedding GH content into WP. This would mean that changes made in WP would be reflected in GH.

As I was looking for a simple way to both replace GitBook and avoid MS Werd, I realized that the WordPress interface is pretty easy to figure out, and with WPGHS, changes in WP can be sent to GH. Now that sync looks like a much better idea. Now we can compose in the WP editor and sync directly to GH which serves as a backup, a forkable, version-controlled repository, and project management system.

Next post will be an overview of the process of setting up a new repo and connecting to WP.