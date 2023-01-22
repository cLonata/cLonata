## **Branches**

The main branch should be named main.
The people working on a product decide if they want to work with further branches.

If you need further branches, it is advisable, to add the number of the issue and a short title inside of a branch name, e. g.:
- 100-validation-errors
- 101-basic-search
- 102-german-translation
- 103-live-deployment
- 104-url-formatting

## **Commits**
- We use the syntax from Conventional Commits.
- Commit messages include one of the following prefixes:

```  - fix: to fix bugs
  - feat: to introduce new features
  - chore: to make general changes
  - ci: to work on continuous integration/continuous deployment
  - refactor: to improve existing source code
```
- Commit messages should be written in the present form
- Commit messages should be written in English
- Commit messages should start with a lowercase character
- It is advisable to add the issue number to a commit message

*Practical examples of commit messages:*
- fix: display validation errors properly, refs #100
- feat: implement basic search, refs #101
- chore: add correct german translation, refs #102
- ci: repair live deployment, refs #103
- refactor: unify URL formatting, refs #104

*If a commit is a work in progress, it should be marked as such:*
- fix: display validation errors properly (WIP), refs #100
- feat: implement basic search (WIP), refs #101
- chore: add correct german translation (WIP), refs #102
- ci: repair live deployment (WIP), refs #103
- refactor: unify URL formatting (WIP), refs #104
