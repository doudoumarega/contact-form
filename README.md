# Contact Form

An accessible, HTML-only contact form for the [roadmap.sh Contact Form project](https://roadmap.sh/projects/contact-form) in the HTML Fundamentals learning path.

## Overview

This project builds a single-page **Acme Support** contact form using native HTML elements, semantic page structure, and browser-side validation. It intentionally does not include CSS or JavaScript, in accordance with the exercise.

## Intended Features

- Semantic page structure with `<header>`, `<main>`, and `<footer>`.
- A form using `method="post"` and a placeholder submission endpoint (`/send`).
- Properly associated labels and inputs for full name and email.
- A subject dropdown with several topics.
- A required message field with a minimum character length.
- An accessible `<fieldset>` and `<legend>` for a single-choice referral question.
- An optional checkbox for product updates.
- A submit button and built-in browser validation.

These describe the completed exercise requirements; make sure the final HTML includes all of them before submitting.

## Project Files

```text
contact-form/
├── contact-form.html
└── README.md
```

## Run Locally

1. Clone or download the repository.
2. Open `contact-form.html` in a web browser.
3. Test required fields, email validation, message length, and the radio-button grouping.

No installation or build step is needed to view the page. The form endpoint `/send` is a placeholder: **there is no backend**, so submitting valid data will not deliver a message. A server would be needed to process the POST request.

## What I Practiced

- The difference between `id` (label association) and `name` (submitted form field key).
- How radio inputs share a `name` to allow only one selection in a group.
- Accessible grouping with `<fieldset>` and `<legend>`.
- Built-in browser validation via `required`, `minlength`, and `type="email"`.
- The distinction between client-side validation and server-side validation.
- How browser form data becomes name/value pairs in an HTTP request.

## Links

- **Project requirements:** https://roadmap.sh/projects/contact-form
- **HTML Fundamentals:** https://roadmap.sh/packs/html

## Author

**Mamadou MAREGA**  
GitHub: https://github.com/doudoumarega
