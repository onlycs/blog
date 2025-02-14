---
title: Creating the Blog
---
# 1. Deciding I wanted a blog
One day, I came across the blog of vaxry, the lead developer of Hyprland, and I thought to myself, "you know what would be cool? A blog of your own!" And then I sat on that idea for over a year because I'm lazy as fuck.

# 2. Finding my blogging software
Early yesterday morning, I got some of that juicy early-morning motivation and decided to actually do some research on how to make a blog. I'm impartial to Obsidian, I use it to take all of my notes currently. According to the internet, I would have to take markdown and turn it into HTML. That sounded too complicated to make on my own—[I already made my own programming language, and it was hell](https://github.com/onlycs/jasmine)—so my friends at Reddit said I either needed to pay [almost $10 per month](https://obsidian.md/publish), or look for a static site generator. I decided to go for the latter because I'm poor.

After [some](https://gohugo.io/) [more](https://www.reddit.com/r/rust/comments/162e40h/obsidiangarden_a_static_site_generator_for/) [dead ends](https://astro.build/)  I found [quartz](https://quartz.jzhao.xyz/) and it was good, actually. More importantly, I could change the colors (most default dark themes are too dark for me, I don't know what to say). After cloning their git repo, and shamelessly copying Adwaita's color palette I was good to continue to...

# 3. CI
I was expecting this to be a pain but it wasn't actually. This might be the best CI experience I've ever had, and that's saying a lot, 'cause I've had to make [so](https://github.com/onlycs/attendance/actions/) [many](https://github.com/onlycs/fluidsim/actions) [workflows](https://github.com/onlycs/oreobot/actions) over the years, and setting up any one of them were absolute hell. Turns out, [quartz provides](https://quartz.jzhao.xyz/hosting#github-pages) a copy-pastable Github Actions Workflow File which worked, actually

# 4. Now I have a blog
I don't really know what to do with this. I'm probably not going to edit posts I make unless there are typos or something. I think it might be cool to keep an archive of the stuff I do with my life.