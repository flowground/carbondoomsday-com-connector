# ![LOGO](logo.png) CarbonDoomsDay **flow**ground Connector

## Description

A generated **flow**ground connector for the CarbonDoomsDay API (version v1).

Generated from: https://api.apis.guru/v2/specs/carbondoomsday.com/v1/swagger.json<br/>
Generated at: 2019-05-07T17:39:53+03:00

## API Description

A real-time RESTish web API for worldwide carbon dioxide levels.

## Authorization

Supported authorization schemes:
- Basic Authentication

## Actions

### CO2 measurements from the Mauna Loa observatory.<br/>
> <br/>
> This data is made available through the good work of the people at the<br/>
> Mauna Loa observatory. Their release notes say:<br/>
> <br/>
>     These data are made freely available to the public and the scientific<br/>
>     community in the belief that their wide dissemination will lead to greater<br/>
>     understanding and new scientific insights.<br/>
> <br/>
> We currently scrape the following sources:<br/>
> <br/>
>   * [co2_mlo_weekly.csv]<br/>
>   * [co2_mlo_surface-insitu_1_ccgg_DailyData.txt]<br/>
>   * [weekly_mlo.csv]<br/>
> <br/>
> We have daily CO2 measurements as far back as 1958.<br/>
> <br/>
> Learn about using pagination via [the 3rd party documentation].<br/>
> <br/>
> [co2_mlo_weekly.csv]: https://www.esrl.noaa.gov/gmd/webdata/ccgg/trends/co2_mlo_weekly.csv<br/>
> [co2_mlo_surface-insitu_1_ccgg_DailyData.txt]: ftp://aftp.cmdl.noaa.gov/data/trace_gases/co2/in-situ/surface/mlo/co2_mlo_surface-insitu_1_ccgg_DailyData.txt<br/>
> [weekly_mlo.csv]: http://scrippsco2.ucsd.edu/sites/default/files/data/in_situ_co2/weekly_mlo.csv<br/>
> [the 3rd party documentation]: http://www.django-rest-framework.org/api-guide/pagination/#pagenumberpagination

*Tags:* `co2`

#### Input Parameters
* `ppm` - _optional_
* `date` - _optional_
* `date__range` - _optional_ - Multiple values may be separated by commas.
* `ordering` - _optional_ - Which field to use when ordering the results.
* `page` - _optional_ - A page number within the paginated result set.
* `limit` - _optional_ - Number of results to return per page.

### CO2 measurements from the Mauna Loa observatory.<br/>
> <br/>
> This data is made available through the good work of the people at the<br/>
> Mauna Loa observatory. Their release notes say:<br/>
> <br/>
>     These data are made freely available to the public and the scientific<br/>
>     community in the belief that their wide dissemination will lead to greater<br/>
>     understanding and new scientific insights.<br/>
> <br/>
> We currently scrape the following sources:<br/>
> <br/>
>   * [co2_mlo_weekly.csv]<br/>
>   * [co2_mlo_surface-insitu_1_ccgg_DailyData.txt]<br/>
>   * [weekly_mlo.csv]<br/>
> <br/>
> We have daily CO2 measurements as far back as 1958.<br/>
> <br/>
> Learn about using pagination via [the 3rd party documentation].<br/>
> <br/>
> [co2_mlo_weekly.csv]: https://www.esrl.noaa.gov/gmd/webdata/ccgg/trends/co2_mlo_weekly.csv<br/>
> [co2_mlo_surface-insitu_1_ccgg_DailyData.txt]: ftp://aftp.cmdl.noaa.gov/data/trace_gases/co2/in-situ/surface/mlo/co2_mlo_surface-insitu_1_ccgg_DailyData.txt<br/>
> [weekly_mlo.csv]: http://scrippsco2.ucsd.edu/sites/default/files/data/in_situ_co2/weekly_mlo.csv<br/>
> [the 3rd party documentation]: http://www.django-rest-framework.org/api-guide/pagination/#pagenumberpagination

*Tags:* `co2`

#### Input Parameters
* `date` - _required_

## License

**flow**ground :- Telekom iPaaS / carbondoomsday-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
