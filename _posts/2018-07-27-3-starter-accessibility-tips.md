---
layout: post
title:  The 3 Easiest Ways to Start Making Your Site More Accessible
date:   2018-07-27
category: "Accessibility Quick Tips"
---

## The 3 Easiest Ways to Start Making Your Site More Accessible
Accessibility can feel like a big, unattainable hurdle if you've never thought about it before and don't have much experience. Here are the top three things (listed from easiest to hardest to implement) you can start with to make your website better for everyone.
1. Link text. Screen readers and other assistive technologies can read out lists of links to help users navigate websites. When every link reads "Click Here" or "Read More", it is incredibly unhelpful. Links like that are also unhelpful to all users, who may not be positive exactly where the link is leading them. Instead, use descriptive link text within your main text. Example: "To access further content, [sign in](#)", not "[Click here](#) to sign in and view more content". This is one of the simplest changes you can make and it will help make your content clearer for everyone.
1. Alternative text (often shortened to "alt text"). Any images you use should have alt text as an attribute. This text tells users with screen readers what image is being presented. It also helps convey information in other cases, such as when images aren't loading on a page or when a search engine is scanning the page. Alt text can be added in HTML with the `alt=""` attribute and many text editors allow for alt text input when inserting an image. Tips for alt text:
    - Do not use the words "picture of" or "image" in your alt text - the screenreader will convey that information separately and it could be confusing.
    - Be as clear as you can be without writing an entire paragraph of text. Alt text should have, at most, the amount of information expressed in a brief Tweet.
    - Do not use images of text; instead, just type out the text.
    - Decorative images (and ONLY decorative images) should have empty alt text to denote that they are unrelated to the content.
1. Try running your website through [WAVE - WebAIM's Web Accessibility Evaluation Tool](http://wave.webaim.org/). Input your URL and a report will be run, with a sidebar explaining the annotations on your site. WAVE will give lists of Errors, Alerts, Features, Structural Elements, HTML5 and ARIA elements, and Contrast Errors on the page. When you click on each icon you can learn about what it means, why it matters, and how to fix it. You should go through the entire list of errors and fix as many as possible, and also look into the other alerts and features that were identified in order to learn more about your own site. Automated testing is a good way to start looking into your site's accessibility features and issues, although should never be used as a replacement for human checking. There are many other accessibility checkers, but WAVE is the simplest and is a very good starting place. To dive in further, try testing with [the aXe browser extension](https://www.deque.com/axe/) or look into [W3C's list of automated accessibility testers](https://www.w3.org/WAI/ER/tools/). 

Spending time making your website more accessible will help everyone who tries to use it (and may save you from some lawsuits down the road!). Remember, accessibility is easiest to implement in the early phases of a project than going back and retrofitting, so get started now!
