# Let's search through Via jobs using Python and Pandas!
_By Naman Bhandari_

## Directory Structure

```
.
├── assets
├── via_jobs.ipynb
├── via_jobs.csv
└── README.md
```

## Outline

### Background

As a recent graduate of General Assembly's data science program, I was searching for jobs where I could put my recently learned skills to good use. A fellow college alumnus alerted me to jobs available at Via, the ride-sharing company, where many jobs suitable for my background were available.

As I began taking a look, I noticed that there were probably 150 different jobs available on Via's jobs page: https://boards.greenhouse.io/via.

I wasn't quite sure how to tackle this. Click on each post? Read through each one? It all sounded very time consuming, and I wished there was an easier way to accomplish this task. I clicked on a few, wondering all the while.

### A Solution

Suddenly, it dawned on me. Here I was, a corporate finance professional with quite a few years of investment banking and private equity experience who also recently developed top-notch data analytics and data science skills. Why couldn't I put those skills to use in my search?

A-ha! The answer was clear. The jobs listed on Via's jobs website were listed on a single page, sequentially, like so:

<p align="center">
<img src="assets/via_jobs_page.png" />
</p>

It became clear to me that I could simply scrape all the URLs on the the webpage, and the content within the URLs, and analyze the text in Pandas to see if I could search for certain keywords in each job description that were aligned with my search. Those keywords were:

- Python
- Pandas
- SQL
- Machine Learning
- Investment Banking
- Private Equity

### Outcome

After performing my scrape and analyzing the content of each job, I aligned on the following five jobs that I was interested in:

- [Data Scientist](https://boards.greenhouse.io/via/jobs/4113118002)
- [Business Analytics Associate](https://boards.greenhouse.io/via/jobs/4113116002)
- [City Economics Associate](https://boards.greenhouse.io/via/jobs/4130157002)
- [Financial Operations Associate](https://boards.greenhouse.io/via/jobs/4185299002)
- [Revenue & Pricing Associate](https://boards.greenhouse.io/via/jobs/4130535002)

### Next Steps

Find a contact at the company that I can speak with to discuss my methodology and ask how I can help the company, and how I believe the company could help me. My resume is available in the link below:

[Naman Bhandari Resume](https://www.dropbox.com/s/jz18ox4304bo55t/Bhandari%20Resume%2001%2009%2018.pdf?dl=0)