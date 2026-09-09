# Technical debt crisis -- Why the economics of technical debt work against it
//todo need to write a catchy intro paragraph introducing my main thesis: technical debt can never be solved as a problem because it is not perceived as such by companies.

## How we got here
//The software engineering approach to a problem is to first recognize it, then study it, then measure its impact, then design a solution, and then, finally, measure the quality of the solution by how much it's reducing the original problem.
//By repeating this process, sofware engineering, as a community, has produced the knowledge and tooling for unwitting engineers to write, review, package, and ship software seamlessly, without caring to solve again problems their predecessors had already solved.
//The scale of modern software and the frictionless process to produce it are the result of these advancements.
In the short lifespan of its existence, the software engineering practice, has gone from punchole cards containing small programs that would take hours if not days to write the most simple programs to producing the tooling (such as compilers and orchestrators) and practices (such as agile) allowing teams around the globe to coordinate, build applications of millions of lines of code and serve them to billions of users. All seamlessly and concurrently.

That is an incredible feat. 
However, all of this did not happen without bumps in the road.
At some point during this software (r)evolution, we encountered a peculiar problem that, to this day, it is still tormenting many software engineers: **technical debt**.

Contrary to other software engineering problems, technical debt has never been solved, despite having received a lot of attention throughout the years: frameworks, metrics, tools, blog posts, methodologies, and a plenty of academic research endeavors.
Alas, nothing really sticked on the long term.

The reasons it has never been solved could be many, including that tech debt might actually be too big of a problem to actually tackle in the time we had since the term was coined in 1992 by Ward Cunningham (that's 34 years ago and counting).

However, I do not think we can say that before we admit to ourselves that there never was a real interest in solving it.
And we can deduce this by having a look at how projects come to life and evolve to become critical business assets.

New software projects have the problem that requirements are not yet fully clear or well-defined (or possibly, even non-existant!).
This means that a implementing correct, technical debt free and change-resilient solution is impossible.
In this case managing technical debt means essentially just ignore it and iterate as many times as possible to achieve a product-market fit.
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
