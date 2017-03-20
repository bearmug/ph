---
layout: "post"
title: "Multiple Galleries"
subtitle: "A post with multiple galleries arranged with ISOTOPE"
active: "journal"
image:
  feature: "pc007.jpg"
date: "2016-02-01"
header-img: "img/postcover/pc008.jpg"
comments: "true"
gallery1: 
  - image_path: /gallery/archive/ph01/bg01.jpg
    image-caption:
    image-copyright: © bearmug
  - image_path: /gallery/archive/ph01/bg02.jpg
    image-caption:
    image-copyright: © bearmug
  - image_path: /gallery/archive/ph01/bg03.jpg
    image-caption:
    image-copyright: © bearmug
gallery2: 
  - image_path: /gallery/archive/ph05/bg01.jpg
    image-caption:
    image-copyright: © bearmug
  - image_path: /gallery/archive/ph05/bg02.jpg
    image-caption:
    image-copyright: © bearmug
  - image_path: /gallery/archive/ph05/bg03.jpg
    image-caption:
    image-copyright: © bearmug
---


<html class="no-js" lang="en">
<head>
	<meta content="charset=utf-8">
</head>

    <body>

<section id="content" role="main">
		<div class="wrapper">
	<br><br>
			<h2>{{page.title}}</h2>




<p> Content of your post HERE </p>

<p> Add as many paragraphs amongst your galleries as you want. </p>


           <!-- Gallery __-->
			
{% include subgallery.html id="gallery1" %}

<!-- end of GALLERY __ -->

<p> Add as many galleries as you want, including as many photos as you want. Simply edit the <b>FRONT MATTER</b> of the post, adding the corresponding <b>path</b>, <b>caption</b> and <b>copyright</b> info for each one of your photos. </p>

           <!-- Gallery __-->
			
{% include subgallery.html id="gallery2" %}

<!-- end of GALLERY __ -->

		</div><!-- end of WRAPPER __ -->
	</section>

