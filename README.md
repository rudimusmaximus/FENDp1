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


# Design Decisions and My Project 'point of view'  

As a learning exercise, this section describes my design decisions.

## Layout with Flexbox and One CSS
No content left behind across views AND no menu required lead me to think a Flexbox would be best.

## Fonts & Icons  
I was surprised this wasn't covered in detail. I'm looking for opportunities to establish my preferred solutions here. Two possibilities come to mind:
 - https://fonts.google.com/ for a preferred font. Rather than attempt to match the mock-up, I'll pick one.
 - https://fontawesome.com/ for icons in the future, but no initial use; later, there may be good use for brand icons like GitHub and LinkedIn for example as I add content.  

## Tables  
None used.

## Images  
We are responsible for images. I like to use Canva.com but for this, I'll explore Google Draw for placeholder mock-ups. We were directed to an entire class on this. I went with screen captures of my profile on LinkedIn for hero image, my services landing page (Squarespace integrated with Chatlio), and my GitHub rep project 'DevFlow'.

# Ongoing Questions and Lessons Learned  

## Questions as I Completed this:  
These are working notes, I'll be seeking answers on these questions. If you can add any comments, please do. Thank you.  

TODO: advice requested.  

| Question | Answer |
| :--- | :--- |
| 1. Unused class | When marking up semantic HTML, should we include classes that will not be used OR include most and delete unused at some version? I could see where for maintainability, it might be easier to include them at the beginning. Is it costly to have unused classes? **OR** is this to be avoided like unused functions? |
| 2. What is an HTML template vs an HTML document? | The Phrasing of #18 General Meta Rules got me thinking. Also, in a scripting context, I recall talk of scriptlets using templated HTML. Unsure if they are related. Documenting for follow up research. |
| 3. In HTML Style Rules  | Why are we asked to optionally omit type attributes for style sheets and scripts? |
| 4. Are we going to cover hosting? What is done here if we want to host something a non developer can 'sample'? | TODO: I've heard GitHub sites for some. But I'd expect at least an overview and pointers to other offerings or sources including solutions like GitHub or serving sites/apps ourselves? (especially low use or temporary) |
| 5. This is a private repository, how to best turn in? | TODO: Can we use a zipped release on GitHub to turn it in? Review when finished. |
| 6. Is [this practice](https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/) a "hack"? | |  
| 7. Not sure my CSS is indented properly | please advise; I see requirement for indenting the CSS; is it supposed to mimic the hierarchy in the HTML? I was writing it to be brief, combining where I could. Is this not best practice? |
| 8. Best Practice or Not? | In the course, there was a video that recommended setting a max-width catch all in your main css to avoid overflow, but I've seen comments about tags being heavy (more porcessing) than classes. So, i preferred classes. Any comments here? See the example. |  

**Example for Question 8**
```css
img, embed, object, video {
  max-width: 100%;
}
```  

## Lessons learned:  

| Area | Comments |
| :--- | :--- |
| 1. HTML | a. When using `<section>` tags, you must use a heading tag (h1,h2...) as the first child in a section to be valid|
| 2. Images | a. I could have used placeholder.com for my images (adding https of course) <br/><br/> b. Attempting to use `srcset` but need more examples. Working now. <br/><br/> c. I'm not at all happy with the resolution of my images; I need some direction on this topic. HELP. |
| 3. use of validators | This was very helpful to run early when you have your structure worked out, so you can focus on the rest; |
| 4. color w layout changes | Used background color to highlight break-point layout changes; commented out when done |  

## DevFlow
I used my DevFlow process to do this work including creating issues for each section of the rubric. This included following git commit guidelines, 'Git Flow' branching model, custom label scheme. Hosted on GitHub and used Atom and GitKraken with it's new "Glo Boards".
Please let me know if you'd like to get access to the repo or board. Just send me your email to add you.
I'll use this approach on the remaining projects as it's my evolving way of doing projects.

## Glo Board In Progress Example
![image](https://app.gitkraken.com/api/glo/boards/5b1316054f33b715001b0476/attachments/5b160607c9b0cf0e0093b7b8)

## Finished View of Largest breakpoint
![image](https://app.gitkraken.com/api/glo/boards/5b1316054f33b715001b0476/attachments/5b16991ac9b0cf0e0093dd15)
