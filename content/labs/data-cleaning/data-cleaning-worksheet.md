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

### Confidentiality of personally identifying data

1.  If all of the data in this survey were made available, would it be possible
    to identify or nearly identify some individuals (perhaps by combining it with
    other information)?  Who might have access to the additional information that
    would be needed?
    
2. Could a personally identified individual suffer harm from being identified 
   in these data? (What sorts of harm?)
   
3. What ethical responsibilities do researchers working with this data have in light
   of your previous answers?
    

### Dealing with missing data

Very often some values of some variables are not recorded for some individuals.
There are many reasons why data might be missing. Perhaps the data collection
protocol changed over time. Perhaps some subjects declined to answer some questions
on a survey. Perhaps some information is simply not available for some individuals. 

Before proceeding to analyse a data set, researchers need to decide how to handle missing
data.

4. For several people, `age` is missing.
   Consider the pros and cons of each of these possible
    options for addressing the problem. How likely is the option to
    create an ethical issue and what might that issue be if there is
    one?

    a.  Fill with the median value from the data set.

    b.  Fill with the mean value from the data set.

    c.  Remove records where `age` is missing and make a note of this in the
    data cleaning documentation.

5.  For several records, the college experience of at least one of the
    parents is missing.  Is there a sub-population with which this might
    be more likely to happen? 
    What ethical issue(s) might arise if we simply remove anyone
    for whom this values is missing?

6. For several records, `disability` is missing.
    Removing the related records could negatively affect the diversity
    of this study. Why?

7.  There are several other fields left blank on various records. You
    try to take each omission on a case by case basis, doing what you
    think is right. This might influence both reliability and
    hospitality. Why?

### Dealing with (possibly) incorrect data

Just because values are included in a data set doesn't mean that those 
values are correct. Unusual observations might catch our eye and lead
us to investigate further.

8.  One current GPA is listed as 1.35. This is much lower than the GPAs of 
other students from that university, where the mean GPA is approximately 3.0.
You're pretty sure that the 1 and the 3 must have been swapped so you go ahead 
and change the GPA to a more reasonable 3.15. 
What ethical issues might you be violating?

## Ethical Issues Definitions

{{% ethical-issues-list %}}

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
