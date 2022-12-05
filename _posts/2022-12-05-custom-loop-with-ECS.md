---
title: "Custom-Loop-with-Ele-Custom-Skins"
date: 2022-12-05
---


When you install Ele Custom Skins you get a new tab on your theme builder: loop
[theme builder start]
<img src="/assets/images/loop in theme builder.png" alt="Open Theme Builder with Ele Custom Skins installed" style="width:100%;"/>

Click add now.
The library page comes up.  If you already have done the design work (which you have), you can select that at this point, otherwise create a fresh template that you can copy and paste into or design from scratch.
[open theme builder]
Select insert.
At this point, the Elementor/ElementorPro editor opens up.
[design in loop]

This is where you actually do the design/layout work.  Because you have already done all the styling, you should be able to use that here (either select your design from the library page or copy and paste it into here).

Set the dynamic fields (post title, featured post) as you would normally, so drag and drop a post title, featured image and whatever else you need.  This part should be identical to how you would work normally.

Once you're happy with the design, hit publish and go back in to the page you want to add this to (in this case home).
Don't set any conditions when you save.
Your design now shows up in the theme builder as a loop.
Add the posts widget where you want your latest post to appear.  Under layout > skin select custom. Select a default template > select the loop design you've just created.
[loop insert to posts]
[posts pre skin]
Set columns and posts per page to 1.  If you want, you can play around with the query, but by defalt you will have the latest post only visible now, because you set posts per page to 1 and the default query shows posts from newest to oldest.
