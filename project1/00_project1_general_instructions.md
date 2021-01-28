Instructions for 432 Project 1
================

-   [Introduction](#introduction)
-   [Should I work alone or in a
    group?](#should-i-work-alone-or-in-a-group)
-   [What Makes an Acceptable Data
    Set?](#what-makes-an-acceptable-data-set)
-   [Project 1 involves two tasks](#project-1-involves-two-tasks)
    -   [Detailed Instructions for Task 1 (The
        Proposal)](#detailed-instructions-for-task-1-the-proposal)
    -   [Detailed Instructions for Task 2 (Analysis and
        Presentation)](#detailed-instructions-for-task-2-analysis-and-presentation)
    -   [Templates for Project 1](#templates-for-project-1)
-   [Submission Information and
    Deadlines](#submission-information-and-deadlines)
-   [Getting Help](#getting-help)

# Introduction

It is hard to learn statistics (or anything else) passively; concurrent
theory and application are essential. Expert clinical researchers and
statisticians repeatedly emphasize how important it is that people be
able to write well, present clearly, work to solve problems, and show
initiative. This project assignment is designed to help you develop your
abilities and have a memorable experience.

In Project 1, you will be analyzing, presenting and discussing a pair of
regression models, specifically a linear regression and a logistic
regression, describing a data set you identify.

# Should I work alone or in a group?

You can choose either to work alone, or with one other person, to
complete Project 1. If you work in a group for Project 1, you will need
to work alone for Project 2 later in the term.

-   You will need to identify your Project 1 partner as part of your
    proposal submission.
-   If you are working with a partner, all work must be submitted by
    exactly one of you to [Canvas](https::/canvas.case.edu) while your
    partner will submit a one-page note to Canvas indicating the members
    of the partnership and that the partner will submit the work.

# What Makes an Acceptable Data Set?

1.  **Shareable with the World**. The data must be available to you, and
    shared with me and everyone else in the world (without any
    identifying information) as a well-tidied .csv file on 2020-03-01.
    If the data is from another source, the source (web or other) must
    be completely identified to me. Ongoing projects that require
    anyone’s approval to share data are not appropriate for Project 1,
    but can be used (with Dr. Love’s approval) for Project 2.

    -   You should have the data in R by 2020-02-21, so that you will
        have sufficient time to complete the other elements of this
        proposal. Any data you cannot have by that time is a bad choice.
    -   For Project 1, you may not use any data set used in the 431 or
        432 teaching materials. You may not use any data set included in
        [an R package that we are
        installing](https://thomaselove.github.io/432/r_packages.html)
        this semester, other than NHANES.
    -   You must use meaningfully different data sets in 432 Projects 1
        and 2.
    -   You **are** allowed to use NHANES data in Project 1, but only if
        you are combining information from at least three NHANES data
        sets. If you used NHANES data in your 431 project, you can use
        NHANES data again in Project 1 for 432, but you must study new
        outcomes.
    -   You are permitted to use BRFSS data, but you are not permitted
        to use data from SMART BRFSS, since we will be using that
        regularly in class.

2.  **Size**. A **minimum** of 100 complete observations are required on
    each variable. It is fine if there are some missing values, as well,
    so long as there are at least 100 rows with complete observations on
    all variables you intend to use in each model. The **maximum** data
    set size is 1000 observations, so if you have something larger than
    that, you’ll need to select a subset.

3.  **Outcomes**. The columns must include at least one quantitative
    outcome and one binary categorical outcome. If necessary, the binary
    outcome can be generated from the quantitative outcome (as an
    example, your quantitative outcome could be resting heart rate in
    beats per minute, and your binary outcome could be whether the
    resting heart rate is below 70 beats per minute.)

4.  **Inputs**. You will need at least four regression inputs
    (predictors) for each of your two models. At least one of the four
    must be quantitative (a variable is **not** quantitative for this
    purpose unless it has at least 10 different, ordered, observed
    values), *and* at least one must be multi-categorical (with between
    3 and 6 categories, each containing a minimum of 30 subjects) for
    each model. Your other inputs can represent binary,
    multi-categorical or quantitative data. You can examine different
    candidate predictors for each outcome, or use the same ones in both
    your linear and logistic regression models. Depending on your sample
    size, you can study more regression inputs. Specifically, if you
    have N complete observations in your data set, you are permitted to
    study up to 4 + (N-100)/100 candidate regression inputs, rounding
    down.

If you have a question about whether a data set is appropriate for
Project 1, please feel free to ask it [via
Piazza](https://piazza.com/case/spring2021/pqhs432) using the
**project1** label.

# Project 1 involves two tasks

In task 1 (which you’ll do in February), you will develop a [project
proposal](https://github.com/THOMASELOVE/432-2021/tree/master/project1/01_project1_proposal_instructions.md),
due at the start of March.

-   The proposal requires you to have completed the cleaning of the data
    you’ll use.
-   This part of the project involves selecting data, ingesting it into
    R and cleaning it, then describing the data.

In task 2 (which you’ll do in March), you will develop your [analyses
and present your
results](https://github.com/THOMASELOVE/432-2021/tree/master/project1/02_project1_analysis_and_presentation_instructions.md),
and this will be due near the end of March.

-   The work you’ll do in March will involve analyzing the data, fitting
    and displaying models, and putting together your presentation.

See the [Course
Calendar](https://thomaselove.github.io/432/calendar.html) for
deadlines.

## Detailed Instructions for Task 1 (The Proposal)

The [Task 1
instructions](https://github.com/THOMASELOVE/432-2021/tree/master/project1/01_project1_proposal_instructions.md)
are now available.

## Detailed Instructions for Task 2 (Analysis and Presentation)

The [Task 2
instructions](https://github.com/THOMASELOVE/432-2021/tree/master/project1/02_project1_analysis_and_presentation_instructions.md)
are now available.

## Templates for Project 1

Templates for the work in Tasks 1 and 2 are available. See the detailed
instructions for each task for links.

# Submission Information and Deadlines

All Project 1 work is to be submitted [via
Canvas](https://canvas.case.edu/).

Deadlines are found on the [Course
Calendar](https://thomaselove.github.io/432/calendar.html).

# Getting Help

If you have a question about whether a data set is appropriate for
Project 1 or anything else about Project 1, please feel free to ask it:

1.  [via Piazza](https://piazza.com/case/spring2021/pqhs432) using the
    **project1** label.
2.  at TA office hours
3.  directly of Professor Love before or after class (or, if necessary,
    via email, although we prefer Piazza)