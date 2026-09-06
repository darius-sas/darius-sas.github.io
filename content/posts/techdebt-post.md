# Technical debt crisis -- Why technical debt doesn't matter and never did

The software engineering approach to a problem is to first recognize it, then study it, then measure its impact, then design a solution, and then, finally, measure the quality of the solution by how much it's reducing the original problem.
By repeating this process, sofware engineering, as a community, has produced  the knowledge and tooling for unwitting engineers to write, review, package, and ship software seamlessly, without caring to solve again problems their predecessors had to solve.
The scale of modern software and the frictionless process to produce it are the result of these advancements.

Curiosly, at some point during this software (re)volution, we identified a peculiar e problem that, to this day, is tormenting many software engineers: **technical debt**.

Contrary to other software engineering problems, technical debt has never been solved, despite having received a lot of attention throughout the years: frameworks, metrics, tools, blog posts, work culture, methodologies, and a lot of academic research endeavors, have been proposed but nothing really sticked on the long term.

The reasons it has never been solved could be many, including the one that TD might actually be too big of a problem to actually tackle in the time we had since its formulation in 1992 by Ward Cunningham (that's 34 years and counting).

However, I do not think we can say that before we admit to ourselves that there never was a real interest in solving it.
And we can deduce this by having a look at two run-of-the-mill projects you might encounter in your career as a software engineer:

1. A startup's new project, where requirements are not yet defined (or possibly, even non-existant!). In this case managing technical debt means essentially just ignore it and iterate as many times as possible to achieve a product-market fit.
Until you don't have one, any new line of code has a death timer of a few months at most, which makes any kind of technical debt repayment activities counterproductive, thus the only incentive to repay it comes from motivated, individual programmers and not a company need -- thus resulting in localized solutions that bring limited advantages.

1. A long-standing project built by a large corporation, in this case, this product has achieved product-market fit and it produces value to the business.
Assuming the company is planning to increase the business activities relying on this product, the development team will be under pressure to deliver new featues and/or scale existing functionality.
This is the best case scenario where td management could actually bring value, however, we have to consider the scale and receivers of such value.
Alas, in most cases, whatever the scale of the ROI of the repayment, will not be enough (or **visible** enough) to convince business to invest int such activities, especially given that the main receivers of the investement it's not going to be the company itself (from the managementpoint of view) but either the external company doing the actual implementation work or the programmers working for the company.
Neither of these are translatable to a reliable and quantifiable ROI that can justify the investment to the company's board or investors.
Therefore, it does not align with the company's goals.

On the other hand, if no plans include the development of the product, there are little to no incentives in combatting technical debt.

1. Open source


For technical debt to be resolved in a company, it needs to be a top company priority, directly tied to the revenue stream.
Thus, since for most of the companies this axiom does not hold, we are bound to never solve technical debt.



Note, I want to be clear that I do think TD is an actual problem that threatens software projects, but I also think that only some projects (and by that I mean a small fraction) actually benefit (on the long term) by investing resources into managing TD.

