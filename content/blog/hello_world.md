+++
title = "Hello, world (again)!"
description = "I have another blog."
slug = "hello-world"
date = "2024-06-28"

[taxonomies]
tags = ["misc", "personal"]
+++

Growing up in that — in retrospect, relatively brief — period of time when the Internet had already become popular,
but social media platforms had not yet taken over, I had made multiple attempts to host a standalone blog.

The first was when I was, I don't know, 11? 12? I bought a domain (no idea with what money) matching the then
*really cool* username I had on various forums, set up hosting (also no idea with what money), and installed WordPress.
I don't know what I blogged about in that first iteration, because that website (and its *cool* domain name)
is long-lost to the digital abyss. I don't think I posted very much, though, and probably 
lost interest pretty quickly. The idea of having my own website and a blog was cooler than actually running them.

<!-- more -->

After that, like many kids in the late 00's, I'd gone through Facebook,[^1] Tumblr,[^2] and Twitter,[^3]
(and also LiveJournal,[^4] and probably others I'm forgetting), but couldn't make any of them stick. 
Whatever their initial intent, all of those platforms eventually developed their own dynamics, 
and for whatever reason those never clicked with me.
So, despite being on the Internet pretty much all the time, I had very little in terms of significant online presence.

I'd made other attempts at running a standalone website and blog, but was still more into the idea 
of just having them, instead of actually publishing things and maintaining it all. One of those iterations ran
a self-hosted version of WordPress that I let get very out of date, until someone
found a known security exploit and replaced my front page with a picture of the grim reaper or a skeleton
in a black hood, or something else equally *badass,* complete a message that I've been pwned
(almost certainly using some automated tool, so I couldn't even feel special). 

So that attempt failed, too.

And then, around 2013, I fell in love with Python, had someone at my college introduce me to Flask,[^5] 
and had such a blast with it that I decided I *had to* use it to rebuild my website and blog. I was learning
Python, Flask, and web development as a whole as I went along, so I reinvented the wheel constantly throughout 
the process, and built most of it from scratch with (often unidiomatic, probably ugly) Python,
(probably ugly) Jinja2 templates, (probably very ugly) hand-rolled CSS, and CoffeeScript[^6] — 
later replaced by (probably very unidiomatic and very, very ugly) vanilla JS. Being Flask, 
the whole thing had to be rendered by the backend on the fly, 
meaning that I had to have a server that ran the Python process all the time, and therefore deal with managing 
that server, which included figuring out a way to restart the Python process that served my website every time
the server was rebooted — all before I both knew saner ways to manage infrastructure, and that the even saner way was
not to have a dynamic, server-side rendered website at all. The footer said something like "built using rubber bands, 
misshapen screws, and a rusty multitool," so I was at least self-aware.

But it was mine, I built it myself, and I loved it. It even had multilingual (well, bilingual) support, 
so I could have a Russian version, an admin page so that I could post from the web, including from my phone, 
and a 404 page that showed a random GIF from [Black Books.](https://en.wikipedia.org/wiki/Black_Books)

Most of all, maybe because I felt so invested in it, for the first time I posted content with some regularity. 
Most of that content was random and probably strange (whatever thoughts I had about 
politics and tech, as well as short stories and sketches of theater scenes), and no one read it unless
I specifically sent them a link (and even then who knows), but I managed to keep it going for several years,
until I left college and let life get in the way.

Eventually, it went down, and I didn't bother to start it up again.

Between then and now, I had sometimes thought about starting a new blog, but 

a) knew that as fun as it was at the time,
I didn't want to build and manage it myself again, and 

b) didn't feel I had anything interesting to share. 

I did make a new personal website (at this domain), because I wanted something to put in the "website" 
field on platforms like GitHub and elsewhere, and thought it might help finding a job,
but didn't make too much effort. It just had my name and links to my GitHub, LinkedIn, and (eventually outdated)
resume.

I'd thought about starting another blog, but repeatedly stopped at "I have nothing interesting to share" and 
"do I build it myself?", until a few weeks ago, when I read Nicole Tietz-Sokolskaya 
[Affirmations for bloggers.](https://ntietz.com/blog/blogging-affirmations/)
It's a wonderful post, which addressed both of those and more,
and it persuaded me that as long as something was interesting to me, it might be interesting
to someone else, and that no, I don't need to build another thing from scratch myself, until/unless I decide
I want to do that. Later, if ever.

Oh, and earlier this month I was 
admitted to the [Recurse Center,](https://www.recurse.com/) and decided I wanted to have a blog
to share my experience and keep myself accountable (more about RC to follow).

So, here we are. I have a blog again. It's built with [Zola](https://www.getzola.org/) 
and [Abridge](https://abridge.pages.dev/) and is (as it should be) static,
so should not go down unless something goes very wrong with Netlify or my domain. 
I still plan on adding a Russian version because I do have ideas for blog posts in Russian — 
which Zola/Abridge support, but I haven't fully figured it out, so that can happen later. 
There are also things I want to tweak in the design (Abridge
is great, but not everything in it is for me, which is okay). But it's here, and more than good enough 
for me to get started.

I hope this one lasts longer than the previous ones.

<small>Huge thanks to Hunter *(themagicruby on most social media)* for designing the logo.</small>

<hr>

[^1]: Not a platform for blogging, although some people did use it that way.

[^2]: Initially seemed like a platform for blogging, but quickly turned into *its own thing.*

[^3]: Which introduced "microblogging," and for years many people had no idea 
[what it was supposed to be](https://en.wikipedia.org/wiki/Twitter#cite_ref-Inc_44-0) 
(although [some](https://www.wired.com/story/black-twitter-oral-history-part-i-coming-together/)
figured it out sooner than others), until it turned into *its own thing*, and then... whatever it is now.

[^4]: Big on the Russian-speaking Internet way past its prime in the West.

[^5]: I don't remember your name, but thank you.

[^6]: ... it was cool at the time?



