# Jobspiq open data: India's tech job market

Free, citable data from [Jobspiq](https://jobspiq.in), an AI job search platform for technology professionals in India.

Each folder in [`data/`](data/) is a **dated snapshot** of the datasets published at [jobspiq.in/data](https://jobspiq.in/data). The website shows live figures that change every day; the files here never change once committed, so you can cite an exact version.

## Datasets

| File | What it contains | Window |
|---|---|---|
| `skills-demand-india.csv` | Active tech job postings in India that mention each skill, and each skill's share of all tech postings | Postings seen in the 30 days before the snapshot date |
| `tech-salaries-stated-india.csv` | Quartiles of salaries that employers **state** in tech job postings (no estimates), by experience, role family and skill, with the number of stated salaries behind every row | Postings seen in the 90 days before the snapshot date |

Column definitions are in [`data/README.md`](data/README.md).

The data covers active technology job postings located in India, or remote and open to candidates in India. It contains **aggregate numbers only**: no job descriptions, no copied postings and no personal data.

## How to cite

> Source: Jobspiq, "[dataset name]", snapshot [YYYY-MM-DD], https://github.com/jobspiq/jobspiq-public. Licensed CC BY 4.0.

GitHub's **Cite this repository** button (from [`CITATION.cff`](CITATION.cff)) gives the same in APA and BibTeX.

## Method and limits

- Postings are collected from LinkedIn, Naukri, remote job boards and employer career pages, and duplicates are merged. A job counts once per skill.
- Salaries are only those stated in the posting. Most postings state none, so every salary row shows its sample size, and groups with fewer than 25 stated salaries are left out. Employers who publish pay are not a random sample of all employers.
- These are job postings, not hires, and they do not measure total employment.

Longer method notes for Jobspiq's published research are in [`methods/`](methods/).

## Licence

The data is licensed under [Creative Commons Attribution 4.0 International](LICENSE) (CC BY 4.0): you may share and adapt it for any purpose, including commercially, as long as you credit Jobspiq.

## Contact

Questions, corrections or press enquiries: support@jobspiq.in · Press kit: [jobspiq.in/press](https://jobspiq.in/press)
