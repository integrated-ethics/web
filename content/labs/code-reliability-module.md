---
title: "Reliability Module"
author: "TODO"
date: "2021-06-29"
output:
  blogdown::html_page:
    toc: true
    fig_width: 6
    dev: "svg"
---

Reliability Module

Module Summary

 

**Ethics background** required: Familiarity with the virtue ethics,
deontological, and utilitarian ethical frameworks would be helpful. They
are briefly reviewed for those who need the information

**Subject matter** referred to in this module: computer programming,
testing, documentation, code structure, user training

**Placement** in overall ethics curriculum:

> Academic year: Junior or Senior courses. Good candidate for course
> that covers professionalism,
>
> software engineering. Students should have had experience with larger
> projects.

            Recommended previous modules: First year curriculum plus
additional modules

            Recommended follow-up modules: Nothing specific

**Time** required:

            In class: 30 minutes * *

**Learning objectives**:

-   Students understand that code reliability is an ethical issue

-   Students review and learn new practices that influence reliability

-   Students practice recognizing reliability issues in coding scenarios

-   Students think about how to incorporate good techniques for coding
    that encourage the creation of reliable code even if it is not
    specifically asked for

**Module overview**:

[Ethical issues to be considered]{.ul}: Code reliability

[Exercise flow:]{.ul}

-   In groups, read scenarios where unreliable software caused a
    problem.

-   From each scenario, identify the point of unreliability

-   Establish that code reliability is an ethical issue by looking at
    these scenarios and the virtues violated, harm done, or rules broken
    by these mishaps.

-   Brainstorm techniques that students have learned during their
    coursework that improves the chance that code will be reliable and
    suggest which of the techniques might have improved the outcome of
    the scenarios

-   Brainstorm professional practices that should routinely be
    incorporated even if not included in the project requirements

-   For each of the best practices revealed above discuss reasons why
    people in a real-life pressure-filled situation might be tempted to
    skirt some the practices.

**Preparation:** Read the entire module and print/post copies of
reliability scenarios to be distributed to groups.

Instructors Guide

**Lesson plan**

[Activity (20 min)]{.ul}

Distribute the short summaries of software mishaps, each (or more than
1) to a small group of students. On the scenario handouts, groups are
asked to:

-   Read their scenario as a group

-   Determine together what the reliability issue was for their
    scenario.

-   Determine if there is a moral (ethical) issue related to that
    reliability issue

*To determine ethicality, students are referred to three different
ethical frameworks by answering a question that framework would pose.
Here we provide the question and the framework that would use the
question:*

-   *Does the unreliability of the software you are considering cause
    moral values (virtues) of you or your society to be violated?
    (virtue ethics -- examples of virtues are honesty, integrity,
    perseverance, generosity, frugality, helpfulness, concern for
    others, etc.)*

-   *Does the unreliability of the software you are considering cause
    harm to people without producing great value to many more? (a
    tradeoff) (utilitarianism asks if the outcome violates the greater
    good)*

-   *Is there a rule that would be violated by allowing this software to
    continue to be used knowing its faults? (deontology -- ethical
    framework based on an ethical code, corporate guidelines, city laws
    etc. )*

After group work is complete:

-   As a class, discuss why reliability is (or is not) an ethical issue
    by referring to the scenarios. Each group should report on their
    scenario. Make sure that students can support their conclusions
    using one or more of the questions posed in the handout.

    -   Students may conclude, for example, that the issue with the Mars
        Orbiter was not an ethical issue since no lives were at stake,
        but if frugality is a virtue, it could be (so much money was
        lost). They may reach different conclusions on other scenarios
        as well, but several should be seen as clearly ethical/moral
        issues.

-   Make a visible list of techniques related to writing good code that
    students have learned in courses and that could improve the
    reliability of code. When possible, refer to a particular scenario
    (read in class or otherwise) that could have been improved by that
    technique.

**Examples:**

-   Thoroughly retest software after making hardware changes -- this
    > would have helped with the Ariane 5 issue. If the hardware is
    > impossible to test on, build a software simulator of the hardware.

