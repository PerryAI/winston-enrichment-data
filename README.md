# winston-enrichment-data

Public datasets, repackaged as Parquet for the Winston enrichment app. No private or scraped data.
Files are attached to the releases of this repository, not committed.

| File | Rows | Source | License |
|---|---|---|---|
| `companies_1.parquet`, `companies_2.parquet`, `companies_3.parquet` | 24,483,115 companies with a website domain, sorted by domain and split in three | [People Data Labs Free Company Dataset](https://docs.peopledatalabs.com/docs/free-company-dataset), file dated 15 Sep 2026 | CC BY 4.0. Data by People Data Labs |
| `providers.parquet` | 9,494,255 active NPIs, sorted by practice state and specialty | [CMS NPPES Downloadable File](https://download.cms.gov/nppes/NPI_Files.html), October 2026 | Public, FOIA-disclosable US government data |

`providers.parquet` adds specialty names from the [NUCC Health Care Provider Taxonomy](https://www.nucc.org/index.php/code-sets-mainmenu-41/provider-taxonomy-mainmenu-40) code set, version 26.1.

Columns are listed in each release's notes. Release `data-2026-10` is the first build.
