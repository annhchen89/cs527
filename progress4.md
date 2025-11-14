### Progress Report 4 - Fixing Test from Idoft
Team members: __Yong Han Lin (yonghan5)__, __Ann Chen (hueic2)__
___

**We submitted 18 pull requests (6 accepted, 1 rejected, 4 pending), in total fixed 29 tests.**

### Effort and Challenges
___
- Ran Nondex on ```apache/shenyu``` and discovered 10 tests
- Worked on fixing six of the test within ```apache/shenyu``` caused by Json and hashmap and create two PRs for the change. 
- Worked on ```primefaces/primefaces```, initally wasn't able to run nondex on the test, founded that it was cause by interfering with Mockito. The fix was to remove Mockito from plugin argLine to run nondex correctly. 
- For INRIA/spoon, I ran NonDex on all modules and discovered four additional failing tests. I found that two of them already had open PRs from a former student; however, they were not accepted and were left open. I saw in the contributing guidelines that “If there is no activity on an issue or on a pull request for 3 months, it’s closed,” so I assumed they were considered closed. I opened new PRs with my changes and referred to the old PRs in my PR descriptions. For the other two tests, I fixed them and opened two new PRs.

---
### Points
- Point we think we earned:
  - Opened 15: 45 points
  - Accepted 13: 65 points
  - Rejected 1: -2 points
  - DeveloperFixed 2: 4 points
  - DeveloperWontFix 1: 0.33 points
  - Total: 112.33 points
