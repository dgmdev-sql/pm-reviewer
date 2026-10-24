# CTPRJMGT Project Management Reviewer

An interactive, web-based study application designed for the CTPRJMGT Project Management midterm examination. This application provides a structured review of core curriculum materials, visual diagrams for complex concepts, and a comprehensive assessment module.

## Deployment

**Live Application:** [pm-reviewer.vercel.app](https://pm-reviewer-two.vercel.app/)

## Core Features

- **Comprehensive Curriculum Coverage:** Detailed study modules spanning five foundational lessons.
- **Interactive Assessment:** A 35-item multiple-choice quiz engine with immediate feedback and detailed rationale.
- **Systematic Content Highlighting:** A structured study system prioritizing definitions, mandatory terminology, and conceptual relationships.
- **Adaptive Interface:** Responsive design supporting desktop, tablet, and mobile viewing environments.
- **Theme Support:** User-selectable light and dark modes with persistent local storage.
- **Zero-Dependency Architecture:** Built entirely with semantic HTML5, CSS3 Custom Properties, and Vanilla JavaScript for maximum performance and portability.

## Curriculum Structure

| Lesson | Focus Area | Key Concepts |
|:---:|---|---|
| 1 | Introduction to Project Management | Project attributes, Triple/Quadruple Constraints, 10 Knowledge Areas, PMI standards. |
| 2 | The PM and IT Context | Systems approach, organizational structures, cultural frames, Agile/Scrum frameworks. |
| 3 | Process Groups | The I-P-E-M-C lifecycle, integration mapping, formal methodologies (PRINCE2, RUP). |
| 4 | Integration Management | Strategic selection methods (NPV, ROI), project charter development, integrated change control. |
| 5 | SDLC Methodologies | Software Development Life Cycle models (Waterfall, Agile, Spiral, DevOps) and selection criteria. |

## Local Development

To run this application locally, no build steps or package managers are required.

1. Clone the repository:
   ```bash
   git clone https://github.com/dgmdev-sql/pm-reviewer.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pm-reviewer
   ```
3. Open `index.html` in any modern web browser.

## Technical Specifications

- **Typography:** Inter (Google Fonts)
- **Styling:** CSS Variables (Design Tokens), Flexbox/Grid Layouts, Media Queries
- **Logic:** Vanilla JavaScript (DOM manipulation, state management, event handling)
- **Assets:** Inline SVG diagrams
