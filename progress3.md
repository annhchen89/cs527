### Progress Report 3 - Fixing Test from Idoft
Team members: __Yong Han Lin (yonghan5)__, __Ann Chen (hueic2)__
___

**We submitted 12 pull requests (4 accepted, 1 rejected, 7 pending), in total fixed 19 tests.**

### Effort and Challenges
___
- Ran NonDex across all modules in ```EsotericSoftware/kryo```, identified 2 additional failing tests, implemented fixes, and submitted a PR addressing these failures — both fixes have been accepted.
- Worked on ```Google/error-prone``` where the ```StreamResourceLeakTest.positive``` test passes in latest commit, so I found the commit it was first fixed with git bisect and ran the auto_check_fix_commit.sh and output the logs.
- Ran NonDex on all modules in ```Google/error-prone```; no additional nondeterministic tests were detected.  
- Ran NonDex on modules in ```apache/accumulo```, uncovering 3 additional failing tests.  
- Implemented fixes for 2 of the failing tests in ```apache/accumulo``` and submitted two corresponding PRs to the repository.
- Worked on ```INRIA/spoon``` and fixed all three failing tests in this repository (will run nondex on the modules to find new tests this week). I spent over three hours on each test, as the causes of the failures were unfamiliar to me. Through this process, I learned several new aspects of Java and testing, such as reflection-based model construction, enum and annotation handling.
- Worked on ```MyCATApache/Mycat-Server``` and fixed one test and opened PR.

---
### Points
- Point we think we earned:
  - Opened 7: 21 points
  - Accepted 11: 55 points
  - Rejected 1: -2 points
  - DeveloperFixed 2: 4 points
  - DeveloperWontFix 1: 0.33 points
  - Total: 78.33 points
