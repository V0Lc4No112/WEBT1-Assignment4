# Assignment 4 - Forms and Validation

Mereikhan Sholanbayev, IT-2511

Three forms built with Bootstrap 5.3 and HTML only. There is no JavaScript and no `novalidate`.
Open `index.html` in a browser. No installation is needed, but the pages need internet access
to load Bootstrap from the CDN and the Montserrat font from Google Fonts.

## Files

- `index.html`: links to the three tasks.
- `task1.html` and `css/task1.css`: Task 1, the train ticket form restyled with my own CSS.
- `task2.html` and `css/task2.css`: Task 2, the AITU Hack 2026 registration form with HTML validation.
- `task3.html`: Task 3, the fixed table reservation form.

## Task 1 - Book a train ticket

- Bootstrap components: radio button group (`btn-check`), floating labels, date inputs, select,
  inline radios, input group, switch, checkbox and buttons.
- My CSS: Montserrat, the five colours, rounded corners, the card shadow and the button colours.
- From, To, Departure, Carriage class, Phone, Email and the agreement are `required`.
- Passengers is a select with 1 to 6 adults. "Clear" is `type="reset"`.
- On a phone `flex-column-reverse` puts "Find trains" above "Clear" without changing the HTML order.

## Task 2 - AITU Hack 2026 registration

Every rule uses `type`, `required`, `min`, `max`, `step`, `minlength` and `maxlength` only (no `pattern`).
`css/task2.css` shows the red border and the `.invalid-feedback` text with `:user-invalid`,
so errors appear only after the user changes a field or tries to submit.

## Task 3 - Reserve a table

The same fields as the original form, with labels, names, correct input types, `required`,
one radio group, a real submit button and Bootstrap layout.

## Checks

- All HTML files pass the W3C Nu HTML Checker and both CSS files pass the W3C CSS validator.
- No horizontal scroll from 320px to 1920px.
- All forms can be used with the keyboard only.
