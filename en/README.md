# Deliverables self-checklist for programmers

The deliverables self-checklist for programmers is a checklist that enables developers themselves to check for coding protocol violations and simple coding errors in system development using Java. The published document is a sample for cases in which [Nablarch](https://nablarch.github.io/docs/LATEST/doc/en/index.html) is used for the framework. 

In large-scale system development projects, many developers with varying skills and experience work together, and this gap in skills and experience tends to result in a significant variance in quality. Deliverables from developers who are not sufficiently skilled or experienced create a significant amount of work for reviewers, so reviewers will need to point out and correct things outside of the checks reviewers want to focus on, which may lead to quality degradation. 

This checklist addresses this issue by prompting developers themselves to check and correct these issues before submitting their deliverables. This improves the quality of deliverables submitted for reviews, reduces the workload of the reviewers and prevents decreases in quality. 

While this checklist presumes that Nablarch is used, only around 30% of the check items are dependent on Nablarch. The remaining 70% are points that need to be checked for Java, SQL, testing and UI. If a framework other than Nablarch is used, the points can be customized to suit the situation of the project.

## How to use this document

- Before applying this checklist to a project, check the items and customize them according to your project. Points that can be checked using a static checking tool are not included in this checklist as it is assumed that a tool will be used to check those points in addition to the use of this checklist. 

    ＜ 	Examples of customization＞

    　　Example 1 : Customizing points that differ from the coding protocol defined for the project

    　　Example 2 : Omitting points that can be checked with the static checking tool used for the project instead

    　　Example 3 : Customizing the points that are dependent on Nablarch when a different framework is used

    　　Example 4 : If the developers are skilled in Java and development standards and coding protocol have been shared but many of the developers do not have much experience with using Nablarch, We used only the points that are dependent on Nablarch.

- Define how to use the checklist, taking into account the skills and experience of the developer and the development process, and share and use it in the project. Be aware that if excessive checking work is assigned to developers when deciding on how to use the checklist, the checks will be treated like a formality. 

      ＜Examples of how to use the checklist＞
      
      　　Example 1: Instructing developers that they must perform a self-check with this checklist before requesting a review (including reviews at the 30% point)
      
      　　Example 2: Dividing check points into those to be used when completing coding and those to be used when completing unit testing and using each check point at the right time.
      
      　　Example 3: Exempting some developers from this check according to the reviewer’s assessment of their skills, as it is not necessary for all developers to check all points.

## Related documents

- [Checklist of completion conditions for Programming and Unit testing work](https://fintan.jp/?p=1367)

  　Using this checklist as one of the check points in the checklist of completion conditions for PG and UT work prevents omissions in PG and UT work. 

- Coding protocols

  　Points requiring particular attention in the [Java coding protocol](https://github.com/nablarch-development-standards/nablarch-style-guide/blob/master/en/java/java-style-guide.md) and other coding protocols are defined in this checklist to enable efficient development.

## Accessing this document

This document can be viewed or downloaded using the following links.

- [Deliverables_self-checklist_for_programmers.xlsx](./docs/Deliverables_self-checklist_for_programmers.xlsx?raw=true)
- [Deliverables_self-checklist_for_programmers.pdf](./docs/Deliverables_self-checklist_for_programmers.pdf?raw=true)

## Licensing

This document is provided under<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"> the international Creative Commons Attribution + ShareAlike 4.0 license.</a>
<br />
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
  <img alt="Creative Commons license" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" />
</a>
