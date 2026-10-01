CCNY Fall 2021 Calendar Scraping

This project parses the CCNY Fall 2021 academic calendar using Python,
BeautifulSoup, requests, and pandas.

The original CCNY page currently returns a 403 response because of
Cloudflare protection. The requests attempt is shown in the notebook,
and a locally saved copy of the Fall 2021 calendar HTML is used for
parsing.

The final pandas DataFrame contains:

- a date index
- `dow` for day of the week
- `text` for the calendar event description

The final dataset contains 36 calendar entries.

- Furkan Kagan Bilgi
