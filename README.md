# Automotive sales

Purpose of this repository is to gather data about automotive sales, so that it can be easy to compare sales across time (month, quarter, month, ytd etc.), energy source (bev, phev, ice etc.), geography (USA, EU, Germany, Norway, China etc.), vehicle type (light passenger vehicle, light truck, SUV, CUV, corssover etc.).

For the start there will appear some links. Later there should be some json files with data and then some github page which will present this json data in graphical form probably using Elm.

Later maybe some Rust server which can download and parse some data from xlsx files from https://bea.gov.

## Links

- This https://duckduckgo.com/?q=suv+sales+usa+2019+wikipedia
  - gives this https://en.m.wikipedia.org/wiki/Automotive_industry_in_the_United_States
    - embeds this https://en.m.wikipedia.org/wiki/File:Total_Vehicle_sales_in_the_US.png which says "Source: U.S. Bureau of Economic Analysis".
      - with this https://duckduckgo.com/?q=total+vehicles+sales+site%3Abea.gov
        - I got this https://www.bea.gov/docs/gdp/auto-and-truck-seasonal-adjustment
          - which points to this https://www.bea.gov/system/files/2019-11/gap_histALT_0.xlsx
