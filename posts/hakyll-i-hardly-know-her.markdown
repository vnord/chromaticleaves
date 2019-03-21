---
title: Hakyll? I hardly know her!
date: 2019-03-20
tags: hakyll, web development
metadescription: And we're live, again!
---

Phew! Finally. A static website that doesn't suck. This isn't the first time
I've generated a static website and blog with Hakyll, and it may not be the
last time -- but here's for hoping that it's the best time.

I stole the general setup from Eric Rasmussen's private website,
[Chromatic Leaves](http://chromaticleaves.com). Getting it to build was
not too much trouble. Only two lines of Haskell imports had to be modified. The Sass/Foundation
code was somewhat more troublesome - I don't know much about the syntax, and figuring out
that the way that quotes were being used in some variables was no longer compatible
with more recent versions of Sass took some time.

I then proceeded to make some aesthetic changes, such as using [GlassTTY](https://github.com/svofski/glasstty)
for the header font, underlining tags, and some other minor changes. I also uploaded
some of the old posts that I wrote many years ago for my first Hakyll blog.

Lastly, I integrated Disqus. In theory this is very easy, and it was -- but I got tripped
up by the way that Firefox caches some resources, and was under the impression that
things were not working as expected, which cost me a considerable amount of time in debugging.

I plan to post more frequently this time -- I hope to make some more technical posts,
more reviews of all sorts of things, as well as some commentary on the art of brewing coffee.
Also please note that the older posts (from 2015) do not represent my present-day self.
I've changed and grown since then. I still think they hold some interest, though.
