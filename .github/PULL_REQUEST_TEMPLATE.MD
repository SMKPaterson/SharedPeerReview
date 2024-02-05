# NDC Enterprise Code Review Checklist
Refer to the [Peer Reviews](https://ncratleosengtools.atlassian.net/wiki/spaces/NDCE/pages/50587346/Peer+Reviews) Confluence page for an overview of the NDC Enterprise peer review process.
### FIRST - DONE BEFORE CREATING PULL REQUEST >>> Add Message For Your Reviewers
---

[Type over this text to write any general message for your reviewers. Do this **before** clicking "Create pull request".]

---
### SECOND - DONE AFTER CREATING PULL REQUEST >>> Tick All Relevant Boxes 
The section below comprises checkbox items. Do not delete any item.  To get the best responses from your reviewers, please help them by checking all items relevant to your code updates.
#### Complexity of Logic 
- [ ] Very complex
- [ ] Moderately complex
- [ ] Simple
- [ ] None
#### Code Hygeine
- [ ] There is no duplicated code
- [ ] Naming conventions followed
- [ ] Full and clear code comments
- [ ] Null never returned
- [ ] New classes and functions small and do one thing 
- [ ] Copied and pasted code has NOT been used
#### Documentation
- [ ] Documentation Updated & Reviewed
#### Registry Changes
- [ ] Changes to existing NDC Enterprise or Advance NDC registry entries
- [ ] New NDC Enterprise or Advance NDC registy entries created
- [ ] Other registry changes
#### Builder Project Flow Changes
- [ ] FastStart
- [ ] Reference
- [ ] VG
- [ ] Adjunct
- [ ] CxTH
#### Edge Cases
Indicate the relevant edge cases your reviewers must consider, in addition to the *happy path*.
- [ ] Timeouts scenarios
- [ ] Reloading of views
- [ ] ITR responses
- [ ] Bad data input (long strings, invalid chars, boundary values, etc)
- [ ] Multi language handling
- [ ] Network problems
- [ ] Device faults
- [ ] Data persistence (CDI, data dictionary)
- [ ] Power failure
- [ ] Hardware differences (e.g. Touchscreen vs. FDK, IMCRW vs. DIP, CDM vs. MDM, etc.)
- [ ] Out of sequence flows
#### Testable Acceptance Criteria
Having the user story defined with testable accetance criteria in G-W-T format can help reviewers better understand how the code will be used.
If this is not needed then tick reason why not
- [ ] User Story has acceptance test criteria defined in G-W-T format
- [ ] Not needed because not a user story
- [ ] Not needed because development technical task
- [ ] Not needed because of other reason
#### Builder Fixer Tool
- [ ] Builder Fixer Tool used 
#### Other Teams
Indicate if your code impacts other teams, such as Activate Enterprise
- [ ] Have they been consulted on your changes?
- [ ] Have they provided edge cases that your code changes must handle?
- [ ] Have they already reviewed your code changes?
