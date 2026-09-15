# Technical debt crisis -- Why the economics of technical debt work against it
# Technical debt: a people problem

//todo need to write a catchy intro paragraph introducing my main thesis: technical debt can never be solved as a problem because it is not perceived as such by companies.
// Let's take the example of bugs, companies are forced to solve bugs because it impacts the revenue streams. Systems, practices, tools have all been hypothesized, studied, implemented and used to help software teams manage bugs around the world.
//Technical debt is strikingly similar to software bugs, if not two face of the same coin. If there is a lot of technical debt, there are a lot of bugs, if there are a lot of bugs, there's a lot of technical debt (it would help to have a reference here) making those bugs easier to appear.

## Making rocks think is easy
In the short lifespan of its existence, the software engineering practice, has gone from punchole cards containing small programs that would take hours, if not days, to write the most simple functionality to producing the tooling (such as compilers and orchestrators) and practices (such as agile) that allows teams around the globe to coordinate and build applications of millions of lines of code and serve them to billions of users.
All seamlessly and concurrently.

While this is an extremely impressive feat, all of it did not happen without encountering a few bumps along the road.
The most peculiar bump that, to this day, it's still tormenting many software engineers is **technical debt**.
At least in my opinion.

Technical debt is the lazyness of one engineer that becomes the bane of another -- with the catch that it might be the same engineer.
By the way, formally speaking, technical debt represents design or implementation constructs that are expedient in the short term but create a technical context making future changes more costly or impossible (cite Dagstuhl).

Contrary to other software engineering problems, like transforming text into an optimized string of 0s and 1s capable of making a rock think, technical debt is a people problem, not a math problem..
And contrary to math problems, it can never be really *solved*.
And not by lack of attempts either.
A lot of resources have been spent throughout the years to produce frameworks, metrics, tools, blog posts, methodologies, guidelines, and intricated academic theories.
Alas, nothing really sticked on the long term. Because nothing actually solved the problem.

//This reads very "rigid", completely opposite from previous section.
## The causes
To understand *how* this has come to be the case, we have to start looking at the reason *why* we produce software.

Let's take the example of *new* software projects, where, in most cases, requirements are not yet fully clear to the client, or possibly, even not yet existant.
This means that implementing a correct and complete solution is impossible. 
The best one can do, and hope for, is an approximation that will require continuous adjustments as the requirements continuously change.

In this case managing technical debt means essentially just ignore it and iterate as many times as possible to achieve a product-market fit, a point where requirements will change slightly less.
Until you don't have one, any new line of code has a maximum lifetime of a few months at most, which makes any kind of technical debt repayment activities counterproductive.
The only need to repay it comes from frustrated, individual programmers resulting in localized solutions that bring limited or short-termed advantages.
When the debt is no longer sustainable, the best solution is to rebuild the project from scratch, component by component and possibly migrating to a more resilient, scalable architecture.

At some point, the project will become big enough to become a business-critical asset for the company that developed it (which, presumably has also scaled in size).
Assuming the company is planning to mantain (or increase) the business activities relying on this product, the development team will be under pressure to keep delivering new features and/or scale existing functionality.

This is the moment in time where repaying tech debt could actually bring value in the long-term by cutting those interest payments down.
However, most companies do not do this -- or are very cautious if they do it -- and prefer keeping the debt.

## Tech debt economics fail to deliver
The reasons is a combination of low or unclear ROI with a high upfront investment and uncertain short-term benefits.
Indeed, the ROI is almost always impossible to quantify, due to lack of standardized approaches and tools that give a deterministic, objective, and complete result.
Paying back technical debt implies dedicating part of the team that would otherwise implement new features to do refactoring, and the benefits of such refactoring are mostly only visible to the programmers working on the system (who may also be contractors!).
This drastically increases the perceived risk of the investment, resulting in many companies prefering to "keep doing what they were doing", because it's safer and because the value it's clear to the end user, unlike the repayment of technical debt. 
Moreover, and maybe most importantly, it's a *predictable cost with a predictable solution*: just throw more money at the problem (either hardware or engineers).

My point is that technical debt economics almost never work because the other available solutions to the problems it poses have a better appeal to the business side of the organization.
For most companies, until it's crystal clear that technical debt distrupts the revenue stream, they will prefer to not act on it. And when they do act, the solution is almost never repayment, but rather doubleing down.

Technical debt has never been solved because there was never the economical incentive to do so: business prioritizes users, not developer experience.

## The survivorship bias of TD-ridden projects
Why do the stories of the most successful companies in the world rarely involve technical debt management?
Because things need to move at a pace that's too fast to be able to control tech debt. They certainly mitigated it, but it was never the point and always a means.

## Where to go from here

## Conclusions

Note, I want to be clear that I do think TD is an actual problem that threatens software projects, but I also think that only a small fraction of projects actually benefit (on the long term) by investing resources into managing TD.

// Fit this somewhere? 
// As software engineers, we have to admit this to ourselves if we want to go somewhere from here.
