This repo contains data on Covid emergency aid awarded by UK public authorities, joined with Companies House data.

It is correct as of Friday 25 June 2021. Check the [EC State Aid Transparency Public Search](https://webgate.ec.europa.eu/competition/transparency/public?lang=en) for the latest data.

Sources
-------

This data is as published on the [EC State Aid Transparency Public Search](https://webgate.ec.europa.eu/competition/transparency/public?lang=en) on Friday 25 June 2021.

It was supplied to us directly by the EC support team, pre-filtered by them to contain only state aid granted by the UK.

We then filtered it to contain only aid granted under the following schemes (Covid-related emergency aid):

- [SA.56792](https://ec.europa.eu/competition/elojade/isef/case_details.cfm?proc_code=3_SA_56792) (CBILS, later replaced by SA-56841).
- [SA.56794](https://ec.europa.eu/competition/elojade/isef/case_details.cfm?proc_code=3_SA_56794) (CBILS, later replaced by SA-56841)
- [SA.56841](https://ec.europa.eu/competition/elojade/isef/case_details.cfm?proc_code=3_SA_56841) (COVID-19 Temporary Framework for UK authorities).


And we then joined it with [Companies House data](http://download.companieshouse.gov.uk/en_output.html) (last updated 1 June 2021) to obtain basic information about the companies being supported. This data is contained in the columns starting `ch_`.

Notes on the data
-----------------

Under EC transparency regulations for emergency Covid aid, UK authorities are only required to report the following subsidies:

- Subsidies with a value of more than 100,000 EUR
- Subsidies granted more than 12 months ago.

This data therefore does not contain BBLS or smaller CBILS/CLBILS loans.

Licensing
---------

The EC publishes its original data under the [Creative Commons Attribution 4.0 International (CC BY 4.0) licence](https://ec.europa.eu/info/legal-notice_en).