---
title: "Student Handout for the Ethics of Data Cleaning Lab"
output: html_document
---

The field names of a dataset used to understand the reasons that
students leave college before graduation are shown below.

-   Name of university

-   Gender

-   Age

-   College experience of mother (2 year, 4 year, graduate)

-   College experience of father (2 year, 4 year, graduate)

-   How college is funded -- loans, grants, scholarships, paid by family

-   Mental illnesses experienced during college years (yes, no)

-   Physical disability (including pregnancy) (yes, no)

-   Semester GPA when student withdrew

-   Overall GPA

-   Commuter (yes, no)

-   Veteran (yes, no)

-   Major

1.  Anonymity is a well-known ethical issue with data collection. If all
    of the data in this survey was made available to the researchers,
    would it be sufficiently anonymous? Why or why not? If a survey is
    not anonymous, which ethical issue(s) might be a problem?

The rest of the exercise considers the ethicality of several data
cleaning options. You will be asked to evaluate various ways to deal
with bad data. It may be helpful to review the list of potential ethical
issues in computing and data science found on the next page as you
consider each scenario.

2.  For several records the field representing the age of the student is
    left out. Consider the pros and cons of each of these possible
    options for addressing the problem. How likely is the option to
    create an ethical issue and what might that issue be if there is
    one?

<!-- -->

a)  Fill with the median of the student population

b)  Fill with the mean of the student population

c)  Remove records where age is missing and make a note of this in the
    data cleaning documentation

<!-- -->

3.  For several records the college experience of at least one of the
    parents is left blank -- is there a population with which this might
    be more likely to happen? Since one cannot guess at the experience
    of the parents, these records would likely be removed. What ethical
    issue(s) might arise with the action?

4.  For several records the physical disability field is left blank.
    Removing the related records could negatively affect the diversity
    of this study. Why?

5.  There are several other fields left blank on various records. You
    try to take each omission on a case by case basis, doing what you
    think is right. This might influence both reliability and
    hospitality. Why?

6.  One GPA is listed as 1.35. Since this is an outlier, you look at the
    students' overall gpa which is 3.0. You're pretty sure that the 1
    and the 3 must have been swapped so you go ahead and change the GPA
    to a more reasonable 3.15. What ethical issues might you be
    violating?

**Ethical Issues Definitions**

**Media Literacy**: Determining if an online article, video, etc. is
factual, reliable, and unbiased

**Accessibility**: Ensuring to the best of one's ability that the
products we make and use are available to those with special needs,
including economic, physical, mental, and emotional

**Data Visualization**: Employing techniques that represent data in a
clear, accessible way that accurately reflects the meaning of the
original values 

**Transparency**: Representing data, algorithms, or any information that
affects a user in an open, explicit, and easily comprehensible format

**Diversity**: Having a variety of people (race and ethnicity, age,
gender, skills and education level, sexual orientation, religion, etc.)
contributing to the development of an idea or product in an effort to
avoid bias and increase the breadth of insight into product needs

**Sustainability**: Practices that serve to protect the environment
including living creatures and other naturally occurring resources and
features

**Intellectual Property**: Crediting the creator or discoverer of work;
affording control over the work to the creator of the work

**Decision Making for AI**: Taking responsibility for how an
artificially intelligent machine makes ethical decisions, especially
those involving life-altering actions

**Freedom of Speech**: Granting the rights and enforcing the limitations
of the public to express themselves and correspond through electronic
communication

**Dignity**: Valuing human and animal life, well-being, and connection
above productivity or end results

**Physical and Mental Health**: Proactively taking care to protect the
health of employees (including oneself) and consumers of one's product 

**Professional Citizenship**: Contributing voice and opinion within
one's expertise regarding the ethicality of the work of those around
them

**Reliability**: Ensuring that one's work is consistently functional as
specified through adequate testing/duplication with a variety of users

**Hospitality**: Creating work that is easily understandable and usable
by peers in a similar field

**Privacy and Security**: Balancing the need for protecting personal and
group data with the use of that data for the welfare of the public

**Algorithmic Bias**: Recognizing and reducing any unintended biases
present in an algorithm/model that may have arisen as a result of
ignorance, assumptions, or past discriminatory societal patterns

**Data Integrity**: Handling data in a way that minimizes bias or the
potential for false results

**Professional Ethics**: Contributing one's best effort in the workplace
while respecting one's peers and upholding the requirements of one's
employer and the discipline's overarching guild
