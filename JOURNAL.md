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

**Reproduction commit link:** [https://github.com/RaphaelDMCode/pathreview/commit/3ecb95c8ae4565ece97e88db49f10177ec107c39]

**Reproduction summary:** [1–2 sentences: How did you reproduce the issue? What did you observe?]

To Reproduce the Issue, I first use the Command [pytest tests/unit/test_readme_scorer.py -q] given in the GitHub Issue Comment, which will then show a Unit Test Fail with 22 Passed, and 1 Failed, with the [assert 51 > 100] Assertion Error. This type of Issue would be labeled as a Documentation Type of Issue, more specifically a Test Issue. The Issue is that the [ReadmeScorer] had correctly counted the [README] Text Fixture that contains only about ~51 Words. This shows that the Scoring Function/Logic itself is not the Problem, but the Unit Test’s Fixture where it fell short to Satisfy the Assertion being made.

**PLAN.md link:** [https://github.com/RaphaelDMCode/pathreview/blob/fix/156-readme-scorer-fixture/PLAN.md]

**Walkthrough video (recommended):** [<img src='Issue-Reproduce-Walkthrough.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />]

**Blockers or open questions:**
[Anything you're still uncertain about going into Week 9, or leave blank]
Currently None

---

## Week 9 — Solution building & PR submission

### Check-in 1 (mid-week)

**Current progress:**
[What have you implemented so far? Which sub-tasks from PLAN.md are done?]

**Next steps:**
[What are you working on for the rest of the week?]

**Blockers:**
[Anything slowing you down? Or leave blank.]

---

### Check-in 2 (end of week)

**PR link:** [link to your submitted pull request]

**Branch:** [the branch name you worked on, e.g. `fix/123-short-description`]

**What you built:**
[1–3 sentences summarizing what your fix does and how it works]

**Tests added or updated:**
[Which test files did you touch? What do they cover?]

**Self-review confirmation:** [ ] make check passes  [ ] make test-unit passes

**Draft PR feedback received from:** [name or Slack handle, or "none"]

---