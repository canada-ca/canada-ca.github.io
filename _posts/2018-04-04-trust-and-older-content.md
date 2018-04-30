---
draft: true
layout: post
title: "Dates matter: Trust and older content on Canada.ca"
gradelevel: 8
ref: datesmatter
date:   2018-04-04 09:48:44 +0100
datemodified: "Date modified: April 4, 2018"
published: false
lang: en
alt: Screenshot of a Canada.ca page showing the date modified
description: In a recent usability study, we saw people disregarding Canada.ca search results that seemed too old. Find out how you can validate your content and show that it's still current.
---
**By Patrick Lajeunesse, Digital Transformation Office**

In a recent usability study, we saw people disregarding Canada.ca search results that seemed too old. They assumed that because the page had not been “modified” for some time that the information on that page could not be relied upon. However, the content was perfectly valid and had in fact just been reviewed.

How can we can help show that content is still relevant? By indicating when pages were last reviewed for accuracy.

## You can see how old content is on Canada.ca ##

<img class="img-responsive border" src="/images/dates-matter/pagewithdate-small-en.jpg" alt="Screenshot of a blurred Canada.ca page showing the date modified near the bottom on the left side." />

(You'll see the date this post was published if you look near the bottom of this page.)
Since it's in the same place on every Canada.ca web page, people can count on finding the date if they want to know how current the information is.

The second place people see the date is in search engine results. Both on Internet search engines:

<img class="img-responsive border" src="/images/dates-matter/blog-date-internet-serp-en.png" alt="Internet search results page for 'Vaccines while pregnant' showing a Canada.ca result (Vaccinations and pregnancy) with June 30, 2015 highlighted">

...and on Canada.ca search:

<img class="img-responsive border" src="/images/dates-matter/blog-date-canadadotca-serp.png" width="1024" alt="Canada.ca search results page for 'vaccines while pregnant' showing a result (Vaccinations and pregnancy) with June 20, 2015 highlighted">

## Why content age matters ##

When trying to accomplish a task, people really notice the age of the content presented. The more recent your content looks, the more credible it seems to people. Without this piece of information they may not be successful finding what they are looking for.
That’s why the design guidance for Canada.ca requires you to implement the “Date modified” component.

<ul><li> <a href="https://www.canada.ca/en/treasury-board-secretariat/services/government-communications/canada-content-information-architecture-specification/headers-footers-navigation.html#toc3">Headers, footers and navigation for Canada.ca</a></li></ul>

But for it to be useful for people, the component needs to be managed well. And that can be the difficult part. Often, if there's no reason to update the content, we don’t review it. Then the “Date modified” stays the same as the date published.

Content can start to look old even if it's still accurate and relevant. This creates problems, especially with content that can appear out-of-date quickly.


## Watch people disregarding old content ##

In this video, Canadians are trying to see if it's safe for pregnant women to get the flu shot (it is and they should!). Here's what happens when they see that content is from more than 2 years ago:

{::nomarkdown}
<figure class="wb-mltmd wb-init video cc_on">
	<video poster="/images/dates-matter/old-content-video-poster.jpg" title="Thinking information is out of date">
		<source type="video/mp4" src="/images/dates-matter/trust-of-old-content.mp4" />
		<track src="#inline-captions" kind="captions" data-type="text/html" srclang="en" label="English" />
	</video>

<figcaption>
<details id="inline-captions">
				<summary>Transcript: People looking at older content</summary>
  <p class="wet-boew-vd">(Participant 1)</p>
				<p class="wet-boew-vd">(Video showing someone looking at a Canada.ca search results page. Text appears pointing to a result for "Vaccination and pregnancy", which has a date of "June 20, 2015".)</p>
				<span class="wb-tmtxt" data-begin="6.02s" data-dur="6.84s">And, so this is from 2015 so I'll just scroll down a little bit to see if maybe...</span>
				<p class="wet-boew-vd">(The picture zooms into filter controls on the side of the page. The mouse moves over "By date: Past year" and clicks the link.)</p>
				<span class="wb-tmtxt" data-begin="14.12s" data-dur="4.84s">...maybe from the past year - I'll filter my results...</span>
				<p class="wet-boew-vd">(The search results reload and the Vaccination and pregnancy page is gone.)</p>
				<span class="wb-tmtxt" data-begin="17.12s" data-dur="4.84s">...in case there's something more current.</span>
				<p class="wet-boew-vd">(Text appears saying that "The filter hid the best result".)</p>
				<p class="wet-boew-vd">(Participant 2)</p>
				<p class="wet-boew-vd">(Someone is looking at a Canada.ca search results page on a mobile phone.)</p>
				<span class="wb-tmtxt" data-begin="26.12s" data-dur="3.84s">This information goes back to 2015.</span>
				<p class="wet-boew-vd">(They tap the first result and see the Vaccination and pregnancy page. They begin scrolling down.)</p>
				<span class="wb-tmtxt" data-begin="29.00s" data-dur="4.84s">I wonder if there's anything that's newer than that.</span>
				<span class="wb-tmtxt" data-begin="32.00s" data-dur="3.84s">Although that's still pretty current...</span>
				<span class="wb-tmtxt" data-begin="36.41s" data-dur="3.84s">...I'd feel better if there was something a little newer.</span>			
				<p class="wet-boew-vd">(Participant 3)</p>
				<p class="wet-boew-vd">(Another person on a different mobile phone is looking at Canada.ca search results. They scroll down and look at the first result.)</p>
				<span class="wb-tmtxt" data-begin="48.72s" data-dur="2.84s">Vaccination and pregnancy ok...</span>
				<p class="wet-boew-vd">(They seem ready to tap the link to the page, but hesitate.)</p>
				<span class="wb-tmtxt" data-begin="52.42s" data-dur="3.84s">...but that's like from 2015</span>
				<span class="wb-tmtxt" data-begin="55.12s" data-dur="3.84s">Where's the latest information from it?</span>
</details>
</figcaption>
 {:/nomarkdown}

Even if the information is perfectly valid, people still thought there should be something newer.

## Review content regularly to confirm it’s up to date, not just when you change it ##

Review your content regularly as part of your content management lifecycle. How often to review depends on the content. Make sure you understand the business lifecycle of the content and review as often as makes sense.

These tests have confirmed something we've had our eye on for a while. Currently, our guidance suggests only updating the “Date modified” component when making significant changes to content. We’ll be making changes to the guidance to reflect the need for a regular content review cycle that reaffirms content currency for people on Canada.ca.

## If you reviewed the page and it's still valid, update its “Date modified” ##

If you've done a full review of the content and decided it's still valid, then you can update the “Date modified” component. The date issued remains the same, but this provides a signal that the content has been assessed and is still current.

It's very important not to update the “Date modified” component of pages without the proper review, just because you want to make them <strong>look</strong> new. Knowing the actual date something was modified or reviewed is important. It should only be done as part of a content lifecycle review process that has actually determined that the content is still valid.

## We want to hear from you ##

Let us know what you think about optimization for Canada.ca. Email us at <a href="mailto:information@tbs-sct.gc.ca">information@tbs-sct.gc.ca</a> or tweet using the hashtag <a href="https://twitter.com/search?q=%23Canadadotca">#Canadadotca</a>.

## About Patrick
<div class="col-md-3 col-xs-12">
   <div class="pull-left" style="margin-bottom: 15px;">
   <img class="img-responsive" style="margin-bottom: 15px;" src="/images/DTO-aboutus/DTO_blog_photo_DSC_3035_277x370.jpg" width="185px" alt="Patrick Lajeunesse" />
      Patrick Lajeunesse <br />
      <b>Senior Design Researcher</b>
   </div>
</div>

<div class="col-md-9 col-xs-12">
<figcaption>

<p>Patrick has been working in user experience design and research for 20 years. With a degree in Psychology, he applied his research and analysis training to digital communications and design for the United Nations and other international agencies based in Geneva, Switzerland before moving to Ottawa.</p><p>He spent a decade working in start-ups based in Ottawa and Connecticut, leading design for products used by some of the largest school districts in the United States. Patrick has been working to improve service delivery for the Government of Canada since 2009.</p>

</figcaption>
</div>
