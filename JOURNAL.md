## Week 7 — Issue selection

**Issue link:** [https://github.com/ascherj/pathreview/issues/156]

**Issue title:** [README scorer test fixture is too short for its own word-count assertion #156]

**Tier:** [x] Tier 1  [ ] Tier 2  [ ] Tier 3

**Problem summary:**
[In 3–5 sentences, in your own words: what the issue is (not a copy-paste of
the title), what is currently broken or missing, and what a successful fix
would accomplish. Naming the part of the codebase it affects is helpful context.]
The Issue basically is that the README Scorer Test Scorer Test is Failing due to the Fact that the Text Fixture only contained about ~51 Words, and that the Test expected it to have more than 100 Words to be counted as "comprehensive". The Scorer itself is not the Broken, it is just that the Test Data simply does not Matches the Test and such. A Successful Fix that would Accomplish would be to Extend the Fixture so that the Test can accurately Validates what it intended behavior of the README Scorer do and such.

**Branch name:** [fix/156-readme-scorer-fixture]

**Setup confirmation:** [x] App runs locally at localhost:5173

**Cohort ledger:** [x] Issue added to cohort ledger