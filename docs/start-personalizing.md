---
layout: default
title: Personalize Lilium
---


# Personalize Lilium

## You are free to experiment every option until you find your favourite one

As you can see, Lilium is a very simple template, it's similar to a blog, but there's still a lot you can change to make this digital garden *your* digital garden.

1. [Where to start](#start)
   * [Title](#sitetitle)
   * [Top navigaton](#topnav)
   * [About page](#about)
   * [Floating elements](#floating)
2. [Useful tips](#tips)

<hr>

<h3 id="start">Where to start</h3>

There are some basic features that you need to override before you publish your garden. This is the only time you’ll need to see the code, I promise.

<h4 id="sitetitle">Title</h4>

The first thing you need to do is change the site’s name from "Lilium Digital Garden" to **the actual name of your digital garden**.

To do so, you have to open the file named "_config.yml" with a text editor. On the very first line you'll find the site’s name, you just change that and save the file. Then you'll probably need to serve the site again, as I explained [here](set-up-lilium.md) (if you're running it locally this means stop it, run "**bundle ecex jekyll serve**" again, then reload the page).

<h4 id="topnav">Top navigation</h4>

Top navigation is **the simple menu you see above the title**. You can add more pages there, but for now I suggest you to just delete the "Document" and the "Download Lilium" links.

To do so, you have to open the "_includes" folder, and then open the "nav.html" with a text editor. You'll find a list of four links, all you have to do is delete these last two and save the document.

![setting top navigation](/imgs/how-to-5.png)

<h4 id="about">About page</h4>

Another thing you’ll obviously want to edit is the “About” page. You can add your personal information there, such as bio, contacts and so on. At the bottom of this page you’ll find some tips on how to write on a Jekyll page (such as syntax etc).

Remember that the content of the "About" page is written inside **the "about.md" document in the "_pages" folder**. ⚠️ Make sure you edit this document and NOT the "about.html" document in the "_layouts" folder.

<h4 id="floating">Floating elements</h4>

The floating elements are:
1. the "About me" block you se on right bottom corner of the pages,
2. the social icons on the "About" pages.

These, of course, contains more personal information. To edit them you’ll have to edit  **the "floating-about.html" document and the "floating-social.html" document inside the "_includes" folder**.

For the floating about, replace the text between the “<p>” tag and the “</p>” tag with your own text.

For the social icons, replace my social urls with yours. I provided some other icons that are not displayed (such as LinkedIn, YouTube, Pinterest, Reddit and Twitch) inside the “assets/icons” folder. To replace them you'll just have to type the name of the social in this space.

![setting social links](/imgs/how-to-6.png)

Or you can add or remove icons by duplicate or delete a whole block contained between the "<li>" and the "</li>".

_**We're done!**_ 🎉

Last thing you can do, if you want to, is delete the "docs" folder and all the "how-to-number.png" images from the "imgs" folder, so you can start your brand new digital garden.

<hr>

<h3 id="tips">Useful Tips</h3>

Now you're free to do whatever you want with your digital garden. But before my job is done, let me give you just a couple of tips that will probably make you spare some time.

Jekyll is an amazing tool, but there are some basic rules that you'll learn soon. One of them is **the language**. In Jekyll we write in a language called *markdown language*, and that's why your notes are stored in files that have the ".md" extension.

Markdown is pretty easy to learn, it’s actually just a combination of symbols, like “#” for titles, single “*” for italic and double for bold, and so on. Anyway, it could be useful to refer to a [guide](https://www.markdownguide.org/basic-syntax).

To make it even easier, I suggest you download a proper text editor, like [Atom](https://atom.io/) or [Visual Studio](https://visualstudio.microsoft.com/), that can help you with any syntax mistakes. When you are ready, you'll discover how many amazing things you can create by mixing markdown with some HTLM.

Another thing that you should probably know is that to be creative does not mean to be messy. It’s much easier to use a Jekyll site if its directories are in order. So, when you create a new note, you should put it **in the "_notes" folder**. This way, it will appear in the "Seeds" section, which is a blog-style list of your entries. [Here](https://jekyllrb.com/docs/collections/) you can find a lot of information on that page, such as how to change the order of the displayed notes. In any case, I suggest you to take a look at the [Jekyll](https://jekyllrb.com/) documentation.

<hr>

I believe we're good here. I hope you found my guide useful. Now it's time to **start enjoying your new digital garden!**

For any question or issue you can contact me on [GitHub](https://github.com/crixer18) of via [email](mailto:web@zulianis.eu). ☕ Also, if you like the template, please [consider buying me a coffee](https://ko-fi.com/stefanozuliani#checkoutModal).
