# techtipbites-tk-website-static

[![Netlify Status](https://api.netlify.com/api/v1/badges/7792228c-7bf4-4823-b9da-5f974b5fa04b/deploy-status)](https://app.netlify.com/sites/techtipbites/deploys)

~~placeholder~~ Static  blogging website for techtipbites.tk

I was looking to setup a static website for *FREE* to write blogs. Let me know how you'll like/dislike it.

### <u>What:</u>

This is a static website powered by [Hexo](https://hexo.io/). My choice for the theme is [Cactus](https://github.com/probberechts/hexo-theme-cactus) with it's [Dark varient](https://probberechts.github.io/hexo-theme-cactus/cactus-dark/public).

If you want to create one of your own. Checkout the blog "" with template source at [git:hexo-static-blog](https://github.com/turn-a-round/hexo-static-blog.git)

### <u>Developer Friendly Details:</u>

##### <u>How To:</u>



##### <u>Branch Details:</u>

###### master

[***Warning***]This branch contains the actual live site.  

The steps to add a new page/post/article are:

1. Always create a *post/<title>* or *page/<title>* or *article/<title>* or *topic/<topic-name>*  branch from master
2. Put your page/post/article(s)/topic-post(s) in that branch
3. Check thoroughly by running `npm run server` in your local system
4. Create a Pull Request (PR) and let the administrator know your intentions.
5. Please don't try to serve the whole platter at once. As the name suggests, we're here to take a *<u>tip</u>* and/or a *<u>bite</u>* at a time.

###### preview

This branch is the experimental ground for new pages, posts, structures, themes. Create a new *feature* branch from it if necessary.

###### develop

If anything is feasible and lucrative enough to pass the *preview* phase. It'll be merged to *develop* & then will start its journey towards ***master***.