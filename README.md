# LinkedIn Job Scraper

Automatically scrapes job postings from LinkedIn and logs them to a structured Google Sheet — complete with filters, timestamps, and customization for any role or region.

---

## Why I built this

When job hunting, manually browsing LinkedIn and copying job info into a spreadsheet gets tedious fast. This automation streamlines the process so you can track and filter new listings in real-time without lifting a finger.

---

## What it does

- **Inputs:**
  - LinkedIn search URL (with filters like title, location, date posted, etc.)

- **Logic:**
  - Scrapes job postings using n8n + browser automation or an API-based scraper
  - Filters out irrelevant results (e.g., Fortune 500 companies)
  - Cleans and structures the data (job title, company, location, link, date)
  - Adds a timestamp and logs results to Google Sheets

- **Outputs:**
  - Real-time job listing feed in a Google Sheet
  - Optional notifications or tagging logic

---

## Demo

[Loom Video → LinkedIn Job Scraper Demo](https://www.loom.com/share/eac9a0478cf545098f848c2b6ef00d04)

---

## Tools Used

- [n8n](https://n8n.io/)
- [Google Sheets (OAuth2)](https://workspace.google.com/products/sheets/)
- [Apify / Puppeteer / Browserless] (for scraping — can be swapped based on preference)
- [LinkedIn](https://linkedin.com/) (front-end scraping via public search pages)

---

## Notes

- Currently built for individual job seekers, but easily extendable to recruiters or agencies
- Filtering logic can be adjusted to focus on startups, exclude enterprise companies, or sort by role seniority
- Add-ons could include email alerts, auto-apply integrations, or matching job-to-resume scoring
