# Overview

For this project, you'll be building a portfolio website. You will be provided a design mockup as a PDF-file, and you must replicate that design in HTML and CSS. You will develop a responsive website that will display images, descriptions and links to each of the portfolio projects.

# Requirements

1. Design

    - The page at minimum includes all of the following:

        - [x] at least 4 images
        - [x] title text (h1, h2, etc.)
        - [x] regular (paragraph) text
        - [x] a logo.

    - Semantics HTML

        - [x] HTML5 semantic tags such as `<header>, <footer>, <article>, <section>` etc. are used to add meaning to the code.

        - [x] No `<div>` or `<section>` tags are without a CSS class or id.

    - Provide at least one of the following customizations:

        - [x] Customize images and text.

        - [x] Customize placement of the elements on the page (grid layout) with HTML, CSS or both.

        - [x] Customize CSS styles applied at minimum to paragraph and heading elements.

    - Grid Base Layout

        - [x] Page utilizes a grid-based layout with styles making use of the flexbox layout or a framework like Bootstrap, Foundation, etc.

1. Responsiveness

    - [x] All content is responsive and displays on all display sizes. This includes:

        * Desktop
        * Mobile: Google Nexus 5
        * Tablet: Apple iPad

    - [x] All content is rendered on all three devices. No content should be hidden on mobile devices.

    - [x] Viewport meta tag is included in HTML. (i.e. `<meta name=”viewport” …)`

    - [x] If a CSS framework is used, classes provided by the CSS framework are used to make images responsive, otherwise media-queries are used to ensure responsiveness of images.

1. Separation of Concerns

    - [x] Portfolio completely separates structure (HTML) from design/style (CSS). There are no style attributes present in the body of the HTML document. There are no `<style>` elements in the document.

    - [x] Files are organized with a directory structure that separates files based on functionality.

1. Code Quality

    - HTML Formatting Rules

        - [x] All code ( HTML element names, attributes, attribute values) is lowercase (except text/CDATA).
        - [ ] Code does not have trailing white spaces.
        - [x] Indentation is consistent (either all tabs or all 2 spaces or all 4 spaces etc).
        - [x] Code uses a new line for every block, list or table element and indent every such child element (it's acceptable to put all `<li>` elements in one line).
        - [x] [Optional] When quoting attribute values, code uses double quotation marks.

    - HTML Style Rules

        - [x] HTML documents use HTML5 `<!doctype html>`.
        - [x] Code passes HTML and CSS validators.
        - [ ] *[Optional] Code does not use entity references unless necessary e.g. characters with special meaning in HTML (like < and &) as well as control or “invisible” characters (like no-break spaces).
        - [ ] [Optional] Code omits type attributes for style sheets and scripts.

    - CSS Formatting Rules

        - [x] Code does not have trailing white spaces.
        - [x] Indentation is consistent (either all tabs or all 2 spaces or all 4 spaces etc).
        - [x] Code indents all block content, that is rules within rules as well as declarations to reflect hierarchy and improve understanding.
        - [x] Code uses a semicolon after every declaration for consistency and extensibility reasons.
        - [x] Code always uses a space after a property name's colon, but no space between property and colon, for consistency reasons.
        - [x] Code always use a single space between the last selector and the opening brace that begins the declaration block.
        - [x] Code always start a new line for each selector and declaration.
        - [ ] Code always put a blank line (two line breaks) between rules.
        - [ ] [Optional] Code uses double quotation marks for attribute selectors or property values. Do not use quotation marks in URI values (url()).

    - CSS Style Rules

        - [x] Code uses meaningful or generic ID and class names that are as short as possible but as long as necessary.
        - [x] Code does not use element names in conjunction with IDs or classes.
        - [ ] Code uses shorthand properties where possible.
        - [x] [Optional] Code omits unit specification after 0 values.
        - [ ] [Optional] Code includes leading 0s in decimal values for readability.
        - [ ] [Optional] Code uses 3-character hexadecimal notation where possible.
        - [ ] [Optional] Code separate words in ID and class names by a hyphen.
        - [ ] [Optional] Code avoids user agent detection as well as CSS "hacks"—try a different approach first.

1. General Meta Rules

    - [x] templates and documents use UTF-8 encoding. (no BOM) i.e. `<meta charset="utf-8">`.
