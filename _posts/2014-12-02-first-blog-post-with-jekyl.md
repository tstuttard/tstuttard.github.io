---
layout: default
title: First Blog Post using Jekyl
---

I have been wanted to start writing my own blog for quite a while now but have been too lazy to find a 
blogging platform, find hosting for it and then set everything up.

I googled `best blogging platform for programmers`.

I clicked on a hacker news link and the general consensus for simplicity was use github pages with jekyl
and this is me giving it a go.

#### Setting up Github Pages

I created a repository with the name tstuttard.github.io, note that it must be *`yourgithubusername.github.io`*

I then cloned the new repo locally with `git clone git@github.com:tstuttard/tstuttard.github.io.git`,
created an index.html file and finally committed my initial changes and pushed it to the master branch.
 
Github Pages uses the master branch's file for the static website so when you push
any changes to the master branch they should be reflected at http://yourgithubusername.github.io.

It then takes around 10-15 minutes for your site to be viewable, which made me think that I had somehow fucked up
this really simple process. After refreshing twice every minute it was then finally up showing my index.html page.

#### Setting up Jekyl

To use Jekyl you need to ensure you have ruby installed on your local machine.
Check this with `ruby --version`

I had ruby installed already so next up was creating a gemfile which lists what gem's will be included in your project.
Ruby gem's are packages written and shared by other members of the Ruby community and gem's can have dependencies
on other gems.
It allows for less wheels being reinvented and more collaboration.

In my Gemfile I had two lines:

`
source 'https://rubygems.org'
gem 'github-pages'
`

I then installed bundler which is used as a gem management tool and installs your gems in one location on your machine.

I then ran `bundle install` which installs all the required gems in my Gemfile.

I created some folders and additional layout files that jekyl and github-pages relies on, pushed them to the master
branch and the new changes were now showing on my site.
I haven't gone into detail about the files jekyl and github pages uses as they would make this post even longer.
You can find information about this on [Jekyl's Website](http://jekyllrb.com/)
and [Github Page's Jekyl Tutorial](https://help.github.com/articles/using-jekyll-with-pages/).

Boom! First Post Done! Comment, Like and Subscribe for more of this. *(Still to be implemented)* 



