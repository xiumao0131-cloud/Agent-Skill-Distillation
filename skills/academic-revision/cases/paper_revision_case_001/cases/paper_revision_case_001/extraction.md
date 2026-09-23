# Skill Extraction: Case 001


## Case Goal

Extract reusable capabilities from an academic document revision workflow.


---

# Extracted Capabilities


## 1. Requirement Resolution


Observation:

The agent needed to compare multiple standards:

- teacher feedback
- guidelines
- reference examples


Extracted Rule:

When standards conflict, compare sources before making changes.



---


## 2. Document Structure Awareness


Observation:

Visible text formatting is not enough.

Word document objects matter.


Extracted Rule:

Check document structure, not only rendered text.



---


## 3. Minimal Modification


Observation:

The task required formatting correction rather than rewriting.


Extracted Rule:

Only modify necessary parts.



---


## 4. Verification


Observation:

A successful modification requires checking the final document.


Extracted Rule:

Always verify after modification.



---

# Failure Risks


Potential agent failures:


1. Following only general formatting knowledge

2. Editing visible text without checking document objects

3. Over-polishing academic content

4. Claiming completion without verification



---

# Contribution to Skill


This case contributed to:

Academic Revision Skill v0.1


Main rules extracted:

- requirement resolution
- document integrity
- minimal editing
- verification workflow
