### Final Project Report - Fixing Test from Idoft
Team members: __Yong Han Lin (yonghan5)__, __Ann Chen (hueic2)__
___
### Effort and Challenges
During the semester, we worked on 15 repositories. In total, we fixed 63 tests (40 accepted, 3 rejected, 17 pending, 1 inspired a fix, and 2 were fixed by developers), and we ran NonDex on all modules across all repositories to find ID tests that were not already listed in pr-data.csv:
- apache/shenyu: In this repo, we fixed ten ID tests and three OD tests.
- apache/streampipes: We fixed nine ID tests in this repo. Five were accepted, but the remaining four are still open PRs.
- EsotericSoftware/kryo: We fixed seven ID tests, and all were accepted.
- OpenAPITools/openapi-generator: We fixed five ID tests in this repo, and all PRs were accepted. 
- immutables/immutables: We fixed four ID tests in this repo caused by JSON and HashSet ordering, and all PRs were accepted.
- awspring/spring-cloud-aws: We fixed five ID tests in this repo and opened PRs, but the maintainers have not reviewed them yet.
- google/error-prone:
- apache/accumulo: 
- INRIA/spoon: We fixed seven tests in this repo: two were accepted, and five are still open. For the open PRs, the maintainers discussed the issue in one case but did not reach a conclusion. In another PR, a maintainer asked questions about my changes but did not follow up. Since they suggested opening one PR at a time, I added “review” to the titles of two PRs and waited for their response, but the comments in both PRs remain unresolved, which has left the remaining PRs open.
- primefaces/primefaces: This repo had two ID tests when we first worked on it. We fixed them and opened a PR for one of the tests. However, the maintainer did not believe the failure was flaky, so we did not open a second PR.
- quarkusio/quarkus:
- google/guava: 
- MyCATApache/Mycat-Server: This repo is unmaintained (the last commit was two years ago), although we did open a PR.
- google/gson: Although this repo was assigned to us, we did not work on it because the previously identified ID tests in pr-data.csv were all labeled as “DeveloperWontFix”.
---
### Points
- Point we think we earned:
  - Opened 17: 51 points
  - Accepted 40: 200 points
  - InspiredAFix 1: 4 points
  - Rejected 3: -6 points
  - DeveloperFixed 2: 4 points
  - Unmaintained 1: 0.25 points
  - Total: 253.25 points