-   Good documentation and code structure could have helped the
    > maintenance programmers of the financial software find the bug
    > more quickly

-   With the Y2K problem, careful pre-planning with original software
    > could have avoided this widespread issue.

Other best practices that could avoid reliability issues in these or
other scenarios

-   Train users on software

-   Have outsiders and inexperienced users review the user manual

-   Test the software with inexperienced users (not just the software
    team) to see if they induce errors and find the software easy to
    use/learn.

-   Consider all possible cases, or have error messages for those not
    addressed

-   Write code that forces users to give correct input (data type,
    range, etc.)

-   Re-test after fixing bugs

-   Think beyond just meeting the user specifications. If, in the course
    of creating the software, you think other reliability features are
    important, speak up!

-   Anticipate uses of software that are different from the current use.
    Example: you are writing a program that will be processing whole
    dollar amounts. What if the user decided later that prices could
    include dollars and cents?

-   Provide adequate training or mentoring for the programmer assigned
    to the job

[Reflection as a class (10 min)]{.ul}

While students might have learned about reliability techniques, it is
helpful to warn them that, in practice, there might be barriers to
implementing them. Have students discuss these two questions. (Some
answers are provided)

-   **What might keep you as a software engineer from adhering to these
    best practices?**

    -   *The number one issue is probably time*

        -   *Not enough time to plan (development phase)*

        -   *Not enough time to test*

        -   *Not enough time to code!*

    -   *Might not want to bring up other reliability features if you
        feel that you are over-stepping your bounds with your supervisor
        or the customer*

-   **What coding strategies should you employ, whether you are told to
    or not, to increase the reliability of software?**

    -   *Plan before coding and make sure that you understand the
        specifications*

    -   *Test as you go along -- don't wait until the end where there is
        a time-crunch*

    -   *Good documentation and code structure*

    -   *Use encapsulation to keep the user from introducing input that
        is out of range.*

    -   *Make notes of potential future issues (assumptions you are
        making about hardware etc.)*

    -   *If you don't have enough training for a particular job, speak
        up!*

[Assessment]{.ul} (to be included at a later date on a quiz, paper, or
exam to determine if LOs were reached)

-   What does it mean for code to be "reliable"?

*It operates failure-free in a specified environment for a specified
amount of time*

-   Name four causes of unreliable code

*Some are: poor planning, poor/incomplete testing, poor code structure,
poor documentation, poor user interface, testing only with people who
created the code*

-   Provide an example of unreliable code that shows that code
    reliability is an ethical issue. Explain your rationale for calling
    reliability an ethical issue in this case.

    -   *All scenarios violated the virtues of quality and excellence.*

    -   *The financial software scenario would violate the virtue of
        compassion -- not writing the code/documentation well forced the
        maintenance programmer to work harder than necessary*

    -   *In the case of the patriot missile detection system and many
        others (UK Child support system, Heathrow baggage claim), it
        certainly caused great harm to many without producing benefit to
        many more (did not serve the greater good)*

    -   *Many scenarios violate the ACM code of ethics principle 1.2
        "Avoid harm"*

    -   *ACM code of ethics also provides principle 2.5 Give
        comprehensive and thorough evaluations of computer systems and
        their impacts, including analysis of possible risks.*

    -   *Article 2.6 of the ACM code of ethics says "Perform work only
        in areas of competence" In the junior programmer scenario, Kim
        was not adequately trained for the job she was given*

 

**Student handouts are attached**

U.S Patriot Missile Defense Scenario

In February of 1991, a U.S. Patriot missile defense system in Saudi
Arabia, failed to detect an attack on an Army barracks. A government
report found that a software problem led to an inaccurate tracking
calculation that became worse the longer the system operated.

<https://raygun.com/blog/costly-software-errors-history/>

The general definition of the word "reliable" according to Webster's
Dictionary is "giving the same result on successive trials."

