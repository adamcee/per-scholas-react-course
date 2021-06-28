# Per Scholas Website Project
## Build Your Own Porfolio Website

## Overview
This project is designed to help you prepare for your upcoming web development course and refresh your skills. By finishing this project, you'll be better prepared for the fast pace of our curriculum covering the skills necessary for you to become a full-stack developer. 

Most of all, it will get you back in the swing of coding!

## Assignment: Create your Homepage!
A hompage is a great professional asset for any software developer, and for anyone working in tech. You are going to create a [static webpage](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines#web_page) as your own homepage using HTML and CSS.

This site can be a part of your professional portfolio and a great asset in developing your career.

You will be evaluated in the following fashion:

1. [Setup](#setup) and [Configuration.](#configuration) **It is normal for setting up a development environment to take time and effort.** When you start your job, they'll expect you to take at least a day to get set up! So, give yourself time to do this. Be patient. It counts for **30%** of your assignment grade!


2. [Add content and clean up the page.](#add-content-and-clean-up-the-page) This is work to get you going. It counts for **20%** of your assignment grade.

3. [Give your page structure with flexbox!](#give-your-page-structure-with-flexbox) This is **50%** of your assignment grade.

4. [Bonus! Make your page responsive!](#bonus-make-your-page-responsive) so it looks good on a mobile device. Use the reference site as an example of how your page should look. This is an extra **20%**!


## Setup

You will need the following things:

1. A programming text editor. I highly recommend [installing Visual Studio Code](https://code.visualstudio.com), as a popular text editor leveraged both among industry teams and in the course.

2. A web browser. I highly recommend using [Google Chrome](https://www.google.com/chrome/). Chrome and Chrome Devtools (part of the [web browser](https://en.wikipedia.org/wiki/Web_browser)) are industry standards for frontend development and we'll be using them in the course.

3. A [Github account](https://github.com/). You will be submitting your pre-work by submitting a link to a github repository containing your work..

**Click on the links above for installation/setup instructions for all operating systems.**

## Configuration
1. [Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repository so that you have a main copy of this set of files under your own Github account.
2. Use [`git clone`](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone) to make a copy of your own forked repository (from your Github account) to your local directory (on your device)

3. [Open up](https://docs.microsoft.com/en-us/visualstudio/ide/develop-code-in-visual-studio-without-projects-or-solutions?view=vs-2019) the local copy of this repository using Visual Studio Code. Rename the "Per-Scholas-React-Course" to "Per-Scholas-React-Course-{your full name here without spaces in [CamelCase](https://en.wikipedia.org/wiki/Camel_case)}" as a local directory to contain your final README.md file and other files.

4. [Set up Visual Studio Code with Github](https://code.visualstudio.com/docs/editor/github)

5. [Save and push changes](https://www.atlassian.com/git/tutorials/saving-changes) to your own Github account

6. Install the Visual Studio Code [Liveserver extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer). You will use this to host your website as you work.
<img width="1919" alt="vs-code-liveserver" src="https://user-images.githubusercontent.com/4441280/123363003-46a3f580-d537-11eb-8bd0-1520f30410ff.png">

7. Ensure the [`index.html`](index.html) and [`styles.css`](index.html) files from this project are included in your forked copy on your own github repository.

## Overview

The index.html page linked above contains the skeleton of your site. We have created several useful CSS classes which you will define. For those who are interested we are using the [BEM CSS Methodology](https://en.bem.info/methodology/quick-start/), which is an industry-standard way to organize your CSS.

For this project we are going to follow the basic page structure on the homepage of software engineer [Brittany Chiang](https://brittanychiang.com). 

>Fun fact - I found these sites [here](https://uxdesign.cc/sixteen-sick-portfolios-4159b3e2c235). I found that by Googling, a programmer's best friend. Always Be Googling! 

Our point is, though, that being a software developer means developing the skill of finding information - of figuring things out, and learning how to learn. 

**You should constantly be googling new terms/concepts during class, or, be writing them down to ask about and/or google later!**.

Returning to the assignment, this page design for this homepage project has several key elements:

>
1. Nav bar
2. Center Column with:
  A) A Hero section
  B) Content sections below the fold.
3. A left column with a sidebar.
4. A right column with a sidebar.

Note how all the critical information on this page is **above the fold**. "Above the fold" means, everything you can see when a website first loads without having to scroll down at all. 

>"Above the fold" page load time and performance are critical issues when developing real-world web apps with React.js or any other tool.**

For now we are focusing on simple page layout and design and don't have to worry about performance but it's good to start thinking about these things.

Your job will be to add content and CSS to the site. 

**In particular your job is to use [CSS Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/), to bring this page to life and give it structure!**


# Your Tasks

## Know Your Tools.

1. [Review how to open Chrome Devtools](https://developer.chrome.com/docs/devtools/open/).
2. [See how you can use Chrome Devtools to view and change your CSS!!](https://developer.chrome.com/docs/devtools/css/). **You should be doing this as you work** - it's a LOT faster than making changes in your text editor. Prototype the changes using Devtools, then add them in your text editor!

## Add content and clean up the page

1. Replace all of the sample text with your own words and about yourself. **This doesn't have to be perfect -- just be sure there are no spelling or grammar errors**. 

2. Use a [web-safe font](https://blog.hubspot.com/website/web-safe-html-css-fonts) for section headings **and** section paragraphs (the main content/text of each section). 

**There is an example of this in the styles.css file for the assignment**.

3. Make the "Get in Touch" `<a>` tag (also called a link or href) a [mailto](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#attr-href) link so that people can email you! If you're not comfortable using your real email address, just use a made-up email address like "test123@test123.com".

4. Make the background color of your main content section (the center column) different from the side columns.

5. Remove the numbers ("1", "2", etc) from the ordered list in your header nav section. [See here](https://stackoverflow.com/questions/40670124/how-do-i-remove-the-numbers-in-ol/40670629). **FYI the "header nav section" is the small menu in the header reading "About, Experience".**

6. Make the header nav section links [relative links](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks#absolute_versus_relative_urls) to their main content sections, i.e. clicking on "About" should take you to the "About" section of your page. Google "relative links" if the above link isn't helpful.


## Give your page structure with flexbox

**IMPORTANT: You may not use CSS frameworks for this assignment. Write your own CSS. Feel free to find examples of relevant CSS to reference - many are linked to in this README.**

**This is the guts of your assignment.** Use CSS Flexbox to structure your portfolio page! We want a similar structure to the example site. I recommend reading [A complete guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/). Additional resources are [here](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox), [and here](https://github.com/afonsopacifer/awesome-flexbox). Break this task down like so:

I've added some background colors to help you visualize the page structure. I **HIGHLY** recommend adding background colors to help you visualize as you apply flexbox styles to structure the page.

1. First, apply flexbox to put the header at the top of the page, and everything else below the header. 
2. Then, use flexbox to create your three column-layout (left, center, right). 
3. Next use flexbox to create the "content sections" of the center column. 
4. Now make sure your first "Hero Section" with the large text is styled well.

## Bonus: Make your page responsive

Making a [responsive site which looks good on tablets and mobile devices](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design) is a **critical** job skill for frontend developers. Make your portfolio page mobile-friendly!! Again, the reference site does an excellent job in this regard and should be your guide. Again, [Chrome Devtools is your friend](https://developer.chrome.com/docs/devtools/device-mode/#viewport) while doing this. [Here](https://coder-coder.com/build-flexbox-website-layout/) are some [resources](https://www.freecodecamp.org/news/learn-flexbox-build-5-layouts/)
