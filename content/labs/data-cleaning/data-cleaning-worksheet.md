---
title: "Data Cleaning"
author: ''
date: '2021-07-06'
pagecat: worksheet
output:
  word_document: default
  html_document:
    df_print: paged
  pdf_document: default
publishdate: '2021-07-06'
---

## University Students Data

The field/variable names of a data set used to understand the reasons that
students leave college before graduation are shown below.


-   `university`: Name of university

-   `gender`: Gender of the student

-   `age`: Age of the student

-   `mother_ed`: College experience of mother (2 year, 4 year, graduate)

-   `father_ed`: College experience of father (2 year, 4 year, graduate)

-   `how_funded`: How college is funded -- loans, grants, scholarships, paid by family

-   `mental_illness`: Mental illnesses experienced during college years (yes, no)

-   `disability`: Physical disability (including pregnancy) (yes, no)

-   `current_gpa`: Semester GPA in the semester when student withdrew

-   `overall_gpa`: Overall GPA of the student

-   `withdrew`: Did the student withdraw after current semester? (yes, no)

-   `commuter`: Does the student commute? (yes, no)

-   `veteran`: Is the student a veteran? (yes, no)

-   `major`: Academic major(s)

## Exercises

It may be helpful to review the list of potential ethical
issues in computing and data science below as you consider the exercises 
below.

### Anonymity

1.  Anonymity is a well-known ethical issue with data collection. If all
    of the data in this survey was made available to the researchers,
    would it be sufficiently anonymous? Why or why not? If a survey is
    not anonymous, which ethical issue(s) might be a problem?


### Dealing with missing data

Very often some values of some variables are not recorded for some individuals.
There are many reasons why data might be missing. Perhaps the data collection
protocol changed over time. Perhaps some subjects declined to answer some questions
on a survey. Perhaps some information is simply not available. 

Before proceeding to analyse a data set, researchers need to decide how to handle missing
data.

2. For several records, `age` is missing.
   Consider the pros and cons of each of these possible
    options for addressing the problem. How likely is the option to
    create an ethical issue and what might that issue be if there is
    one?

    a.  Fill with the median of the student population.

    b.  Fill with the mean of the student population.

    c.  Remove records where `age` is missing and make a note of this in the
    data cleaning documentation.

3.  For several records, the college experience of at least one of the
    parents is missing -- is there a population with which this might
    be more likely to happen? Since one cannot guess at the experience
    of the parents, these records would likely be removed. What ethical
    issue(s) might arise with the action?

4. For several records, `disability` is missing.
    Removing the related records could negatively affect the diversity
    of this study. Why?

5.  There are several other fields left blank on various records. You
    try to take each omission on a case by case basis, doing what you
    think is right. This might influence both reliability and
    hospitality. Why?

### Dealing with (possibly) incorrect data

Just because values are included in a data set doesn't mean that those 
values are correct. Unusual observations might catch our eye and lead
us to investigate further.

6.  One current GPA is listed as 1.35. Since this is an outlier, 
    you look at the students' overall gpa which is 3.0. You're pretty sure that the 1
    and the 3 must have been swapped so you go ahead and change the GPA
    to a more reasonable 3.15. What ethical issues might you be
    violating?

## Ethical Issues Definitions

**Media Literacy**: Determining if an online article, video, etc. is
factual, reliable, and unbiased.

**Accessibility**: Ensuring to the best of one's ability that what we 
produce is available to those with special needs,
including economic, physical, mental, and emotional.

**Visualization**: Employing techniques that represent data and models
in a clear, accessible way that accurately reflects the data and what 
we can learn from them.

**Transparency**: Representing data, algorithms, processes, or any information
that affects stakeholders in an open, explicit, and easily comprehensible
format.

**Diversity**: Having a variety of people (race and ethnicity, age,
gender, skills and education level, sexual orientation, religion, etc.)
contributing to the development of an idea or product in an effort to
avoid bias, to increase the breadth of insight into the development 
process, and to ensure different groups don't experience disproportionate
benefits or costs.

**Sustainability**: Practices that serve to protect the environment
including living creatures and other naturally occurring resources and
features.

**Intellectual Property**: Crediting the creator or discoverer of work;
affording control over the work to the creator of the work.

**Decision Making**: Taking responsibility for how a system or organization
makes decisions, especially those involving life-altering actions.

**Freedom of Speech**: Granting the rights and enforcing the limitations
of the public to express themselves and correspond, including through electronic
communication.

**Dignity**: Valuing human and animal life, well-being, and connection
above productivity or end results.

**Physical and Mental Health**: Proactively taking care to protect the
health of colleagues, customers, clients, consumers, employees, and oneself.

**Professional Citizenship**: Contributing voice and opinion within
one's expertise regarding the ethicality of the work of those around
them.

<!-- Should this be expanded beyond just ethics citizenship? -->

**Reliability**: 
Ensuring that one's work consistently does what claims to do.

<!-- Ensuring that one's work is consistently functional as -->
<!-- specified through adequate testing/duplication with a variety of users. -->

**Hospitality**: Creating work that is easily understandable and usable
both by peers in a similar field and by other stakeholders and interested 
parties.

**Privacy and Security**: Balancing the need for protecting personal and
group data with the use of that data for the welfare of the public.

**Bias**: Recognizing and reducing any potential biases
present in an algorithm, model, or process that may have arisen as a result of
ignorance, assumptions, or past discriminatory societal patterns.

**Data Integrity**: Collecting and handling data in a way that accurately
reflects the phenomena being studied and is appropriate for the analysis 
techniques employed.
<!-- minimizes bias or the potential for false results. -->

**Professional Ethics**: Contributing one's best effort in the workplace
while respecting one's peers and upholding the requirements of one's
employer and the discipline's overarching guild.
