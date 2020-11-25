# Electronika 13.0 Solutions
This repo contains the solutions to Electronika 13.0, which was conducted on
22-Nov 2020 as part of NISB's tech fest "Adroit".

This PDF was compiled using an awesome program called [pandoc](https://pandoc.org/).

If you want to compile it yourself,
* Clone this repo `$ git clone https://github.com/nisbweb/electronika13.git`
* Get pandoc, and the required filters

Run this in the root of the repo-

```bash
$ pandoc --from markdown "electronika13-solutions.md" -o "electronika13-solutions.pdf" \
--pdf-engine xelatex --filter=pandoc-crossref --citeproc
```
