# Personal Habit Tracker Dashboard - Advanced HTML Fundamentals

## 1. Problem Statement

Develop a personal habit tracker dashboard displaying weekly progress, a daily log, monthly goals, and motivational tips using **only HTML** (no CSS or JavaScript). The application showcases practical HTML features including accessible tables with `<caption>` and `scope`, progress indicators with `<meter>` and `<progress>`, collapsible sections with `<details>`, machine-readable time and data elements, and semantic navigation. The focus is on clean progress tracking layout, semantic markup, and accessibility.

---

## 2. Tech Stack

| Category | HTML Concepts |
|----------|---------------|
| **Document Structure** | `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, `<meta>` tags (description, keywords, viewport), `<title>` |
| **Semantic Elements** | `<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>` |
| **Text Formatting** | `<h1>`-`<h3>`, `<p>`, `<strong>`, `<em>`, `<small>`, `<q>` |
| **Tables** | `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tr>`, `<th>` with `scope`, `<td>`, `summary` attribute |
| **Time Element** | `<time>` with `datetime` attribute for machine-readable dates and times |
| **Data Element** | `<data>` with `value` attribute for machine-readable habit counts and streak values |
| **Progress Indicators** | `<progress>` for monthly goal tracking bars, `<meter>` for weekly habit completion gauges |
| **Interactive Elements** | `<details>`, `<summary>` for collapsible tips and motivation sections |
| **Abbreviations** | `<abbr>` with `title` attribute for expanded acronym meanings |
| **Inline Quotations** | `<q>` for quoting habit-building strategy examples |
| **HTML Entities** | `&#10003;` (checkmark), `&#10007;` (cross), emoji entities for streak status |
| **Lists** | `<ul>`, `<li>` for navigation links and tracking tips |
| **Links** | `<a>` with `href` for internal navigation anchors |
| **Separators** | `<hr>` for visual content separation between dashboard sections |
| **Accessibility** | `aria-label` for navigation landmarks, `scope` on table headers, semantic HTML5 |

**Total Concepts:** 30+ HTML elements and attributes focused on progress tracking and habit data presentation

---

## 3. Expected Outcomes

1. **Accessible Tables:** Implement habit tracking tables with `<caption>`, `<thead>`, `<tbody>`, `<th scope="col">`, and `summary` attributes for screen reader compatibility
2. **Progress Indicators:** Use `<meter>` for weekly completion gauges and `<progress>` for monthly goal bars to visually represent progress
3. **Time Elements:** Use `<time>` with `datetime` attribute for machine-readable habit completion times and dates
4. **Data Elements:** Apply `<data>` with `value` attribute for habit counts, streaks, and targets in machine-readable format
5. **Consolidated Weekly View:** Present a single table combining weekly completion, categories, and streak data
6. **Daily Habit Log:** Show a single-day log with checkmark/cross status indicators using HTML entities
7. **Monthly Goals Table:** Display goal progress with `<progress>` bars in a compact table format
8. **Collapsible Sections:** Create expandable tips panels using `<details>` and `<summary>` elements
9. **Semantic Navigation:** Build quick-link navigation with `<nav>` element and `aria-label` for accessibility
10. **Inline Quotations:** Use `<q>` elements for quoting habit-building strategies

---

## 4. Additional Notes

- **Pure Semantic HTML:** Zero CSS or JavaScript dependencies - leverages native HTML features exclusively
- **Progress Tracking Focus:** Demonstrates proper use of `<meter>` and `<progress>` elements for displaying measured values and task completion
- **Compact Design:** Avoids repetition by consolidating streaks into the weekly table and showing a single daily log sample
- **Accessibility Compliant:** Follows <abbr title="Web Content Accessibility Guidelines">WCAG</abbr> standards with proper table headers, scope attributes, and ARIA labels
- **Machine-Readable Dates:** All times and dates use `<time datetime>` for calendar integration and search engine understanding
- **Progressive Disclosure:** Tips use native `<details>`/`<summary>` to reduce information overload
- **Browser Compatibility:** All features supported in modern browsers (Chrome 88+, Firefox 85+, Safari 14+, Edge 88+)
