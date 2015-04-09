---
layout: post
title: "Saturday: Lovebirds and Applications"
date: 2015-03-21 16:34:11 +0100
comments: true
categories:
author: Pilar Huidobro
---
Yesterday, Shelly came over to my house, got to meet my parents, my dog and, the newest members of our family,  Boco and Pusheen, whom I had just picked up from a breeder that very morning.

<center>
<img src="/images/Saturdaylovebirds/Fred.jpg" width="30%" height="30%"hspace="10"> <img src="/images/Saturdaylovebirds/birbs.jpg" width="30%" height="30%"hspace="10"> </center>

She came mid afternoon and we were able to get a lot done for the team:

###Solve the deploy problem
I had already run into this problem several times, having my personal blog, the ruby habits blog and this blog all on my computer (and then having to go through solving this problem **again** after installing bootcamp on my computer and restoring it to my last backup). So this is an annoying problem where you can't deploy because something's up with your _deploy folder. Shelly was having this problem so I told her that when she came over we could look at it and solve it together since I'd gone through that problem several times.
Usually the solution is as follows:

- `rm -rf _deploy` *within your git folder* to remove an existing deploy folder, if it exists, which isn't working
- `mkdir _deploy`  to make a new deploy folder`cd _deploy` to move into the new deploy folder
- `git init`to initialise this folder, that way git knows to keep track of this folder too
- `git remote add origin (your repo url)`sets the origin as the default branch
- `git config branch.master.remote origin`after this the deploy folder should be set up and you should be able to deploy using `rake deploy`

###Settle our team name
Unfortunately, as adorable and fitting as Team Neko was as a team name, it was taken by a convention organisation team, and so it was time to pick a new team name. Linking back to a  conversation we had on [our first meeting](http://teamneko.github.io/blog/2015/03/05/first-meeting/) we thought it would be great to have something linked to a mythological creature, we both like them and thought it would be a nice way to include something we love in into our work.

We were very happy thinking along the lines of Team Kelpie until we realized people might think we ourselves were the kelpies... *Seriously? I was just thinking how cute our logo could be! Shelly and I each with a strand of kelp in our hair hugging a kelpie!* It was at this point that I may or may not have brought up Nessie and how my favourite creature growing up was Tessie from Earthbound. Since Tessie is a real life cultural thing and not just something from a game, we thought it would make a nice team name while still being unique and different to Nessie. *Although Tessie is from Lake Tahoe, we decided to stick to that name because as adorable as "**D**essie" would be, the **D**anube isn't a lake and **N**eusiedler See would have given us **N**essie again...*

> And that's how the name Team Tessie came about. We love mythological creatures, **we love dinosaurs** and we love Tessie, need I say more?

###Get started on our application
Even though there was still quite a bit of time to go, we thought it would be a good idea for us to start filling out the application. We started off by adding ourselves in as a team, adding that we would like to work on Hoodie, fantastic team of coaches and Jan, who would be our mentor in the project (Shelly met him and a whole bunch of the Hoodie gang at .concat() and said they were absolutely lovely). We started working on our personal student but quickly got stuck on writing "About Me"s. *Did everyone else feel awkward answering that payment question, or was it just me?* We decided it would be best if we finished answering our individual parts another day by ourselves and proceeded to sort out other things, like our current availability  schedules so we could keep meeting up to work on stuff together, our team twitter and e-mail account, etc... 

All in all, it was a very productive day and I'm glad that Shelly was able to come out here. We even thought of a bunch of fun things, such as the possibility of coming here on Fridays to work on our project/BBQ.

~Pilar