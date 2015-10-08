---
title: "New beginnings: Embracing Hugo"
date: 2015-10-07
comments: true
sharing: true
footer: true
categories: [tech, hugo, octopress]
author: "Ramjee Ganti"
---
Two years back around the same time, I moved my then defunct site to s3 building on [octopress](http://octopress.org). This [post]({{< ref "post/2013-10-30-ramjeeganti-dot-com-on-s3.md" >}}) details my experience with the beginnings. This post details my experience with this whole new (at-least to me) of building sites.

* In the initial days octopress served it's purpose. Before octopress my major pain had been in making sure the site was up and running without my intervention. S3 and octopress addressed that issue wonderfully well. I never had to worry if my site would go down, if I have to do an upgrade, if I have to renew my hosting and so on.
* One more advantage has been the ridiculously low cost of maintenance. A few dollars an year.
* I also migrated many of my earlier posts from some of the many blogs I used to maintain to this domain with ease.
* It allowed me to focus on my writing than on small niggling issues with formatting.

The above begets the question, why did I then move away from octopress(I continue to use s3 for hosting).

* Even though octopress was great platform, I never could get my head around how it worked.
* I like having clear separation of concerns and octopress theming and content were very tightly bound. Switching to another theme was a huge effort.
* Octopress 3 was going to address most of these issues, but it has been in the making for over an year.

All the above gave me an excuse to neglect writing and inadvertently let this site rot (just like millions of others).

A few months ago, when I looking to revive my efforts to write, I was looking for an octopress alternative. This had to meet the following requirements.

* Separation of concerns, presentation(theme) and content(posts/pages) should not be tightly coupled. I should be able to change the theme with little to no effort.
* Decent inbuilt features but very lightweight.
* Strongly opinionated in the way it advocates stuff, but has the flexibility to build just more than blogs.

The above led me to [Hugo](https://gohugo.io). I liked it enough to experiment and within no time was up and running. A few minor hiccups were addressed thanks to some blog posts and basic but functional documentation. In the process I also setup auto deploy using [Codeship](https:codeship.com). Now I just have to write, commit and push and the post is updated on the site.

The following posts helped me a lot in getting to speed:

* http://nathanleclaire.com/blog/2014/12/22/migrating-to-hugo-from-octopress/
* http://zackofalltrades.com/notes/2014/05/hugo-from-scratch/
* http://loads.pickle.me.uk/2015/07/25/hugo-s3-hosting/

Lets hope I sustain this momentum of writing often.