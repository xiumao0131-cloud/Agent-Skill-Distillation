# Academic Revision Evaluator

Version: v0.1


## Purpose

This evaluator is used to assess whether an agent has correctly completed academic document formatting and citation revision tasks.

The evaluation focuses on:

- requirement compliance
- formatting accuracy
- citation correctness
- document integrity
- modification discipline


---

# Evaluation Framework


## 1. Requirement Compliance (20 points)

Check whether the agent correctly understood external requirements.


Criteria:

- [ ] Identified all available standards

- [ ] Built a requirement checklist

- [ ] Did not ignore teacher feedback or reference examples

- [ ] Correctly handled conflicting requirements


Failure examples:

- Following general formatting rules while ignoring provided teacher requirements

- Applying one standard without checking conflicting evidence



---

## 2. Formatting Accuracy (20 points)

Check whether document formatting matches requirements.


Criteria:

- [ ] Font is correct

- [ ] Font size is correct

- [ ] Paragraph formatting is correct

- [ ] Indentation and spacing are correct

- [ ] Layout changes do not introduce new problems



---

## 3. Citation and Footnote Accuracy (20 points)

Check whether citations are correctly handled.


Criteria:

- [ ] Footnotes exist in correct positions

- [ ] Footnote format matches requirements

- [ ] References are not fabricated

- [ ] Footnotes are real document objects when required


Failure examples:

- Manually typing fake footnotes

- Creating unsupported citations



---

## 4. Document Integrity (20 points)

Check whether the document structure remains valid.


Criteria:

- [ ] Original content is preserved

- [ ] Document structure is not damaged

- [ ] Hidden formatting issues are checked

- [ ] Metadata is not fabricated



---

## 5. Modification Discipline (20 points)

Check whether the agent follows minimal modification principles.


Criteria:

- [ ] Only required changes are made

- [ ] No unnecessary rewriting

- [ ] No unauthorized style improvement

- [ ] Important changes are explained



---

# Automatic Failure Conditions


The task fails if the agent:


- Changes author's academic arguments without permission

- Invents citations or sources

- Fabricates document information

- Deletes important original content

- Claims completion without verification



---

# Output Evaluation Report


The evaluator should produce:


## Summary

Task result:

- Passed
- Needs revision
- Failed


## Score

Total score:

__/100


## Issues Found


For each issue:


Location:

Problem:

Expected:

Actual:

Suggested rule improvement:



---

# Skill Improvement Loop


When evaluation fails:


1. Record failure case

2. Identify missing rule

3. Update rules.yaml

4. Add example to case library

5. Increase Skill version


Example:


v0.1:

Failed to detect fake footnote


↓

Add rule:

real_word_footnote_required


↓

v0.2
