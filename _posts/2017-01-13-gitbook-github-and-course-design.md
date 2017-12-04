---
ID: 5093
post_title: Gitbook, Github, and course design
author: Colin
post_excerpt: ""
layout: post
permalink: >
  http://merelearning.ca/education/gitbook-github-and-course-design/
published: true
post_date: 2017-01-13 15:39:51
---
<div class="canva-embed" style="padding: 50% 5px 5px 5px; background: rgba(0,0,0,0.03); border-radius: 8px;" data-height-ratio="0.5" data-design-id="DABapoEYB5A"></div>
<script src="https://sdk.canva.com/v1/embed.js" async=""></script>

<a href="https://www.canva.com/design/DABapoEYB5A/view?utm_content=DABapoEYB5A&amp;utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">twil</a> by <a href="https://www.canva.com/cmadland?utm_campaign=designshare&amp;utm_medium=embeds&amp;utm_source=link" target="_blank" rel="noopener">cmadland</a>

The more I dig into <a href="http://gitbook.com" target="_blank" rel="noopener">Gitbook</a> and <a href="http://github.com" target="_blank" rel="noopener">Github</a> as a platform for online course design and delivery, the more I think that it is going to be a great way to reduce the hassle of typical course design projects that rely on MS Word files emailed back and forth and to and fro.

What I discovered this week is that, in order to sync a Gitbook project with Github, it works best to initiate the project with a README.md in Github first, then connect Gitbook.

In another universe, I would have found this out the hard way because I had a project initiated in Gitbook that I connected to an essentially empty repository in Github. I then found out that Github is considered the master and it overwrote my work in Gitbook.

That's usually a bad thing.

This was kinda bad, but not horrible. It would have been a loss of a couple thousand words that could have been rewritten without too much trouble. But still.

Fortunately, and here is one of the advantages of Git...I was able to recover, because I had the history saved in Gitbook.

I realize that there are recovery tricks for MS documents and such, but it was so very easy with Git.

Another thing I've realized, just today, is that the connection between Gitbook and Github is such that Gitbook can essentially be used as a text-based authoring environment for a Github repository. Well, duh, you might say. That's what Github is; a text-based authoring environment.

True, but Github has grown around the needs of people working with programming code, and for the uninitiated (read: everyone I will be working with to design courses), the Github interface is very different from what they are used to, and that is very intimidating.

Here is what a user encounters in Github.

<img src="http://known.merelearning.ca/file/6b4425d9ad74250dd1507b9bdf155e8b" alt="Screenshot of Github" width="572" height="354" />

For someone who is just used to working in Word, the language here might as well be Greek. 'Pull requests', 'Branches', 'Commits', 'Forked'. And not only that, but what do they edit and how?

Let me be clear that this is not a criticism of Github <em>for what it is designed for.</em> Simply an observation, that, to the uninitiated, it is confusing.

Compare that with Gitbook.

<img src="http://known.merelearning.ca/file/9cdb40f693edda6704d7f7f34cdcfd30" alt="" width="580" height="348" />

This is the same level beyond the homepage and the first page a user sees after they select a project.

Obviously, its not the same as Word, so there will be some learning involved; it's actually much simpler and cleaner than Word. It's also simpler and cleaner than Github.

The file structure of the repository is hidden, and it is clear what the user needs to do to edit the file.

And once you get into the editor (two clicks from here in GH, one click in GB). Things are different again.

Github. How many learning designers would like to teach their SMEs to write in markdown?

<img src="http://known.merelearning.ca/file/b13829fffbe00aec9204a8a55282f440" alt="" width="600" height="335" />

&nbsp;

Gitbook. WYSIWYG for the win! That toolbar is all you need, and none of the bloaty crap that's in Word.

<img src="http://known.merelearning.ca/file/5f180c5896ef41f13b247fec3af5b36a" alt="" width="600" height="330" />

And here's the kicker...you can have your SMEs compose in GB, which is designed for narrative text, and everything is backed up to GH, where you can serve out to Jekyll.

But...does that scale? (Seriously, does it? I need to know.)