### Progress Report 3 - Fixing Test from Idoft
Team members: __Yong Han Lin (yonghan5)__, __Ann Chen (hueic2)__
___

**We submitted 10 pull requests (4 accepted, 1 rejected, 5 pending), in total fixed 17 tests.**

### Effort and Challenges
___
- Ran NonDex across all modules in ```EsotericSoftware/kryo```, identified 2 additional failing tests, implemented fixes, and submitted a PR addressing these failures — both fixes have been accepted.
- Worked on ```Google/error-prone``` where the ```StreamResourceLeakTest.positive``` test passes in latest commit, so I found the commit it was first fixed with git bisect and ran the auto_check_fix_commit.sh and output the logs.
- Ran NonDex on all modules in ```Google/error-prone```; no additional nondeterministic tests were detected.  
- Ran NonDex on modules in ```apache/accumulo```, uncovering 3 additional failing tests.  
- Implemented fixes for 2 of the failing tests in ```apache/accumulo``` and submitted two corresponding PRs to the repository.



- Worked on ```INRIA/spoon``` and ```MyCATApache/Mycat-Server```, fixed two tests and open two PR in total.

---
### Points
- Point we think we earned:
  - Opened 5: 15 points
  - Accepted 11: 55 points
  - Rejected 1: -2 points
  - DeveloperFixed 2: 4 points
  - DeveloperWontFix 1: 0.33 points
  - Total: 72.33 points
