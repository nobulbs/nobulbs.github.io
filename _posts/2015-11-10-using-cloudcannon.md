---
title: "Using Cloudcannon, a web based, static site editor"
layout: post
published: true
---



OK, this is a bit of an experiment. I'm writing this post in [Cloudcannon](https://cloudcannon.com), which is synched up to my Github Pages No Bulbs account. At least, it should be.

Why do this? Well, we like static sites for lots of reasons: they're quick, portable, secure and simple to set up. I've been using Jekyll for a few years now and wouldn't use a database driven CMS, given a realistic choice.

There are problems with handing over a Jekyll site to a client or web editor colleagues. You write posts in Markdown, build the site via the command line and upload the outputted files to your webspace (or push them to Github). It's fairly complex. What we want is a nice visual editor and something that will do all the deployment in the background. Cloudcannon purports to do just that.

So, first things first. I'm writing this logged in as a developer using the code editor. That way I can add front matter. Next I'll try editing logged in as normal editor, then I'll add a new post. How will I add front matter?&hellip;

## First impressions

Cloudcannon was a bit flakey. I suspect this is partly down to Github not publishing updates straight away, which is often the case even when you push changes via the command line. But I found I couldn't delete a file without pulling the repo, making changes on my PC and pushing them back in the normal way.

I need to spend a bit more time with it. But the client login didn't work either.

## Prose

`prose.io` is another editor I'm trying on this post.

Prose worked a lot better. Changes were instant and the login process simpler. You'd need a _little_ knowledge to handle front matter: adding `layout: post` to every blog post would seem odd. Perhaps there's a way round that.
