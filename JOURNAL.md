## Week 7 — Issue selection

**Issue link:** [https://github.com/ascherj/pathreview/issues/156]

**Issue title:** [README scorer test fixture is too short for its own word-count assertion #156]

**Tier:** [x] Tier 1  [ ] Tier 2  [ ] Tier 3

**Problem summary:**
The Issue basically is that the README Scorer Test Scorer Test is Failing due to the Fact that the Text Fixture only contained about ~51 Words, and that the Test expected it to have more than 100 Words to be counted as "comprehensive". The Scorer itself is not the Broken, it is just that the Test Data simply does not Matches the Test and such. A Successful Fix that would Accomplish would be to Extend the Fixture so that the Test can accurately Validates what it intended behavior of the README Scorer do and such.

**Branch name:** [fix/156-readme-scorer-fixture]

**Setup confirmation:** [x] App runs locally at localhost:5173

**Cohort ledger:** [x] Issue added to cohort ledger

---

## Week 8 — Reproduction & solution planning

**Issue Reproduction Documentation:**
After inputting [pytest tests/unit/test_readme_scorer.py -q] in the GitBash Terminal, it returns a Test Result that shows 22 Tests Passed and 1 Test Failed. The Failing Test, [test_readme_with_all_quality_signals], produced the Assertion Error: [assert 51 > 100], which shows the Issue is Reproducible by Confirming the Issue Described in GitHub Issue #156.

**Reproduction commit link:** [link to commit documenting the reproduced issue]

**Reproduction summary:**
[1–2 sentences: How did you reproduce the issue? What did you observe?]

**PLAN.md link:** [link to PLAN.md in your fork]

**Walkthrough video (recommended):** [link to your Loom video, ≤2 min — recommended, not graded]

**Blockers or open questions:**
[Anything you're still uncertain about going into Week 9, or leave blank]

---