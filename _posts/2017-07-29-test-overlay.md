---
title:  "Test: OVERLAY"
date:   2017-07-29 23:36:53 -0300
layout: single

author: Billy Rick
author_profile: true

header:
#  overlay_image: /assets/images/beans.jpg
   overlay_color: "#333"

categories: ['artes visuales', 'cine']
---
Prueba de imagen, agregando imagen al header, utilizando teaser, image y og_image.

#### UNA

<figure>
	<a href="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_b.jpg"><img src="http://farm9.staticflickr.com/8426/7758832526_cc8f681e48_c.jpg"></a>
	<figcaption><a href="http://www.flickr.com/photos/80901381@N04/7758832526/" title="Morning Fog Emerging From Trees by A Guy Taking Pictures, on Flickr">Morning Fog Emerging From Trees by A Guy Taking Pictures, on Flickr</a>.</figcaption>
</figure>

#### DOS

Apply the `half` class like so to display two images side by side that share the same caption.

<figure class="half">
	<a href="/assets/images/emoticon_10x6.gif"><img src="/assets/images/emoticon_10x6.gif"></a>
	<a href="/assets/images/libro_10x6.gif"><img src="/assets/images/libro_10x6.gif"></a>
	<figcaption>Dos imágenes muy bonitas</figcaption>
</figure>

#### TRES

Apply the `third` class like so to display three images side by side that share the same caption.

<figure class="third">
	<img src="/assets/images/emoticon_10x10.gif">
	<img src="/assets/images/libro_10x10.gif">
	<img src="/assets/images/emoticon_10x10.gif">
	<figcaption>Tres imágenes muy hermosas.</figcaption>
</figure>

## Alineación de imágenes

Centrada

![image-center]({{ site.url }}{{ site.baseurl }}/assets/images/emoticon_10x10.gif){: .align-center}

Izquierda

![image-left]({{ site.url }}{{ site.baseurl }}/assets/images/emoticon_10x10.gif){: .align-left} The rest of this paragraph is filler for the sake of seeing the text wrap around the 150×150 image, which is **left aligned**.

As you can see the should be some space above, below, and to the right of the image. The text should not be creeping on the image. Creeping is just not right. Images need breathing room too. Let them speak like you words. Let them do their jobs without any hassle from the text. In about one more sentence here, we'll see that the text moves from the right of the image down below the image in seamless transition. Again, letting the do it's thing. Mission accomplished!

Sin alinear

![no-alignment]({{ site.url }}{{ site.baseurl }}/assets/images/emoticon_10x10.gif)

Derecha

![image-right]({{ site.url }}{{ site.baseurl }}/assets/images/emoticon_10x10.gif){: .align-right}

And now we're going to shift things to the **right align**. Again, there should be plenty of room above, below, and to the left of the image. Just look at him there --- Hey guy! Way to rock that right side. I don't care what the left aligned image says, you look great. Don't let anyone else tell you differently.
