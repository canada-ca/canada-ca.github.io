---
layout: post
title:  "Using expand/collapse for making choices"
pubdate: "September 18, 2020"
langpage: "https://blogue.canada.ca/2020/09/17/afficher-masquer.html"
date:   2020-09-18
published: true
draft: true
lang: en
alt: "Using expand/collapse for making choices"
description: "In November 2019, the DTO modified Canada.ca guidance to allow the use of the expand/collapse design pattern to present a choice between mutually exclusive answers."
---
Since March 2020, the Digital Transformation Office (DTO) has conducted over 45 usability tests and user research studies to offer evidence-based guidance that helped inform the publication of pandemic-related web resources. We are also relying on previous optimization projects to provide a more usable, consistent and trustworthy online experience on Canada.ca. 

The expand/collapse pattern is just one of many patterns in the Canada.ca design system library that can help you improve the way users interact with your web content. But use it with care!

## Testing the pattern with users

In November 2019, the DTO modified Canada.ca guidance to allow the use of the expand/collapse design pattern to present a choice between mutually exclusive answers. Also known as the accordion pattern, the expand/collapse pattern allows you to hide content until it’s requested or relevant. A trigger link shows or hides the content when a user selects it.

<div class="pattern-demo mrgn-bttm-md">
  <p>Example:</p>
  <details>
    <summary>You must click on this area to expand and collapse the content</summary>
    <p>This text is hidden until it is revealed.</p>
  </details>
</div>

The expand/collapse pattern was successfully tested during 2 optimization projects with the Canada Revenue Agency (CRA). In both projects, we used the pattern to simplify page layouts and reduce cognitive load. The pattern helps people find and focus on the content that’s relevant to their situation.

[Research summary: Contact the CRA](https://blog.canada.ca/research-summaries/cra-contact-us-research-summary.html)

Based on the positive results of our optimization projects, we’ve used the expand/collapse pattern on more pages to help Canadians find the answers they need regarding the COVID-19 pandemic.

* [Canada Emergency Response Benefit](https://www.canada.ca/en/services/benefits/ei/cerb-application.html#payments)
* [Canada Emergency Student Benefit](https://www.canada.ca/en/revenue-agency/services/benefits/emergency-student-benefit/cesb-how-much.html)
* [Canada’s COVID-19 Economic Response Plan](https://www.canada.ca/en/department-finance/economic-response-plan.html#individuals)

## When to use expand/collapse

You can use the expand/collapse pattern in 2 specific situations:

### 1. Presenting a choice between mutually exclusive answers

Use this pattern when people need different answers depending on their situation and when these answers are mutually exclusive. Research has shown that when all the options are visible, people tend to spend time reading answers that are irrelevant to their task. They may not realize the content is under a heading that doesn’t apply to them. They get confused and think they have the right answer when they don’t.

Using this pattern can help people focus only on what applies specifically to them. 

<br><figure>
<img class="img-responsive border" alt=" Below the question Is your direct deposit and mailing information up to date with the CRA? expand/collapse patterns offer 2 possible answers: Yes and No.The second image shows the Yes option expanded with the message, Great. This will ensure your benefit payment will be delivered to you."
 src="/images/expand-collapse-2.jpg" width="600">
</figure>
<figcaption>The expand/collapse pattern.</figcaption>
<br>

### 2. Presenting secondary information

You can also use this pattern to prevent secondary content from interfering with the main task.

This can be content that applies to most people, but that only a few people may need to use (for example, a privacy statement or additional details not needed to accomplish the main task).

It can also be content that applies only to a minority of people (such as when there is specific information for a specific audience).

<br><figure>
<img class="img-responsive border" alt=" Content about re-applying for CERB includes an expand/collapse pattern for 'If you start working again.' The second image shows the pattern expanded to display content for people who stop working and then start again during a later benefit period."
 src="/images/CERB.JPG" width="500">
</figure>
<figcaption>The expand/collapse pattern for one of the CERB pages.</figcaption>
<br>

The code and instructions for how to implement this pattern are in the Template and pattern library of the Canada.ca design system: 
* [Expand/Collapse - Canada.ca design pattern](https://design.canada.ca/common-design-patterns/collapsible-content.html)

## User-tested templates and layouts

Starting with user-tested templates, patterns and design principles can help your team get going quickly, saving you time and money. 

For more information on how to use this and other design patterns, check out the [Canada.ca design system](https://www.canada.ca/en/government/about/design-system.html).

## Learn more

* [Accordions on mobile](https://www.nngroup.com/articles/mobile-accordions/)
* [Expand/Collapse - Canada.ca design pattern](https://design.canada.ca/common-design-patterns/collapsible-content.html)
* [Improving content on Canada.ca](https://blog.canada.ca/pages/project-overview.html)

## Connect with the Digital Transformation Office at Treasury Board Secretariat

* Email: [dto.btn@tbs-sct.gc.ca](mailto:dto.btn@tbs-sct.gc.ca)
* Twitter: #Canadadotca (English) / #Canadapointca (French)
* Slack: [http://design-GC-conception.slack.com](https://design-gc-conception.slack.com/join/shared_invite/enQtODE1OTc5Mzg5NzQ4LWQ3MjZjMTdjMjk2ZTZmMTJjYWQ3ZmRiNDYwYjRmN2NjYzQyNjFlNDBlY2FkNWE1ODg2YjExY2QwZmVjN2MwMGM)
