Title: Goodbye SquareSpace, Hello Github.io
Date: 2019-03-21 17:00
Category: Blog
Tags: pelican, publishing, github, squarespace
Authors: Josh
Summary: Why I migrated from SquareSpace to Github.io for my personal site.

TL;DR: I used SquareSpace from 2012 to 2019, but finally made the switch to github.io using Pelican to generate my site.

Sometime in 2012 or 2013, I decided that I needed to register a domain and stand up a site. I had been reading about "personal marketing" to land that sweet sweet job. I bought a domain (you're looking at it), I designed and purchased business cards, then moved on to standing up a web site.

Having worked with LAMP stacks in my day job, I was keen on rolling my own site, and hosting at my apartment in downtown Indianapolis. After a few days of setup, configuration, and general messing around, I realized a very important thing, I am NOT a web developer and I am NOT a web designer. I am a backend, systems engineer.

I looked around for different hosting solutions and I had heard quite a bit about [SquareSpace](https://en.wikipedia.org/wiki/Squarespace), thanks to all the shows on [Revision3](https://en.wikipedia.org/wiki/Revision3) (RIP). I mean, Kevin Rose used it, his site would it the front of [Digg](https://en.wikipedia.org/wiki/Digg), and then never go down. For less than $100 bucks a year, I had a whole host of features and functionality that I thought I would need. Plus, they had amazing, professional templates and a awesome WYSIWYG editor.

Over the next weekend, I looked through all the available templates, figured out what I wanted my site to say about me, and started implementing what would remain my sites look for the duration of my time on the platform. I made it clean with a few pictures of projects I was working on that included little burbs. Setup integration to all my social platforms, then quickly removed most of them. I published my site and felt good about taking my "brand" into my own hands.

Between publishing my site and today, I used my account for my wedding invitations and RSVP process, made a few joke pages (sorry Shawn), and mostly left my site unchanged. Is it worth $100 a year to have a static site that basically just links to your [LinkedIn profile](https://www.linkedin.com/in/joshuarobertbailey/) and your rarely touched [Github account](https://github.com/binkocd)?

At the end of 2018, I decided I was going to cut down on accounts that I had at various sites. SquareSpace firmly came into view when I received a marketing email.

I looked at why I wanted a website and how I was using it. I wanted a site to show off my skills and help me land that sweet gig that I was promised. Having a static site that "anyone could do" didn't hit those marks to me.

Over the last few weeks, I have been looking into different static site generators. I had some time with [Jykell](https://jekyllrb.com/) via a [Docker Mastery course on Udemy](https://www.udemy.com/docker-mastery/), but I don't have a lot of Ruby experience. I started looking at Python based projects and finally landed on Pelican. I started a Docker, but I really had no idea how to use [Pelican](https://blog.getpelican.com/), let alone how to use it in an undocumented container.

After some easy setup, thanks to [this guide](https://fedoramagazine.org/make-github-pages-blog-with-pelican/), I started making some basic content. After I got my github.io PoC up, I thought "good enough for what I need" and started rolling everything over from SquareSpace.

My hope is that I can get a decent baseline created and then start to migrate from manual publishing and pushing to some CI/CD process.
