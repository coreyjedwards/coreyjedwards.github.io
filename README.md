# Corey Edwards

I am a geography student at Riverside City College, and I plan to transfer to a four-year university to continue. With my knowledge of geographic information systems, I want to improve people's day-to-day lives by helping create healthy living environments, both physical and mental.

---

## COVID-19 Case Rates by ZIP Code, New York City, 2020

![This map shows the rate of reported COVID-19 cases for different ZIP codes in New York City](https://coreyjedwards.github.io/images/lab2_layout_edwards.png)

**Question:** Where in New York City were COVID-19 case rates highest and lowest in 2020?

**Data:** COVID-19 ZCTA (COVID19_ZCTA), case data by ZIP code from the NYC Department of Health and Mental Hygiene, 2020, hosted on ArcGIS Online. Accessed 11 Oct. 2026.

**Method:** I used ArcGIS Pro to add the COVID19_ZCTA layer from ArcGIS Online to a new map project. I symbolized the COVID Case Rate field with graduated colors, using natural breaks with five classes and a sequential color ramp, so each ZIP code shows its rate instead of its raw case count. I then built a layout with a title, legend, north arrow, scale bar, and source note.

**A design choice I made and why:** I used five classes instead of three or seven. Three classes would have hidden how the rates were distributed, and seven would have been harder to read.

**A limitation of this map:** The map shows each ZIP code's rate for the whole year. It does not show when the cases happened, so a ZIP code that had most of its cases in one month looks the same as one with steady cases all year.

---

## The 2018 Kilauea Eruption StoryMap

![This map shows the phases of the 2018 Kilauea eruption and how the lava affected the surrounding area](https://coreyjedwards.github.io/images/kilauea_eruption.png)

[Interactive version](https://storymaps.arcgis.com/stories/9cbce01880b6409485f781d11fa9700c)

**Question:** How did the 2018 Kīlauea eruption change the coastline and land area of the affected region over time?

**Data:** Landsat 8 satellite images from March 27, July 17, and August 2, 2018, and February 26, 2019 (U.S. Geological Survey), and the Kilauea 2018 Lava Flow Extents layer (Esri, Learn ArcGIS).

**Method:** I used ArcGIS Online Map Viewer to add four Landsat 8 images and the Kilauea 2018 Lava Flow Extents layer. I styled the images in natural color (bands 4, 3, 2) and shortwave infrared, or SWIR (bands 7, 5, 4), and adjusted the brightness and contrast. SWIR showed more of the active lava through the smoke in the July and August images. I then built an ArcGIS StoryMap with a sidecar for the four dates and a swipe map comparing March 2018 to February 2019, and published it publicly.

**A design choice I made and why:** I used a swipe map so readers can compare March 2018 with February 2019 on one screen. I outlined only the lava flow extent and left out other features so attention stays on where the lava went.

**A limitation of this map:** The map shows the eruption from above. It does not show what it was like for people on the ground or how the eruption affected nearby residents.

---

## Data sources

- COVID-19 ZCTA (COVID19_ZCTA). NYC Department of Health and Mental Hygiene, 2020. ArcGIS Online, services3.arcgis.com/HHsRcAgIU6SqBiQd/arcgis/rest/services/COVID19_ZCTA/FeatureServer. Accessed 11 Oct. 2026.
- Landsat 8 imagery. U.S. Geological Survey, 2018 to 2019.
- Kilauea 2018 Lava Flow Extents. Esri, Learn ArcGIS.

## Where this is going

I plan to add more maps and web maps, choosing the most interesting, complex, and important ones. I want this portfolio to show that I can create many kinds of maps, including maps with important or pressing information about the present, the past, and possible futures. I also want it to show how much I enjoy making maps and presenting crucial information in a way that anyone can read and understand.
