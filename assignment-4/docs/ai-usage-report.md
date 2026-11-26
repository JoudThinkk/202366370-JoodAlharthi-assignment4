# AI Usage Report - Assignment 4

## 1. Tools Used & Use Cases

- **Google Gemini:** Used in earlier portfolio iterations for brainstorming and initial implementation ideas for GitHub API integration, filtering, form validation, local storage, and documentation structure.
- **Copilot SDK in VS Code:** Used during Assignments 3 and 4 to review the repository against the assignment rubric, refine HTML/CSS/JavaScript, improve accessibility and safe API rendering, update technical documentation, and document AI use.

No AI-generated text or code was submitted without review and verification.

## 2. Usage Log

| ID | Tool (model) | Date | Purpose | Files affected | What you changed and how you verified it |
| :--- | :--- | :--- | :--- | :--- | :--- |
| A01 | Google Gemini (2.5 Pro) | 2026-11-08 | Designed GitHub API integration and project filtering concepts in the earlier portfolio iteration. | `assignment-4/js/script.js`, `assignment-4/index.html` | Reviewed and adapted the API request, loading/error states, and combined search/filter behavior; verified syntax and behavior during local testing. |
| A02 | Google Gemini (2.5 Pro) | 2026-11-08 | Assisted with form validation and notification ideas in the earlier portfolio iteration. | `assignment-4/js/script.js`, `assignment-4/css/styles.css`, `assignment-4/index.html` | Reviewed, adapted, and tested required-field, email-format, success, and error feedback behavior. |
| C01 | Copilot SDK in VS Code | 2026-11-26 | Reviewed Assignment 4 requirements and planned the final implementation. | `HW4Guides.md`, `assignment-4/index.html`, `assignment-4/css/styles.css`, `assignment-4/js/script.js` | Verified existing features against the rubric, then identified final polish, documentation, accessibility, and validation work. |
| C02 | Copilot SDK in VS Code | 2026-11-26 | Improved the portfolio page structure and navigation. | `assignment-4/index.html`, `assignment-4/css/styles.css` | Added a skip link, semantic main navigation, and a dark-mode state label. Checked matching section IDs and responsive navigation behavior. |
| C03 | Copilot SDK in VS Code | 2026-11-26 | Added polished responsive presentation behavior. | `assignment-4/css/styles.css`, `assignment-4/js/script.js` | Added a reduced-motion-safe reveal effect, mobile navigation, repository link styling, and dark-theme navigation colors. Reviewed CSS and JavaScript syntax. |
| C04 | Copilot SDK in VS Code | 2026-11-26 | Improved API rendering safety and theme accessibility. | `assignment-4/js/script.js` | Replaced dynamic repository `innerHTML` construction with DOM elements and text nodes, and synchronized the theme toggle's accessible pressed state. Verified JavaScript syntax and inspected API rendering code. |
| C05 | Copilot SDK in VS Code | 2026-11-26 | Updated Assignment 4 documentation and AI declaration. | `assignment-4/README.md`, `assignment-4/docs/technical-documentation.md`, `assignment-4/docs/ai-usage-report.md` | Updated Assignment 4 details and setup/testing information, and added this declaration and usage log. Reviewed all paths and Markdown sections. |

## 3. Benefits & Challenges

Using AI helped identify missing polish quickly, propose a safe implementation pattern for API output, and organize documentation consistently. The main challenge was ensuring that suggestions matched the actual files and did not contain assumptions about the workspace or deploy environment. I addressed this by reviewing every change, checking paths and syntax, and testing the application rather than submitting generated output unchanged.

## 4. Learning Outcomes

This process reinforced how to use AI for implementation review instead of blind code generation. I strengthened my understanding of semantic HTML, accessible controls, responsive CSS, DOM safety, local storage, asynchronous API behavior, and the importance of verifying code with observable tests.

## 5. Responsible Use & Modifications

I reviewed and modified all AI-assisted suggestions to fit this portfolio. Dynamic API text is rendered through DOM APIs rather than raw HTML, navigation and theme controls were checked for accessibility, and final documentation was updated to match the real repository structure. I understand the submitted code and take responsibility for all implementation and documentation decisions.

## 6. Evidence Packaging

Before Blackboard submission, save the complete unedited AI conversations used for this assignment in `conversations/` and save AI-produced intermediate text or files in `artifacts/`. Package both directories as `202366370-JoudAlharthi-assignment4-ai-evidence.zip`. Do not commit the evidence archive or source logs to the repository.

## 7. Declaration

I declare that this report and the attached evidence document all of my AI use in this assignment, with complete and unedited conversations, and that I understand and can explain all the code I submitted. I understand that undeclared AI use or a false declaration will be treated as plagiarism according to KFUPM regulations.

- **Name:** Joud Khalid Alharthi
- **Student ID:** 202366370
- **Date:** 2026-11-26
