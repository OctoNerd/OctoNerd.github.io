---
layout: post
title: "HTML - Semantic Elements"
date: 2016-09-10
category: HTML
---

W3c describes semantic elements as an element that clearly describes its meaning to both the browser and the developer. 

This is important for code readability and making sure that you are clearly conveying the purpose of the code you write. A page full of anonymous divs will make the life of anyone who ventures into your code much more difficult, including (and especially) you. Instead, you should consider which elements would best describe and represent the thing you are putting on your page. For example, using the article element to section out space for.. well, the article on your blog is better than just using a div. This makes it easy to see at a glance what that element is meant to be. 

Semantic elements are not just for the human observer though. Search engines use web crawlers to search and classify webpages and the easier you make their jobs, the higher your site will show on search results. Designing for screen readers is another worthy reason to use semantically correct elements in your html. A screen reader is just what it sounds like, a program that parses the content of a page and then reads it aloud. The web is about freedom and accessibility, without semantic elements anyone who is using a screen reader is going to have a much more difficult time using your site. Things like using the nav element to place you page navigation links really adds to the screen reader user's experience. 

While using semantic elements is useful to many and the new HTML5 elements help out a lot to cover most use cases, it is easy to spend too much time trying to figure out exactly what element to use. If you can't find an element that accurately describes what you want, using descriptive class names is better than nothing. For some help deciding what elements to use, check out html5 doctor's [HTML5 flow chart][HTML5-element-flowchart].


[HTML5-element-flowchart]: http://html5doctor.com/downloads/h5d-sectioning-flowchart.png
