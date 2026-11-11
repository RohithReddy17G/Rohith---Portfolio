# G. Rohith Reddy — Portfolio

This repository contains the source for my personal portfolio and resume website. It is a static site designed for GitHub Pages and includes my education, certificates, technical skills, data-engineering projects, and contact links.

## Live site

After GitHub Pages is enabled, the site will be available at:

- `https://rohithreeddy17g.github.io/Rohith---Portfolio/`

The custom domain can also point to this repository by configuring DNS and adding a `CNAME` file when the domain is ready to move from Netlify.

## Featured projects

- [SQL + Python Data Jobs Analysis](https://github.com/RohithReddy17G/sql_python_project) — five Jupyter notebooks covering skill demand, trends, salary distributions, and optimal skills for Data Analysts in India.
- [Data Warehouse & Mart Build](https://github.com/RohithReddy17G/sql_data_engineering_projects/tree/main/2_DW_MART_build) — an end-to-end DuckDB warehouse and analytical-marts pipeline.
- [Data Jobs Analysis](https://github.com/RohithReddy17G/sql_data_engineering_projects) — SQL analysis of data-engineering job demand and compensation.
- [Automated Sales ETL Pipeline](https://github.com/RohithReddy17G/sales-pipeline) — a Python, pandas, SQLite, and SQL ETL example.

## Run locally

Because this is a static site, it can be previewed with any local web server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.

## GitHub Pages deployment

The workflow in `.github/workflows/deploy-pages.yml` deploys the repository whenever changes are pushed to `main`:

1. Open **Settings → Pages** in the repository.
2. Set **Source** to **GitHub Actions**.
3. Push changes to `main` or run the **Deploy portfolio to GitHub Pages** workflow manually.

The site uses relative asset paths, so the same files work on the repository Pages URL and on a custom domain.

## Contact

- GitHub: [RohithReddy17G](https://github.com/RohithReddy17G)
- LinkedIn: [Gunda Rohith Reddy](https://www.linkedin.com/in/gunda-rohith-reddy-234a17359/)
- Email: [gundarohithreddy@gmail.com](mailto:gundarohithreddy@gmail.com)
