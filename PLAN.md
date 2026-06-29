---
name: Academy Static Website
overview: Build a single-page static site under website/ with all five SKILLNEST Academy courses showing full 12-week syllabus content, plus mandatory fields (name, duration, placeholder price), collapsible sections for readability, and contact/enroll CTA.
isProject: false
---

# Static Academy Course Page

## Goal

Create one marketing page at website/index.html that displays all 5 courses from academy/README.md with mandatory fields:

- Course name
- Full content (complete 12-week syllabus per course)
- Duration: 12 weeks, default 2.5 h/week (~30 contact hours)
- Price: placeholder text Contact for pricing

## Site structure

skillnest/
- academy/ (existing)
- website/
  - PLAN.md
  - README.md
  - index.html
  - css/styles.css
  - assets/

## UX and content rules

- Single-page layout with all five courses stacked vertically.
- Each course has summary details always visible.
- Full syllabus is inside a collapsible details section.
- First course is open by default, others are collapsed.
- Sticky jump navigation links to all five course IDs.
- Contact/enroll CTA is included in each course and in footer.

## Full course content source

Source content is based on academy course guides and included in index.html.

### 1. Basic Computer Knowledge

- ID: #course-basic-computer
- For: Adults 18+ and teens 15+ (teen 13-14 variant available)
- Description: Everyday computer skills from Windows basics to email, cloud, docs, and spreadsheets.
- Prerequisites: None
- Capstone: Organized folder tree, professional email with attachment, one-page CV/About Me, monthly budget spreadsheet, 3-minute presentation.

12-week syllabus included in index.html table.

### 2. Microsoft Office Package

- ID: #course-office
- For: Teens 13-17 and adults 18+
- Description: Word, Excel, and PowerPoint from beginner to business use.
- Prerequisites: Basic Computer Knowledge or equivalent
- Capstone: Word proposal (3+ pages), Excel dashboard with charts, PowerPoint pitch (10-12 slides).

12-week syllabus included in index.html table.

### 3. Basic Web Development

- ID: #course-web
- For: Teens 13-17 and adults 18+
- Description: HTML, CSS, JavaScript, Bootstrap, GitHub, and deployment.
- Prerequisites: Comfortable with files, browser, and keyboard
- Capstone: Responsive portfolio or landing page, deployed online.

12-week syllabus included in index.html table.

### 4. Basic Java Programming

- ID: #course-java
- For: Teens 14-17 and adults 18+
- Description: Java fundamentals through OOP and file handling.
- Prerequisites: Basic Computer Knowledge and comfort with logic/math
- Capstone: Multi-class console app with menu and file save/load.

12-week syllabus included in index.html table.

### 5. Computer for Kids

- ID: #course-kids
- For: Ages 8-12
- Description: Safe intro to computers, internet, creativity, and Scratch coding.
- Prerequisites: None (parent/guardian consent required)
- Capstone: My Digital Project presented to class and parents.

12-week syllabus included in index.html table.

## Styling approach

- Semantic HTML5 layout.
- CSS-only implementation (no JS required).
- Responsive, single-column course blocks with collapsible syllabus sections.
- Sticky jump navigation.
- Table wrappers with horizontal scroll on small screens.
- Accessible color contrast and visible focus states.

## Delivery checklist

- [x] website/PLAN.md
- [x] website/index.html
- [x] website/css/styles.css
- [x] website/README.md
- [x] Mandatory fields per course: name, full 12-week content, duration, price
- [x] 60 syllabus rows total (12 weeks x 5 courses)
