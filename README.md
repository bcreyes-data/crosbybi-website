# Crosby BI website

Source for [crosbybi.com](https://www.crosbybi.com/), the single-page site for Crosby BI (Power BI consulting).

## Structure

- `index.html` holds the whole page: markup, styles and script. English copy lives in the HTML; Spanish copy lives in the `ES` object in the script.
- `images/` holds the logo, headshot and report screenshots.

## Contact form

The form posts to [Web3Forms](https://web3forms.com), which emails each inquiry. Paste the access key into `FORM_ACCESS_KEY` near the top of the script in `index.html`. While the key is empty, or if sending fails, the form opens the visitor's email app with the message filled in and addressed to `CONTACT_EMAIL`.

## Editing copy

Each translatable element has a `data-i18n` key. Change the English text in the HTML and the matching entry in `ES`.
