# FreePDX Blog

Decided to use Jekyll (Links below).  The template is the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes) which looks like a good starting poing for a basic blog.

The goal is to brush up on front-end web design from scratch, but also to showcase some projects I've been working on that are of interest.  Using Jekyll gives me exposure to Ruby, which was also a goal. 

## Development platform

Since I have a ThinkPad, I'm running Windows.  To get Jekyll up and running, I'm using [WSL2](https://docs.microsoft.com/en-us/windows/wsl/install-win10) 
- I'm hosting on [GitHub Pages](https://pages.github.com/) for now, since it's really easy to get that up and running, and backed by Git version controlling.  It's pretty nice.
- Getting Jekyll/Ruby/WSL to cooperate with each other was a bit of a head-scratcher, but it's not too hard.  There are a lot of WSL specific sites with info, but none really worked well.  In the end, I installed Ubuntu 20.04 in WSL2 from the Microsoft Store, and followed a [Ubuntu Guide](https://www.digitalocean.com/community/tutorials/how-to-set-up-a-jekyll-development-site-on-ubuntu-20-04)
- There's a special trick that I haven't seen documented - you MUST run the Ubuntu shell as administrator, otherwise you will fail running the site locally with `bundle exec jekyll serve`

---

## Troubleshooting

If you have a question about using Jekyll, start a discussion on the [Jekyll Forum](https://talk.jekyllrb.com/) or [StackOverflow](https://stackoverflow.com/questions/tagged/jekyll). Other resources:

- [WSL2 Announcement](https://devblogs.microsoft.com/commandline/announcing-wsl-2/)
- [Ruby 101](https://jekyllrb.com/docs/ruby-101/)
- [Setting up a Jekyll site with GitHub Pages](https://jekyllrb.com/docs/github-pages/)
- [Configuring GitHub Metadata](https://github.com/jekyll/github-metadata/blob/master/docs/configuration.md#configuration) to work properly when developing locally and avoid `No GitHub API authentication could be found. Some fields may be missing or have incorrect data.` warnings.