According to ANSI/IEEE, software reliability is defined as: the
probability of failure-free software operation for a specified period of
time in a specified environment.

Answer the following questions with your group

-   According to the definitions, in what way was the software in your
    scenario unreliable?

-   The next question relates to the ethicality of unreliable software.
    Determining the ethicality of something is sometimes hard to do. If
    you have studied ethics previously, you may have a method. If not,
    here are some things to consider about your scenario:

    -   Does the unreliability of the software you are considering cause
        moral values (virtues) of you or your society to be violated?
        Virtues include:

        -   Honesty, integrity, compassion, courage, excellence,
            dignity, justice, kindness, patience, quality, perseverance,
            respect, service, transparency, etc.

    -   Does the unreliability of the software you are considering cause
        harm to people without producing great value to many more? (a
        tradeoff)

    -   Is there a rule that would be violated by allowing this software
        to continue to be used knowing its faults?

Be prepared to discuss your answers with the whole group

U.K.'s Child Support Agency Scenario

In 2004, EDS introduced a highly complex IT system to the U.K.'s Child
Support Agency (CSA). At the exact same time, the Department for Work
and Pensions (DWP) decided to restructure the entire agency. The two
pieces of software were completely incompatible, and irreversible errors
were introduced as a result. The system somehow managed to overpay 1.9
million people, underpay another 700,000, had US\$7 billion in
uncollected child support payments, a backlog of 239,000 cases, 36,000
new cases "stuck" in the system, and has cost the UK taxpayers over
US\$1 billion.

<https://raygun.com/blog/costly-software-errors-history/>

The general definition of the word "reliable" according to Webster's
Dictionary is "giving the same result on successive trials."

According to ANSI/IEEE, software reliability is defined as: the
probability of failure-free software operation for a specified period of
time in a specified environment.

Answer the following questions with your group

-   According to the definitions, in what way was the software in your
    scenario unreliable?

-   The next question relates to the ethicality of unreliable software.
    Determining the ethicality of something is sometimes hard to do. If
    you have studied ethics previously, you may have a method. If not,
    here are some things to consider about your scenario:

    -   Does the unreliability of the software you are considering cause
        moral values (virtues) of you or your society to be violated?
        Virtues include:

        -   Honesty, integrity, compassion, courage, excellence,
            dignity, justice, kindness, patience, quality, perseverance,
            respect, service, transparency, etc.

    -   Does the unreliability of the software you are considering cause
        harm to people without producing great value to many more? (a
        tradeoff)

    -   Is there a rule that would be violated by allowing this software
        to continue to be used knowing its faults?

Be prepared to discuss your answers with the whole group

Y2K Problem Scenario

The Year 2000 problem, also known as the Y2K problem, the Millennium
bug, Y2K bug, the Y2K glitch, or Y2K, refers to events related to the
formatting and storage of calendar data for dates beginning in the year
2000. Problems were anticipated, and arose, because many programs
represented four-digit years with only the final two digits -- making
the year 2000 indistinguishable from 1900. The assumption of a
twentieth-century date in such programs could cause various errors, such
as the incorrect display of dates and the inaccurate ordering of
automated dated records or real-time events.

<https://en.wikipedia.org/wiki/Year_2000_problem>

The general definition of the word "reliable" according to Webster's
Dictionary is "giving the same result on successive trials."

According to ANSI/IEEE, software reliability is defined as: the
probability of failure-free software operation for a specified period of
time in a specified environment.

Answer the following questions with your group

-   According to the definitions, in what way was the software in your
    scenario unreliable?

-   The next question relates to the ethicality of unreliable software.
    Determining the ethicality of something is sometimes hard to do. If
    you have studied ethics previously, you may have a method. If not,
    here are some things to consider about your scenario:

    -   Does the unreliability of the software you are considering cause
        moral values (virtues) of you or your society to be violated?
        Virtues include:

        -   Honesty, integrity, compassion, courage, excellence,
            dignity, justice, kindness, patience, quality, perseverance,
            respect, service, transparency, etc.

    -   Does the unreliability of the software you are considering cause
        harm to people without producing great value to many more? (a
        tradeoff)

    -   Is there a rule that would be violated by allowing this software
        to continue to be used knowing its faults?

