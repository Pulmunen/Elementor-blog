---
title: "Custom-Loop-with-Ele-Custom-Skins"
date: 2022-12-05
---


When you install Ele Custom Skins you get a new tab on your theme builder: loop
<img src="{{site.baseurl | prepend: site.url}}/docs/assets/theme-builder-start.png" alt="theme builder start" />

Click add new to add a new loop.
The theme builder library page comes up.  If you already have done the design work, you can select that at this point, otherwise create a fresh template that you can copy and paste into or design from scratch.

<img src="{{site.baseurl | prepend: site.url}}/docs/assets/open-theme-builder.png" alt="open theme builder" />

Select insert.

At this point, the Elementor/ElementorPro editor opens up - by default with the latest post as preview.

<img src="{{site.baseurl | prepend: site.url}}/docs/assets/design-in-loop.png" alt="design in loop" />


This is where you actually do the design/layout work.  Because you have already done all the styling, you should be able to use that here (either select your design from the library page or copy and paste it into here).

Set the dynamic fields (post title, featured post) as you would normally, so drag and drop a post title, featured image and whatever else you need.  This part should be identical to how you would work normally.

Once you're happy with the design, hit publish to save. Don't set any conditions when you save. 

Your design now shows up in the theme builder as a loop.


<img src="{{site.baseurl | prepend: site.url}}/docs/assets/loop-in-theme-builder.png" alt="Inserting loop into posts widget" />


Add the posts widget where you want your latest post to appear.  Under layout > skin select custom. Select a default template > select the loop design you've just created.

Set columns and posts per page to 1.  If you want, you can play around with the query, but by defalt you will have the latest post only visible now, because you set posts per page to 1 and the default query shows posts from newest to oldest.

<img src="{{site.baseurl | prepend: site.url}}/docs/assets/select-loop-in-posts.png" alt="Selecting and setting the loop" />


### Further resources (YouTube)

The Ele Custom Skins homepage itself links to a [WPTuts video](https://www.youtube.com/watch?v=DwLFdaZ69KU&t=94s).These are usually really good.

A video with a bit more background is from [LivingWithPixels](https://www.youtube.com/watch?v=F7QRFgw4DCo).
