---
title: "Avoiding Algorithmic Bias"
date: "2021-07-21"
pagecat: lab
author: Lori Carter
bibliography: ../ie-references.bib
link-citations: true
nocite: '@Lee:2019'
---

# Student Materials

-   Long version of worksheet with questions and EU Guidelines
    -   [web version](avoiding-algorithmic-bias-worksheet/)
    -   [Markdown](https://raw.githubusercontent.com/integrated-ethics/web/main/content/labs/avoiding-algorithmic-bias/avoiding-algorithmic-bias-worksheet.md)
-   Scenarios only version of worksheet
    -   [scenarios only](avoiding-algorithmic-bias-scenarios/)
    -   [Markdown](https://raw.githubusercontent.com/integrated-ethics/web/main/content/labs/avoiding-algorithmic-bias/avoiding-algorithmic-bias-scenarios.md)
-   EU AI Guidelines slide deck
    -   [web version](/slides/eu-ai-guidelines.html)
    -   [Markdown](https://raw.githubusercontent.com/integrated-ethics/web/main/static/slides/eu-ai-guidelines.Rmd)

# Overview

**Ethics background** required: Ideally, students should be familiar
with the 4 ethical frameworks presented in the first year curriculum
(virtue ethics, deontology, utilitarianism, analogies). If they (or the
instructor) are not, a brief summary is provided in the reflection.

**Subject matter** referred to in this lab: Algorithms

**Placement** in overall ethics curriculum:

-   Academic year: Year 2-4 core course that talks about
    algorithms or machine learning.

-   Recommended previous labs: First year ethics curriculum

-   Recommended follow-up labs: No direct follow-up labs

**Time** required:

-   In class: 30 minutes (online version is also included)

**Learning objectives**:

-   Students are introduced to or reminded of the dangers of algorithmic
    bias in predictive algorithms

-   Students are introduced to a deontological set of guidelines to
    evaluate an algorithm for bias

-   Students apply the guidelines to actual algorithms and practice this
    evaluation

-   Students review the four ethical frameworks and evaluate the benefit
    of using each in regard to evaluating predictive algorithms

**Ethical issues to be considered:**
Algorithmic bias, diversity, transparency

**Flow**

-   Students read and talk about algorithms with issues

-   Students are introduced to the *EU Ethics Guidelines for Trustworthy AI*
    ([Floridi 2019](#ref-Floridi:2019))

-   Students evaluate the algorithms previously presented based on these
    guidelines

**Preparation**

-   Read through the entire lab.

-   Print enough of each of the 3 scenarios to distribute one each to group of
    2-4 students. Or give all three scenarios to each group and assign one of
    the scenarios to each group.

-   Prepare a PowerPoint (or similar) slide to project with the 7 EU
    Guidelines on it. Or use [this web page]().

<!-- For example, if you have a class of 20 students, you might want to print 2 copies of each. -->
<!-- **If this lab is to be presented online**

See online addendum. Students work through the assignment and then
peer-review the assignment of another student.
-->

# Guide for Instructors

## Lesson plan

### Introduction (5 minutes)

Ask students for the definition of “algorithm.” (Something like a
step-by-step approach to use as a guideline for producing a program that
the computer can use to solve a problem)

Remind students that their college application was probably subject to
some sort of algorithm to determine whether they were admitted.
**Ask class to suggest what some of the steps might have been** in the
decision making process. (*This is similar to question 1 from the worksheet.*)

Here are some possibilities:

-   Is the GPA > X (X depends on institution)

-   Is the SAT/ACT > X

-   5 points for each area of community service

<!-- -   3 points for faith statement -->

**To students:** Generally, these types of algorithms are point-based.
Why would a point-based method be adopted? What are the benefits?
(probably something about objectivity)

Do you see any problems with the point-based method? (possible
responses: not everything can be boiled down to numbers, how to decide
how many points something is worth, is it easier for some students to
meet the requirements (parents can pay for tutoring, for example))

### Activity 1 (5 min)

Facilitate the division of students into groups of 2-4 members. Each
group should be given one of the scenarios in the worksheet.
Direct the students to read the scenario as a group and discuss
what went right and what went wrong.

-   Scenario 1: Market crash of 2008 (algorithms as objective agents)
-   Scenario 2: Automating Hiring (providing feedback to an algorithm)
-   Scenario 3: Modeling Churn (seeking fairness)

### Preparation for activity 2 (5 min)

**Instructor should read or summarize after the previous group activity is finished:**

> Point-based algorithms for making decisions are a rudimentary form of
> Artificial Intelligence. Kaplan and Haenlein recently defined AI as “a
> system’s ability to correctly interpret external data, to learn from
> such data, and to use those learnings to achieve specific goals and
> tasks through flexible adaptation.” Our example of a point-based
> algorithm for college admission is used to predict who will most likely
> succeed at a particular college or university. Similarly, each of the
> scenarios that you read involved simple predictive algorithms.

> We hear frequently of the challenges with AI and even simple predictive
> algorithms share the same issues. Recently, the EU came up with a set of
> guidelines to help diminish the chance of ethical issues in such
> algorithms. As we go through these guidelines, think back on our college
> admissions example and the example that you read in your group and see
> if any of them would be helpful to consider if you were in charge of
> developing such an algorithm. Be prepared to discuss your observations
> with your group.

**Note to instructor**: The *EU Ethics Guidelines for Trustworthy AI*
should be made available to students so they can follow along.

-   One easy approach is to project the guidelines on a screen for the class. You
    can use this [web-based slide deck](/slides/eu-ai-guidelines.html).
-   It is a good idea for students to participate in the reading
    (assign 1 guideline to a student to read) so that they are more engaged.
-   These also appear on the student worksheet.

**Note to instructor**: Definition of AI.
There are some weaknesses to the definition of AI given by
Kaplan and Haenlein. In particular, many of the terms used
in the definition do not have self-evident meanings, so it would
probably be difficult to use this definition to decide whether
something is or is not an example of AI. Try not to focus on
the issue of defining AI – keep the focus on the scenarios
and the ethical issues they raise.

### Activity 2 (5 min)

Students discuss with their group observations that they made regarding
the potential benefits of applying 1 or more of the guidelines to the
college admissions scenario or to the scenario read as a group.

### Reflection (10 min)

Have each group report on one or more of the guidelines that would have
helped in the design of either the college admission scenario or the
scenario that they read. If they choose to use their group scenario, have the group
first summarize the scenario. It is probably best to ask if other groups
have comments on that same scenario before moving on.

**Ask the students**: Who can tell me which ethical framework is being
used by applying a set of guidelines to vet a predictive algorithm?
(virtue ethics, deontological, analogies, utilitarianism?) If they need
a refresher:

-   Virtue ethics: making a decision based on whether the outcome
    upholds a set of virtues (honesty, compassion, patience, hard-work
    are some examples)

-   Deontological ethics: making decisions based on a set of rules
    (**this is the expected choice**)

-   Analogies: making a decision based on a similar situation where the
    ethicality of the similar situation was widely accepted

-   Utilitarianism: making a decision based on what is best for the
    majority

**Ask the students** if they believe that this was an appropriate
framework to use in this case. Why or why not?

Possible answers:

-   Probably good if used only as guidelines. It’s a good starting place

-   Virtue ethics might be a good secondary approach, and some of the
    virtues (respect for diversity, for example) are included in the
    guidelines

-   Analogies probably would not be a good approach as it is not a
    single decision that must be made and it would be very difficult
    to arrive at an appropriate analogy

-   Utilitarianism is probably what caused the problem in the first
    place – designers would figure that it would work for most people.

### Assessment

-   Assess the deontological approach to evaluating an algorithm for
    ethicality compared to the virtue ethics, analogy, or utilitarianism
    approach. Is it better, worse, explain.

-   Provide 2 of the guidelines listed in the EU Ethics Guidelines for
    Trustworthy AI that we talked about in class

-   Summarize one of the examples of predictive algorithms that
    exhibited bias that were presented in class. Specifically state the
    bias, and explain how it could have been avoided.

### Sources

All of the scenarios were excerpted from [O’Neil](#ref-ONeil:2016) ([2016](#ref-ONeil:2016)).
Cathy O’Neil is also the author of *Weapons of Math Destruction*.

Principles are directly from the text of [Floridi](#ref-Floridi:2019) ([2019](#ref-Floridi:2019)),
compiled by the High-Level Expert Group on Artificial
Intelligence set up by the European Commission.

AI definition is from [Kaplan](#ref-Kaplan:2019) ([2019](#ref-Kaplan:2019))

### Additional reading

[Lee, Resnick, and Barton](#ref-Lee:2019) ([2019](#ref-Lee:2019))

### References

<div id="refs" class="references csl-bib-body hanging-indent">

<div id="ref-Floridi:2019" class="csl-entry">

Floridi, Luciano. 2019. “Establishing the Rules for Building Trustworthy AI.” *Nature Machine Intelligence* 1 (6): 261–62. [https://ai.bsa.org/wp-content/uploads/2019/09/AIHLEG\\\_EthicsGuidelinesforTrustworthyAI-ENpdf.pdf](https://ai.bsa.org/wp-content/uploads/2019/09/AIHLEG\_EthicsGuidelinesforTrustworthyAI-ENpdf.pdf).

</div>

<div id="ref-Kaplan:2019" class="csl-entry">

Kaplan, Michael, Andreas; Haenlein. 2019. “Siri, Siri, in My Hand: Who’s the Fairest in the Land? On the Interpretations, Illustrations, and Implications of Artificial Intelligence.” *Business Horizons* 62 (1): 15–25.

</div>

<div id="ref-Lee:2019" class="csl-entry">

Lee, Nicol Turner, Paul Resnick, and Genie Barton. 2019. “Algorithmic Bias Detection and Mitigation: Best Practices and Policies to Reduce Consumer Harms.” <https://www.brookings.edu/research/algorithmic-bias-detection-and-mitigation-best-practices-and-policies-to-reduce-consumer-harms/>.

</div>

<div id="ref-ONeil:2016" class="csl-entry">

O’Neil, Cathy. 2016. “How Algorithms Rule Our Working Lives.” <https://www.theguardian.com/science/2016/sep/01/how-algorithms-rule-our-working-lives>.

</div>

</div>
