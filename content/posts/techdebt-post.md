# Technical debt crisis -- Why technical debt doesn't matter and never did or why the economics of technical debt never worked

## How we got here
The software engineering approach to a problem is to first recognize it, then study it, then measure its impact, then design a solution, and then, finally, measure the quality of the solution by how much it's reducing the original problem.
By repeating this process, sofware engineering, as a community, has produced  the knowledge and tooling for unwitting engineers to write, review, package, and ship software seamlessly, without caring to solve again problems their predecessors had to solve.
The scale of modern software and the frictionless process to produce it are the result of these advancements.

Curiosly, at some point during this software (re)volution, we identified a peculiar e problem that, to this day, is tormenting many software engineers: **technical debt**.

Contrary to other software engineering problems, technical debt has never been solved, despite having received a lot of attention throughout the years: frameworks, metrics, tools, blog posts, work culture, methodologies, and a lot of academic research endeavors, have been proposed but nothing really sticked on the long term.

The reasons it has never been solved could be many, including the one that TD might actually be too big of a problem to actually tackle in the time we had since its formulation in 1992 by Ward Cunningham (that's 34 years and counting).

However, I do not think we can say that before we admit to ourselves that there never was a real interest in solving it.
And we can deduce this by having a look at how sucessful projects become successful.

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
Indeed, the ROI is almost always impossible to quantify, due to lack of standardized approaches and tools that give a deterministic, objective result.
Paying back technical debt implies dedicating part of the team that would otherwise implement new features to do refactoring, and the benefits of such refactoring are mostly only visible to the programmers working on the system.
This drastically increases the perceived risk of the investment, resulting in many companies prefering to "keep doing what they were doing", because it's safer.

On the other hand, if no plans include the development of the product, there are little to no economical incentives in combatting technical debt.

My point is that for technical debt to be resolved in a company, it needs to be a top company priority, directly tied to the revenue stream.
In other words, technical debt economics almost never work, and other solutions to the problems it poses have a better appeal to the business side of the organization.

From this situation, it stems that technical debt has never become that problem that resulted in an industry-wise investment preventing new tools and standards being adopted to mitigate the problem.

Note, I want to be clear that I do think TD is an actual problem that threatens software projects, but I also think that only for a small fraction of projects actually benefit (on the long term) by investing resources into managing TD.

