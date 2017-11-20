---
title: Learning Jekyll/Liquid Templating
date: 2017-10-20 13:45
author: Carl Boettiger
image: http://placehold.it/900x300
alttext: Time is an illusion. Lunchtime doubly so.
lead: "We pay a huge price for the underlying complexity of dynamic code running on a server for every request - a price we could avoid paying when this kind of complexity is not required."
categories: jekyll static_sites
comments: false
#category: jekyll
subheading: create a ultra fast cms that scales with you
---

## Some quick thoughts on learning Jekyll
After recieving a few queries on how to get started with Jekyll I thought I’d jot down my own opinions here. Of course there is already rather good documentation for the software and plenty of blogs providing tutorials. While no doubt more than adequate, I have more opinions on how to get started actually learning what’s going on than I could easily fit into a tweet, and also a couple favorite links to references so I thought I’d jot down my reply in long form here.

### Brief Background
Jekyll is a fantastic and popular static blogging platform, written in Ruby by a Github founder, Tom Preston-Werner, which powers this site (at least currently). Similar static website generators exist for Python (Hyde) Haskell (yst), and probably others, but Jekyll is quite widespread.

With the (unofficial) slogan of the bloging platform for hackers, Jekyll is aimed at folks who don’t mind a little coding. If you’re looking for a polished, user-friendly product where a huge community of developers has written most imaginable extensions, check out Wordpress.org. If you want something where you can easily get into the guts and customize everything, Jekyll may be the best game in town. Compared to a dynamic site, a static site is much more lightweight, which translates into faster, more stable, and less expensive. What’s not to like?

Where to start?
A couple pre-configured Jekyll setups have emerged to reduce the learning curve, most notably Octopress and Jekyll Bootstrap. In my opinion, in an attempt to make things easier through tricks such as automated Ruby makefiles (Rakefiles) I think these projects have actually made Jekyll appear much more complicated than it really is, as evidenced by the number of talented programmers running Octopress with the identical configuration. They may get you started faster, but their use of advanced techniques to provide more functionality out-of-the-box makes for a tougher learning curve.

See the Jekyll-Bootstrap’s introduction to Jekyll for a nice explanation of how Jekyll is laid out. Understand the basic YAML headers, and the role of the and you’ve mastered the basics. Or read on below for my take on getting started.

