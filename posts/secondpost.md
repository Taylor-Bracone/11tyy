---
title: Slot Slot Slot
description: Slotted Content.
date: 2021-10-24
tags:
  - Imagine
layout: layouts/post.njk
---

If you are following along with my post, as you may know I am on a team with my fellow peers and we are continuing to work on our web components to make a working card. The census of the team was to break the card up among all of us through different components such as the icon, the card framework, the banner, everything all together.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/88sr8wswnygi4njw8h7a.png)

**Slot Composition:**

Utilizing slots can help to make content look and seem more aseptically pleasing. I took the liberty of drafting some very basic level HTML to further show how to create separate DOM trees with different elements all rolled up into one, together.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4gm0seu5ooukxterp65n.png)

We are looking to use slots to pass the HTML into the different parts of the card such as the header, sub header, and the overall body as mentioned above.

**Our Code & Examples:**
Our code is still a work in progress and we are still working out some kinks as we speak. Learning-card has been recently created with a decent amount of slots.

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/edgf6izrmiiyrbp1e61p.png)

In this image, the div wraps around the entire created banner with icon called with the header. The two slots inside that are contained, pertain to the header and the sub header. This maps on a different scale to what I mentioned above. This shows how slots are used inside the component.


**Link to Repo:** 
https://github.com/TheKodingKrab/project-two
https://github.com/Taylor-Bracone/project-two 