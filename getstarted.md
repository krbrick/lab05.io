---
layout: page
---
# Build your website in 3 steps

There's a very easy way to use this theme, and there's a hard way. For most people (including myself!), I suggest going the easy route. If you're an advanced user and want to tinker with the hard way (using ruby gems), then [skip the easy way](https://github.com/daattali/beautiful-jekyll#the-hard-way-using-ruby-gems) if you know what you're doing.

## The easy way (recommended!)

Getting started is *literally* as easy as 1-2-3 :smile:

Scroll down to see the steps involved, but here is a 40-second video just as a reference as you work through the steps. If you don't already have a [GitHub account](https://github.com/join), you'll need to sign up.

![Installation steps](assets/img/install-steps.gif)
<ul>
<div class="gs-section-01" markdown="1">
<li>Fork this project
Fork this project by clicking the <strong>Fork</strong> button at the top right corner of this page. Forking means that you now copied this entire project and all the files into your account.
</div>

<div class="pretty-text" markdown = "1">
<style>
.pretty-text {
  margin-top: 100px;
  margin-bottom: 100px;
  padding-left: 30px;
  padding-right: 30px;
  text-align: justify;
}
<li>Rename the project to `<yourusername>.github.io`
Click on __*Settings*__ at the top (the cog icon) and on that page you'll have an option to rename the project (*Repository name*). This will create a website with the **Beautiful Jekyll** template that will be available at `https://<yourusername>.github.io` within a couple minutes (check out the [FAQ](https://beautifuljekyll.com/faq/#custom-domain) if you want to use a different project name). If after a few minutes your website is still not ready, try making any edit to any file, just to force GitHub to re-build your site.
</style>
</div>

<li>Customize your website settings

Edit the `_config.yml` file to change any settings you want. To edit the file, click on it to view the file and then click on the pencil icon to edit it (watch the video tutorial above if you're confused).  The settings in the file are self-explanatory and I added comments inside the file to help you understand what each setting does. Any line that begins with a hashtag (`#`) is a comment, and the other lines are actual settings.

Note that in the video above I only edited one setting in the `_config.yml` file. **You should actually go through the rest of the settings as well. Don't be lazy, go through all the settings!**

<li>Congratulations! You have a website!
</ul>
After you save your changes to the `_config.yml` file (by clicking on *Commit changes* as the video tutorial shows), your website should be ready in a minute or two at `https://<yourusername>.github.io`. Every time you make a change to any file, your website will get rebuilt and should be updated in about a minute or so. Your website will be initialized with several sample blog posts and a couple other pages.

Note that this was the easy way to *create* your website, but it does come at a cost: when Beautiful Jekyll gains new features in the future, *updating* your website to include all the latest features is cumbersome. See the [FAQ](https://beautifuljekyll.com/faq/#updating) for help with upgrading in the future.

<style>
.pretty-text {
  margin-top: 100px;
  margin-bottom: 100px;
  padding-left: 30px;
  padding-right: 30px;
  text-align: justify;
}
.pretty-text p {
  line-height: 1.8;
  padding-bottom: 80px;
  }
.gs-section-01 h3 { 
     color: red }

.gs-section-01 p {
     font-size: 30px;
}
</style>
