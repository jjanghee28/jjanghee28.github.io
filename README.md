[![](https://i.imgur.com/zNBkzj1.png)](https://beautifuljekyll.com/plans/)

# Beautiful Jekyll

[![xscode](https://img.shields.io/badge/Available%20on-xs%3Acode-blue?style=?style=plastic&logo=appveyor&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABACAMAAACdt4HsAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAAZQTFRF////////VXz1bAAAAAJ0Uk5T/wDltzBKAAAAlUlEQVR42uzXSwqAMAwE0Mn9L+3Ggtgkk35QwcnSJo9S+yGwM9DCooCbgn4YrJ4CIPUcQF7/XSBbx2TEz4sAZ2q1RAECBAiYBlCtvwN+KiYAlG7UDGj59MViT9hOwEqAhYCtAsUZvL6I6W8c2wcbd+LIWSCHSTeSAAECngN4xxIDSK9f4B9t377Wd7H5Nt7/Xz8eAgwAvesLRjYYPuUAAAAASUVORK5CYII=)](https://xscode.com/daattali/beautiful-jekyll)
[![Gem Version](https://badge.fury.io/rb/beautiful-jekyll-theme.svg)](https://badge.fury.io/rb/beautiful-jekyll-theme)

> *Created by [Dean Attali](https://deanattali.com)* &middot; [Demo](https://beautifuljekyll.com/)

**Beautiful Jekyll** is a ready-to-use template to help you create a beautiful website quickly. Perfect for personal sites, blogs, or simple project websites.  [Check out a demo](https://beautifuljekyll.com) of what you'll get after just two minutes.  You can also look at [my personal website](https://deanattali.com) to see it in use, or see examples of websites other people created using this theme [below](#showcased-users-success-stories).

**If you enjoy Beautiful Jekyll, please consider [supporting me](https://github.com/sponsors/daattali) for over 5 years of development (and to unlock rewards!) ❤**

## Table of contents

- [Features](#features)
- [Sponsors 🏆](#sponsors)
- [**Build your website in 3 steps**](#build-your-website-in-3-steps)
- [Plans](#plans)
- [Add your own content](#add-your-own-content)
- [Customizing parameters for each page](#customizing-parameters-for-each-page)
- [Supported parameters](#supported-parameters)
- [Showcased users (success stories!)](#showcased-users-success-stories)
- [FAQ and support](#faq-and-support)
- [Credits and contributions](#credits)

# Features

Check out [*What's New?*](https://beautifuljekyll.com/updates/) to see the latest features.

- **SIMPLE**: The primary goal of Beautiful Jekyll is to allow literally *anyone* to create a website in a few minutes.
- **Modern**: Uses the latest best practices and technologies to achieve nearly perfect scores on Google Chrome's Audit.
- **Mobile-first**: Designed to look great on both large-screen and small-screen (mobile) devices.
- **Highly customizable**: Many personalization settings such as changing the background colour/image, adding a logo.
- **Flexible usage**: Use Beautiful Jekyll directly on GitHub or via a Ruby gem - choose the best [development method](#build-your-website-in-3-steps) for you.
- **Battle-tested**: By using Beautiful Jekyll, you'll be joining 50,000+ users enjoying this theme since 2015.
- **SEO and social media support**: Customize how your site looks on Google and when shared on social media.
- **Comments support**: Add comments to any page using either [Disqus](https://disqus.com/), [Facebook comments](https://developers.facebook.com/docs/plugins/comments), [Utterances](https://utteranc.es/), or [Staticman](https://staticman.net).
- **Tags**: Any blog post can be tagged with keywords, and an index page showing all the tags is automatically generated.
- **Analytics**: Easily integrate Google Analytics, or other analytics platforms, to track visits to your website.
- **Photos support**: Any page can have a cover photo around its title, and any blog post can have an associated image.
- **RSS**: An RSS feed is automatically created, so you can even host a podcast easily with Beautiful Jekyll.

<h2 id="sponsors">Sponsors 🏆</h2>

> There are no sponsors yet

[Become the first sponsor for Beautiful Jekyll and unlock special rewards\!](https://github.com/sponsors/daattali/sponsorships?tier_id=39856)

# Build your website in 3 steps

There's a very easy way to use this theme, and there's a hard way. For most people (including myself!), I suggest going the easy route. If you're an advanced user and want to tinker with the hard way (using ruby gems), then [skip the easy way](https://github.com/daattali/beautiful-jekyll#the-hard-way-using-ruby-gems) if you know what you're doing.

## The easy way (recommended!)

Getting started is *literally* as easy as 1-2-3 :smile:

Scroll down to see the steps involved, but here is a 40-second video just as a reference as you work through the steps. If you don't already have a [GitHub account](https://github.com/join), you'll need to sign up.

![Installation steps](assets/img/install-steps.gif)

### 1. Fork this project

Fork this project by clicking the __*Fork*__ button at the top right corner of this page. Forking means that you now copied this entire project and all the files into your account.

### 2. Rename the project to `<yourusername>.github.io`

Click on __*Settings*__ at the top (the cog icon) and on that page you'll have an option to rename the project (*Repository name*). This will create a website with the **Beautiful Jekyll** template that will be available at `https://<yourusername>.github.io` within a couple minutes (check out the [FAQ](#faq-and-support) if you want to use a different project name). If after a few minutes your website is still not ready, try making any edit to any file, just to force GitHub to re-build your site.

### 3. Customize your website settings

Edit the `_config.yml` file to change any settings you want. To edit the file, click on it to view the file and then click on the pencil icon to edit it (watch the video tutorial above if you're confused).  The settings in the file are self-explanatory and I added comments inside the file to help you understand what each setting does. Any line that begins with a hashtag (`#`) is a comment, and the other lines are actual settings.

### 4. Congratulations! You have a website!

After you save your changes to the `_config.yml` file (by clicking on *Commit changes* as the video tutorial shows), your website should be ready in a minute or two at `https://<yourusername>.github.io`. Every time you make a change to any file, your website will get rebuilt and should be updated in about a minute or so. Your website will be initialized with several sample blog posts and a couple other pages.

Note that in the video above I only edited one setting in the `_config.yml` file. **You should actually go through the rest of the settings as well. Don't be lazy, go through all the settings :)**

Also note that this was the easy way to *create* your website, but it does come at a cost: when Beautiful Jekyll gains new features in the future, *updating* your website to include all the latest features is cumbersome. See the [FAQ](#faq-and-support) for help with upgrading in the future.

## The hard way (using ruby gems)

If you followed the easy method above, then you already have your site and you can skip this section! If you want to use Beautiful Jekyll as a ruby gem instead, follow the [advanced installation instructions](https://beautifuljekyll.com/getstarted/#install-steps-hard). This is harder to set up initially, but it makes it super easy to keep your site up to date with Beautiful Jekyll when more features are added in the future.

# Plans

Beautiful Jekyll is, and always will be, free. But if you want to remove the Beautiful Jekyll ad from your website, use a Dark Mode skin, or unlock other special rewards, [check out the different plans](https://beautifuljekyll.com/plans).

# Add your own content

To add pages to your site, you can either write a markdown file (`.md`) or you can write an HTML file. It's much easier to write markdown than HTML, so I suggest you do that ([here's a great tutorial](https://markdowntutorial.com/) if you need to learn markdown in 5 minutes).

To see an example of a markdown file, click on any file that ends in `.md`, for example [`aboutme.md`](./aboutme.md). On that page you can see some nicely formatted text (there's a word in bold, a link, a few bullet points), and if you click on the pencil icon to edit the file, you'll see the markdown code that generated the pretty text. Very easy!

In contrast, look at [`tags.html`](./tags.html). That's how your write HTML - not as pretty. So stick with markdown if you don't know HTML.

Any markdown or HTML file that you create will be available on your website under `https://<yourusername>.github.io/<pagename>`. For example, if you create a file `about.md` (or `about.html`) then it'll exist at `https://<yourusername>.github.io/about`.

Files you create inside the [`_posts`](./_posts) directory will be treated as blog entries. You can look at the existing files there to get an idea of how to write blog posts. Note the format of the blog post files - they must follow the naming convention of `YEAR-MONTH-DAY-title.md`. After you successfully add your own post, you can delete the existing files inside [`_posts`](./_posts) to remove the sample posts, as those are just demo posts to help you learn.

# Customizing parameters for each page

**One last important thing**: In order to have your new pages use this template and not just be plain HTML pages, **you must add [YAML front matter](https://jekyllrb.com/docs/front-matter/) to the top of each page**:


```
---
---
```

This is where you'll be able to give each page some extra parameters (such as a title, a subtitle, an image, etc - [below is a list of all parameters](#supported-parameters)). Add any parameters you want between these two dashed lines, for example:

```
---
title: Contact me
subtitle: Here you'll find all the ways to get in touch with me
---
```

If you don't want to use any parameters on a page, you still need to use the two dashed lines. If you don't, then your file will be shown as-is without the Beautiful Jekyll template.

You can look at the top of [`aboutme.md`](https://raw.githubusercontent.com/daattali/beautiful-jekyll/master/aboutme.md) as an example.

**Important takeaway: ALWAYS add the YAML front matter, which is two lines of three dashes, to EVERY page. If you have any parameters, they go between the two lines.**

# Supported parameters

Below is a list of the parameters that Beautiful Jekyll supports (any of these can be added to the YAML front matter of any page). Remember to also look in the `_config.yml` file to see additional site-wide settings.

## Main parameters

These are the basic YAML parameters that you are most likely to use on most pages.

Parameter   | Description
----------- | -----------
title       | Page or blog post title
subtitle    | Short description of page or blog post that goes under the title
tags        | List of tags to categorize the post. Separate the tags with commas and place them inside square brackets. Example: `[personal, analysis, finance]`
cover-img   | Include a large full-width image at the top of the page. You can either provide the path to a single image (eg. `"/path/to/img"`) , or a list of images to cycle through (eg. `["/path/img1", "/path/img2"]`). If you want to add a caption to an image, then the image should be provided as `{"/path/to/img" : "Caption of image"}`.
thumbnail-img | For blog posts, if you want to add a thumbnail that will show up in the feed, use `thumbnail-img: /path/to/image`. If no thumbnail is provided, then `cover-img` will be used as the thumbnail. You can use `thumbnail-img: ""` to disable a thumbnail.
comments    | If you want do add comments to a specific page, use `comments: true`. Comments only work if you enable one of the comments providers (Facebook, disqus, staticman, utterances) in `_config.yml` file. Comments are automatically enabled on blog posts but not on other pages; to turn comments off for a specific post, use `comments: false`.

## Parameters for SEO and social media sharing

These parameters let you control what information shows up when a page is shown in a search engine (such as Google) or gets shared on social media (such as Twitter/Facebook).

Parameter   | Description
----------- | -----------
share-title | A title for the page. If not provided, then `title` will be used, and if that's missing then the site title (from `_config.yml`) is used.
share-description | A brief description of the page. If not provided, then `subtitle` will be used, and if that's missing then an excerpt from the page content is used.
share-img   | The image to show. If not provided, then `cover-img` or `thumbnail-img` will be used if one of them is provided.

## Less commonly used parameters

These are parameters that you may not use often, but can come in handy sometimes.

Parameter   | Description
----------- | -----------
readtime    | If you want a post to show how many minutes it will take to read it, use `readtime: true`.
show-avatar | If you have an avatar configured in the `_config.yml` but you want to turn it off on a specific page, use `show-avatar: false`.
social-share | By default, every blog post has buttons to share the page on social media. If you want to turn this feature off, use `social-share: false`.
nav-short   | By default, the navigation bar gets shorter after scrolling down the page. If you want the navigation bar to always be short on a certain page, use `nav-short: true`
gh-repo   | If you want to show GitHub buttons at the top of a post, this sets the GitHub repo name (eg. `daattali/beautiful-jekyll`). You must also use the `gh-badge` parameter to specify what buttons to show.
gh-badge  | Select which GitHub buttons to display. Available options are: [star, watch, fork, follow]. You must also use the `gh-repo` parameter to specify the GitHub repo.
layout      | What type of page this is (default is `post` for blog posts and `page` for other pages). See _Page types_ section below for more information.

## Advanced parameters

These are advanced parameters that are only useful for people who need very fine control over their website.

Parameter   | Description
----------- | -----------
footer-extra | If you want to include extra content below the social media icons in the footer, create an HTML file in the `_includes/` folder (for example `_includes/myinfo.html`) and set `footer-extra` to the name of the file (for example `footer-extra: myinfo.html`). Accepts a single file or a list of files.
before-content | Similar to `footer-extra`, but used for including HTML before the main content of the page (below the title).
after-content | Similar to `footer-extra`, but used for including HTML after the main content of the page (above the footer).
head-extra   | Similar to `footer-extra`, but used if you have any HTML code that needs to be included in the `<head>` tag of the page.
language    | HTML language code to be set on the page's &lt;html&gt; element.
full-width  | By default, page content is constrained to a standard width. Use `full-width: true` to allow the content to span the entire width of the window.
js          | List of local JavaScript files to include in the page (eg. `/assets/js/mypage.js`)
ext-js      | List of external JavaScript files to include in the page (eg. `//cdnjs.cloudflare.com/ajax/libs/underscore.js/1.8.2/underscore-min.js`). External JavaScript files that support [Subresource Integrity (SRI)](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) can be specified using the `href` and `sri` parameters eg.<br/>`href: "//code.jquery.com/jquery-3.1.1.min.js"`<br/>`sri: "sha256-hVVnYaiADRTO2PzUGmuLJr8BLUSjGIZsDYGmIJLv2b8="`
css         | List of local CSS files to include in the page
ext-css      | List of external CSS files to include in the page. External CSS files using SRI (see `ext-js` parameter) are also supported.

## Page types

- **post** - To write a blog post, add a markdown or HTML file in the `_posts` folder. As long as you give it YAML front matter (the two lines of three dashes), it will automatically be rendered like a blog post. Look at the existing blog post files to see examples of how to use YAML parameters in blog posts.
- **page** - Any page outside the `_posts` folder that uses YAML front matter will have a very similar style to blog posts.
- **home** - The home layout is meant to act as the homepage of your blog posts - it will display all your blog posts, sorted from newest to oldest. A file using the `home` layout must be named `index.html` (not `index.md` or anything else!).
- **minimal** - If you want to create a page with minimal styling (ie. without the bulky navigation bar and footer), assign `layout: minimal` to the YAML front matter.
- If you want to completely bypass the template engine and just write your own HTML page, simply omit the YAML front matter. Only do this if you know how to write HTML!

# Showcased users (success stories!)

If you'd like to showcase yourself and join this list, [upgrading to the Individual plan](https://github.com/sponsors/daattali/sponsorships?&tier_id=7362) will give you that publicity plus some other rewards!

## Project/company websites

| Website | Description |
| :------ |:----------- |
| [repidemicsconsortium.org/](https://www.repidemicsconsortium.org/) | R Epidemics Consortium |
| [vaccineimpact.org](https://www.vaccineimpact.org/) | Vaccine Impact Modelling Consortium |
| [derekogle.com/fishR](http://derekogle.com/fishR/) | Using R for Fisheries Analyses |
| [joecks.github.io/clipboard-actions](http://joecks.github.io/clipboard-actions/) | Clipboard Actions - an Android app |
| [deanattali.com/shinyjs](http://deanattali.com/shinyjs/) | shinyjs - an R package |
| [blabel.github.io](http://blabel.github.io) | Library for canonicalising blank node labels in RDF graphs |
| [reactionic.github.io](http://reactionic.github.io) | Create iOS and Android apps with React and Ionic |
| [ja2-stracciatella.github.io](http://ja2-stracciatella.github.io) | Jagged Alliance 2 Stracciatella |
| [ddocent.com](http://ddocent.com/) | RADSeq Bioinformatics and Beyond |
| [guitarlessons.org](https://www.guitarlessons.org/) | Free online guitar lessons for all |
| [terremotocentroitalia.info](https://www.terremotocentroitalia.info/) | Information about the 2016 Italy earthquake |


## Personal websites

| Website | Who | What |
| :------ |:--- | :--- |
| [deanattali.com](https://deanattali.com) | Dean Attali | Creator of Beautiful Jekyll |
| [ouzor.github.io](http://ouzor.github.io) | Juuso Parkkinen | Data scientist |
| [derekogle.com](http://derekogle.com/) | Derek Ogle | Professor of Mathematical Sciences and Natural Resources |
| [melyanna.github.io](http://melyanna.github.io/) | Melyanna | Shows off her nice art |
| [chauff.github.io](http://chauff.github.io/) | Claudia Hauff | Professor at Delft University of Technology |
| [kootenpv.github.io](http://kootenpv.github.io/) | Pascal van Kooten | Data analytics |
| [sjackman.ca](http://sjackman.ca) | Shaun Jackman | PhD candidate in bioinformatics |
| [anudit.in](http://www.anudit.in/) | Anudit Verma | Engineering student |
| [sharepointoscar.github.io](http://sharepointoscar.github.io) | Oscar Medina | Independent Hacker |
| [ocram85.com](https://ocram85.com) | Marco Blessing | A personal blog about PowerShell and automation |
| [khanna.cc](https://khanna.cc/) | Harry Khanna | Law and software |

# FAQ and support

Beautiful Jekyll is used by 50,000+ people with wildly varying degrees of web skills, so it's impossible to answer all the questions that may arise. Below are answers to some very common questions. Many questions are often not specifically related to Beautiful Jekyll and are instead more about Jekyll or web development in general. Many such questions can be answered by reading the [Jekyll documentation](https://jekyllrb.com/), using Google, or asking on the [Jekyll support forum](https://talk.jekyllrb.com/).

- ### How can I incorporate new features of Beautiful Jekyll into my old site?

  If you installed Beautiful Jekyll using "the easy way" (by forking the GitHub project), then unfortunately there is no easy way to bring all the newest changes into your website. It's a bit messy, but what most people recommend is to delete your current GitHub project and start fresh: (1) make a copy of any files that you modified/created (generally this means the `_config.yml` file, all blog posts, and any additional pages you created), (2) delete your project on GitHub, (3) re-fork Beautiful Jekyll, (4) add all the content you previously created. Since this is cumbersome, you might want to try creating your website using "the hard way" this time so that in the future you can update more easily!

  If you installed Beautiful Jekyll using "the hard way" (as a ruby gem), then updating to the latest version to get the newest features only requires you to change the version in the config file (for example, change `remote_theme: daattali/beautiful-jekyll@4.0.0` to `remote_theme: daattali/beautiful-jekyll@5.0.0`). You should also look at the [updates](https://beautifuljekyll.com/updates/) to see if any Breaking Changes happened. 

- ### How do I add a favicon to my site?

  Easy! Just place a valid `favicon.ico` in the root directory of your project. And then wait! It can take a while to update.

- ### How do I change the number of posts per page OR the colour of the navigation bar OR the image in the navigation bar OR ...?

  Beautiful Jekyll is built to be very customizable, and as such, many questions about "how do I change ..." can be answered by looking at the `_config.yml` file and modifying the parameters there.

- ### What's the difference between the config file and the YAML parameters?

  Great question! The config file is for site-wide settings, while the YAML parameters are added to each page individually and are applied on a per-page basis.

- ### What if I want to use the same YAML parameter for all pages?

  You can set default values for YAML parameters in the config file. Open the `_config.yml` file, scroll down to the line `defaults:` and that's the section you can use. For more information, see the [official jekyll documentation about default values](https://jekyllrb.com/docs/configuration/front-matter-defaults/).

- ### How do I make small modifications to how my website looks?

  If you want to make any visual changes that are not in `_config.yml`, you'll need to add your own CSS rules to the file `assets/css/custom.css` in order to overwrite the default Beautiful Jekyll style. If you don't know how to use CSS, I highly recommend spending 30 minutes to [learn the basics](https://www.w3schools.com/css/).

- ### How do I use a custom domain for my site?

  GitHub lets you have your website for free using their `github.io` domain. If you want your own domain (such as `https://myname.com`), it's easy and will cost about $10-$15 per year. First you need to buy a domain name (I recommend [Namecheap](https://namecheap.pxf.io/daattali)) and then follow the [instructions GitHub provides](https://docs.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site).

- ### What if I want a **free domain**, but not `https://<yourusername>.github.io`?

  Every GitHub user can have one repository (repository = project) named `<yourusername>.github.io` and the website for that repository will be `https://<yourusername>.github.io`.

  If you want your project to be named something else, for example `MyAwesomeProject`, that's no problem! All you have to do is go to _Settings_ at the top right corner of the page, and rename your repository to `MyAwesomeProject` (**remember to click on the _Rename_ button to confirm!**). Then you need to scroll down to the _GitHub Pages_ section and choose "master branch" as the source (not "master branch /docs folder"!).

  Now your website will be at `https://<yourusername>.github.io/MyAwesomeProject`.

- ### How do I move the blog to another page instead of having it on the home page?

  The default style of Beautiful Jekyll is to feature the blog feed on the front page. For some sites that's not the ideal structure, and you may want to have a separate dedicated page for the blog posts. To have the blog hosted on a different URL (for example at `<mysite.com>/blog`), copy the `index.html` file into a folder with the same name as the desired page (for example, to `blog/index.html`), and in the `_config.yml` file you need to add a parameter `paginate_path: "/<page name>/page:num/"` (for example `paginate_path: "/blog/page:num/"`).

- ### How do I use math equations in my posts?

  MathJax can be easily integrated into your website with a one-line addition. You can see [this discussion](https://github.com/daattali/beautiful-jekyll/issues/195) for more information.

# Contributions

Thank you to [all past contributors](https://github.com/daattali/beautiful-jekyll/graphs/contributors). If you find any problems or would like to contribute in any way, feel free to create a pull request/open an issue/send me a message.

You can also contribute by becoming an [official sponsor](https://github.com/sponsors/daattali/sponsorships?tier_id=39856) to help keep Beautiful Jekyll well-maintained.

# Credits

This template was not made *entirely* from scratch. I'd like to give special thanks to [Jekyll Now](https://github.com/barryclark/jekyll-now) and [Bootstrap Clean Blog](https://github.com/IronSummitMedia/startbootstrap-clean-blog), from whom I've taken several ideas initially.

I'd also like to thank [Dr. Jekyll's Themes](https://drjekyllthemes.github.io/), [Jekyll Themes](http://jekyllthemes.org/), and another [Jekyll Themes](http://jekyllrc.github.io/jekyllthemes/) for featuring Beautiful Jekyll in their Jekyll theme directories.
