# Per Scholas React Curriculum: Course Pre-Work Project

## Overview
This pre-work will help you prepare for the course and refresh your skills. The course will move at a fast pace, so, the more pre-work you can do, the better you'll do in the course and the more you will get out of it.

**This pre-work is also a great chance to boost your grade!! Participation counts, and completing all of the pre-work assignments will count towards 5% of your total grade.**

Most of all, it will get you back in the swing of coding!

# Setup

The only thing you need to do the pre-work are a computer, [Visual Studio Code](https://code.visualstudio.com) and the [Google Chrome Browser](https://www.google.com/chrome/).

**Click on the links above for installation instructions for all operating systems.**

Visual Studio Code has some great remote collaboration tools and is the recommended editor for the course. Google Chrome is the industry standard tool for doing frontend development work, and you will be required to use it and it's Chrome Developer tools during the course.

1. [Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repository so that you have a main copy of this set of files under your own Github account.
2. Use [`git clone`](https://www.atlassian.com/git/tutorials/setting-up-a-repository/git-clone) to make a copy of your own forked repository (from your Github account) to your local directory (on your device)
2. [Open up](https://docs.microsoft.com/en-us/visualstudio/ide/develop-code-in-visual-studio-without-projects-or-solutions?view=vs-2019) the local copy of this repository using Visual Studio Code. Rename the "Per-Scholas-React-Course" to "Per-Scholas-React-Course {your full name here}" as a local directory to contain your final README.md and other files.
3. [save and push changes](https://www.atlassian.com/git/tutorials/saving-changes) to your own Github account

# Assignments
## Create your Homepage!
A hompage is a great professional asset for any software developer, and for anyone working in tech. You are going to create a [static webpage](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines#web_page) as your own homepage using HTML and CSS.

**Among other assignments, you will continue to develop this portfolio page over the course and will launch it for the world to see.**

This site will be a part of your professional portfolio and a great asset in helping you develop your career.

### Instructions
1. Create a file named `index.html`. It should look [like this](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer&ssr=false#overview):

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
  <body>
    <p>This is my page</p>
  </body>
</html>
```

This is the skeleton of your homepage. In Google Chrome, open your `index.html` file. The `File > Open` command will bring up a dialog window you can use - double-clik on your file to open it.

**Every time you change this file, you will have to refresh your browser window to see the changes!**

2. Create your page structure.

For this project we are going to follow the basic page structure on the homepage of software engineer [Brittany Chiang](https://brittanychiang.com). I'll be sharing other examples of good design throught this assignment. 

**Fun fact - I found these sites [here](https://uxdesign.cc/sixteen-sick-portfolios-4159b3e2c235). I found that by Googling, a programmer's best friend. Always Be Googling! 

Our point is, though, that being a software developer means developing the skill of finding information - of figuring things out, and learning how to learn. **You should constantly be googling new terms/concepts during class, or, be writing them down to ask about and/or google later!**.

But, returning to the assignment, this page design has several key elements:

1. Nav bar
2. Ceter Column with:
  A) A Hero section
  B) Content sections below the fold.
3. A left column with a sidebar.
4. A right column with a sidebar.

Note how all the critical information on this page is **above the fold**. "Above the fold" means, everything you can see when a website first loads without having to scroll down at all. 

**"Above the fold" page load time and performance are critical issues when developing real-world web apps with React.js or any other tool.**

For now we are focusing on simple page layout and design and don't have to worry about performance but it's good to start thinking about these things.

Here's the `index.html` page with comments and some additional HTML elements indicating our basic page structure. Your job will be to add CSS to this, specifically [CSS Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/), to bring this page to life!

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
  <body>
    <!--- PAGE HEADER WITH NAV BAR AND LOGO --->
      <header>
        <nav>
      </header>

    <!---LEFT SIDEBAR SECTION --->
    <div></div>

    <!---MAIN SECTION --->
      <main>
        <section id="hero">
        </section>
        <section id="about">
        </section>
      </main>
    <!---RIGHT SIDEBAR SECTION --->
    <div></div>
    <p>This is my page</p>
  </body>
</html>
```