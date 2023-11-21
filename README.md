# Awesome Procurement Data [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Carefully curated list of awesome US federal government procurement data resources.

The US Federal Government obligates something like $1 trillion each year through federal contracts. It also generates a ton of data about federal procurement. This list attempts to create access to the APIs, utilities, and systems that power the federal #govcon landscape.

Contributions welcome. Add links through pull requests or create an issue to start a discussion. Read the [contribution guidelines](contributing.md) first.

## Contents

- [Official Government Resources](#official-government-resources)
- [Utilities and Client Libraries](#utilities-and-client-libraries)
- [Data Science](#data-science)

## Official Government Resources

- [SAM.gov Entity/Exclusions Extracts Download APIs](https://open.gsa.gov/api/sam-entity-extracts-api/) - The API that allows access to SAM.gov's entity information
- [SAM.gov Opportunities API](https://open.gsa.gov/api/get-opportunities-public-api/) - All the federal contract opportunities in SAM.gov
- [CALC API](https://open.gsa.gov/api/dx-calc-api/) - Labor Rates from GSA's eight GSA professional services schedules
- [FPDS API](https://www.fpds.gov/wiki/index.php/ATOM_Feed_FAQ) - The XML feed we all know and... well, we know it anyway...
- [USASpending](https://api.usaspending.gov) - Maybe the GOAT of GovCon APIs?
- [SBIR API](https://www.sbir.gov/api/) - An API that powers the SBIR.gov website
- [FAR](https://github.com/GSA/GSA-Acquisition-FAR) - The FAR in various formats (including XML, ePub, docx, and PDF)
- [Acquisition Gateway Document Library API](https://open.gsa.gov/api/ag-api/) - Structured data that for documents on the Acquisition Gateway (May not be publicly accessible).

## Utilities and Client Libraries

- [FPDS](https://github.com/dherincx92/fpds) - Accessing the Federal Procurement Data System (FPDS) ATOM feed in Python and a CLI
- [PSC Selection Tool](https://psctool.us/home) - An API maintained by the Defense Pricing and Contracting (DPC) office for accessing NAICS and PSC codes.
- [FSCPSC](https://www.fscpsc.com/) - A "prediction engine" for NAICS and PSC codes. It has a cool [API](https://api.fscpsc.com/), too!
- [pysam](https://github.com/jpleger/pysam) - A python wrapper over the SAM API
- [SamDotNet](https://github.com/mheadd/SamDotNet) - A C# wrapper over the SAM API
- [procurement-tools](https://github.com/tandemgov/procurement-tools) - A python library for various procurement-related tasks

## Data science and other cool stuff

- [David Gill's Acquisition Innovation repo](https://github.com/DGill-Procurement/AcquisitionInnovation) - Structured transaction reports from USASpending.gov and some NLP utilities using R
- [DIIG CSIS Lookup Tables](https://github.com/CSISdefense/Lookup-Tables) - A bunch of tables used in procurement (including NAICS codes, contracting offices, etc)
- [USASpending Bot](https://github.com/coforma/usa-spending-bot) - A slack bot that uses usaspending.gov's API to retrieve data on awarded contracts
- [SAM.gov webscraper](https://github.com/jankaltenegger/SAM.gov-Webscraper) - Use Google Sheets to track SAM opportunities? Here's a tool for that
