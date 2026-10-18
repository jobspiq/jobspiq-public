# Column definitions

Each `YYYY-MM-DD/` folder is a snapshot taken on that date. Files are UTF-8 CSV.

## skills-demand-india.csv

| Column | Meaning |
|---|---|
| `rank` | Rank by number of active postings |
| `skill` | Skill name |
| `active_jobs` | Active tech job postings that mention the skill |
| `share_of_tech_jobs_pct` | Those postings as a percentage of all active tech postings |
| `page_url` | Live page for the skill on jobspiq.in |
| `as_of` | Date the figures were computed |
| `window_days` | Postings seen in this many days before `as_of` |
| `attribution` | Required credit line |

## tech-salaries-stated-india.csv

| Column | Meaning |
|---|---|
| `group_type` | `overall`, `experience`, `role_family` or `skill` |
| `group` | The group within that type |
| `stated_salaries` | Number of employer-stated salaries behind the row |
| `lower_quartile_lpa`, `median_lpa`, `upper_quartile_lpa` | Quartiles in lakh rupees per year. Each salary is the midpoint of the range stated in the posting |
| `as_of` | Date the figures were computed |
| `window_days` | Postings seen in this many days before `as_of` |
| `attribution` | Required credit line |

Experience is the minimum years the posting asks for. Groups with fewer than 25 stated salaries are not included.
