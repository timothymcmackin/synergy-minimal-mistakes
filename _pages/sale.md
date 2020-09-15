---
title: Horses for sale
permalink: /sale
layout: single
# classes: wide
# sidebar:
#   - title: For sale
#     nav: sidebar-sale
gallery_william:
  - url: /assets/images/shutterstock_453308077.jpg
    image_path: /assets/images/shutterstock_453308077_th.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: /assets/images/shutterstock_102368917.jpg
    image_path: /assets/images/shutterstock_102368917_th.jpg
    alt: "placeholder image 2"
    title: "Image 2 title caption"
  - url: /assets/images/shutterstock_1095093683.jpg
    image_path: /assets/images/shutterstock_1095093683_th.jpg
    alt: "placeholder image 3"
    title: "Image 3 title caption"
gallery_james:
  - url: /assets/images/shutterstock_453308077.jpg
    image_path: /assets/images/shutterstock_453308077_th.jpg
    alt: "placeholder image 1"
    title: "Image 1 title caption"
  - url: /assets/images/shutterstock_102368917.jpg
    image_path: /assets/images/shutterstock_102368917_th.jpg
    alt: "placeholder image 2"
    title: "Image 2 title caption"
  - url: /assets/images/shutterstock_1095093683.jpg
    image_path: /assets/images/shutterstock_1095093683_th.jpg
    alt: "placeholder image 3"
    title: "Image 3 title caption"
  - url: /assets/images/shutterstock_453308077.jpg
    image_path: /assets/images/shutterstock_453308077_th.jpg
    alt: "placeholder image 4"
    title: "Image 4 title caption"
---

## William

<style>
.flex-container {
  /* We first create a flex layout context */
  display: flex;
  
  /* Then we define the flow direction 
     and if we allow the items to wrap 
   * Remember this is the same as:
   * flex-direction: row;
   * flex-wrap: wrap;
   */
  flex-flow: row wrap;
  
  /* Then we define how is distributed the remaining space */
  justify-content: space-evenly;
  
  padding: 0;
  margin: 0;
  list-style: none;
}

.flex-item-text {
  padding: 5px;
  margin-top: 10px;
  max-width: 300px;
}

.flex-item-video {
  padding: 5px;
  width: 300px;
  max-height: 400px;
  margin-top: 10px;
  line-height: 150px;
  color: white;
  font-weight: bold;
  font-size: 3em;
  text-align: center;
}
</style>

<div class="flex-container">
<div class="flex-item-video">
<iframe width="280" height="157" src="https://www.youtube.com/embed/Kqw5P_7R3ic" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<div class="flex-item-text">
<p>
William is a great horse!
He is a 9-year-old thoroughbred and he is friendly and cuddly.
He loves riding and is great with riders who are trying to build their confidence.
</p>
</div>
</div>

{% include gallery id="gallery_william" caption="Here are some more pictures of William." %}

## James

<div class="flex-container">
<div class="flex-item-video">
<iframe width="280" height="157" src="https://www.youtube.com/embed/Kqw5P_7R3ic" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<div class="flex-item-text">
<p>
James is a nice horse.
He likes to run and jump and is very energetic.
</p>
</div>
</div>

{% include gallery id="gallery_james" layout="half" caption="James is also a nice horse. His gallery is two by two instead of three by three." %}