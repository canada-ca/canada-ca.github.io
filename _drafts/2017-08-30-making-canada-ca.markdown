---
layout: post
title:  "Making Canada.ca for Canadians"
wordcount: 1066
gradelevel: 10.9
ref: template
date:   2017-08-30 15:43:44 +0100
categories: category
published: false
lang: en
---

In 2012, the Government of Canada began working towards a more centralized web presence. The vision for Canada.ca was to make it easier for Canadians to find what they were looking for, whichever department or agency might provide it. Here's the research and testing we did to tackle the challenge of designing the site's information architecture and navigation.

## Themes: bridges across the thousand islands

<img class="img-responsive" alt="Bridge across the Thousand Islands" src="/images/thousand-islands-bridge_600x400.jpg">

Image credit: [Ad Meskens](https://commons.wikimedia.org/wiki/User:Ad_Meskens)

While some people know which department provides a service, many don’t know or care. As each department and agency maintains a website of their own, there hasn't been a single online window where a Canadian could find all government services.

Canada.ca couldn't just be a list of island names. We wanted to develop a set of labels that would be meaningful to people who visited for the first time. They had to reflect the mental models of citizens, to be the obvious link to click to find their task.
 
Building a bridge, however, is not a simple process. We had to research the most in-demand services, consult with the departments that delivered them, brainstorm and research keywords, validate our labels with Canadians and, finally, figure out how to make them all fit on a webpage.

### Step 1: List our top tasks

The first thing we did when planning Canada.ca was to develop a list of the 100 most in-demand tasks that citizens undertook with the federal government. In 2013, we worked with departments and agencies to collect and analyze as much web traffic data as we could to create an inventory of top 100 Government of Canada tasks (such as renewing a passport or getting a local weather forecast).

### Step 2: Card sort with stakeholders

In June of 2013, we card sorted the top tasks with internal stakeholders to come up with a preliminary list of about 20 categories to organize Canada.ca content. 

After analysis and consultation, we proposed an initial set of 15 subject-based categories, such as taxes or immigration, that would form the main navigation for canada.ca. These would form the mortar to build bridges between the services and information on departmental websites. Internally, we've come to refer to these big topics as themes.

<!-- In addition to the themes and topics, there were also two more structures that came out of the card sort,
- 1 based on administrative categories like media or contact information
- 1 based on audiences like indigenous peoples or seniors 
*not sure this adds to the story, maybe worth tackling in a separate post?* -->

### Step 3: Tree test with Canadians

Coming up with the themes was only the first step, both for the structure and the navigation on Canada.ca. Underneath there are narrower topics and subtopics - in techincal terms, a hierarchical subject-based taxonomy. 

To try out our themes and topics with users, we did the first of many online tree tests with citizens in July 2013. In this test, 848 participants navigated (browsed?) the themes and the first layer of topics to choose where they would expect to accomplish representative top tasks.

<!-- insert image of treejack here -->

<!-- The tree we provided during the testing reflected both the theme and topic structure as well as the other structures that came out of the card sort. *not sure we need this para* -->

This demonstrated to us that many Canadians really were thinking through a subject-based approach. As a result, we were able to simplify our initial tree to remove unclear labels that didn't help citizens choose where to click. We were also able to inform some of the visual layout, by keeping content about government separate from services and information that were more directly focused on citizens.

### Step 4: Building out the rest of the navigation tree

With themes and top-level topics confirmed, we started to create deeper layers of the navigation tree. 

As each topic needs to reflect all government has to say about it, so as not to leave visitors stranded, departments with knowledge of the services and policies in each theme and topic area lead the development of the taxonomies.

Even now, 3 years later, theme leads are still making changes to the topic tree to make improvements to service findability. Usability  tests continue to be carried out to test these changes.

### Step 5: User interface test

In addition to tree testing, we also built designs for the pages and menus where the taxonomy would actually appear on the website. 

Because we had 15 top level themes and hundreds of topics between them, we needed to decide whether to create a simpler first level, such as putting all the themes under a "Services and information" menu, like Amazon's 'departments', displaying themes on more than one row, or hiding only a part of them under a "More services" option. 

<!-- para above: don't really recall this being part of the prototypes that we built, but it was a long time ago. are there screencaps? -->

Driven by our goals of improved findability and reduced time to task, we also needed to decide between a light navigation, with a menu all on one page, or pages for each topic, and what they could contain.

We built simple prototypes of two different options for themes and did usability testing with 30 citizens. Based on this, we adopted the design which is still in use today:

<img class="img-responsive" alt="Themes on canada.ca" src="/images/themes_1000x457.jpg">

## Ongoing testing and optimization

Research and testing on themes and navigation have only increased since Canada.ca was first launch and we will continue to refine the navigation model.

After 4 years, many of the bridges of topics and search are now in place and we're now shifting our focus to end-to-end task improvements.

## Find out more

We’re happy to share what we’ve learned. Email us at ux.eu@tbs-sct.gc.ca

## Explore further

* [Top task management on Canada.ca]() describes how we compiled the top 100 task list for Canada.ca and how we continue to improve it and use it to manage the website
* We've put together an overview of the testing we've done and research we've focused on over the past few years in [Canada.ca iterative improvements](https://canada-ca.github.io/category/2017/09/11/iterative-improvements.html)
* [How we're optimizing top tasks on Canada.ca](https://canada-ca.github.io/category/2017/08/21/optimization-overview.html) shares more about how we're focusing now on improving specific top tasks on Canada.ca
* [Tree testing](https://www.nngroup.com/articles/tree-testing/) is a good primer from the Nielson Norman Group on how to conduct tree testing for website navigation
* [New Thinking](http://gerrymcgovern.com/new-thinking/) is where Gerry McGovern posts weekly on a range of top task management and digital transformation themes 
* In [Why we say no to surveys and focus groups](https://www.dta.gov.au/blog/surveys-and-focus-groups/), Leisa Reichelt at Australia's Digital Transformation Agency describes the value their team gets from task-based usability testing