Be prepared to discuss your answers with the whole group

NASA's Mars Climate Orbiter Scenario

On its mission to Mars in 1998 the Climate Orbiter spacecraft was
ultimately lost in space. Although the failure bemused engineers for
some time it was revealed that a sub contractor on the engineering team
failed to make a simple conversion from English units to metric. An
embarrassing lapse that sent the \$125 million craft fatally close to
Mars' surface after attempting to stabilize its orbit too low. Flight
controllers believe the spacecraft plowed into Mars' atmosphere where
the associated stresses crippled its communications, leaving it hurtling
on through space in an orbit around the sun.

<https://raygun.com/blog/costly-software-errors-history/>

The general definition of the word "reliable" according to Webster's
Dictionary is "giving the same result on successive trials."

According to ANSI/IEEE, software reliability is defined as: the
probability of failure-free software operation for a specified period of
time in a specified environment.

Answer the following questions with your group

-   According to the definitions, in what way was the software in your
    scenario unreliable?

-   The next question relates to the ethicality of unreliable software.
    Determining the ethicality of something is sometimes hard to do. If
    you have studied ethics previously, you may have a method. If not,
    here are some things to consider about your scenario:

    -   Does the unreliability of the software you are considering cause
        moral values (virtues) of you or your society to be violated?
        Virtues include:

        -   Honesty, integrity, compassion, courage, excellence,
            dignity, justice, kindness, patience, quality, perseverance,
            respect, service, transparency, etc.

    -   Does the unreliability of the software you are considering cause
        harm to people without producing great value to many more? (a
        tradeoff)

    -   Is there a rule that would be violated by allowing this software
        to continue to be used knowing its faults?

Be prepared to discuss your answers with the whole group

Ariane 5 Flight 501 Scenario

Europe's newest un-manned satellite-launching rocket reused working
software from its predecessor, the Ariane 4. Unfortunately, the Ariane
5's faster engines exploited a bug that was not found in previous
models. Thirty-six seconds into its maiden launch the rocket's engineers
hit the self destruct button following multiple computer failures. In
essence, the software had tried to cram a 64-bit number into a 16-bit
space. The resulting overflow conditions crashed both the primary and
backup computers (which were both running the exact same software). The
Ariane 5 had cost nearly \$8 billion to develop, and was carrying a
\$500 million satellite payload when it exploded.

<https://raygun.com/blog/costly-software-errors-history/>

The general definition of the word "reliable" according to Webster's
Dictionary is "giving the same result on successive trials."

According to ANSI/IEEE, software reliability is defined as: the
probability of failure-free software operation for a specified period of
time in a specified environment.

Answer the following questions with your group

-   According to the definitions, in what way was the software in your
    scenario unreliable?

-   The next question relates to the ethicality of unreliable software.
    Determining the ethicality of something is sometimes hard to do. If
    you have studied ethics previously, you may have a method. If not,
    here are some things to consider about your scenario:

    -   Does the unreliability of the software you are considering cause
        moral values (virtues) of you or your society to be violated?
        Virtues include:

        -   Honesty, integrity, compassion, courage, excellence,
            dignity, justice, kindness, patience, quality, perseverance,
            respect, service, transparency, etc.

    -   Does the unreliability of the software you are considering cause
        harm to people without producing great value to many more? (a
        tradeoff)

    -   Is there a rule that would be violated by allowing this software
        to continue to be used knowing its faults?

Be prepared to discuss your answers with the whole group

Heathrow Terminal 5 Opening Scenario

Just before the opening of Heathrow's Terminal 5 in the UK, staff tested
the brand new baggage handling system built to carry the vast amounts of
luggage checked in each day. Engineers tested the system thoroughly
before opening the Terminal to the public with over 12,000 test pieces
of luggage. It worked flawlessly on all test runs only to find on the
Terminal's opening day the system simply could not cope. It is thought
that "real life" scenarios such as removing a bag from the system
manually when a passenger had left an important item in their luggage,
had caused the entire system to become confused and shut down. Over the
following 10 days some 42,000 bags failed to travel with their owners,
and over 500 flights were cancelled.

