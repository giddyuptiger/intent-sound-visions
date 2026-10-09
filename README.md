# Intent Sound & Visions website

Static rebuild of intentsoundandvisions.com (originally on Wix) for Intent Sound & Visions LLC, Topanga, CA. Plain HTML and CSS, no build step.

    python3 -m http.server 8000   # then open http://localhost:8000

## Pages

| Path | Page |
| --- | --- |
| `/` | Home: one-liner for event buyers, services, signature moments, crew band, contact |
| `/capabilities/` | Capabilities, with anchors `#sound`, `#lighting`, `#video` |
| `/work/` | Work (was Portfolio): event work first, music videos last |
| `/crew/` | Crew: roles for production companies and agencies |
| `/about/` | About |
| `/contact/` | Quote form; `/contact/thanks/` after sending |
| `/s-projects-side-by-side/` | Old Wix portfolio address, forwards to `/work/` |

The first commit is a faithful copy of the Wix site; the second applies the changes from the site cleanup plan.

## Forms

Both forms post to FormSubmit (formsubmit.co), which emails the submission to hello@intentsoundandvisions.com. The first time a form is sent, FormSubmit emails that inbox a confirmation link; click it once and every later submission arrives as a normal email. The quote form accepts one attachment (floor plan or brief).

## Before this goes live on the real domain

1. Confirm the copy marked below with Spencer.
2. Remove `robots.txt` and the `noindex` meta tag in each page. They are there so this preview does not compete with the live domain in search.
3. Change the form `_next` addresses and the `og:image` address from the GitHub Pages URL to the real domain.
4. Point intentsoundandvisions.com at the new host.

## To confirm with Spencer

- "Spencer Hinkle, who also performs as HNKLLE" on About.
- "We reply within one business day" on Contact.
- The unnamed crew credits on Crew (festival, Venice venue, party and wedding band).
- Which consoles and software to list on Crew.
- Prices: none are published yet.
- Case studies for Work need client permission first (the planner wedding, the festival, the Venice venue).

Images and the display font were exported from the Wix site and belong to Intent Sound & Visions.
