# ClassVoteX – Digital School Election Platform

## Project Overview

**ClassVoteX** is a digital platform for organising and running school and class elections. It is designed to help students learn about candidates, participate in elections online and make the voting process easier to manage.

The project is being developed as part of **CM501 – Frontend Web Development** at **Munich University of Digital Technologies (MUDT)**.

## Problem Statement

School elections can involve paper ballots, manual coordination and manual vote counting. These processes can take time and create extra work for teachers and election organisers.

ClassVoteX aims to provide a clear, accessible digital experience for presenting candidates and supporting the election process.

## Project Objectives

- Present election information and candidate profiles clearly.
- Make the voting experience straightforward for eligible students.
- Provide a responsive and accessible interface.
- Organise election-related information in one place.
- Build a foundation that can be extended with secure authentication, election administration and results management.

## Planned / Core Features

- **Election homepage:** Introduces the election and explains how to participate.
- **Candidate profiles:** Shows candidates, their positions and campaign information.
- **Voting interface:** Provides an interface for eligible voters to make their selection.
- **Election information:** Displays election dates, rules and instructions.
- **Results presentation:** Provides a place to display results when they are published.

> Features are subject to the current development stage. Do not assume that a feature is implemented until it is present and tested in the project.

## HTML Baseline Checklist (M1–M10)

The following checklist adapts the CM501 HTML baseline requirements to ClassVoteX. Use it to review the actual HTML pages before submission. Mark a requirement complete only after checking the code or testing the page.

| ID | ClassVoteX requirement | ✓ / ✗ |
|---|---|---|
| **M1** | Every page declares the correct document language (for example, `lang="en"`), viewport, a page-specific title, meta description and favicon. | ☐ |
| **M2** | Pages use meaningful landmarks such as `header`, `nav`, `main` and `footer`, and provide a working “Skip to main content” link. | ☐ |
| **M3** | Main navigation is marked up as a list of links. The current page is identified with `aria-current="page"` where appropriate. | ☐ |
| **M4** | Each page has one clear `h1` (for example, “ClassVoteX – School Elections”) and a logical heading hierarchy without skipped levels. | ☐ |
| **M5** | Candidate photos, school/election images and other meaningful images have useful `alt` text. Images include appropriate dimensions and lazy loading where suitable. At least one relevant image is grouped in a `figure` with a caption where appropriate. | ☐ |
| **M6** | Candidate lists, election steps and voting instructions use appropriate HTML lists. Related content is grouped with meaningful `article` or `section` elements. | ☐ |
| **M7** | Links use descriptive text (not vague text such as “click here”). Contact information uses `address`, `mailto:` or `tel:` where relevant. | ☐ |
| **M8** | Election dates, deadlines and result publication dates use `time` with a machine-readable `datetime` value where appropriate. | ☐ |
| **M9** | Any form (such as a voter sign-in, candidate application or feedback form) has properly associated labels, clear instructions and accessible validation/error messages. | ☐ |
| **M10** | HTML validator reports 0 errors; axe reports 0 accessibility violations for the checks performed; and all interactive controls can be used with a keyboard. | ☐ |

### M10 testing tools

- [W3C HTML Validator](https://validator.w3.org/) – check each HTML page for markup errors.
- [axe DevTools](https://www.deque.com/axe/devtools/) – check pages for accessibility issues.
- **Keyboard check** – use Tab and Shift+Tab to move through links and controls, Enter/Space to activate controls, and confirm that focus is visible and the page can be used without a mouse.

## Optional HTML Enhancements (O1–O8)

Choose optional enhancements when they make sense for the ClassVoteX content. These are not mandatory baseline requirements.

| ID | Optional enhancement | Possible ClassVoteX use |
|---|---|---|
| **O1** | `srcset` / `<picture>` | Serve candidate or school images at suitable resolutions for different screen sizes. |
| **O2** | Table with `caption` and `th scope` | Present a results summary or election schedule in a data table when a table is the clearest format. |
| **O3** | `<details>` / `<summary>` | Create expandable election FAQs, voting instructions or candidate information. |
| **O4** | `<dl>` | Present election facts such as voting period, eligible year groups and election status as term-description pairs. |
| **O5** | `<blockquote>` / `<abbr>` | Display a candidate statement as a quotation or explain abbreviations used on the site. |
| **O6** | Icon link with `aria-label` | Give icon-only links, such as social/contact links, an accessible name. |
| **O7** | `<iframe>` with `title` | Embed relevant external content only when needed, with a descriptive title. |
| **O8** | `lang` on a foreign-language passage | Mark candidate statements or other passages written in a language different from the page language. |

## Accessibility and Voting Integrity

ClassVoteX should be designed so that students can understand and navigate the election information regardless of how they access the site. Use semantic HTML, visible keyboard focus, readable text, descriptive links and accessible form controls.

The frontend checklist does not by itself guarantee a secure or anonymous election. Any real voting deployment will also need carefully designed authentication, eligibility checks, vote-submission controls, privacy protections and reliable result handling.

## Planned Project Structure

```text
project/
├── README.md
├── frontend/
├── backend/
├── database/
└── documentation/
```

This is a suggested structure and can be adjusted to match the actual files in the repository.

## Technology Stack

Document the technologies actually used as development progresses.

- **Frontend:** To be documented
- **Backend:** To be documented, if implemented
- **Database:** To be documented, if implemented
- **Deployment:** To be documented

## Project Status

**Status:** In development

## Future Improvements

- Secure student authentication and voter eligibility checks.
- Administrator tools for creating and managing elections.
- Clear election scheduling and closing procedures.
- Accessible results dashboards.
- Responsive layouts for phones, tablets and desktops.
- Privacy, security and auditability improvements for real-world use.

## Vision

To make school elections easier to understand and participate in through an accessible, well-organised digital platform.

---

**Project:** ClassVoteX  
**Course:** CM501 – Frontend Web Development  
**Institution:** Munich University of Digital Technologies (MUDT)
