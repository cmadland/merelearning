---
ID: 5112
post_title: Learning along the way
author: Colin
post_excerpt: ""
layout: post
permalink: >
  http://merelearning.ca/education/learning-along-the-way/
published: true
post_date: 2017-10-03 21:23:55
---
I'm a little more than a year into this gig at TWU and feel that I've accomplished some important things, though not without some significant assistance along the way.

My first major priority was to upgrade our LMS from Moodle 1.9 (released in 2007; shelved in 2010 IIRC) that we have been running as is since we installed and customized it a decade ago. The thing with customizing Moodle is that you don't get to keep those customizations if you want to upgrade.

It didn't make sense at all to upgrade our current system on our own current servers, so we decided to sign on with the EduCloud service offered through BCNET. This is a great deal where our Moodle instance is hosted on UBC servers and is managed by TRU. We provide tier 1 support for our users and tier 2 support comes through TRU.

For a relatively small school like TWU, this frees up a lot of energy and capital for us.

I am the first login recorded on the server at 8:45 am Monday, March 22, 2017 and as of September 1, 2017, all new courses are being offered in Moodle 3.1, and the transition has been pretty nice so far.

We did two major rounds of faculty training in preparation for the move. The first was in May and June and we had a modest turnout of faculty who wanted to get a head start over the summer. This was good to see, but the trouble was that we hadn't fully provisioned faculty accounts yet, so we created 30 sample accounts and 30 sample courses for faculty to sign in and go through the motions of backing up their course from 1.9 and restoring it into 3.1.

Surprisingly, this backup/restore between the two systems was pretty painless. The only real trouble we had was courses above our 256MB upload limit (usually courses with hundreds of MB of PDFs...). To work around this, we could either run the backup without the course files, or run it in several stages.

We created all the Fall 2017 courses on June 21, then provisioned faculty accounts and enrolled them into their courses on June 26. Notably, this was a manual enrolment process using a CSV file upload, as we were still thinking through the details of how to automate user creation and enrolments.

July was predicatably slow with a few training sessions for individual faculty and departments, but most people are pretty scarce during July and into the first couple weeks of August.

On August 17, we enrolled all students into their courses using the same CSV upload that we used for faculty. This would become a bit of a problem in the first couple weeks of September. More on that later.

Our decision to run a manual upload was driven primarily by the need to get students into their courses by the time faculty were due back on campus in mid-August. At the time, we didn't yet know how we were going to manage automating enrolments, and i was getting a little nervous.

Next day, August 18, we had a working database pulling data from Jenzabar and feeding it into the Moodle (forgive my non-computer-sciency descriptions). Awesome! Wow! Now we had a process that could update enrolments twice a day. Students who dropped courses would be pulled from Moodle and those who added courses would be added a tthe next sync. Or so we thought...

The last two weeks of August were a blur of training, welcome back events, retreats, eclipse watching, training, and more training. In all, by the time the first all-faculty meeting was held, about 80% of attendees indicated that they had been to at least one training session!

Classes started on September 7 and we started to realize the implications of having had enrolled students both manually and through the database. Every student had two enrolments in each course. Some students, those who dropped a course after Aug 17 had only one enrolment (manual). Others who registered after Aug 17 had only the DB enrolment. The trouble was that the DB enrolment process wasn't changing the manual enrolments, so course lists in Moodle didn't match Jenzabar and students weren't seeing courses disappear from their own course overview after they dropped.

Then the Office of the Registrar discovered that waitlisted students still had access to courses. That one was solved when we discovered a typo in a script. But it led to further aggravation of the problem of not being able to remove manually enrolled students in a bulk process.

So it was a few days of 'hemming' and 'hawing' until we decided to identify all of the students enrolled in courses with only a manual enrolment and to suspend their enrolment in those courses. Worked like a charm. Actually, better than a charm. Charms don't work well with tech.

All in all, inside 6 months of signing into a fresh install of Moodle, we had all new courses launched for Fall 2017, as well as all users in their proper courses.

I call that a win.