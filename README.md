# Automotive sales

Purpose of this repository is to gather data about automotive (cars, trucks etc.) sales, so that it can be easy to compare sales across time (month, quarter, month, ytd etc.), energy source (bev, phev, ice etc.), geography (USA, EU, Germany, Norway, China etc.), vehicle type (light passenger vehicle, light truck, SUV, CUV, corssover etc.).

For the start there will appear some links. Later there should be some json files with data and then some github page which will present this json data in graphical form probably using Elm.

Later maybe some Rust server which can download and parse some data from xlsx files from https://bea.gov.

## Available

- This https://duckduckgo.com/?q=suv+sales+usa+2019+wikipedia
  - gives this https://en.m.wikipedia.org/wiki/Automotive_industry_in_the_United_States
    - embeds this https://en.m.wikipedia.org/wiki/File:Total_Vehicle_sales_in_the_US.png which says "Source: U.S. Bureau of Economic Analysis".
      - with this https://duckduckgo.com/?q=total+vehicles+sales+site%3Abea.gov
        - I got this https://www.bea.gov/docs/gdp/auto-and-truck-seasonal-adjustment
          - which points to this https://www.bea.gov/system/files/2019-11/gap_histALT_0.xlsx
- This https://duckduckgo.com/?q=car+sales+report+usa+2019
  - gives this https://www.best-selling-cars.com/international/2019-latest-international-worldwide-car-sales/ which says "New light and passenger vehicle registrations in various major markets in the world monitored by the VDA"
    - https://duckduckgo.com/?q=VDA gives
      - https://en.m.wikipedia.org/wiki/Verband_der_Automobilindustrie
      - https://www.vda.de/
        - https://www.vda.de/en/Search-Results.html?q=annual+report+2019
          - https://www.vda.de/en/services/Publications/annual-report-2018.html
          - https://www.vda.de/en/services/Publications/annual-report-2016.html
          - https://www.vda.de/en/services/Publications/annual-report-2014.html
          - https://www.vda.de/en/services/Publications/annual-report-2013.html
          - https://www.vda.de/en/services/Publications/annual-report-2012.html
- https://duckduckgo.com/?q=car+sales+data+usa+2019+site%3Areddit.com
  - https://www.reddit.com/r/CarsIndia/comments/dtcfa9/car_sales_for_october_2019_is_up_1_yoy/
    - https://www.team-bhp.com/forum/indian-car-scene/215376-october-2019-indian-car-sales-figures-analysis.html
      - "Thanks to the team at Auto Punditz for sharing these sales numbers with us!"
        - http://www.autopunditz.com/

## Paywall

- https://wardsintelligence.informa.com/search#?q=sales&page=1&gating=Data&sortBy=date&sortOrder=desc#searchTop
  - https://wardsintelligence.informa.com/WI060724/US-SAAR-History-by-Month-1980current
  - https://wardsintelligence.informa.com/WI964290/North-America-Production-October-2019
- https://www.statista.com/statistics/200002/international-car-sales-since-1990/
- https://duckduckgo.com/?q=car+sales+data+usa+2019+site%3Areddit.com
  - https://www.reddit.com/r/teslamotors/comments/d1mu2v/usa_august_overall_car_sales_2019/
    - There is no data: "Full September 2019 Top 15 groups, Top 40 brands and Top 285 All-models below" https://bestsellingcarsblog.com/2019/09/usa-august-2019-fleet-incentives-lift-market-to-largest-gain-in-4-years-10-3-toyota-rav4-and-honda-cr-v-break-all-time-records/
      - but here I can read September and October data now https://bestsellingcarsblog.com/2019/11/usa-october-2019-hyundai-kia-11-honda-motor-8-2-shine-in-market-down-1-6-on-track-for-17m-year/. Maybe it won't be available next month?
         - For detailed tables: "Source: Manufacturers, ANDC, GCBC"
         - For incentive outlays: "Source : ALG"
