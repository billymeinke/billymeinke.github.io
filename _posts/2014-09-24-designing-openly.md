---
layout:     post
title:      "Designing openly"
subtitle:   "Free software & conference media production"
date:       2015-04-09 12:00:00
author:     "Billy Meinke"
header-img: "img/floral.png"
---
<div class="row">
<div class="col-md-8">
<h1>Over the last several years</h1><p> I've volunteered time with TCC Hawaii, an organization behind the TCC Conference - credited as the first fully-online conference to exist. The web was young in 1996, and the conference relied upon a listserv (mailing list) to connect all the attendees and support conversation around online learning. You can check out a fun presentation from Alan Levine <a href="http://cogdogblog.com/2015/03/19/tcc20/">here</a>, with a rundown of how technology (specifically ICT) and education have changed in the last 20 years.</p>
</div>
<div class="col-md-4">
<img src="{{ site.baseurl }}/img/keynote-flyer.png" alt="TCC 2015 keynote flyer advertisement" class="img-responsive">
</div>
</div>
<p>Two years ago, co-designed the participation badges offered at the TCC conference with the conference organizers Bert Kimura and Curtis Ho, along with grad students in the ETEC department. This year, we worked on the conference's branding and logo, testing out designs I made entirely with free software and some good feedback from other folks working behind the scenes. I wanted to document the process for a couple reasons, but also that I want to be able to reference the process the next time I need to use these tools.</p>

<h2 class="section-heading">Free things</h2>

<p>Things that you don't have to pay for are great. And things that you can do anything you want with (on top of just using as-is) is even better. Fortunately, the software I used to create the flyers, stickers, and the stage banner for TCC are all free software. The icons came from the Noun Project, and the font from Mozilla. Here's a rundown of the free stuff I used:</p>

<p>
	<ul>
		<li><a href="https://gimp.org"><b>GIMP</b></a> (Gnu Image Manipulation Program) // raster graphics editing</b></a></li>
		<li><a href="https://inkscape.org"><b>Inkscape</b></a> // vector graphics editing</li>
		<li><a href="https://www.nounproject.org"><b>The Noun Project</b></a> // various icons/shapes, pattern-making tutorial</li>
		<li><a href="https://www.mozilla.org/en-US/styleguide/products/firefox-os/typeface/"><b>Fira Sans</b></a> // Mozilla font</li>
	</ul>
</p>

<p>Interestingly enough, I wouldn't say it took any extra effort to use free/open content and software to create these media bits. It's more evident that the workflows I've been following have removed the need for most non-free resources when designing media. Here are my notes about creating these things openly.</p>

<h2 class="section-heading">Iconifying things at the Noun Project</h2>

<p>I ventured to the Noun Project to take a look at the latest icons that might represent Hawaii (where the conference is based), online education, and community. Here's a snapshot of the icons I downloaded while poking around:</p>

<div class="row">
<div class="col-lg-10 col-lg-offset-1">
<a href="https://thenounproject.com/billymeinke/downloads/"><img src="{{ site.baseurl }}/img/icon-dl.png" alt="Billy Meinke's favorite on the Noun Project" class="img-responsive"></a>
</div>
</div>

<p>You might notice that some of the icons are replaced with a black box. This appears to be a Noun Project glitch, and I haven't looked into why this happens. I occasionally find icons that have anomolies in them, sometimes corrupting only the SVG but not the PNG file, or vice versa.
</p>
<p>At any rate, I downloaded the PNGs to Google Drive and had the conference social media team offer feedback on the designs. After several iterations, we settled on using a globe icon with a hibiscus overlay (which began as 2 separate icons), and a Hawaiian canoe for the main design. I also chose another flower design to create the patterned background for the flyer and stage banner.
</p>

<div class="row">
<div class="col-lg-10 col-lg-offset-1">
	<img src="{{ site.baseurl }}/img/icons-early.png" alt="Post Sample Image" class="img-responsive">
</div>
</div>

