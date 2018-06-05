# Project 1 (FENDp1): Build a Portfolio Site.  
Part of Udacity's Front End Nano Degree. April - Oct 2018.

Create a progressive web app that works from small to large screens.
It should be able to be modified to present my projects from FEND;
and, expandable for previous and current professional activities.

# Requirements

Satisfy project rubric and all issues under FEND epic issue #1.  

## Functional requirements are as follow:  

| Criteria | Meets Specifications |
| :--- | :--- |
| 1. Comply with rubric | a. all issues under FEND epic issue #1 [github.com/rudimusmaximus/FENDp1/issues/1](https://github.com/rudimusmaximus/FENDp1/issues/1) |
| 2. Personalize | a. Fonts <br/><br/> b. Custom colors <br/><br/> C. Additional content <br/><br/> D. My own images |
| 3. HTML and CSS Validation | a. Pass [W3C's Validators](http://validator.w3.org/). Note: the validators consider the following errors, whereas Udacity accepts these errors as acceptable: <br/><br/>  - HTML5: **Bad value X-UA-Compatible for attribute http-equiv on element meta** when using the X-UA-Compatible meta tag.<br/><br/> - CSS3: **Property [some property here] is an unknown vendor extension** when using vendor prefixed properties (like -moz-box-sizing).|
| 4. Content Organization | a. Must use [HTML5 semantic (structural) elements](https://www.w3.org/wiki/HTML_structural_elements#Enter_HTML5_structural_elements). Also see rubric. |
| 5. Five | a. Ability to x, <br/><br/> b. B |  

# Design Decisions and My Project 'point of view'  

As a learning exercise, this section describes my design decisions.

## Layout with Flexbox and One CSS
No content left behind across views AND no menu required lead me to think a Flexbox would be best.

A single CSS file will be used to also contain any dynamic CSS because there's not enough complexity to require multiple files.

## Fonts & Icons  
I was surprised this wasn't covered in detail. I'm looking for opportunities to establish my preferred solutions here. Two possibilities come to mind:
 - https://fonts.google.com/ for a preferred font. Rather than attempt to match the mock-up, I'll pick one.
 - https://fontawesome.com/ for icons in the future, but no initial use; later, there may be good use for brand icons like GitHub and LinkedIn for example as I add content.  

## Tables  
None used.

## Images  
We are responsible for images. I like to use Canva.com but for this, I'll explore Google Draw for placeholder mock-ups. We were directed to an entire class on this.  TODO: i'll examine this and update.  

# Ongoing Questions and Lessons Learned  

## Questions as I Completed this:  

| Question | Answer |
| :--- | :--- |
| 1. Unused class | When marking up semantic html, should we include classes that will not be used OR include most and delete unused at some version? |
| 2. What is an HTML template vs an HTML document? | The Phrasing of #18 General Meta Rules got me thinking. Also, in a scripting context, I recall talk of scriptlets using templated HTML. Unsure if theyare related. Documenting for follow up research. |
| 3. In HTML Style Rules  | Why are we asked to optionally omit type attributes for style sheets and scripts? |
| 4. Are we going to cover hosting? What is done here if we want to host something a non developer can 'sample'? | TODO: I've heard GitHub sites for some. But I'd expect at least an overview and pointers to other offerings or sources including solutions like GitHub or serving sites/apps ourselves? (especially low use or temporary) |
| 5. This is a private repository, how to best turn in? | TODO: Can we use a zipped release on GitHub to turn it in? Review when finished. |
| 6. Is [this practice](https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/) a "hack"? | |  


## Lessons learned:  

| Area | Comments |
| :--- | :--- |
| 1. HTML | a. When using `<section>` tags, you must use a heading tag (h1,h2...) as the first child in a section to be valid, <br/><br/> b. B |
| 2. Images | a. I could have used placeholder.com for my images (adding https of course), <br/><br/> b. Attempting to use `srcset`, but need more examples. |
| 3. Three | a. Ability to x, <br/><br/> b. B |
| 4. Four | a. Ability to x, <br/><br/> b. B |
| 5. Five | a. Ability to x, <br/><br/> b. B |  

## DevFlow
I used my DevFlow process to do this work including creating issues for each section of the rubric. This included following git commit guidelines, 'Git Flow' branching model, custom label scheme. Hosted on GitHub and used Atom and GitKraken with it's new "Glo Boards".
Please let me know if you'd like to get access to the repo or board. Just send me your email to add you.
I'll use this approach on the remaining projects as it's my evolving way of doing projects.

## Glo Board
![image](https://app.gitkraken.com/api/glo/boards/5b1316054f33b715001b0476/attachments/5b160607c9b0cf0e0093b7b8)

## Finished View of Largest breakpoint
![image](https://app.gitkraken.com/api/glo/boards/5b1316054f33b715001b0476/attachments/5b1606254f33b715001b6811)
