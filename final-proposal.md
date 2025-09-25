# Title
Fixing Java Flaky tests
# Team Members
yonghan5, hueic2
# Problem
Fixing Flaky Test from ```pr-data.csv```, will start with ```google/guava``` and ```EsotericSoftware/kryo```
# Proposed Solution
For the each test, we will use tools like nondex to detect and debug the root cause of flakiness, and to implement the fix. 
# Evaluation
Verify the fix with nondex, and submit a pull request to the original repositories.
# Initial Results
Created 2 tentative PRs in public fork. 
# Immediate Next Steps
Create the real PR to the original repository. 