<p>The image above show the second-iteration sticker designs, but there was a unanimous vote for the canoe icon to be used, but on a round sticker. The blue and green colors were found after dropping the conference website's base colors into Adobe's <a href="kuler.adobe.com">Kuler</a> tool and looking for colors that would play nice with the existing branding TCC has in place.
</p>

<h2 class="section-heading">Patterns a plenty</h2>

<p>After having come across a handful of neat-looking patterned backgrounds on websites and print media, I was lucky enough to spot a tutorial shared through the Noun Project's <i>Gazette</i> newsletter that explained the process. The author used Adobe Illustrator in the tutorial, so I had to adapt the process for use with GIMP. Aside from menu items being in slightly different places, and the UI looking somewhat different, I'm not missing anything that could be accomplished by paying for software to get this job done.</p>

<p><a href="http://mrare.ca/blog/how-to-make-a-repeatable-pattern-in-illustrator">How to make a repeatable pattern in Illustrator</a>
</p>

<p>The process essentially helps you create a pattern tile that can be placed into the program files of your image editing program (in my case Inkscape) and then used as a pattern fill in GIMP. At first I created a much more complex pattern, but opted for a more simple design after exporting it and testing it as a fill.
</p>

<div class="row">
<div class="col-lg-8 col-lg-offset-2">
<img src="{{ site.baseurl }}/img/flower-pattern.png" alt="Post Sample Image" class="img-responsive">
</div>
</div>

<p>Locating the folder I needed to copy the pattern image file into (seen above) was a pain, as it wasn't documented very well anywhere I could find quickly. I thumbed through several tutorials that led users through a similar file structure and generalized their directions for GIMP. Once the pattern was in the folder and GIMP was restarted, my pattern appeared as a fill option.</p>

<div class="row">
<div class="col-lg-10 col-lg-offset-2">
<img src="{{ site.baseurl }}/img/patterns-menu.png" alt="GIMP pattern menu tool window" class="img-responsive">
</div>
</div>

<h2 class="section-heading">From GIMP to print</h2>

<p>I used GIMP to create PNG and PDF image files for the print media, which the icons and patterns would be a part of. I use GIMP fairly often, and this time it allowed me to construct print media ranging from 2" round stickers to the 70"x24" stage banner. Printing costs weren't terrible, ~$120/ea for the large banner and several hundred stickers. The 11"x17" flyers worked out to about $3/ea, which seemed a bargain.</p>

<div class="row">
<div class="col-lg-10 col-lg-offset-1">
<p class="caption"><a title="Curtis Says Ho" href="http://flickr.com/photos/cogdog/16248339604"><img src="http://farm9.static.flickr.com/8624/16248339604_707530e778.jpg" class="img-responsive" alt="Curtis Ho at TCC 2015"/></a><br /><small><a href="http://creativecommons.org/licenses/by-sa/2.0/">Licensed CC BY-SA</a> <a title="Curtis Says Ho" href="http://flickr.com/photos/cogdog/16248339604">Flickr photo</a> by <a href="http://flickr.com/people/cogdog">cogdogblog</a></small></p>

<p class="caption"><a title="Presenting With Friends" href="http://flickr.com/photos/cogdog/16239792704" alt="TCC 2015 banners"><img src="http://farm8.static.flickr.com/7638/16239792704_1367a2b426.jpg" class="img-responsive" /></a><br /><small><a href="http://creativecommons.org/licenses/by-sa/2.0/">Licensed CC BY-SA</a> <a title="Presenting With Friends" href="http://flickr.com/photos/cogdog/16239792704">Flickr photo</a> by <a href="http://flickr.com/people/cogdog">cogdogblog</a></small></p>
</div>
</div>

<h2 class="section-heading">Rounding it out</h2>
<p>Well, that's the gist of how I used free software and a few hours here and there to create conference media for TCC 2015. Documenting and reflecting on work projects is something I lost touch of over the last several years. With any luck (and the recent standing up of my Jekyll-based blog on Github pages), there will be more to come soon.</p>

<p class="small">*All icons on the page are used under a CC BY license or are in the Public Domain. Yes, I paid $1.99/ea on the Noun Project to the creators of icons I used in the print media but did not provide attribution for. Totally worth it.</p>