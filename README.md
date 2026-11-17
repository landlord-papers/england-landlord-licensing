# England landlord licensing schemes

Which councils in England run selective or additional licensing for private rented homes, where each scheme applies, and when it starts and ends. Every row was read on the council's own website, and each gives the page it came from and the date it was checked.

- 86 councils, including every London borough and the big rented cities
- 100 schemes, plus a row for each council that says it runs none
- Checked on 8 and 9 November 2026

Maintained by [Landlord Papers](https://landlordpapers.co.uk), free tools for private landlords in England. Each council has a page there with its schemes and what the new landlord register means for it, for example [Leicester](https://landlordpapers.co.uk/register/council/leicester). The full list, by region, starts at [landlordpapers.co.uk/register/council](https://landlordpapers.co.uk/register/council).

## Files

- `licensing-schemes.csv`: one row per scheme, or one `none` row for a council that runs no scheme
- `licensing-schemes.json`: the same rows as JSON

| Column | Meaning |
|---|---|
| `council` | The council, as GOV.UK's list of councils by region names it |
| `region` | Its region of England |
| `checked` | The date the council's pages were read, as YYYY-MM-DD |
| `council_licensing_page` | The council's own private renting or property licensing page |
| `scheme` | `selective`, `additional`, or `none` |
| `area` | Where the scheme applies, in the council's words as far as they go |
| `starts` | When it started or starts: a date (YYYY-MM-DD), or a month where the council gives only that |
| `ends` | When it ends, if the council says |
| `scheme_source` | The page that states the scheme |
| `note` | Anything else the council says, in plain English |
| `details` | The council's page on Landlord Papers |

## Things to know

- This file lists the selective and additional schemes each council chooses to run. Mandatory licensing for houses in multiple occupation applies everywhere and isn't listed here: see [GOV.UK on HMOs](https://www.gov.uk/renting-out-a-property/houses-in-multiple-occupation-hmo).
- Councils start, renew and end schemes often. Check the council's page before relying on a row.
- Councils not in the file haven't been checked yet, not "no scheme".
- This is guidance, not legal advice.

## Corrections

If a scheme has changed, open an issue with the council's page.

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You can reuse the data, including commercially, if you credit Landlord Papers with a link to https://landlordpapers.co.uk.
