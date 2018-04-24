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
_This segment presents the type of collaboration situation in which InnerSource applies.
We'll review 3 common approaches to this situation and the benefits/drawbacks of each.
InnerSource provides a way to achieve those desired benefits without the associated drawbacks._

* Example consumer wanting a feature from an example producer.
* For feature requests not taken, the consumer can:
* **Wait it out**
  * Wait and see if the producer will do the work later.
  * Benefits: least amount of work for the consumer.
  * Drawbacks: Don't get the functionality (might never get it).
  * Story: team wanting us to upgrade a library that was easier for them to support.
* **Work around**
  * Do extra work to compensate for the feature's absence
  * Benefits: Get the functionality by the team's own efforts only.
  * Drawbacks:
    * (consuming team): own the long-term burden of maintenance for the new code.
    * (other teams): can't use what the consuming team has built.
    * (company): duplicate effort in the same problem space.
  * We had to work around the QMA performing a case-sensitive check on incoming HTTP headers.
* **Escalate**
  * Try to influence the producer to do the work via appeal to their management chain from ours.
  * Benefits: Get the feature without needing to build or maintain it.
  * Drawbacks:
    * High friction -> lots of (non-productive) time for both consumers and producers.
    * Not scalable

## How Do I InnerSource? (Danese)
_This segment explains how InnerSource works at a high level.  You'll also learn and also the key terms to use when discussing InnerSource._

* Consuming team submits code fufilling the feature request to the producing team.
* Explanation we usually give about how house rules help you know how to behave and what to expect as a guest
* Hosts expect you’ll take your shoes off inside or that you won’t let the cat out, etc.
* Guests expect clean and perhaps private space
* Define the **Product Owner** and **Trusted Committer** on the Host team as well as the **Contributor** on the guest team.
* Describe how all 3 work together to get the code in.
* Point out that the host team remains in control via specifying up-front any constraints on the completed work.

## What are the benefits of InnerSource? (Russ)
* Guest team gets their feature now without the long-term burden of maintaining it.
* Others can use the work of the guest team.
* Host team gets a desired feature.
* Scalability for the host team.
  * Key teams that were able to reduce interrupt-driven work by 60%, which gave them back their capacity to plan and execute
  * 5 teams building AWS EC2 deployment at once together.
  * Force multiplier for sustained output from the host team.
* Better requirements and prioritization alignment.
  * The work of the team organically shifted to AWS Lambda deployment because that's where people wanted to contribute
* Break down traditional silos.
  * After engineers learned how to talk to each other a natural way they started working together on other things - e.g. node-api-blueprint.

## What are the underlying principles of InnerSource? (Danese)

* This concept (mentorship) comes straight out of the Apache Way.
Trusted Committers are team members who not only understand the codebase well enough to coach someone else in writing good pull requests to achieve a desired outcome, but they also have the knack of passing on that wisdom in a constructive way.
* In Open Source it is an honor to get voted to Trusted Committership.
* Mentorship must be prioritized to be effective.
* Participation in an InnerSource contribution is voluntary on the part of both the guest and host teams.

## Conclusion (Russ & Danese)
* Russ summarizes the content of the training.
* Danese invites those watching to join the InnerSource Commons.
