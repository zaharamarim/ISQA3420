#Three Use Cases

####Use Case 1:
######Title:Developer commits code to be examined for vulnerabilities
######Primary Actor: Developer
######Goal in Context: Gather vulnerability information for all external source code that is used by developers
######Stakeholders: Developer / Manager
######Preconditions: Developer is able to check in external source code to vulnerability system. NIST vulnerability database is up to date. 
######Main Success Scenario: Developer checks in code and vulnerability information is recorded to the Risk DB. 
######Failed End Conditions: Developer is unable to check in code. Checked in code is not checked for vulnerabilities, failing to update Risk DB. 
######Trigger: Code check in

####Use Case 2:
######Title: Manager check code for copyright
######Primary Actor: Manager
######Goal in Context: 
######Stakeholders: Developer / Manager
######Preconditions:
######Main Success Scenario:
######Failed End Conditions:
######Trigger:

####Use Case 3:
######Title:  Check Vulnerabilities
######Primary Actor: Manger
######Goal in Context: Check vulnerabilities information for all external source used by user.
######Stakeholders: Manger
######Preconditions: Manger is able to check in external source code/ Policies to vulnerability system
######Main Source Scenario: Manger is able to check in and vulunerability information is recorded to the Risk DB.
######Failed End Conditions: Manger is unable to check in vulunerability, failing to update Risk DB.
######Trigger: Vulnerbility check in.
