# Per Scholas React Curriculum: Course Pre-work Project

## Overview
This pre-work will help you prepare for the course and refresh your skills. The course will move at a fast pace, so, the more pre-work you can do, the better you'll do in the course and the more you will get out of it.

**This pre-work is also a great chance to boost your grade!! Participation counts, and completing all of the pre-work assignments will count towards 5% of your total grade.**

Most of all, it will get you back in the swing of coding!

## Setup

The only thing you need to do the pre-work are a computer, [Visual Studio Code](https://code.visualstudio.com) and the [Google Chrome Browser](https://www.google.com/chrome/).

**Click on the links above for installation instructions for all operating systems.**

Visual Studio Code has some great remote collaboration tools and is the recommended editor for the course. Google Chrome is the industry standard tool for doing frontend development work, and you will be required to use it and it's Chrome Developer tools during the course.

# Assignments
## Create your Homepage!
A hompage is a great professional asset for any software developer, and for anyone working in tech. You are going to create a [static webpage](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Pages_sites_servers_and_search_engines#web_page) as your own homepage using HTML and CSS.

**Among other assignments, you will continue to develop this portfolio page over the course and will launch it for the world to see.**

This site will be a part of your professional portfolio and a great asset in helping you develop your career.

### Instructions
1. Create a file named `index.html`. It should look [like this](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer&ssr=false#overview):

```html
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

[Here's the `index.html` page with comments and some additional HTML elements](assignments/portfolio-page/index.html) indicating our basic page structure. Your job will be to add CSS to this, specifically [CSS Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/), to bring this page to life!


### Requirements

1. Replace all of the sample text with your own words and about yourself. **This doesn't have to be perfect -- just be sure there are no spelling or grammar errors**. 

2. Use a [web-safe font](https://blog.hubspot.com/website/web-safe-html-css-fonts) for:
  a) Section headings.
  b) Secion paragraphs (the content of each section).

**There is an example of this in the styles.css file for the assignment**.

3. Make the "Get in Touch" `<a>` tag (also called a link or href) a [mailto](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#attr-href) link so that people can email you! If you're not comfortable using your real email address, just use a made-up email address like "test123@test123.com".

4. Make the background color of your main content section (the center column) different from the side columns.

5. Remove the numbers ("1", "2", etc) from the ordered list in your header nav section. [See here](https://stackoverflow.com/questions/40670124/how-do-i-remove-the-numbers-in-ol/40670629). **FYI the "header nav section" is the small menu in the header reading "About, Experience".**

6. Make the header nav section links [relative links](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks#absolute_versus_relative_urls) to their main content sections, **i.e. clicking on "About" should take you to the "About" section of your page. Google "relative links" if the above link isn't helpful.

7. Use CSS Flexbox to structure your n