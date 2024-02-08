# NDC Enterprise Code Review Checklist
Refer to the [Peer Reviews](https://ncratleosengtools.atlassian.net/wiki/spaces/NDCE/pages/50587346/Peer+Reviews) Confluence page for an overview of the NDC Enterprise peer review process.
### FIRST - DONE BEFORE CREATING PULL REQUEST >>> Add Message For Your Reviewers
---

[IN THE WRITE TAB: Type over this text to write a summary note of what's changed. Do this **before** clicking "Create pull request".]

---
### SECOND - DONE AFTER CREATING PULL REQUEST >>> Tick All Relevant Boxes 
The section below comprises checkbox items. Do not delete any item.  To get the best responses from your reviewers, please help them by checking all items relevant to your code updates.
#### Complexity of Logic 
- [ ] Very complex
- [ ] Moderately complex
- [ ] Simple
- [ ] None
#### Code Hygiene
- [ ] Unit tests run and all passed
- [ ] There is no duplicated code
- [ ] Naming conventions followed
- [ ] Full and clear code comments
- [ ] Null never returned
- [ ] New classes and functions small and do one thing 
- [ ] Copied and pasted code has NOT been used
#### Documentation & Specification
- [ ] Documentation Updated & Reviewed
- [ ] Testable G-W-T acceptance criteria are specified in the user story
#### Builder Project Flow Changes & Builder Fixer Tool
- [ ] FastStart
- [ ] Reference
- [ ] VG
- [ ] Adjunct
- [ ] Extra Screen
- [ ] Builder Fixer Tool Run & Issues Fixed
#### Edge Cases
Indicate the relevant edge cases your reviewers must consider, in addition to the *happy path*.
- [ ] Timeouts
- [ ] Reloading of views
- [ ] ITR responses
- [ ] Bad data input (long strings, invalid chars, boundary values, etc)
- [ ] Multi language handling
- [ ] Network problems
- [ ] Device faults & hardware differences (e.g. Touchscreen vs. FDK, IMCRW vs. DIP, CDM vs. MDM, etc.)
- [ ] Data persistence (CDI, data dictionary)
- [ ] Power failure
- [ ] Out of sequence flows
#### Other Teams
Indicate if your code impacts other teams, such as Activate Enterprise
- [ ] Have they been consulted on your changes?
- [ ] Have they provided edge cases that your code changes must handle?
- [ ] Have they already reviewed your code changes?
