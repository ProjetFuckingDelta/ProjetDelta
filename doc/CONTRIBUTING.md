# Contributing

## Introduction <a name="introduction"></a>

This file contains everything you need to know to contribute to the project.

## Table of contents <a name="table-of-contents"></a>

- [Introduction](#introduction)
- [Table of contents](#table-of-contents)
- [Branches](#branches)
- [Merging](#merging)
- [Tests](#tests)
- [Bugs](#bugs)
- [Feature Creation](#feature-creation)

## Branches <a name="branches"></a>

Everything you code must be done in a branch. The branch name follow this policy:
- (TYPE)/(TICKET_NB)/(TICKET_NAME)

Where:
- TYPE is the type of the ticket (feature, bug, etc.)
- TICKET_NB is the ticket number (DELTA-XXX)
- TICKET_NAME is the ticket name

## Merging <a name="merging"></a>

When you are done coding, you must create a pull request to merge your branch into the master branch. The pull request must be reviewed by at least one other person before being merged.

> **Warning:** The pull request must pass **all** the tests before being merged.

## Tests <a name="tests"></a>

Each functionnalities must be tested before being merged into the master branch.

## Bugs <a name="bugs"></a>

If you find a bug, you must create an issue on the github repository. The issue must be reviewed by at least one other person before being assigned to a developer.

## Feature Creation <a name="feature-creation"></a>

### For users

If you want to proposes features, you must create an issue with the label "enhancement" (TODO: valid the label name). The issue must be reviewed by at least one other person before being assigned to a developer.

### For developers

Before coding a feature, you must create a page of users story. The page will contains every aspect of your feature to determine the scope of the feature. The page must be reviewed by at least one other person before being assigned to a developer.

> **Warning**: The page must contains what the feature **should** and **should not** do.

If the feature is too big, you must split it into smaller features.

you must code **only** if the users story page is approved.

Once you are done with coding you **must** test it with your users story page. If the feature is not working as intended, you must fix it before creating a pull request.
