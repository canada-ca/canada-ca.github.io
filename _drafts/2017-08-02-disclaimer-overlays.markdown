---
layout: post
title:  "Using overlays for disclaimers"
ref: template
date:   2017-08-02 09:48:44 +0100
categories: category
lang: en
---

There are many scenarios on Canada.ca when citizens provide input, such as registering or signing in to a service, participating in a consultation or providing feedback. Soliciting this kind of input also means dealing with terms of use, privacy statements or similar disclaimers.

## Usability issue

During usability testing in August and October 2016 on how people interact with consultations on Canada.ca, we observed that disclaimers were often a barrier to participation. This was because in many cases, people were forced to actively provide their consent, even though according to the TBS Directive on Privacy Practices, [consent is usually not required](https://www.tbs-sct.gc.ca/pol/doc-eng.aspx?id=18309).

IS THERE A CLIP WE CAN EMBED?

The core issue here is that for someone who wants to participate in an online consultation, the process of registering and logging in is secondary to their main goal of sharing an idea or providing a comment. Forcing people to wade through disclaimers as part of this process exacerbates this situation by:

* blocking their path with large blocks of difficult-to-parse text
* requiring them to agree or consent to the content of the disclaimer.

Registering or logging in should be handled as quickly as possible, so also making viewing  them down even further on their path to participating. (Better yet, look for ways to avoid requiring registration in the first place!)  

## Solution 

To mitigate this issue, we leveraged the overlay design pattern, which allows secondary content to be available if people are interested, but doesn’t force them to access it.

<img class="img-responsive" alt="disclaimer overlay mockup" src="/images/disclaimer-overlay_776x575.png">

Many variations of overlays are available in the Web Experience Toolkit, but to ensure maximum accessibility, we recommend the [WET Centred popup (Lightbox)](http://wet-boew.github.io/wet-boew/demos/overlay/overlay-en.html) component.

This pattern will be documented in the next iteration of the [Canada.ca Content and Information Architecture Specification](https://www.canada.ca/en/treasury-board-secretariat/services/government-communications/canada-content-information-architecture-specification.html) – look for disclaimer overlays in the section on common design patterns.

## Design recommendation

When a disclaimer is required, using overlays will help you reduce barriers to input, so that citizens can more easily get on with their task. 
