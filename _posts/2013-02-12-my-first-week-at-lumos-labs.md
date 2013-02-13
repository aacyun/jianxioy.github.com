---
layout: post
title: My First Week At Lumos Labs
excerpt: It's been a little more than two weeks since I relocated to <a href="http://en.wikipedia.org/wiki/San_Francisco">San Francisco</a> and about a week since I started working at <a href="http://www.lumosity.com/">Lumos Labs</a>. During that time, I've met countless fun and intelligent individuals and, I must admit, am having an exceptionally enjoyable time at my job thus far.
description: It's been a little more than two weeks since I relocated to San Francisco and about a week since I started working at Lumos Labs. During that time, I've met countless fun and intelligent individuals and, I must admit, am having an exceptionally enjoyable time at my job thus far.
category: blog
---
It's a well-known fact that time passes quickly when you're having fun, and boy, is time zooming by. My first week at [Lumos Labs](http://www.lumosity.com/) went by really fast. There was another software engineer who was starting on the same day as I was so we got introduced to each other pretty quickly. We would be hanging out with each other for the most part of the initial few days regarding administrivia.

Day one was mostly administrivia, a day filled with meetings. First up was my awesome boss, Chris, who is the Lead Engineer for the Rails Team. Lumos Labs is still pretty small (approximately 80 people) and we don't really have managerial positions but we are easing into that stage where some middle management is necessary and Chris is part of that transition. He basically gave me a brief overview of the engineering team in Lumos Labs and what my role would be on the team. I was to be working on the payments system with another Software Engineer, Anthony, who interviewed me last December, and a Product Manager, Matt. I also met my Lab Partner (the name of Lumos' fancy buddy system), Pam, a Marketing Content Manager, who took me out to arguably the best dim sum restaurant in San Francisco, [Yank Sing](http://www.yanksing.com/). I must remember to get her to take me out to lunch more often, she knows where all the good eats are! After that, we met with Lumos' Office and Events Manager, Amanda, who basically introduced us to how the logistics work at Lumos. She takes great care of us and provides us with all the necessary tools so that we're happy employees. I list some of the great perks of being an employee at Lumos later on in the article. The rest of the day was spent setting up my development station with JaMile, our awesome IT Administrator who definitely goes the extra mile in doing so. Setting up my station went by without much problems save some [zsh](http://zsh.sourceforge.net/) path issues due to me using my own [dotfiles](https://github.com/jianxioy/dotfiles). In the end, we managed to get a fresh box with [rbenv](https://github.com/sstephenson/rbenv) going along with the relevant repositories with some recipes from [Chef](https://github.com/opscode/chef). We get licenses for all our favorite development tools such as [Sublime Text 2](http://www.sublimetext.com/) and [Tower](http://www.git-tower.com/) (we even get [RailsCast Pro](http://railscasts.com/pro)) as well as whatever hardware we need to make our work more efficient. Check out the huge [Dell](http://www.dell.com/) monitor at my workstation:

<div class="about-img">
<a href="/static/images/lumos/setup.jpg"><img class="about-image" src="/static/images/lumos/setup.jpg" alt="My devstation." title="My devstation."></a>
</div>

The next day we met with Missy, the Director of HR. She explained to us in great detail about the employee benefits and other administrivia. I spent most of the week pairing with Anthony on small tasks where he would slowly introduce me to the architecture of the payments system and various [Ruby Gems](https://rubygems.org/) in the system. I made my first check in on Wednesday, modifying one of the in-house gems and my first deploy into production on Thursday. It felt good. Anthony introduced me to the basic deploy workflow for the Rails Team which is pretty standard in software engineering. It looks something like this:

1. A developer is designated a [Trello](https://trello.com/) card.
2. Developer creates a local branch and works on the issue. Once the issue has been completed, push the branch to remote.
3. Create a pull request on [GitHub](https://github.com/) and await code review.
4. Once reviewed and a thumbs up has been given, merge.
5. After merging, deploy on staging server. Ensure all tests pass before moving on, if they do not, fix the errors and try again.
6. If all tests pass on the staging server, we are ready to deploy into production.

I'm still working my way around the system and my programming is a little rusty, but I'm getting there. I haven't blown anything up yet so I guess that is a good sign. So far, so good. All I know is that Lumos is a really awesome place to work. Why? Well, let me count the ways:

#### 1. Great Culture

I can't emphasize how important this is in a working environment. So far everyone I've met at Lumos is smart and fun to hang out with. The kinds of people at Lumos are diverse and have varied interests and its atmosphere is extremely collegiate and chill. The founder used to work on Wall Street and he wanted a culture that was basically the negation of Wall Street's culture. Needless to say, he is doing an excellent job cultivating such a culture. I'm thoroughly enjoying working with the people on my team and socializing with them over meals and after hour activities. People at Lumos work hard and play harder.

#### 2. Food, Glorious Food!

At Lumos, we are constantly being fed. You can have all three meals if you wish. I usually have breakfast at home, lunch and dinner at work since I tend to stay late. We have two refridgerators chock full of healthy, organic food from [Bi-Rite Market](http://www.biritemarket.com/), an upscale grocery store in San Francisco (I've never had such delicious microwave meals until I tried the ones from Bi-Rite), a walk-in closet-sized snack bar, two fridges for beverages, one of them alcoholic and the other non-alcoholic, as well as a liquor bar (I'm talking a ton of hard liquor). If there's something you'd like, just add it to the list and they will stock the kitchen for you. Personally, the way to my heart is food. If I am well fed, I'm your bitch. Seriously, I don't mind working if my meals are taken care of. Besides, socializing over meals with fellow coworkers is great.

#### 3. Amenities

We have a laundry service in the office where laundry is picked up once a week and returned clean the next. This is particularly helpful since I can just dump my smelly gym clothes in the collection area after working out and then collect them the next day. Very convenient. The office space is also great. It's the standard Silicon Valley [open-office](http://en.wikipedia.org/wiki/Open_plan) concept. There are comfortable couches and nice office capsules which you can sleep... I mean work in! It's very open and has a lot of light, reminds me a little of the café area in Gates.

#### 4. Company Parties, Events and Trips

The company went to [Hawaii](http://en.wikipedia.org/wiki/Hawaii) and another location last year and I am insanely jealous. Tonight, on my second week, there was a party (I'll take it as an early birthday celebration for me, hehe) at [Chambers](http://chambers-sf.com/). I can't wait to see what else the Culture Team has in store for us over the course of the year.

#### 5. Recreation

We have a ping-pong table, board games, an Xbox, a foosball table and a shuffleboard table. If those do not appeal to you, you can always eat, drink and be merry. If you feel like you've been eating too much, you also get free gym membership to [Sports Club LA](http://sf.sportsclubla.com/), arguably the best gym in the area. It's two blocks away from the office. Check out its sick promotional video:

<iframe width="640" height="360" src="http://www.youtube.com/embed/_1hROYFfxuM" frameborder="0" allowfullscreen></iframe>

I could continue but I bet you're tired of me waxing lyrical about the company. I was contemplating taking pictures of the office but maybe I will do so after ensuring I've not violated any NDAs. It has only been a week but I'm stoked to be working on a product that is one of its kind as well as utilize scientific research to improve people's lives. I look forward to the exciting projects to come and make an impact in people's lives. Hopefully I can be what the following picture (taken at the party) suggests I be:

<div class="about-img">
<a href="/static/images/lumos/amazing.jpg"><img class="about-image" src="/static/images/lumos/amazing.jpg" alt="Be amazing." title="Be amazing."></a>
</div>

**Thanks** to [Chris Friedrich](http://www.linkedin.com/pub/chris-friedrich/3/973/386), [Anthony Zacharakis](http://www.linkedin.com/pub/anthony-zacharakis/16/863/85), [Jason Chen](http://visualchen.com/), [Ming Han Teh](http://hanworks.tumblr.com/), [Hao Yee Chan](https://www.facebook.com/haoyee), [Kevin Bao](https://www.facebook.com/kzbao) and [Nikhil Tibrewal](https://www.facebook.com/nikhil.tibrewal.9) for proofreading this blogpost. Feel free to discuss this post on [Hacker News](http://news.ycombinator.com/item?id=5211933), chat about this with me via [email](mailto:daryl@darylyeo.com) or [Twitter](http://twitter.com/jianxioy). I might add some pictures in the near future.
