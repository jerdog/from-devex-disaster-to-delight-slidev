---
# You can also start simply with 'default'
theme: the-unnamed
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
#background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: "From DevEx disaster to delight: How to champion a DevEx revolution in your organization."
conference: ""
author: Jeremy Meiss
logo: 
info: |
  ## From DevEx disaster to delight: 
  How to champion a DevEx revolution in your organization.

  Is your development team drowning in a sea of bugs, clunky tools, and morale-sapping processes? Are you tired of hearing your developers utter phrases like "I hate this deployment process" and "This codebase is a crime against humanity"? Well, fret no more! This talk will be your hilarious and informative guide to transforming your organization's Developer Experience (DevEx) from a disaster zone to a developer utopia.
  
  We'll delve into the what, why, and how of DevEx, exploring practical strategies you can implement to make your developers' lives easier and more productive. We'll cover everything from tooling and automation to fostering a culture of collaboration and feedback. By the end of this talk, you'll be armed with the knowledge and practical tips to become a DevEx champion in your organization
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
defaults:
  # slide transition: https://sli.dev/guide/animations#slide-transitions
  transition: slide-left
  layout: center
# for this slide only
layout: cover
---

# From DevEx disaster to delight

How to champion a DevEx revolution in your organization.

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

# A DevEx disaster

<!--
We've all had that experience with a developer experience that was a disaster. It could be the worst deployment process you've ever seen, or the most painful codebase you've ever had to work with, or documentation that's so confusing it makes your head spin. Maybe it's a combination of all of these things, and it's enough to make you want to scream. 
-->

---
layout: image-right
image: /images/profile-pic.jpg
---

# Jeremy Meiss

<div class='flex items-center h-full'>
  <div class="grid grid-cols-2 gap-4">
    <card title='Co-Founder, Consultant' imagePath='/images/devexInstitute-whiteLogo.png' imageAlt='DevEx Institute logo'></card>
    <card title='Organizer' imagePath='./images/dodkc-logo.png' imageAlt='RxJS Logo'></card>
  </div>
</div>


<!--

-->

---

## What we're going to cover

1. What is DevEx
2. Key aspects of DevEx
3. Strategies for improving DevEx
4. Become the DevEx champion you always dreamed of being

<!--
Over the next 30 minutes, we'll cover the following topics:
-->

---

# What is Developer Experience (DevEx)?

![good and bad devex](/images/slides/good-and-bad-devex.jpeg)

<!--
From the simplicity of the setup process to the complexity of solving production issues, DevEx directly impacts developer productivity, satisfaction, and ultimately, the quality of the products they build and use.
-->

---

## DevEx is _more_ than just your parent's SDLC

<!--
DevEx is an integral part of the entire development lifecycle, as a direct result of the choice of development tools, technologies, and platforms. That means that the ease of use, reliability, how accessible and understandable documentation, how efficient the build processes are, the effectiveness of testing frameworks, and the smoothness of deployment procedures all have an impact on the overall dev experience.
-->

---
layout: image-left
image: /images/slides/cornell-devex.jpg
backgroundSize: contain
class: my-cool-content-on-the-right
---

## DevEx isn't new

REF: F. Fagerholm and J. Münch, "[Developer experience: Concept and definition](https://ieeexplore.ieee.org/document/6225984?arnumber=6225984)," 2012 International Conference on Software and System Process (ICSSP), Zurich, Switzerland, 2012.

<!--
But DevEx isn't a new thing. The first mention of "developer experience" as a concept was in a paper was presented at the June IEEE 2012 International Conference on Software and System Process in Zurich. There are references in the paper going back to 1985 that deal with "programmer performance and the effects of the workplace." A few things stand out in this paper, which is a really great read.
-->

---
layout: image-left
image: /images/slides/cornell-devex.jpg
backgroundSize: contain
class: my-cool-content-on-the-right
---

## DevEx isn't new

REF: F. Fagerholm and J. Münch, "[Developer experience: Concept and definition](https://ieeexplore.ieee.org/document/6225984?arnumber=6225984)," 2012 International Conference on Software and System Process (ICSSP), Zurich, Switzerland, 2012.

>"New ways of working such as globally distributed development or the integration of self-motivated external developers into software ecosystems will require a better and more comprehensive understanding of developers' feelings, perceptions, motivations and identification with their tasks in their respective project environments."

---
layout: image-left
image: /images/slides/cornell-devex.jpg
backgroundSize: contain
class: my-cool-content-on-the-right
---

## DevEx isn't new

REF: F. Fagerholm and J. Münch, "[Developer experience: Concept and definition](https://ieeexplore.ieee.org/document/6225984?arnumber=6225984)," 2012 International Conference on Software and System Process (ICSSP), Zurich, Switzerland, 2012.

>"...developer experience could be defined as a means for capturing how developers think and feel about their activities within their working environments, with the assumption that an improvement of the developer experience has positive impacts on characteristics such as sustained team and project performance."

<!--
The second was this line, that DevEx could be a means for capturing how devs think and feel about their activities at work, and that improving their experience impacts things like sustained team and project performance.

So all of this interest in DevEx isn't a new concept - but is largely driven by companies trying to sell you something, from the top down, with very little (if any) focus on developers themselves. We've all been there - we've been told we need to adopt a new way of working, and then had some new tool from some friend on the C-Suite who says that by simply using it, we'll be happier, more productive, and instantly a 10x engineer. Meanwhile, you've used it before and it's shit.
-->

---

## A working definition of DevEx

>_"...the **journey** of developers as they learn and deploy technology, which if successful, focuses on eliminating obstacles that hinder a developer or practitioner from achieving success in their endeavors."  
> -Jessica West, Co-Founder, DevEx Institute_

<!--
Let's start with a definition of DevEx - DevEx is the journey of developers as they learn and deploy technology. When successful, it focuses on eliminating obstacles that hinder a developer or practitioner from achieving success in their endeavors.
-->

---

## DevEx includes every interaction a developer/ops practitioner has with systems, tools, and processes  

![alt text](/images/slides/ui-ux-qa.gif)

<!-- 
it is about every interaction a developer or ops practitioner has with systems, tools, and processes. And we've see an evolution in Developer Experience over the years.

-->

---

## Key aspects of DevEx

1. Tools & Automation
2. Developer Environnment Setup
3. Documentation & Knowledge Sharing
4. Collaboration & Communication
5. Culture & Feedback

<!--
Tools & Automation (code editors, version control, deployment pipelines)
Development Environment Setup (streamlined onboarding, consistent configurations)
Documentation & Knowledge Sharing (clear, up-to-date documentation, easy access to resources)
Collaboration & Communication (efficient communication channels, knowledge-sharing platforms, code reviews)
Culture & Feedback (positive work environment, opportunities for feedback and growth)

-->

---

## Impact of poor DevEx

<!--

-->

---

# Benefits of good DevEx

<!--

-->

---



<!--

-->

---

# Strategies for improving DevEx

<!--

-->

---


<!--

-->

---

# Championing DevEx in your org

<!--

-->

---



<!--

-->

---

# Thank you

<!--

-->