<https://www.computerworld.com/article/3412197/top-software-failures-in-recent-history.html>

The general definition of the word "reliable" according to Webster's
Dictionary is "giving the same result on successive trials."

According to ANSI/IEEE, software reliability is defined as: the
probability of failure-free software operation for a specified period of
time in a specified environment.

Answer the following questions with your group

-   According to the definitions, in what way was the software in your
    scenario unreliable?

-   The next question relates to the ethicality of unreliable software.
    Determining the ethicality of something is sometimes hard to do. If
    you have studied ethics previously, you may have a method. If not,
    here are some things to consider about your scenario:

    -   Does the unreliability of the software you are considering cause
        moral values (virtues) of you or your society to be violated?
        Virtues include:

        -   Honesty, integrity, compassion, courage, excellence,
            dignity, justice, kindness, patience, quality, perseverance,
            respect, service, transparency, etc.

    -   Does the unreliability of the software you are considering cause
        harm to people without producing great value to many more? (a
        tradeoff)

    -   Is there a rule that would be violated by allowing this software
        to continue to be used knowing its faults?

Be prepared to discuss your answers with the whole group

Financial Software Scenario

A customer using a financial software package preparing for an upcoming
client meeting. The financial advisor is reviewing his presentation and
recognizes that the investment earning for his client are showing a
negative value when he is certain that the investments have made a gain.
The financial advisor calls the software company asking if he has used
the software incorrectly or if there is a known error. The customer
service representative says that she is not aware of a known error, but
will ask the maintenance programmers to look into the problem. The
programmers had a very difficult time finding the bug, but a week later
they located it. Unfortunately, in the absence of the software, the
financial advisor had to reschedule and lost the client due to the
delay.

The general definition of the word "reliable" according to Webster's
Dictionary is "giving the same result on successive trials."

According to ANSI/IEEE, software reliability is defined as: the
probability of failure-free software operation for a specified period of
time in a specified environment.

Answer the following questions with your group

-   According to the definitions, in what way was the software in your
    scenario unreliable?

-   The next question relates to the ethicality of unreliable software.
    Determining the ethicality of something is sometimes hard to do. If
    you have studied ethics previously, you may have a method. If not,
    here are some things to consider about your scenario:

    -   Does the unreliability of the software you are considering cause
        moral values (virtues) of you or your society to be violated?
        Virtues include:

        -   Honesty, integrity, compassion, courage, excellence,
            dignity, justice, kindness, patience, quality, perseverance,
            respect, service, transparency, etc.

    -   Does the unreliability of the software you are considering cause
        harm to people without producing great value to many more? (a
        tradeoff)

    -   Is there a rule that would be violated by allowing this software
        to continue to be used knowing its faults?

Be prepared to discuss your answers with the whole group

Accounting System Scenario

A computer company is writing the first stage of a more efficient
accounting system which will be used by the government and will save
taxpayers a considerable amount of money. A software engineer is asked
to design a user interface for the system. The accounting system and the
interface contain all of the functionality described in the
requirements. The system is installed, but the user interface is so hard
to use that the complaints of the customer\'s staff are heard by the
customer\'s upper level management. Because of these complaints, upper
level management will not invest any more money in the development of
the new accounting system and they go back to their original more
expensive system.

<https://csciwww.etsu.edu/gotterbarn/artge2.htm>

The general definition of the word "reliable" according to Webster's
Dictionary is "giving the same result on successive trials."

According to ANSI/IEEE, software reliability is defined as: the
probability of failure-free software operation for a specified period of
time in a specified environment.

Answer the following questions with your group

-   According to the definitions, in what way was the software in your
    scenario unreliable?

