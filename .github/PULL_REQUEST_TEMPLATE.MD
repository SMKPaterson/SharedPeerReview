# NDC Enterprise Code Review Checklist
**View this file on GitHub *Preview* tab to enable checkbox ticks**

Refer to the [Peer Reviews](https://ncratleosengtools.atlassian.net/wiki/spaces/NDCE/pages/50587346/Peer+Reviews) Confluence page for an overview of the NDC Enterprise peer review process. This code review checklist supports this process.

To get the best responses from your reviewers, please help them by checking all items relevant to your code updates.
#
## Functional Changes
#
### Complexity of Logic 
Indicate the extent of logic complexity where you made your changes 
- [ ] Very complex
- [ ] Moderately complex
- [ ] Simple
- [ ] None
#
### Copied Code
State if you re-used existing code and pasted it into your changes
- [ ] Copied and pasted code has been used
#
### Registry Changes
Have you made, or had to consider, any changes to the registry
- [ ] Changes to existing NDC Enterprise registry entries
- [ ] Changes to existing Advance NDC registry entries
- [ ] New NDC Enterprise registy entries created
- [ ] New Advance NDC registry enties created
- [ ] Other registry

#
### Edge Cases
Indicate the relevant edge cases your reviewers must consider, in addition to the *happy path*.
- [ ] Timeouts scenarios?
- [ ] Reloading of views?
- [ ] ITR responses
- [ ] Bad data input (long strings, invalid chars, boundary values, etc)
- [ ] Multi language handling
- [ ] Network problems
- [ ] Device faults
- [ ] Data persistence (CDI, data dictionary)
- [ ] Power failure
- [ ] Touchscreen and FDK
- [ ] Card reader differences (IMCRW vs. DIP)
- [ ] Out of sequence flows

#
### Testable Acceptance Criteria
Having the user story defined with testable accetance criteria in G-W-T format can help reviewers better understand how the code will be used.
If this is not needed then tick reason why not
- [ ] User Story has acceptance test criteria defined in G-W-T format
- [ ] Not needed because not a user story
- [ ] Not needed because development technical task
- [ ] Not needed because of other reason

#
### Code Hygeine
- [ ] There is no duplicated code
- [ ] Naming conventions followed
- [ ] Full and clear code comments
- [ ] Null never returned
- [ ] New classes and functions small and do one thing 

#
### Builder Project Flows
Indicate if you made changes to any builder project
- [ ] Adjunct
- [ ] Blank
- [ ] CxTH
- [ ] FastStart
- [ ] NCR Bank Demo
- [ ] Reference
- [ ] VG

#
### Builder Fixer Tool
Indicate if you used the Builder Fixer Tool (bfx.exe) to check for errors
- [ ] Builder Fixer Tool used 

#
### Other Teams
Indicate if your code impacts other teams, such as Activate Enterprise
- [ ] Have they been consulted on your changes?
- [ ] Have they provided edge cases that your code changes must handle?
- [ ] Have they already reviewed your code changes?
