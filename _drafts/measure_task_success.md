---
layout: post
title:  "Measuring findability and task success"
ref: template
date:   2018-01-02 09:48:44 +0100
categories: category
published: false
lang: en
---
Task success is a critical measurement for Canada.ca. Over the years, success rates for most top tasks have been measured in moderated task-based scenario research studies with Canadians.  As we conducted these studies across the vast scope of Canada.ca, we realized that we needed a new way to break down task success metrics to make the results actionable for the right teams.  The team of Theme Leads are responsible for the design of the navigation layer on Canada.ca - the menus and topic pages. Specialists within government institutions tend to work on the destination page content, where user tasks are usually completed. To help assess the success of the navigation layers and Search and identify gaps caused by the content itself, we broke out Findability from the Task Completion Rate. 

Findability success rate
Defined as the percent of participants who visited the target answer page(s) for the task during their task attempt. 
* Usually there is only a single target page, but in some cases, the task can be solved from several pages, in which case all are included as targets. 
* In some cases, the search result snippet for the target page shows enough detail that people can solve the task from the snippet alone. We coded these cases as successful for findability as well, since they used the content of the target page.  
* Findability example: For the task of finding out whether your symptoms are more likely to be the flu versus a cold, the target page selected by the team was the [Flu Symptoms page](https://www.canada.ca/en/public-health/services/diseases/flu-influenza/symptoms-flu-influenza.html).
** 100% of 16 smart phone participants in the Baseline test study found the Flu Symptoms page.  94% (15 of 16 smartphone participants) found the Symptoms page in the Validation study. 

<img class="img-responsive" alt="Chart bars for 100 per cent findability and 50 per cent completion - arrow shows gap of 50%" src="/_images/Content_gap-en.PNG">

Task completion rate = the percent of participants who correctly answered the task, either from the task content on the target page or from correct content on a page other than the target page(s). 
* Task completion example: The flu symptoms target page showed a list of flu and cold symptoms. Participants had to select both headache and fever from a list of symptoms as the most important signals that they had the flu rather than a cold. 
** Only 50% of participants in the baseline study correctly selected both headache and fever, despite finding the target page. We call high findability and low completion a 'Content understanding gap'. 
** Based on what the team learned by watching the task videos of the baseline participants, [the prototype Symptoms page](https://gc-proto.github.io/health-1/validation/services/diseases/flu-influenza.html) was redesigned to focus on answers vs information. The new design included a mobile-friendly version of the symptoms table from the [Is it a cold or the flu poster page](https://www.canada.ca/en/public-health/services/publications/diseases-conditions/is-it-cold-or-flu.html) - 2 of the successful participants in the baseline study had found the link to the poster and used it to succeed.   The gap was completely resolved by the redesign - only 1 participant failed to find the target page and also failed to complete the task. 

## Potential findability and task completion result sets

Findability | Completion | Example
--- | --- | ---
Success | Success |  Found and used target Flu Symptoms page to correctly answer with Fever and Headache
Success | Failure |  Content understanding gap: Found Flu symptoms page but answered incorrectly, usually Fever and Cough 
Failure | Success |  Findability gap: No one happened to find an old PDF in GC publications but they could used it to answer correctly
Failure | Failure |  Didn't find the Flu symptoms page, didn't select the correct answer

Measuring Success and Findability separately allows us to be accurate and consistent in our coding, especially when people search to find the answers. Findability requires that the team declare target pages prior to the testing for a particular task scenario - just as they predeclare the successful answer to the task. The path and the target pages are usually the ones designed to hold the answer to the task, although in some cases, the design may not have been well-thought-out prior to the measurement study. In a sense, the team is stating and pre-registering their hypothesis about the path to successfully completing the task.

* In our Flu symptoms example, the team selected the Symptoms page as the target because it is designed to show the answer. We hypothesized that a few might find the link to the poster or find the poster via search. 

Coding task completion is somewhat simpler once findability is broken out. We start with participants who answered correctly while viewing the target page. If the person was using the target page, usually the only way to get the correct answer is by successfully using a tool, or opening a tab or reading the answer, so they are clearly successful.

* On the flu symptoms page, half the people who got to the target page answered incorrectly - they skimmed too quickly and/or didn't understand that they had to mentally remove the cold symptoms from the flu list to correctly identify the 'flu only' symptoms. The 2 who went on to use the poster were able to be confident in their correct answer.

In a situation where people find the answer on a non-target page, the coding requires a little more work. Usually we review the video to see if the page they had reached does directly display the answer the task, in which case they are coded as successful. More often, the page they found didn't address the answer in enough detail to correctly derive the answer, and people took a lucky guess at the correct answer, which we code as a task completetion failure.


