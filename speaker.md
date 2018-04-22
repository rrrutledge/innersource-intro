This document holds [the shoot playbook segments](https://app.oreilly.com/authors/welcomekit/video.csp) that accompany the reader text in [main.html](https://github.com/rrrutledge/innersource-intro/blob/master/main.html) ([PDF view](https://github.com/rrrutledge/innersource-intro/files/1924845/InnerSource-Intro.pdf)).
The document also holds the bulleted list of speaker notes for each segment via this format:

## Title (Presenter)
_Segment description in complete sentences_

* Bulleted
* list
* of
* speaking
* notes

## Introduction (Danese & Russ)
_What is included in the "Introduction to InnerSource" learning path?  Meet the presenters and hear the summary of the learning path content._

* Each person introduces themselves.
* You are watching this video because you've heard about InnerSource and want to know what it's all about.
* Danese introduces the overall concept of inner source.
* Russ introduces the content of the segements.
  * the general thing that they're going to learn: know what it's about and how to talk about it using familiar, shared terms 
  * situations that are good candidates
  * key principles upon-which effective inner source is based
  * benefits that result from inner source efforts that follow them.

## What does InnerSource solve? (Russ)
_InnerSource is useful because it solves common problems in cross-team collaboration.  Learn the types of problematic situations where InnerSource can help._

* Example consumer wanting a feature from an example producer.
* For feature requests not taken, the consumer can:
* **Wait it out**
  * Wait and see if the producer will do the work later.
  * Advantage: least amount of work for the consumer.
  * Disadvantage: might never get the functionality.
  * Story: team wanting us to upgrade a library that was easier for them to support.
* **Work around**
  * Do extra work to compensate for the feature's absence
  * Advantage: Get the functionality by the team's own efforts only.
  * Disadvantages:
    * (consuming team): own the long-term burden of maintenance for the new code.
    * (other teams): can't use what the consuming team has built.
    * (company): duplicate effort in the same problem space.
  * We had to work around the QMA performing a case-sensitive check on incoming HTTP headers.
* **Escalate**
  * Try to influence the producer to do the work via appeal to their management chain from ours.
  * Advantage: Get the feature without needing to build or maintain it.
  * Disadvantage:
    * High friction -> lots of (non-productive) time for both consumers and producers.
    * Not scalable

## Solution Overview and detail (Danese)

## Solution Detail - up to 1st paragraph - definitions (Danese)

* Explanation we usually give about how house rules help you know how to behave and what to expect as a guest
* Hosts expect you’ll take your shoes off inside or that you won’t let the cat out, etc.
* Guests expect clean and perhaps private space

## Solution Detail

Really point out that the host team remains in control via specificying up-front any constraints on the completed work.

## Benefits (Danese/Russ)
* How to split up this section between us?
* (Danese) Key teams that were able to reduce interrupt-driven work by 60%, which gave them back their capacity to plan and execute
* (Russ) Segue on the scalability point by sharing the story of 5 teams building AWS EC2 deployment at once together.
* (Russ) Our small team of 3 engineers ran a continuous delivery pipeline that grew to be used by (nearly) 200 projects monthly.
* (Russ) The work of the team organically shifted to AWS Lambda deployment because that's where people wanted to contribute
* (Russ) After engineers learned how to talk to each other a natural way they started working together on other things - e.g. node-api-blueprint.

## Principles (Danese)

* This concept (mentorship) comes straight out of the Apache Way.
Trusted Committers are team members who not only understand the codebase well enough to coach someone else in writing good pull requests to achieve a desired outcome, but they also have the knack of passing on that wisdom in a constructive way.
In Open Source it is an honor to get voted to Trusted Committership.

## Conclusion (Russ & Danese)
* Russ summarizes the content of the training.
* Danese invites those watching to join the InnerSource Commons.
