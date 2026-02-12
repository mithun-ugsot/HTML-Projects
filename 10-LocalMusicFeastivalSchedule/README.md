# Local Music Festival Schedule - Advanced HTML Fundamentals

## 1. Problem Statement

Develop a local music festival schedule page displaying performers, timings, stages, and festival information using **only HTML** (no CSS or JavaScript). The application showcases practical HTML features including accessible tables with `<caption>` and `scope`, collapsible sections with `<details>`, machine-readable time and data elements, definition lists for structured metadata, and semantic navigation. The focus is on clean tabular data presentation, semantic markup, and accessibility for event scheduling content.

---

## 2. Tech Stack

| Category | HTML Concepts |
|----------|---------------|
| **Document Structure** | `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, `<meta>` tags (description, keywords, viewport), `<title>` |
| **Semantic Elements** | `<header>`, `<main>`, `<section>`, `<article>`, `<nav>`, `<footer>`, `<address>` |
| **Text Formatting** | `<h1>`-`<h3>`, `<p>`, `<strong>`, `<em>`, `<small>` |
| **Tables** | `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tr>`, `<th>` with `scope`, `<td>`, `summary` attribute |
| **Time Element** | `<time>` with `datetime` attribute for machine-readable dates and times |
| **Data Element** | `<data>` with `value` attribute for machine-readable durations and capacities |
| **Definition Lists** | `<dl>`, `<dt>`, `<dd>` for stage information key-value pairs |
| **Interactive Elements** | `<details>`, `<summary>` for collapsible festival information sections |
| **Abbreviations** | `<abbr>` with `title` attribute for expanded acronym meanings |
| **Word Break** | `<wbr>` for optional line break opportunities in long email addresses |
| **Lists** | `<ul>`, `<li>` for navigation links and information lists |
| **Links** | `<a>` with `href`, `mailto:`, `tel:` for contact information |
| **Separators** | `<hr>` for visual content separation between schedule days |
| **Accessibility** | `aria-label` for navigation landmarks, `scope` on table headers, semantic HTML5 |

**Total Concepts:** 30+ HTML elements and attributes focused on tabular data and event scheduling

---

## 3. Expected Outcomes

1. **Accessible Tables:** Implement schedule tables with `<caption>`, `<thead>`, `<tbody>`, `<th scope="col">`, and `summary` attributes for full screen reader compatibility
2. **Time Elements:** Use `<time>` with `datetime` attribute throughout for machine-readable performance times and festival dates
3. **Data Elements:** Apply `<data>` with `value` attribute for performance durations and venue capacities in machine-readable format
4. **Multi-Day Schedule:** Organize the festival across two days with clear section separation using `<section>` and `<hr>` elements
5. **Multi-Stage Layout:** Present parallel schedules for Main Stage and Acoustic Tent using separate `<article>` elements
6. **Definition Lists:** Structure stage information using `<dl>`, `<dt>`, and `<dd>` for semantic key-value pairs
7. **Collapsible Sections:** Create expandable festival info panels (tickets, rules, food) using `<details>` and `<summary>` elements
8. **Semantic Navigation:** Build quick-link navigation with `<nav>` element and `aria-label` for accessibility
9. **Contact Information:** Use `<address>` element with `mailto:` and `tel:` links for proper contact semantics
10. **Word Break Opportunities:** Apply `<wbr>` in long email addresses to enable graceful text wrapping
11. **Abbreviations:** Use `<abbr>` with `title` attribute to provide full meaning for acronyms
12. **Semantic Article Structure:** Wrap each stage's schedule in `<article>` elements for content independence

---

## 4. Additional Notes

- **Pure Semantic HTML:** Zero CSS or JavaScript dependencies - leverages native HTML features exclusively
- **Tabular Data Focus:** Demonstrates proper use of HTML tables for their intended purpose - displaying structured, tabular schedule data
- **Accessibility Compliant:** Follows <abbr title="Web Content Accessibility Guidelines">WCAG</abbr> standards with proper table headers, scope attributes, and ARIA labels
- **Machine-Readable Dates:** All times and dates use `<time datetime>` for calendar integration and search engine understanding
- **Progressive Disclosure:** Festival details use native `<details>`/`<summary>` to reduce information overload
- **Contact Semantics:** Proper use of `<address>`, `mailto:`, and `tel:` links for festival contact information
- **Browser Compatibility:** All features supported in modern browsers (Chrome 88+, Firefox 85+, Safari 14+, Edge 88+)
- **Real-world Application:** Production-ready patterns suitable for event websites, community bulletin boards, and venue schedules
