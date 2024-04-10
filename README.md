# pr-repository-name-pattern

This repository contains the standards adopted in the creation of repositories.

Repository names follow a naming pattern in the context-name-optional-description format.

Currently, the following context acronyms are used in repositories:

ES: Study - study repository containing code snippets and comments on a given topic.
CO: Knowledge - Exclusive repository for articles and notes, which may be related to an ES repository.
DE: Development - Code repository, personal projects.
PR: Standard - Repository containing information on adopted nomenclatures and standards.
The practice of commonly used semantic commits is adopted:

feat: Indicates the inclusion of a new resource (relates to the MINOR of semantic versioning).
fix: Indicates the correction of a problem (bug fix) (related to the semantic versioning PATCH).
docs: Indicates changes to documentation, such as in the repository's README (does not include code changes).
style: Indicates code formatting changes, such as semicolons, trailing spaces, lint (does not include code changes).
remove: Indicates the deletion of obsolete or unused files, directories or functionalities, reducing the size and complexity of the project and keeping it more organized.
For commit messages, the simplicity approach is followed, using the thought "if I apply this commit it will..." to keep the message concise and direct. Example: If I apply this commit it will add new feature for language support.

Commit messages are not used in the past or gerund.
