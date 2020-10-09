---
layout: post
title:  "Collect feedback, find issues"
pubdate: "October 9, 2020"
langpage: "https://blogue.canada.ca/2020/10/09/recueillir-la-retroaction.html"
date:   2020-10-09
published: true
draft: true
lang: en
alt: "Collect feedback, find issues"
description: "Getting feedback from Canadians on a regular basis helps teams across government continuously improve the service delivery on Canada.ca. In May 2020, a few teams collaborated to launch a pilot study of a widget for getting people’s feedback on Canada.ca pages."
---
In 2020, the main way most Canadians interact with their government is online. Government of Canada web pages are more than just a communications tool. They’re an important service delivery point. 

Getting feedback from Canadians on a regular basis helps teams across government continuously improve the service delivery on Canada.ca. When people can find their answers online, it reduces emails and calls to call centres. 

But what if we could know sooner when people aren’t finding their answers online? 

## Pilot study

In May 2020, a few teams collaborated to launch a pilot study of a widget for getting people’s feedback on Canada.ca pages. The Digital Transformation Office (DTO) worked with: 
* Health Canada/Public Health Agency of Canada (PHAC) 
* Principal Publisher
* Privy Council Office 

The page feedback widget is just a question that sits at the bottom of a page, where the ‘Report a problem’ widget usually is. It asks, “Did you find what you were looking for?” Users can answer yes or no. If they answer no, they have the option to provide more details.

This simple widget is a powerful tool for content owners. It lets them passively monitor the effectiveness of their content. It provides regular insight into whether content is working as intended, and if not, why. 

