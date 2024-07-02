+++
title = "Starting a batch at the Recurse Center"
description = "Notes, plans, hopes, and fears"
slug = "starting-rc"
date = "2024-07-01"
draft = false

[taxonomies]
tags = ["rc", "programming"]

[extra]
toc = true
+++

Today is the first day of my 12-week batch at the [Recurse Center!](https://recurse.com) As I mentioned in my 
[first post,](@/blog/hello_world.md) one reason I wanted to restart my blog was to share my experience as I 
go through my batch. I am doing this in part to help keep myself accountable, and in part to offer a window
into my time at RC for people I've told about it and who were curious.

What follows is some background on why I chose to attend RC (and why now), as well as a semi-structured list of 
things I want to learn or work on, things I'm hopeful about and excited for, and anxieties I want to work through. 

<!-- more -->

## Why RC?

I have been programming professionally for close to 8 years. I've spent most of that time in ML-adjacent roles at 
startups, which has been a blessing in that I got to explore and contribute to many different things (machine learning, 
NLP, backend development, data pipelines, infrastructure, and more), but also a curse because I have felt 
persistent pressure to learn something at just enough depth so that I could use it to build a new feature or product,
as fast as I could. While I have felt able to invest some time into exploring some topics in depth,[^1]
I've also often felt like I've been playing tetris while running on a treadmill, and like I needed
to learn everything yesterday. I wanted to hit pause, take a breath, and get some time to learn things in 
depth, without externally imposed deadlines.

That is exactly what RC aims to provide, and more — most importantly, a community.

### Why now?

I first learned about RC several years ago from [Dan Luu's blog,](https://danluu.com/learning-to-program/) 
went on its website, looked through the application, 
and mentally filed it away under "Would be good to apply some time in the future."[^2] But the fact that
RC batches require a full-time commitment of 6 or 12 weeks,
meaning I would have to take a break from work, (and that the application had multiple open-ended steps) stopped me. 
It didn't feel like the best time.

Then, several months ago I discovered Nicole Tietz-Sokolskaya (awesome) [blog,](https://ntietz.com) which had a link
to the RC application in the footer. And then, just over a month ago I was lucky enough to attend PyCon US, 
where I met [Will Lachance,](https://wrla.ch/) who at one point also brought up RC and encouraged me to apply. Will
also generously offered their time to answer my questions about RC and the application (as did Nicole).
It still didn't feel like the best time, but I realized it never might.[^3] Plus, my experience over the past couple
of years, in both work and life, the good and the difficult, helped realign me towards a 
[growth mindset,](https://www.psychologytoday.com/us/basics/growth-mindset) so I felt like RC would be a good 
fit now more than ever before.

So I applied, and here we are!

### Why 12 weeks?

I originally planned to attend for only 6 weeks, but then increasingly felt that time would completely fly by
(which some accounts of previous Recursers corroborate), so ended up confirming for 12 weeks instead. This decision
caused challenges (I had to leave my current job and put future plans on hold, possibly missing out on some things), 
but I hope it pays off in the long term.[^4]

## What I want to do

The goal for Recursers is to become "dramatically better programmers" by working on projects that are "at the 
edge of their ability" but also bring them joy, 
and "learning generously" by sharing their process with others and participating in the community.

I have a lot of ideas for what I want to learn and work on, and I will almost certainly not be able to do it all.
I am still figuring out what would really be at the "edge" of my ability — enough to push myself, but not so much
that I would get discouraged.

### Technical skills

Some ideas I have right now are:

- Dive into formal methods, specifically [TLA+.](https://en.wikipedia.org/wiki/TLA%2B)
I've been following [Hillel Wayne's](https://www.hillelwayne.com/) newsletter long enough to appreciate that
it would help me be a better engineer, but have never committed myself to going through his 
[Learn TLA+.](https://learntla.com/) Now seems like a great time!
- Learn how databases work at a low level, and maybe try implementing one myself. I've used databases throughout my
career, but much of their inner workings have remained a black box to me.
I plan on starting with the [Red Book](http://www.redbook.io/) and participating in my batch's database internals
study group.
- Learn Zig, because I enjoy learning programming languages, and I think that Zig, with its
first-class C-interop would be a good addition.[^5] I've connected with other Recursers who use Zig or want to learn
more about it, and we might host a study group for it, too. To help get me started, 
I thought I'd [try reimplementing](https://github.com/anna-hope/ziglox) 
the bytecode interpreter from the (amazing) [Crafting Interpreters](https://craftinginterpreters.com/) in Zig.

Some other things I might want to explore that are currently less concrete:

- Graphics/3D programming. I did [The Ray Tracer Challenge](http://raytracerchallenge.com/) last year, and loved it,
but I'd like to learn about real-time graphics programming. We'll see if I get to it, though.
- Building an NLP library in Rust. I've often wished Rust had something like [Spacy,](https://spacy.io/)
but replicating that would be a massive undertaking, and the Spacy team have had a decade to get to where they are now, 
whereas I only have 12 weeks. Working on a word tokenizer, 
an algorithm to segment sentences, and a part-of-speech tagger would be fun, though. But I also don't know if
it is really at the edge of my abilities.
- Building an operating system?
- Building a way to add [DICOM](https://en.wikipedia.org/wiki/DICOM) support to [Zarr?](https://zarr.dev/)

What I've learned so far, though, is that interacting with other Recursers and learning about what they're working
on might upend those goals by presenting me with things to do that I hadn't even considered. I want
to stay open to that, so most of the above is subject to change.

### Meta-skills

- Getting good at pair programming (a big focus at RC)
- Staying motivated when things get hard and progress feels slow (having a community should really help here)
- Being kind to others and myself, and unlearning some unhelpful things I have picked up throughout my life (RC's
[social rules](https://www.recurse.com/manual#sub-sec-social-rules) help provide a structure for this)
- Managing time and keeping myself accountable when there is no superior to set deadlines or report to 
(RC's community also provides help here, and I hope keeping this blog will, too)

## Hopes

That I will have a great time, make friends, gain an amazing community, and grow, professionally and personally.

## Fears 

*I don't want these to get in the way, but I do want to express them to get them out of my brain.*

- That I won't build anything concrete in the time I have
- That I will not use that time effectively (whatever that means)
- That things outside my control will somehow derail everything
- That I don't fully know what the future holds after RC
- A lot of FOMO about attending RC remotely while most of my batch-mates are in-person in Brooklyn. I'm far from the 
only remote Recurser this batch (and only one time zone away, unlike some others who are much farther!), 
but still, there won't be any RC-based board games, yoga sessions, and completely 
spontaneous interactions for me, and I'll have to make more effort to make myself feel "present"

## That's all for now!

If you got to the end, thank you for reading! 
If you're interested in following my journey at RC and beyond, consider subscribing to [my feed!](/atom.xml)
I plan on posting at least once a week for the duration of my batch.

<small>Huge thanks to Nicole Tietz-Sokolskaya and Will Lachance for encouraging me to apply to RC and offering their
time to help me!</small>

<hr>

[^1]: Notably, I managed to learn enough Rust to build a somewhat complex production ML application at a previous
job. It was *definitely* not the best Rust code out there, but I had a blast working on it, and it massively improved 
performance over the previous Python application
(which I had also built, so its performance problems were likely my fault), using a fraction of that application's
computational resources at significantly higher loads. That was fun. 

[^2]: Aside from everything else, I appreciated how much the Recurse Center's website explicitly
promoted including women, trans/queer folks, people of color, and other groups that have been traditionally 
underrepresented in programming circles. It really helped me feel like I would be welcome.

[^3]: There are definitely worse time than others, though. I feel very privileged that I have the ability
and resources (read: enough savings) to do this now.

[^4]: Again, I know that being able to do this is a very big privilege.

[^5]: Also, I have a character flaw in that I often internalize things I really like as part of my identity.
I noticed this was happening with how big a fan I became of Rust, to the point that Zig just *existing* in 
a seemingly similar low-level, systems programming domain started to feel like it was threatening Rust's success,
especially with posts like [this.](https://zackoverflow.dev/writing/unsafe-rust-vs-zig/) Learning Zig felt
like one way to get over whatever this part of me is afraid of.










