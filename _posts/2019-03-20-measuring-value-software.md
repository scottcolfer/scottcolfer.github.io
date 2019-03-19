---
layout: post
title: "How do we measure the value of software features of public services?"
date: 2019-03-20
---

_This is the third in a short series of posts about digital transformation's need for business models, you can read the introductory post [here](https://scottcolfer.com/2019/03/17/digital-transformation-business-model.html)._

We've established that [it's possible to measure value when we're focussed on helping people over profit](https://scottcolfer.com/2019/03/19/value-without-profit.html), we just need to focus on **public value** over private value.

But **public value** is too big to be practical for me, from my position in the 'digital' bit of the Civil Service. I need [SMART](https://en.wikipedia.org/wiki/SMART_criteria)-er value that fits my bit of the world.

## Measuring the outcomes of software

First a reminder: value is context specific:
> “Value” is the most ambiguous word in business. It means something different to every person that says it, primarily based on where they’re positioned in an organisation. ***[Defining value: the most ambiguous word in product development](https://medium.com/swlh/defining-value-the-most-ambiguous-word-in-product-development-3c36af377ecd)**, Jeff Gothelf*

I work on public services within the Civil Service as a 'digital' specialist, so this is the perspective for which is want to define value. This requires me to locate the small bit of public services in which I play a part.

## The public value chain

It's possible to view public services as operating at [three levels](https://scottcolfer.com/2018/05/14/public-service.html):

**Public service** |  
--- |
**1. End-to-end public service**: A service helps a user to do something that needs to be done, and completely meets that need. It also helps government achieve policy intent on behalf of its citizens with whom it has a social contract. Services are best identified as verbs (visit the UK), rather than nouns (biometric residence permit).  |
**2. Features of services**: this is ofen where we (digital) work. Often the things we work on are just one step in a service, like 'applying for a visa' - a software feature of a larger, end-to-end service |
**3. Capabilities of features**: these are the resources required to run the features of services. Examples include people, specialist tools, technology, and data. |

Each level is critically dependent upon the others in order to provide an end-to-end public service since all are required for the overall value of an end-to-end public service. These three levels are the main links in the value chain for public services.

**Public service** | **Value chain** 
--- | --- 
**End-to-end service** e.g. 'visit the UK'  | **Impact** e.g. number of peope who visit the country legally increases
**Features of services** e.g. 'apply for a visa to visit the UK' | **Outcomes** e.g. time taken to successfully apply for a visa decreases
**Capabilities for features** e.g. 'digitisation' project team | **Outputs** e.g. visa application process is 'digitised'


The definition of [public value](https://scottcolfer.com/2019/03/19/value-without-profit.html) in the previous post is particularly relevant for people who have to work out overall impact, like executive agencies and policy teams. But as we're about to see, outcomes for software can be somewhat impact-agnostic. Yes, our digital software needs to support this impact. But the needs met by public-facing software are often broadly similar, and the needs met by staff software are often broadly similar. They may be used to achieve differing impact, dictated by the mission of the sponsoring Department. But the outcomes of the software can potentially be measured in a shared, consistent way.

_It's possible for the links in a value chain to become invisble or even break all together. A [logic model](https://en.wikipedia.org/wiki/Logic_model) can help to restore a value chain when this happens. [Theory of change](https://ctb.ku.edu/en/table-of-contents/overview/models-for-community-health-and-development/logic-model-development/main) are the most common type of logic model used in situations such as these but aren't without [criticism](https://www.nesta.org.uk/blog/whats-wrong-with-theories-of-change/), with system-mapping tools like [Wardley Mapping](https://www.cio.co.uk/it-strategy/introduction-wardley-value-chain-mapping-3604565/) increasingly used to map out value chains._

From my perspective working witin a 'digital' team in the Civil Service, I'm typically working on the software features of end-to-end services - looking at the above value chain, we can see that value in this context is defined by the outcomes of that software has for the users of the software: measurable changes in user behaviour that contribute towards the overall impact that our Department would like to have.

## The value of digital transformation is currently measured by the outcomes of software

OK, we've taken a long journey and arrived at a conclusion. Value from my perspective is likely to mean the outcomes of the software features of end-to-end public services, measured through changes in user behaviour that contribute towards the overall impact that our Deparment would like to have. 

### Value of staff software

For my own organisation, the majority of our portfolio can be described as 'staff software': software for our colleagues to help them do their jobs. This is broadly described by the term '[business to business](https://en.wikipedia.org/wiki/Business-to-business)' software. 

It's possible to say that busines to business software meet three main needs:

1. Doing daily admin
2. Making better decisions
3. Complying with bureaucracy

We can measure the extent to which these needs are being met through measures like:

- Time taken
- Capacity
- Failure demand

As a starting point, the above needs and measures could help us to create a common language for defining the value of staff software in the Civil Service.

*The [video](https://www.mindtheproduct.com/2018/11/driving-growth-vs-building-core-value-by-roan-lavery/) of Roan Lavery's talk at Mind the Product 2018 is a great place to explore value in a B2B context in more depth.*

Test out the above with your most challenging staff services, where we're often told that it's difficult to measure value. 

Let's take hosting or infrastructure. We often consider hosting or infrastructure platforms to be 'technical', and may even hire 'technical' product managers. In reality, hosting and infrastructure are capabilities, they are 'outputs'. If we think differently and instead think of it as a platform to run and change software then the outcome we're looking for is to make it quicker and easier to change software. We might achieve this through things like: certificate management (daily admin), testing software iterations before publishing (making decisions), and maintaining the security of data (complying with bureacracy). All of these can be measured through 'time taken' (which might be measured through number of steps required). All can be measured through failure demand (e.g.  incidents). And improving any or all of them can improve the capacity of an organisation to make changes within fixed resources. 

In theory, this would work for 'consultancy' work too. In situations where we act as experts in a particular field (like service design, user-centred design, working with agility etc) for internal customers/clients/users, we're still trying to help them with daily admin tasks/making better decisions, and complying with bureaucracy. So my assumption is that some variation on the above would work for things like our support for programme design, procurement, and policy design.

### Value of public software

My own organisation also has a significant amount of public-facing software. I find this harder to desribe as simply as staff software, because we meet more varied and complex needs in this space. So I need to go very general as a starting point.

Very broadly speaking, I think that the most common public-facing software in my organisation and across the Civil Service is 'apply for a thing': a webform that allows a member of the public to apply for a public service. This is not the only thing we do by any means, but my starting assumption is that the is the most common and significant thing we do. 

Talking about value is tricky here, as it's arguable that application forms to meet a true user need, since very few users ever say 'I really want to have to complete an application form before accessing a service that I believe I'm entitled to'. Government has a need to check that the publis is genuinely entitled to public services they wish to access and this is the main need being met. The user need is probably something like 'make the application process as simple as possible, with as little 'friction' as possible'. The Service Standard's [manadatory KPIs](https://www.gov.uk/service-manual/service-standard/identify-performance-indicators) provide a good way of measuring how well these needs are being met:

- Completion rate
- User satisfaction
- Cost per transaction
- Adoption

In  fact, we could take this further and start measuring a single score worked out something like the following:

User Value Score = {Adoption*(Completion rate + User Satisfaction)}/Cost per application

This could work at multiple levels. E.g. For an individual online application form, adoption is the % of people who use the online option.
At Department level, adoption is the total number of people who apply for services online (which will be inhibted until forms are digitised). At Government level, adoption is the number of people who apply for services online (which, once again, will be inhibted until forms are digitised).

## We can measure the value of software for the public, and for staff

So we've checked-in with ourselves and found that the Service Standards' mandatory KPIs remain a good way to measure the value of transactional public software, and found a way to measure the value of staff software. We've recognised that the outcomes of software needs to be tied in to the overall impact our end-to-end services are supposed to have, which is likely to support the overall mission of our Department. Although the impact and missions of our Departments may vary a lot, it's possible that we can think about the outcomes of our software in a common and consistent way.  So we're sorted?

Not quite. Finally, we'll talk about how value changes over time in the next post in this series (coming soon).