On May 11 we added the widget to the bottom of two COVID-related pages:
* [Symptoms and treatment](https://www.canada.ca/en/public-health/services/diseases/2019-novel-coronavirus-infection/symptoms.html) 
* [Prevention and risks](https://www.canada.ca/en/public-health/services/diseases/2019-novel-coronavirus-infection/prevention-risks.html) 

### Goal of the pilot

Our goal for this pilot study was to:

* test a new approach for design research and measuring task success
* learn whether we would receive more usable feedback than ‘Report a problem’ 
* identify usability issues 
* inform iterative improvements to the content 
* experiment with machine learning and natural language processes to help sort the feedback

## Feedback widget

Service Canada/Principal Publisher built the widget. By embedding it into pages, departments can capture both qualitative and quantitative feedback from Canadians. 

<figure>
<img class="img-responsive border" alt="A long description can be found after the image."
src="/images/feedback-1.png" width="700">
</figure>
<details>
<summary>Page Feedback Widget</summary>
<p>Widget displays the question: "Did you find what you were looking for?" and offers yes and no options.</p>
</details>

<br><figure>
<img class="img-responsive border" alt="A long description can be found after the image."
src="/images/feedback-2.png" width="700">
</figure>
<details>
<summary>Next screen of Page Feedback Widget.</summary>
 <p>When users select "no," they are asked "What was wrong?" and given the following options:</p>
 <ul>
<li>The answer I need is missing</li>
<li>The information isn't clear</li>
<li>I'm not in the right place</li>
<li>Something is broken or incorrect</li>
<li>Other reason</li>
 </ul>
<p>Selecting "other reason" displays a free text field where they can provide more details, with direction not to include any personal information.</p>
</details>
<br>

## Processing feedback

Adobe Analytics processes the quantitative data - the number of yes versus no responses, and the preset answers for what was wrong. For the pilot study, text-based feedback went to a generic email account at Health Canada. Huge kudos to Health Canada/PHAC for going through the feedback and analyzing it.

Since this pilot, we’ve built a process that pulls text-based feedback directly into a database. We've been experimenting with machine learning to automatically classify it.  We’ve also built a web-based interface to help departments go through the feedback to find trends and insights.

Going through the text feedback can be time-consuming, so the more we can rely on automating the manual parts of this work, the easier it will be to consider a wider deployment of the widget across Canada.ca.

## Privacy

We knew there was a chance we could receive unsolicited personal information even though the widget advises people not to include any. To address this, we sought advice from:
* Privacy Management Division, Health Canada
* National Security Management Division, Health Canada
* IT Security, Health Canada
 
Based on the advice we got, the DTO created a process to strip personal information from incoming feedback. This helped reduce another element of manual processing. The more parts we can automate, the more time teams will have to focus on improvements.

## What we found

As of June 10, we had received 5083 responses through the 2 pilot pages the widget was on. That represented an average of 164 responses per day.

When people answered that they had not found what they were looking for, their answers for what was wrong gave us a clue about the top usability issues on the pages.

<br><figure>
<img class="img-responsive border" alt="A long description can be found after the image."
src="/images/Feedback-graph-1.png" width="700">
</figure>
<details>
<summary>Results of radio buttons analysis.</summary>
 <h3>What was wrong?</h3>
 <ul>
<li>The answer I need is missing</li>
<li>No reason given</li>
<li>Other reason</li>
<li>The information isn't clear</li>
<li>I'm not in the right place</li>
<li>Something is broken or incorrect</li>
</ul>
</details>
<br>

Of the 1015 “what was wrong” submissions, 782 (77%) provided more detail about what was wrong in their own words, using the text box.  

Using this feedback, we started to get a better picture of what was causing issues for people during their visit.  Content specialists then looked at the feedback to understand the detailed intent and causes of frustration.

<br><figure>
<img class="img-responsive border" alt="A long description can be found after the image."
src="/images/feedback-graph-2.png" width="700">
</figure>
<details>
<summary>Results of open text analysis.</summary>
 <h3>Top 10 Themes Referenced</h3>
 <ul>
<li>Symptoms</li>
<li>Permissible activities</li>
<li>Testing</li>
<li>Transmission</li>
<li>Quarantine isolation self-isolation</li>
<li>Treatment</li>
<li>Workplaces</li>
<li>Financial support</li>
<li>Vulnerable Populations</li>
<li>PPE</li>
</ul>
</details>
<br>

This detail enabled Health Canada/PHAC to: 
* triage efforts based on how often they saw similar feedback
* identify areas for improvement
* identify potential gaps in content
* understand if a page had broad issues they needed to assess

For example, we saw a large percentage of feedback asking about less common COVID-19 symptoms that weren’t listed on the Symptoms page. This insight provided evidence to support adding those symptoms to the list.

## Key lessons learned

* The text box provides meaningful feedback from people that is directly related to the content and what they are looking for
* Text-based feedback lets web teams identify terms used by Canadians to support plain language 
* Embedding the feedback widget in the page creates a seamless experience for people
* Two weeks appeared to be enough time to identify patterns and areas for improvement on high traffic pages
* The widget is a fast and cost-effective method for gathering content insights
* The tool helps normalize measuring your content effectiveness and making iterative improvements after it’s published
* The continuous nature of the widget lets teams see the effects of their improvements immediately by monitoring changes in the type of feedback they get  

## Next steps from this pilot

* Pilot the widget on more pages both within and external to AEM (Adobe Experience Manager)
* Refine some functionality of the widget
* Continue refining our machine learning processes
* Develop “dashboards” to see trends and issues at a glance
* Work towards a wider roll-out of the tool

## Final word

Ultimately, the purpose of receiving feedback is to improve web services so that our content can better meet the needs of Canadians. The page feedback widget is a useful tool that provides web, program, and policy teams with valuable insight for service delivery. Lessons learned from this can help us support content guidance and recommendations.

Finally, a big thank you goes to our partners on this pilot. 

## Learn more

* [Increase the feedback - Gerry McGovern](https://medium.com/@gerrymcgovern/increase-the-feedback-3a0d4c904762)

## Connect with the Digital Transformation Office at Treasury Board Secretariat

* Email: [dto.btn@tbs-sct.gc.ca](mailto:dto.btn@tbs-sct.gc.ca)
* Twitter: #Canadadotca (English) / #Canadapointca (French)
* Slack: [http://design-GC-conception.slack.com](https://design-gc-conception.slack.com/join/shared_invite/enQtODE1OTc5Mzg5NzQ4LWQ3MjZjMTdjMjk2ZTZmMTJjYWQ3ZmRiNDYwYjRmN2NjYzQyNjFlNDBlY2FkNWE1ODg2YjExY2QwZmVjN2MwMGM)
