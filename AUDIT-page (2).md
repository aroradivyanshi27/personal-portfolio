# AUDIT-page.md: Session 9 Portfolio

Audit of `index.html` and `style.css` (personal portfolio webpage, Data & AI Practitioner).

## Content audit

| Content | True? | Evidence / What was removed |
|---|---|---|
| Name: Divyanshi Arora | Yes | Confirmed by you as your real name. Used in the `<h1>`, `<title>` and footer. |
| About section | Partly | Text is general and built only from the skills and project names. It contains no invented personal facts (no employer, location, education or years of experience). Edit it so it reflects your own background. |
| Prompt Engineering | Yes | Skill I have learned/practiced |
| Artificial Intelligence & Machine Learning | Yes | Skill I have learned/practiced |
| Exploratory Data Analysis (EDA) | Yes | Skill I have learned/practiced |
| Machine Learning Model Development | Yes | Skill I have learned/practiced |
| Data Visualization | Yes | Skill I have learned/practiced |
| Student Attrition Prediction | Yes (title) | My actual project. The one-line description on the page was written from the project title only, so check it matches what you built. |
| NoBrokerage.com Chatbot | Yes (title) | My actual project. The one-line description on the page was written from the project title only, so check it matches what you built. |
| Email / Phone | Yes | Provided by you: arora.divyanshi27@gmail.com and 8005955443. Shown in the Contact section as `mailto:` and `tel:` links. |
| Social links | N/A | None included. Nothing was added that is not real. |
| GitHub project links | N/A (verify) | None included. Add a link only if it points to an actual working repository. |

## Validation

| Check | Result |
|---|---|
| Nu HTML Checker | 0 errors, 0 warnings (`vnu.jar --also-check-css index.html style.css`), re-run after adding the Contact section |
| Narrow-width check (~375px) | **Not yet tested in a browser.** `style.css` has a `max-width: 600px` breakpoint that stacks skills and projects into one column. Please confirm at 375px in browser dev tools. |
| HTML and CSS are separate | Yes: `index.html` and `style.css`, linked with `<link rel="stylesheet" href="style.css">` |
| No inline CSS | Yes: 0 `style=` attributes and 0 `<style>` tags in `index.html` |
| One `<h1>` | Yes |
| No JavaScript, React or Tailwind | Yes: 0 `<script>` tags |

## Notes

- The published copy (`portfolio-published.html`) has the CSS pasted into a `<style>` block because the hosting accepts only a single file. The source files `index.html` and `style.css` are unchanged.
