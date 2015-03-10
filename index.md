---
title       : Categorization of Continuous Variables
subtitle    : The Good, The Bad, and the Ugly
author      : Danielle McCool
job         : PhD Candidate - Contralateral Breast Cancer
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---{
    class : class1,
    id    : slide1,
    bg    : fffaf0,
    tpl   : slide_layout_1
}

## Levels of Measurement

1. ### Nominal
    sex, status, smoker, HER2_status

2. ### Ordinal
    histopathological differentiation grade (1 = well, 2 = moderately, 3 = poorly), stage of cancer

3. ### Interval
    temperature (&deg;C), date

4. ### Ratio
    BMI, tumor size, duration of adjuvant treatment, number of relatives with cancer

--- .class1 #slide2

title: Slide Title
subtitle: Subtitle
class: image

![Mobile vs desktop users](image.png)

---

title: Segue Slide
subtitle: Subtitle
class: segue dark nobackground

---

title: Agenda
class: big
build_lists: true

Things we'll cover (list should build):

- Bullet1
- Bullet2
- Bullet3

---

title: Today
class: nobackground fill

![Many kinds of devices.](image.png)

<footer class="source">source: place source info here</footer>

---

title: Big Title Slide
class: title-slide

---

title: Code Example

Media Queries are sweet:

<pre class="prettyprint" data-lang="css">
@media screen and (max-width: 640px) {
  #sidebar { display: none; }
}
</pre>

---

title: Once more, with JavaScript

<pre class="prettyprint" data-lang="javascript">
function isSmall() {
  return window.matchMedia("(min-device-width: ???)").matches;
}

function hasTouch() {
  return Modernizr.touch;
}

function detectFormFactor() {
  var device = DESKTOP;
  if (hasTouch()) {
    device = isSmall() ? PHONE : TABLET;
  }
  return device;
}
</pre>

---

title: Centered content
content_class: flexbox vcenter

This content should be centered!



