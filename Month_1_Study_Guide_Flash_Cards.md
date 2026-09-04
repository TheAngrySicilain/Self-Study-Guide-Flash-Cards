# Month 1 Study Guide Flash Cards

Source: Month 1 Self-Study Guide: UI, Modern CSS & React Foundations

## Set 1: HTML Foundations

| Front | Back |
| --- | --- |
| What does `<!DOCTYPE html>` do? | It tells the browser to use modern HTML standards behavior for an HTML5 document. |
| What is the root element of an HTML page? | `<html>`. It contains all other document elements. |
| How do you declare UTF-8 character encoding? | Place `<meta charset="UTF-8">` inside `<head>`. |
| What is the largest HTML heading? | `<h1>`, the highest-level heading. |
| What is a void element? | An element with no child content or closing tag, such as `<br>`, `<img>`, or `<source>`. |
| Which image attribute supports basic accessibility? | `alt`. Use descriptive text for informative images and `alt=""` for decorative images. |
| How does a link open in a new tab? | Use `target="_blank"` on the `<a>` element. |
| Which element creates an unordered list? | `<ul>`; each item is placed in `<li>`. |
| Which element defines a table row? | `<tr>`. Header and data cells use `<th>` and `<td>`. |
| Why use semantic HTML? | It communicates the meaning and purpose of content to browsers and assistive technologies. |
| What does a form's `method` attribute define? | The HTTP method used to submit data, commonly `GET` or `POST`. |
| How do you link an external CSS file? | Use `<link rel="stylesheet" href="styles.css">` inside `<head>`. |
| Which input type creates a slider? | `<input type="range">`. |
| What does a form's `action` attribute define? | The destination URL that receives the submitted form data. |
| How is a label tied to an input? | Match the label's `for` value to the input's `id` value. |
| Which element embeds native video? | `<video>`, often containing one or more `<source>` elements. |
| Which common element is inline by default? | `<span>`. |
| What is the syntax for an HTML comment? | `<!-- This is a comment -->` |
| Which attribute makes a form field mandatory? | `required`. |
| Which element supplies alternative media resources? | `<source>` inside `<picture>`, `<audio>`, or `<video>`. |

## Set 2: CSS and JavaScript

| Front | Back |
| --- | --- |
| What are the four parts of the CSS box model? | Content, padding, border, and margin. |
| How do `content-box` and `border-box` differ? | `content-box` applies width to content only; `border-box` includes padding and border within the declared width. |
| What is Flexbox? | A one-dimensional CSS layout system for arranging items along main and cross axes. |
| Main axis versus cross axis? | The main axis follows `flex-direction`; the cross axis runs perpendicular to it. |
| What is a media query? | A CSS rule that applies styles only when conditions, such as viewport width, are met. |
| What is responsive design? | Designing layouts that adapt to different screens and viewport sizes. |
| What does `map` return? | A new array of the same length, with every item transformed. |
| What does `filter` return? | A new array containing only the items that pass a test. |
| What is mutation? | Directly changing an existing array, object, or state value. |
| What is an immutable update? | Creating a new array or object instead of changing the original. |
| What is a Promise? | An object representing the eventual success or failure of an asynchronous operation. |
| What does `fetch` return? | A Promise that resolves to a Response object. |
| Why check `response.ok`? | `fetch` usually resolves even for HTTP errors such as 404 or 500; `response.ok` identifies success. |
| What is a shallow copy? | A new outer array or object whose nested objects may still share references with the original. |

## Set 3: React, Next.js, and Debugging

| Front | Back |
| --- | --- |
| What is a React component? | A reusable piece of an interface, usually a function that returns UI. |
| Props versus state? | Props are read-only inputs from a parent; state is component-owned data that can change and trigger a re-render. |
| When should you use a functional state update? | When the next state depends on the previous state, such as `setCount(prev => prev + 1)`. |
| What is derived state? | A value calculated from existing props or state instead of stored separately. |
| Why do React lists need keys? | Stable, unique keys let React match items correctly between renders. |
| What is reconciliation? | React's process for comparing render results and efficiently updating the DOM. |
| What is unidirectional data flow? | Data moves down through props; requests for change move up through callbacks. |
| What is a stale state bug? | Code uses an outdated state value; functional updates often prevent it. |
| What is a Server Component in Next.js? | A component rendered on the server; it is the App Router default and cannot use client-only hooks or browser APIs. |
| What is a Client Component? | A component that can use state, effects, event handlers, and browser APIs; its file starts with `'use client'`. |
| What is hydration? | Attaching client-side React behavior to HTML that was rendered earlier. |
| What are DevTools used for? | Inspecting HTML, CSS, JavaScript errors, computed styles, and network requests. |
| What should you inspect for a failed network request? | Request URL, HTTP method, status code, payload, and response body. |
| What is the first step before asking AI to fix a bug? | Make an independent diagnosis and capture the exact error, expected behavior, and smallest relevant code snippet. |

## Review Routine

1. Cover the Back column and answer each Front aloud.
2. Mark a card correct only after defining it and applying it correctly twice without notes.
3. Review missed cards after 1 day, 3 days, and 7 days.
4. Practice these contrast pairs: tag vs. element, block vs. inline, `content-box` vs. `border-box`, props vs. state, mutation vs. immutable update, and Server Component vs. Client Component.
