# Basic HTML Guide

Overview

This project is a submission for a DIO (Digital Innovation One) project challenge focused on fundamental HTML markup. The objective was to build a single web page that demonstrates a defined set of HTML tags covered during the course, along with a small number of additional tags researched independently.

The page includes a clickable table of contents that links to each section, and a "Back to Index" link at the end of every section, allowing the reader to navigate the document without scrolling manually.

## Objective

The challenge required building a page using the following tags, covered in class:

<h1> through <h6>, <p>, <mark>, <small>, <i>, <u>, <strong>, <ol>, <ul>, <li>, <a>, <hr>, <sub>, <sup>, <blockquote>

In addition, three tags were researched independently, with their behavior and purpose documented in the page itself:

<font>, <del>, <abbr>

## Structure

Each tag is presented in its own section, consisting of:

A heading identifying the tag
A short explanation of what the tag does and when it is typically used
A working example of the tag applied to real content
A link back to the index

The index at the top of the page links to each of these sections using anchor links (href="#section-id"), and each section heading has a matching id attribute that serves as the link target. Navigation between sections uses scroll-behavior: smooth in CSS, so the page scrolls smoothly rather than jumping instantly. No JavaScript is used for this behavior.

## Tags Reference

| Tag | Purpose |
|---|---|
| `<h1>` – `<h6>` | Headings and subheadings |
| `<p>` | Paragraphs |
| `<mark>` | Text highlight |
| `<small>` | Smaller text (footnotes, disclaimers) |
| `<i>` | Italic text |
| `<u>` | Underlined text |
| `<strong>` | Important / bold text |
| `<ol>` / `<li>` | Ordered list |
| `<ul>` / `<li>` | Unordered list |
| `<a>` | Links / anchors |
| `<hr>` | Horizontal divider |
| `<sub>` | Subscript text |
| `<sup>` | Superscript text |
| `<blockquote>` | Block quote |
| `<font>` | Legacy text/color styling *(obsolete in HTML5)* |
| `<del>` | Deleted / strikethrough text |
| `<abbr>` | Abbreviation with tooltip (`title` attribute) |
| `<img>` | Image |

## File Structure

basic-html-guide/
├── guia-basico-html.html
└── README.md

## Notes 

The <img> example references logo.png as a placeholder. To display an image correctly, replace the src attribute with a valid path or URL to an actual image file.

The <font> tag is included for educational purposes to illustrate a deprecated approach to styling. In modern development, styling should be handled through CSS rather than presentational HTML attributes.

##  Author

Project built as part of the DIO Web Development learning track.
