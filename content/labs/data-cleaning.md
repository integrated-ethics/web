---
title: "Data Cleaning"
author: "Lori Carter"
date: "2021-07-06"
pagecat: lab
---

# Student Materials

* [web page](data-cleaning-worksheet/)
* [Markdown](https://raw.githubusercontent.com/integrated-ethics/web/main/content/labs/data-cleaning/data-cleaning-worksheet.Rmd)
 
# For Instructors

## Overview

**Main Point**: Choices made in data cleaning have ethical implications.

**Contents**: instructor guide, student handout, suggested assessment
questions

**Summary**: The goal of this module is to show that data cleaning, while necessary,
can be conducted with differing degrees of ethicality. The process of
correcting data (changing location, imputing a new value, removing typos
etc.), removing incomplete records, or leaving questionable data as is
can affect the results of the analysis. Consequently, methods must be
scrutinized. Students will evaluate the ethical ramifications of data
cleaning choices on a fictional data set description.

**Ethics background** required: It is helpful if students have learned
about the virtue ethics and utilitarian frameworks for making ethical
decisions, though not absolutely required. These frameworks are covered
in the first year curriculum.

**Subject matter** referred to in this module: data cleaning, simple
statistics

**Placement** in overall ethics curriculum:

* Academic year: Years two through four -- a class in data
management or data analysis

* Recommended previous modules: First year ethics curriculum
  (specifically virtue ethics and utilitarian modules)

* Recommended follow-up modules: No direct follow-up modules

**Time** required: 

* In class: 20 minutes 
* Out of class: none

**Learning objectives**:

-   Introduce the idea of and need for data cleaning if it has not
    already been covered in class

-   Practice recognizing ethical issues in data cleaning

-   Assess different methods of data cleaning for ethicality

-   Practice articulating and supporting the degree to which an approach
    to cleaning data is ethical in a particular situation

**Ethical issues to be considered**: Transparency, Diversity,
Dignity, Privacy, Data Integrity, Reliability

**Preparation required**

Read through the entire module. Print a student handout for each
student. The handout includes a dataset description, questions for the
students to consider, and definitions of potential ethical issues.

**Exercise flow**

-   Professor introduces the concept of data cleaning

-   Professor reminds students of potential ethical issues to be
    considered along with introducing a description of the dataset to
    be worked on.

-   Students work individually and then in groups to decide if each of
    several suggestions for cleaning the described dataset would
    result in ethical problems

## Lesson plan

### Introduction

*Depending on your class, you may wish to read/summarise this introductory information.*

Bad data leads to bad decisions. Data can be "bad", (also called dirty
or messy) for a variety of reasons. Information can be missing from a
record because someone forgot or did not want to make an entry. The
person entering the data could have introduced a typo. A tool used for
measuring data was not calibrated correctly, or the data was entered
with non-uniform metrics. One example of potentially bad data is called
an outlier. For example, a GPA of 5.0 would be unusual for a college
student where students are generally graded on a 4 point scale. If this
value was found in a record, what should the data analyst working on
checking the validity of the data do?

The process of trying to deal with dirty data in a way that has as
little impact on the results of a study as possible is called data cleaning[^1]. 
It is often said that data analysts spend 80% of their time cleaning and
20% analyzing[^2]. If the time is not spent to clean the data
properly, the results could be incorrect, and the process fraught with
ethical issues.

In our GPA scenario, the first step of cleaning would be to check to see
if the university posting the GPA did, in fact, adhere to a 4 point
scale. If so, the data point is erroneous and the issue needs to be
addressed. If the dataset was used to get the average GPA for a certain
major, for example, and the sample size was very large, the person
cleaning the data could probably remove the record and the results would
not change much. Alternatively, she/he could keep the record and replace
the value with the average or the median GPA of all students in the
major corresponding to the record with the outlier. Often, the median is
used as a replacement value if the data is skewed, and the average if it
the distribution is normal. Another option, if the data had gone through
previous transformations, would be to check backup copies of the data
and see if there was ever an entry for this cell that is within range.
Another approach, though not a good idea, would be to check the major of
the student to determine that it is a hard major, and, if so, randomly
assign a value of 3 for that GPA. To add to the unethicality of this
approach, the data analyst would make no notation that this had been
done. A good data cleaner keeps track of all cleaning decisions so that
the results could be reproduced by another person if need be.

Any of the choices above could introduce ethical issues. Not documenting
data cleaning choices is a violation of the ethical issue of
transparency. Not clearly explaining any of the cleaning choices well
could violate the virtue of hospitality. Randomly choosing a value to
use causes a problem with data integrity and could also introduce a bias
into the results.

### Activity

Pass out the student handout that describes a dataset, the type of
analysis for which it will be used, and some potential data cleaning
transformations. The definitions of various ethical issues is also
included. 

Have the students consider the questions by themselves first
and then with the class or in small groups.

### Notes

1. Regarding **anonymity**: This might be sufficiently anonymous for a very
    large university. However, for a small university it would not. If
    the major was computer science, for example, and the gender was
    female, the student could be easily recognized. Since this survey
    also asks about things like mental illness and the possibility of
    pregnancy, dignity could be an ethical issue at stake here.
    Similarly, if there were few veterans at the school, or few
    non-traditional (older) students, they could be easily recognized.

2.  Regarding missingness for  **age**

    a.  Fill with the median of the student population

    Maybe -- this is skewed data, but you could be missing important
    information -- If the individual was also a vet, you might just go
    with the median of the vets

    b. Fill with the mean of the student population

    Bad option as this is skewed data and this individual might not have
    listed their age because it would be very obvious who they were
    (could be one of the few older students)

    c. Remove records where age is missing and make a note of this in the
    data cleaning documentation

    If your sample size is sufficiently large, you might go with
    this option -- shouldn't affect other metrics -- there
    shouldn't be more males than females for example


3.  Regarding missingness for **parental college experience**:

    More likely to happen for parents with no college experience or
    students who are adopted. Removing these records could affect
    diversity.

4.  Regarding missingness for **physical disability**:

    Some female students might not want
    to indicate that they left college due to pregnancy. Again, a
    diversity issue.

5.  Regarding **reliability** and **hospitality**: 

    If there is no standardized
    way to fix errors in the study, it could not be replicated with
    other data (reliability). Even if the data cleaner documented every
    change, this would be hard to apply to a new case and would make a
    very cumbersome document for someone trying to find errors after
    cleaning or to replicate the study (hospitality).

6.  Regarding the **GPA outlier**, this is simply a data integrity issue. If
    a rough semester caused a student to leave, the GPA could indeed
    have been 1.35. You cannot honestly make another assumption.

## Reflection

Ask the class to reflect on this additional example based on what they
learned from the exercise:

A survey-taker has indicated a major that does not exist at the
university. What possible choices are there to handle this, and what
ethical issues would have to be considered with the choice?

### Possible ideas for professor if students are struggling with reflection

If the analyst replaced the major with one that he/she thought was
closest (perhaps replacing exercise science (doesn't exist) with
kinesiology (does exist)) but doesn't record this change, this could be
a violation of transparency or reliability. While this approach is
reasonable, the cleaner should record the cleaning method so the results
could be reproduced. It might also be wise to produce the final analysis
both with the change made, and with the offending record removed and see
if the results differed significantly.

Ask students to share anything that surprised them from this exercise,
or changed how they might make a data cleaning decision.

## Assessment

*to be included at a later date on a quiz, paper, or exam to determine if LOs were reached*

-   Ask students to define data cleaning.

-   Ask students to provide an example of a data cleaning need along
    with an ethical and unethical way to address it. Ask them to provide
    the ethical issue raised by the poor choice.

-   Applying some the ethics frameworks learned previously to data
    cleaning:

    -   Refer back to the original GPA example in the introduction (an
        outlier of 5 for the GPA) and have the students suggest 3 ways
        to deal with the outlier (assuming it really is an outlier).
        Have the students evaluate the cleaning solutions using both
        the utilitarian approach and the virtue ethics approach.
        Recall that in order to evaluate using the **utilitarian**
        approach they would ask questions like the following:

        -   Who will be affected by this decision?

        -   Who benefits from this decision?

        -   Who will be harmed by this decision?

        -   Do the benefits outweigh the harm?

    -   When using the **virtue ethics** approach students should ask
        questions like:

        -   Does this solution violate my moral values (virtues) or
            those of the society to which I belong? (students should
             recall that virtues include such principles as
             adaptability, compassion, dignity, excellence, honesty,
             inclusivity, justice, patience, transparency)



[^1]: Van den Broeck J, Argeseanu Cunningham S, Eeckels R, Herbst K
    (2005) Data Cleaning: Detecting, Diagnosing, and Editing Data
    Abnormalities. PLoS Med 2(10): e267.
    [[https://doi.org/10.1371/journal.pmed.0020267]{.ul}](https://doi.org/10.1371/journal.pmed.0020267)

[^2]: Browne-Anderson, Hugo. (2018) What Data Scientists Really Do
    According to 35 Data Scientists, Harvard Business Review, August 2018.
    [[https://hbr.org/2018/08/what-data-scientists-really-do-according-to-35-data-scientists]{.ul}](https://hbr.org/2018/08/what-data-scientists-really-do-according-to-35-data-scientists).
    Accessed July 4, 2019.