-   The next question relates to the ethicality of unreliable software.
    Determining the ethicality of something is sometimes hard to do. If
    you have studied ethics previously, you may have a method. If not,
    here are some things to consider about your scenario:

    -   Does the unreliability of the software you are considering cause
        moral values (virtues) of you or your society to be violated?
        Virtues include:

        -   Honesty, integrity, compassion, courage, excellence,
            dignity, justice, kindness, patience, quality, perseverance,
            respect, service, transparency, etc.

    -   Does the unreliability of the software you are considering cause
        harm to people without producing great value to many more? (a
        tradeoff)

    -   Is there a rule that would be violated by allowing this software
        to continue to be used knowing its faults?

Be prepared to discuss your answers with the whole group

Radar System Scenario

A computer company wrote a radar system for ships which identifies
incoming aircraft as friend or foe. A software engineer developed a user
interface which will display needed information. This information can be
used to determine if defensive action is necessary. The radar system and
the interface contain all of the functionality described in the
requirements. Although all of the information required was displayed, it
was not displayed in a way that was adequate for them to distinguish a
military attack plane from a commercial airliner. This contributed to
the loss of many lives.

<https://csciwww.etsu.edu/gotterbarn/artge2.htm>

The general definition of the word "reliable" according to Webster's
Dictionary is "giving the same result on successive trials."

According to ANSI/IEEE, software reliability is defined as: the
probability of failure-free software operation for a specified period of
time in a specified environment.

Answer the following questions with your group

-   According to the definitions, in what way was the software in your
    scenario unreliable?

-   The next question relates to the ethicality of unreliable software.
    Determining the ethicality of something is sometimes hard to do. If
    you have studied ethics previously, you may have a method. If not,
    here are some things to consider about your scenario:

    -   Does the unreliability of the software you are considering cause
        moral values (virtues) of you or your society to be violated?
        Virtues include:

        -   Honesty, integrity, compassion, courage, excellence,
            dignity, justice, kindness, patience, quality, perseverance,
            respect, service, transparency, etc.

    -   Does the unreliability of the software you are considering cause
        harm to people without producing great value to many more? (a
        tradeoff)

    -   Is there a rule that would be violated by allowing this software
        to continue to be used knowing its faults?

Be prepared to discuss your answers with the whole group

Junior Programmer Scenario

One of the main clients of ACME Programming Associates is Always
Airways. Always Airways has employed ACME to create simulators for
training their pilots on various aircraft. One simulator needs to be
updated because the 2020 version of commuter planes used by Always
contains an air circulation monitor that was not previously included on
the cockpit dashboard. The updated simulator needs to be ready for
training pilots next week. They are on a very strict timeline but the
only programmer available to ACME is Kim, a fairly new college graduate
who has only been with the company for 2 months and just finished her
training on the company's proprietary IDE. Since the addition of the
monitor to the dashboard should be a fairly simple change, Kim is
assigned to the job. Kim tested the addition to the best of her ability,
but did not realize that the units used for air circulation could
produce values up to 100 billion. Hence, when the simulator was used by
the pilots, negative numbers appeared.

According to ANSI/IEEE, software reliability is defined as: the
probability of failure-free software operation for a specified period of
time in a specified environment.

Answer the following questions with your group

-   According to the definitions, in what way was the software in your
    scenario unreliable?

-   The next question relates to the ethicality of unreliable software.
    Determining the ethicality of something is sometimes hard to do. If
    you have studied ethics previously, you may have a method. If not,
    here are some things to consider about your scenario:

    -   Does the unreliability of the software you are considering cause
        moral values (virtues) of you or your society to be violated?
        Virtues include:

        -   Honesty, integrity, compassion, courage, excellence,
            dignity, justice, kindness, patience, quality, perseverance,
            respect, service, transparency, etc.

    -   Does the unreliability of the software you are considering cause
        harm to people without producing great value to many more? (a
        tradeoff)

    -   Is there a rule that would be violated by allowing this software
        to continue to be used knowing its faults?

Be prepared to discuss your answers with the whole group
