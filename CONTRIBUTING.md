# Contributing to Impossible Object

Thank you for your interest in this project. This document explains how to contribute.

---

## Philosophy of Contribution

This is not a standard open-source software project. It is a **theoretical framework** that welcomes:

- **Critique** — point out logical flaws, inconsistencies, or unstated assumptions
- **Extension** — develop the formalization, add connections to other fields
- **Translation** — make the theory accessible in other languages
- **Refutation** — if you can show the axioms lead to contradiction, that is valuable
- **Examples** — find concrete instances where the theory seems to apply or fail

---

## Branch Structure
main     ← stable, reviewed content (maintained by @Khamit)
edit     ← all contributions, proposals, drafts
plain

**All pull requests must target the `edit` branch.**

---

## How to Contribute

### 1. Fork the repository

```bash
git clone https://github.com/Khamit/impossible-object.git
cd impossible-object
git checkout -b your-feature-name edit
```
### 2. Make your changes
Follow the existing Markdown style
Use clear, accessible language
Cite sources where possible
If adding mathematical content, use LaTeX-style notation (will be rendered)
### 3. Commit with clear messages
```bash
git add .
git commit -m "Add: connection to category theory in CONNECTIONS/"
git push origin your-feature-name
```
### 4. Open a Pull Request to edit
Describe:
What you changed and why
Any open questions or uncertainties
Whether you consider it a draft or ready for review
Content Guidelines
## THEORY/ files
These represent the core axioms. Changes here should preserve the original intent while improving clarity. Major revisions should be proposed as new files (e.g., 01-information-horizon-v2.md) rather than overwriting originals.
## FORMALIZATION/ files
This is where mathematical and logical development happens. All levels of formality welcome — from sketches to full proofs. Mark tentative claims clearly.
## CONNECTIONS/ files
Links to existing theories, philosophies, scientific results. Each file should explain:
What the external theory says
How it relates to the Impossible Object framework
Where they diverge
## META/ files
Personal reflections, changelog, meta-discussion. The authors-notes.md is maintained by @Khamit; other files in META/ are open for community additions.
Code of Conduct
Be intellectually honest
Distinguish between "I don't understand this" and "this is wrong"
Respect that the author is not an academic — but hold the ideas to rigorous standards
No ad hominem attacks
Mysticism and religious claims are not rejected a priori, but must be translated into structural language to be relevant
Questions?
Open an issue with the label question or reach out to @Khamit directly.
"The best contribution is one that makes the theory either stronger or shows precisely where it breaks."

---