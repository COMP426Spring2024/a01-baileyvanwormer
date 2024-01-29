
# Assignment 1

In this assignment, we will create a set of HTML pages that are styled using CSS.

These pages should describe a mythological character or mythological story. The term "mythological" can be broadly interpreted and can be from any culture or time period (Greek, Roman, Aztek, Norse, Asian) or even a very loose interpretation as in describing the "mythological" 2022 Final 4 game between UNC and Duke. The content subject is up to you. 

## 1. Making a Simple Website

### 1.1 Basics (30 points)

The only real requirements for this assignment are these:

1. There should be a single logical "starting" web page as index.html.
2. There should be at least 3 pages. There is no maximum limit of pages, but don't go crazy.
3. There should be links that navigate between the pages
4. All of the pages should use the same CSS stylesheet
5. All of the pages, stylesheets, images, or other resources are commited to this repository.

### 1.2 HTML (30 points)

The starting, or home page, for this assignment should be titled `index.html`. This is a standard in web development because it allows the server to render it without specify which file you want to view ([why index.html](https://www.lifewire.com/index-html-page-3466505)). This root page will then link to other html pages. These can be named whatever you like. 

At a minimum, you HTML pages should have at least one of **each** of the following: 

1. `<ul>` or `<ol>`.
2. `<table>` .
3. `<img> `.
4. `<selector>`.
5. `<a>`.

In addition to that, all of your html pages should be valid HTML5 ([html validator](http://validator.w3.org/)). Minor warnings about browser incompatibility are OK.

### 1.3 CSS (30 points)

This is the part of the assignment where you can get creative. Googling examples of css and best practices is a great place to start. Especially for this assignment [w3schools](https://www.w3schools.com/css/default.asp) is going to be your best friend. 

At a minimum, your stylesheet should:

1. Have at least 10 selectors
2. Use two or more fonts for different kinds of content
3. Set the background color of some elements, specifying the color by hex notation
4. Set the border of some elements
5. Use the :hover pseudo-class for one or more elements
6. Use at least one class-based selector
7. Use at least one id-based selector
8. Have at least one selector rely on the hierarchical relationship between two elements
9. Use width and/or height to control the geometry of an element
10. Validate as CSS3 using the W3C CSS validation tool ([css-validator](http://jigsaw.w3.org/css-validator/))

Other than these basic features, feel free to use whatever CSS3 attributes you would like. 

### 1.4 Peer View (10 points)

The remaining 10 points of the assignment will be awarded based on the quality of the website as judged by your peers!

Everyone will be required to rate at least 7 other submissions according to a rubric on a scale from 0-5 as follows:

* 0: No Submission
* 1: Poorly designed, content not organized or presented well.
* 2: Meets requirements of assignment but not much to it other than that.
* 3: Good web site with interesting content and pleasing design.
* 4: Better than most other submissions but not necessarily the best.
* 5: Professional-level design and content. Could reasonably be nominated for best website. 

You will get 5 points for completing your reviews plus the average of the reviews your peers gave you. This part of the assignment will be done later in the semester after everyone's submission is turned in and we have had a chance to create the infrastructure necessary for making review assignments and submitting reviews. 

### 2. Deployment

Once you are done with your webpage, please follow the following instructions to deploy it to GitHub pages: 

1. Create a local branch off of your main branch called `gh-pages`. 
2. Push said branch to the GitHub by running `git push -u origin gh-pages`
3. Go to the `Pages` configuration tab, as instructed by the [GitHub website.](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-from-a-branch).
4. When choosing the branch for deploying, please choose the `gh-pages` branch you just deployed, and choose the `/root` folder. 
5. And after a few minutes, you should see your website live! The link should follow the format: `https://comp426spring2024.github.io/a1-YOUR_REPO`. 

Please, do note that if you make changes to your `main` branch after deploying your `gh-pages` branch, you will have to merge your `main` into your `gh-pages` branch for the website to reflect thew updates.

### 3. Turning In The Assignment

Turn the assignment into [Gradescope by Thursday, February 8th, 3:30 pm](https://www.gradescope.com/courses/722298/assignments)

Fill out the [attribution attestation form for A1](https://docs.google.com/forms/d/e/1FAIpQLSdJ4T5zq5duVUQOW7RK4eYMy9Uxac5-QILbXu3fxl6e52f_Og/viewform?usp=sf_link)

Using CSS frameworks like Bootstrap, Bulma, etc. counts as "incorporating code or content found on-line".


