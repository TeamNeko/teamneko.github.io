---
layout: post
title: "(octo)Pressing Problems"
date_text: 2015-03-20 15:02:49 +0100
comments: true
categories: [learning, blogging, git]
author: Pilar Huidobro
---
One of the most fun learning experiences I’ve had while working on our Summer of Code application is getting to work with [octopress](http://octopress.org/). I had previously used it a little bit for my [personal blog](http://althaire.github.io/), but I’d mostly just made a couple of posts and with some help, I was able to set up a new layout.

Working on our team was a whole new challenge. We agreed that it would be a better learning experience for us as a team that if we ran into any trouble, we’d help each other out.

As fun as it has been to learn octopress, I have run into loads of problems! It's not just octopress either, it's git! Practice makes perfect though, right?

The first silly problem I ran into was that I forgot my SSH key password. It shouldn't be that big a deal, right? Just make a new one? *It wasn't working though...* I tried a couple of times to get it to work but it just wouldn't. Finally I had to give in and just watch despairingly as my awesome Github streak reset (keeping it up for 6 days was a huge personal achievement), this wasn't going to be a problem that I would solve in one day. 

Naturally, the next morning I just tried the [basic steps](https://help.github.com/articles/generating-ssh-keys/) I'd been following the day before and... *it worked.* Why? We shall never know, it's just one of those things.
<center>
<img src="/images/ProblemsPost/codeworksmeme.jpg"> </center>

The great news was that it worked and I could continue working, right? **Wrong.** I had naïvely thought that I could keep working on the posts I had to do, even without git, because sitting around and waiting for it to fix itself was a huge waste of time.
>That was a huge mistake and it is one I won't be making *ever* again.

The reason was that was such a terrible mistake was that, of course, in the mean time, Shelly had contributed posts of her own. This meant that I had unwittingly caused a monstrous merge problem, which, to make matters worse, I had no idea how to deal with. 

After many struggles, the solution we applied was to make a new folder, clone the repository onto there, move all the edited markdown folders somewhere else (thank goodness I had only edited markdown files!), `git stash`, move all the edited folders into the newly cloned repository folder, add, commit and finally push. It was a pretty crazy solution, and there's probably a better way to do it, but it did the job!

Shelly and I kept running into obstacles on our git journey, and I feel like it's never been more applicable but practice does make perfect. I feel like the more we use it, the less both of us have been breaking things. 

Just to make sure we don't run into any snags, I made us a little cheat sheet:

<center>
<img src="/images/graphics/octopresscheatsheet.png"> </center>

This whole experience brought back memories of solving puzzles as a kid, or getting through a tough dungeon in a Zelda game. I think we just need to keep practising, but it's been a fun experience running into these troubles and having to find solutions.

~Pilar

