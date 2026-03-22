# Contact Form Project

This repository contains a simple HTML contact form implemented in `Index.html`.

## Features

- Form element: `action="#"`, `method="post"`
- Input fields:
  - Full Name (`type="text"`, `required`, `minlength="2"`, placeholder)
  - Email Address (`type="email"`, `required`, placeholder)
  - Phone Number (`type="tel"`, optional, placeholder)
  - Gender (radio group: Male, Female, Other; required)
  - Interests (checkbox group: HTML, CSS, JavaScript; multi-select)
  - Country (dropdown with default "Select your country" and multiple options)
  - Your Message (`textarea`, `required`, `minlength="10"`, placeholder)
- Submit button labeled: `Send Message`
- Built-in HTML validation and accessibility features
- Internal CSS for centering, spacing, and readable UI

## Usage

1. Open `Index.html` in a browser.
2. Fill out the form fields.
3. Click **Send Message**.

> Note: This form currently uses a placeholder action (`#`) and no form data is submitted to a backend.

## Development

- No build step required.
- You can edit only `Index.html` to change styles or validations.

## License

MIT (or specify as needed).
