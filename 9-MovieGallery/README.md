# Movie Gallery Project - Advanced HTML Fundamentals

## 1. Problem Statement

Develop a movie gallery application displaying film posters, genres, and ratings using **only HTML** (no CSS or JavaScript). The application showcases advanced and lesser-known HTML features including microdata for <abbr title="Search Engine Optimization">SEO</abbr>, responsive images with `<picture>`, rating visualization with `<meter>`, Ruby annotations for international titles, and bidirectional text handling. The focus is on semantic markup, accessibility standards, and structured data implementation for enhanced search engine discoverability.

---

## 2. Tech Stack

| Category | HTML Concepts |
|----------|---------------|
| **Document Structure** | `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, `<meta>` tags (description, keywords, viewport), `<title>` |
| **Semantic Elements** | `<header>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<nav>`, `<footer>`, `<address>` |
| **Text Formatting** | `<h1>`-`<h3>`, `<p>`, `<strong>`, `<em>`, `<small>`, `<cite>`, `<mark>`, `<ins>`, `<dfn>` |
| **🆕 Ruby Annotations** | `<ruby>`, `<rt>`, `<rp>` for pronunciation guides and international text annotations |
| **🆕 Bidirectional Text** | `<bdi>` (bidirectional isolation), `<bdo>` (bidirectional override) for multilingual content |
| **🆕 Responsive Images** | `<picture>`, `<source>` with `media` and `srcset` attributes for adaptive images |
| **🆕 Meter Element** | `<meter>` with `min`, `max`, `value`, `optimum`, `high` for visual rating representation |
| **🆕 Data Semantics** | `<data>` with `value` for machine-readable numerical data, `<time>` with `datetime` for dates |
| **🆕 Microdata/Schema.org** | `itemscope`, `itemtype`, `itemprop` attributes for structured data markup |
| **🆕 Word Break** | `<wbr>` for optional line break opportunities in long URLs and emails |
| **🆕 Abbreviations** | `<abbr>` with `title` attribute for expanded acronym meanings |
| **Images** | `<img>` with `src`, `alt`, `width`, `height`, `loading="lazy"` for performance |
| **Figure & Caption** | `<figure>`, `<figcaption>` for semantic media grouping |
| **Lists** | `<ul>`, `<li>` for genre navigation, `<dl>`, `<dt>`, `<dd>` for definition lists |
| **Interactive Elements** | `<details>`, `<summary>` for collapsible movie synopsis sections |
| **Links** | `<a>` with `href`, `tel:`, `mailto:`, `rel="tag"` for genre taxonomy |
| **Quotes** | `<blockquote>` with `cite` attribute, `<footer>` in blockquote |
| **Separators** | `<hr>` for visual content separation |
| **Accessibility** | `aria-label` for navigation landmarks, semantic HTML5 for screen readers |

**Total Concepts:** 35+ HTML elements including 12 advanced/lesser-known features

---

## 3. Expected Outcomes

1. **Microdata Integration:** Implement Schema.org Movie markup with `itemscope`, `itemtype`, and `itemprop` for enhanced SEO
2. **Responsive Images:** Use `<picture>` and `<source>` elements to serve different image sizes based on viewport width
3. **Visual Ratings:** Display movie ratings using `<meter>` element with appropriate `min`, `max`, `value`, and `optimum` attributes
4. **Ruby Annotations:** Demonstrate `<ruby>`, `<rt>`, and `<rp>` elements for pronunciation guides on international film titles
5. **Bidirectional Text:** Apply `<bdi>` for genre separators and `<bdo>` for directional text override examples
6. **Definition Lists:** Structure movie metadata using `<dl>`, `<dt>`, and `<dd>` for semantic key-value pairs
7. **Data Elements:** Use `<data>` with `value` attribute for machine-readable duration and award counts
8. **Time Elements:** Implement `<time>` with `datetime` attribute for proper date-time markup
9. **Word Break Opportunities:** Apply `<wbr>` for long email addresses to enable graceful text wrapping
10. **Abbreviations:** Use `<abbr>` with `title` attribute to provide full meaning for acronyms like "Oscars"
11. **Text Annotations:** Utilize `<mark>` for highlighting, `<ins>` for content additions, `<dfn>` for term definitions
12. **Lazy Loading:** Implement `loading="lazy"` attribute on images for improved page performance
13. **Interactive Synopsis:** Create collapsible movie descriptions using `<details>` and `<summary>` elements
14. **Semantic Navigation:** Structure genre browsing with `<nav>` element and `aria-label` for accessibility
15. **Accessibility First:** Build with screen reader compatibility using semantic HTML5 elements and proper ARIA attributes

---

## 4. Additional Notes

- **Advanced HTML Focus:** Demonstrates lesser-known but production-ready HTML features often overlooked in basic tutorials
- **SEO Optimization:** Structured data markup enables rich snippets in search engine results for improved visibility
- **Performance Features:** Implements native lazy loading and responsive images without external dependencies
- **Internationalization:** Ruby annotations and bidirectional text support showcase HTML's multilingual capabilities
- **Pure Semantic HTML:** Zero CSS or JavaScript dependencies - leverages native HTML features exclusively
- **Accessibility Compliant:** Follows <abbr title="Web Content Accessibility Guidelines">WCAG</abbr> standards with proper semantic markup and ARIA attributes
- **Browser Compatibility:** All features supported in modern browsers (Chrome 88+, Firefox 85+, Safari 14+, Edge 88+)
- **Real-world Application:** Production-ready patterns suitable for content management systems and static site generators
