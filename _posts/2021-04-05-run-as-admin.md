---
title: "FreePDX Blog - getting it started"
categories:
  - Blog
tags:
  - technology
---
I'm creating a blog, and I'd like to accomplish a few things with it:

- **Learn Stuff** - I've spent most of my programming career either on Windows Desktop development, and I wanted to do some front-end personal devleopment.  Writing a blog from scratch accomplishes that.
- **Explore technology** - How ~~bad~~ difficult can Node.js be?  TypeScript? Sure!  Angular, BootStrap -- all the things.  There are a million ways solve a problem or deliver a project, and I want to see which ones are useful, and which are painful so that I can be better informed about how I go about solving problems moving forward.
- **Document Projects** - I work on A. Lot. Of. Projects.  Along the way, I search a lot of things, and learn a massive amount.  I'm a semi-professional [Builder Of Things](https://www.theimagedepot.com/p894178974) and I hand-build a [Cabin](https://www.theimagedepot.com/p24182796).  I don't always get it right the first time, but if I can put information out there that helps someone, once, that's worth it.  I'm always improving, always getting better.
- **Showcase what I know** - I'm an excellent problem solver and project manager.  I plan on document some problems that have been (and will be!) solved.  Seriously, it's why you want to hire me.

## Development platform

Since I have a ThinkPad, I'm running Windows.  To get Jekyll up and running, I'm using [WSL2](https://docs.microsoft.com/en-us/windows/wsl/install-win10) 
- I'm hosting on [GitHub Pages](https://pages.github.com/) for now, since it's really easy to get that up and running, and backed by Git version controlling.  It's pretty nice.
- Getting Jekyll/Ruby/WSL to cooperate with each other was a bit of a head-scratcher, but it's not too hard.  There are a lot of WSL specific sites with info, but none really worked well.  In the end, I installed Ubuntu 20.04 in WSL2 from the Microsoft Store, and followed a [Ubuntu Guide](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-jekyll-development-site-on-ubuntu-20-04)
- There's a special trick that I haven't seen documented - you MUST run the Ubuntu shell as administrator, otherwise you will fail running the site locally with `bundle exec jekyll serve`
<img src="/assets/images/RunAsAdmin.jpg" alt="Run As Admin screenshot" width="500"/>
