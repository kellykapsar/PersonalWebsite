---
abstract: In this paper, we present a spatially explicit dataset of monthly shipping intensity in the Pacific Arctic region from January 1, 2015 to December 31, 2020. We calculated shipping intensity based on Automatic Identification System (AIS) data, a type of GPS transmitter required by the International Maritime Organization on all ships over 300 gross tonnes on an international voyage, all cargo ships over 500 gross tonnes, and all passenger ships. We used AIS data received by the exactEarth satellite constellation (64 satellites as of 2020), ensuring spatial coverage regardless of national jurisdiction or remoteness. Our analytical approach converted raw AIS input into monthly raster and vector datasets, separated by vessel type. We first filtered raw AIS messages to remove spurious records and GPS errors, then joined remaining vessel positional records with static messages including descriptive attributes. We further categorized these messages into one of four general ship types (cargo; tanker; fishing; and other). For the vector dataset, we spatially intersected AIS messages with a hexagon (hex) grid and calculated the number of unique ships, the number of unique ships per day (summed over each month), and the average and standard deviation of the speed over ground. We calculated these values for each month for all vessels as well as vessels subdivided by ship type and for messages from vessels > 65 feet long and traveling > 10 knots. For the raster dataset, we created a series of spatially explicit daily vessel tracks according to unique voyages and aggregated tracks by ship type and month. We then created a raster grid and calculated the total length, in meters, of all vessel tracks within each raster cell. These monthly datasets provide a critical snapshot of dynamic commercial and natural systems in the Pacific Arctic region. Recent declines in sea ice have lengthened the duration of the shipping season and have expanded the spatial coverage of large vessel routes, from the Aleutian Islands through the Bering Strait and into the southern Chukchi Sea. As vessel traffic has increased, the social and natural systems of these regions have been increasingly exposed to the risks posed by large ships, including oil spills, underwater noise pollution, large cetacean ship-strikes, and discharges of pollutants. This dataset provides scientific researchers, regulatory managers, local community members, maritime industry representatives, and other decision makers with a quantitative means to evaluate the distribution and intensity of shipping across space and through time.
authors:
- admin
- Benjamin Sullender
- Jianguo Liu
- Aaron Poe
date: "2022-08-08T00:00:00Z"
doi: ""
featured: true
image:
  caption: ""
  focal_point: ""
  preview_only: false
publication: In *Data in Brief*
publication_short: In *Data in Brief*
publication_types:
- "2"
publishDate: "2022-08-08T00:00:00Z"
<!--- summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus
  ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. --->
tags: []
title: 'North Pacific and Arctic marine traffic dataset (2015-2020)'
url_pdf: https://www.sciencedirect.com/science/article/pii/S2352340922007387

---

<!---  {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). --->
