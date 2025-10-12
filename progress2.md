### Progress Report 2 - Fixing Test from Idoft
Team members: __Yong Han Lin (yonghan5)__, __Ann Chen (hueic2)__
___

We submitted X pull requests (X accepted, X rejected, X pending), in total fixed X tests.

### Effort and Challenges
___

- We created X pull requests toward ```repo```, ...
- Point we think we earned?:
  - opened X: x points
  - rejected X: x points
  - developerWontFix X: x points
  - Total: x.xx points


tobedeleted:
- fixed 2 more test(no extra PRs)
- the developer at ```apache/accumulo``` replied and also asked to also fix the testBulkFileCheck(), the fix was similar for testDataFileCheck(), also since testDataFileCheck() and testScanFileCheck() uses the same function, testScanFileCheck() is also fixed.
- worked on test that passes in the lastest commit, ```google/error-prone``` but after some more testing with higher iteration with nondex(100), it passes on the commit that was reported on, so this test
  
- Resolved 2 more failing tests (no new PRs were created).

- Received a response from the developer on the apache/accumulo repository. They requested a fix for testBulkFileCheck(). The issue and fix were similar to testDataFileCheck(). Since both testDataFileCheck() and testScanFileCheck() use the same underlying function, the fix also resolved testScanFileCheck().

- Worked on a test that was reported as passing in the latest commit of google/error-prone. After running additional nondex tests (100 iterations), the test consistently passed even on the previously reported commit, indicating that the issue might have been nondeterministic or already resolved upstream before the reported 
