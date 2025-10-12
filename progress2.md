### Progress Report 2 - Fixing Test from Idoft
Team members: __Yong Han Lin (yonghan5)__, __Ann Chen (hueic2)__
___

**We submitted 4 pull requests (2 accepted, 1 rejected, 1 pending), in total fixed 12 tests.**

### Effort and Challenges
___
- Resolved 2 more failing tests (no new PRs were created), received a response from the developer on the ```apache/accumulo``` repository. They requested a fix for ```testBulkFileCheck()``` on the PR for ```testDataFileCheck()```, the issue and fix were similar. And also both ```testDataFileCheck()``` and ```testScanFileCheck()``` use the same underlying function, so the fix also resolved ```testScanFileCheck()```.
  
- Worked on ```quarkus/quarkus``` and ```google/error-prone``` where there are tests that passes in lastest commit, so I went through the process of finding the commit which fixed the flaky test using Git Bisect. 
  - for the ```io.quarkus.arc.test.buildextension.beans.SyntheticBeanCollisionTest.testFailure``` in ```quarkus/quarkus```, I found the commit the commit it was first fixed with git bisect and ran the auto_check_fix_commit.sh and output the log. Also created the PR in idoft with update status.   
  - for the ```com.google.errorprone.bugpatterns.StreamResourceLeakTest.positive``` in ```google/error-prone```, I also went through the process for finding the commit which it was fixed using Git Bisect, however when running auto_check_fix_commit.sh it seems like it was actually passes in the reported commit, and I have also confirmed it the test passes in the report commit by running additional nondex tests (100 iterations), I'm not sure what the next step would be for this test.

---
### Points
- Point we think we earned in total:
  - Opened 1: 3 points
  - Accepted 9: 45 points
  - Rejected 1: -2 points
  - DeveloperFixed 1: 2 points
  - Total: 48 points
