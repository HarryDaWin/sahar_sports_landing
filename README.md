# Sahar Sports

Coming-soon page (`index.html`) plus a short privacy page (`privacy.html`), sharing `style.css`.
No build step. Open `index.html` in a browser to preview.

## Colors

Placeholder grays for now. Swap the values at the top of `style.css`.

## Email signups (Google Form)

1. Make a Google Form with one required **Short answer** question, "Email".
   In **Settings**, turn off "Collect email addresses" and "Requires sign-in".
2. Open the form's ⋮ menu → **Get pre-filled link**, type `test` in the Email box, then **Get link**.
   The link looks like `https://docs.google.com/forms/d/e/<form id>/viewform?usp=pp_url&entry.123456789=test`.
3. In `index.html`, fill in:
   - `GOOGLE_FORM_ACTION`: `https://docs.google.com/forms/d/e/<form id>/formResponse`
   - `GOOGLE_FORM_EMAIL_FIELD`: `entry.123456789`

Signups land in the form's **Responses** tab (link a Google Sheet for a spreadsheet view).
