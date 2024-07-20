
### This repository contains the standards adopted in the creation of repositories. ###

Repository names follow a naming pattern in the <organization>-<projectName>-<context> format.

#### Currently, the following context acronyms are used in repositories: ###

* __ES:__ Study - study repository containing code snippets and comments on a given topic.
* __DE:__ Development - Code repository, personal projects.
* __STD:__ Standard - Repository containing information on adopted nomenclatures and standards.
  
 #### The practice of commonly used semantic commits is adopted: ####

* __feat:__ Indicates the inclusion of a new resource (relates to the MINOR of semantic versioning).
* __fix:__ Indicates the correction of a problem (bug fix) (related to the semantic versioning PATCH).
* __docs:__ Indicates changes to documentation, such as in the repository's README (does not include code changes).
* __style:__ Indicates code formatting changes, such as semicolons, trailing spaces, lint (does not include code changes).
* __remove:__ Indicates the deletion of obsolete or unused files, directories or functionalities, reducing the size and complexity of the project and keeping it more organized.
  
For commit messages, the simplicity approach is followed, using the thought "if I apply this commit it will..." to keep the message concise and direct, example: If I apply this commit it will `add new feature for language support`. __Commit messages are not used in the past or gerund__ .
