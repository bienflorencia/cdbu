+++
title = "NaturalistaUY: where are there more opportunities to fill information gaps?"
subtitle = "Presentation at the LatinR Conference"

date = 2021-11-10T00:00:00  # Schedule a publish date
lastmod = 2021-11-10T00:00:00 # Date last modified
draft = false  # Display this post? (true/false)

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["admin"]

tags = ["r", "community-science", "inaturalist"]
summary = ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["rBiodiversidata"]

# links = [{name = "See the Presentation", url = "/files/PresentationBiodiversidata.pdf"}]
links = [{name = "Access the Shiny app", url = "https://github.com/bienflorencia/LatinR2021/tree/main/iNatUy_priority_map"}, {name = "Slides", url = "https://github.com/bienflorencia/LatinR2021/blob/5081c1cac28a4207a653771da89870146ab7bca3/docs/xaringan_latinR/Presentacion_NaturalistaUY.pdf"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Left"

  # Show image only in page previews?
  preview_only = false

+++

**This work was presented at the LatinR Conference 2021**. Using as a basis the data entered into the iNaturalist platform for Uruguay (downloaded on 21 October 2021), we set out to generate an interactive map that ranks areas with biodiversity data deficits and allows us to highlight those where additional biodiversity records could be particularly valuable in filling knowledge gaps. The grids were categorised as 'No records', 'Very High', 'High', 'Medium', 'Low', and 'Very Low' priority, based on each taxonomic group. The data was then used as the basis for creating an app in Shiny, using the shiny and leaflet packages. The app allows to visualise the map of Uruguay with the hexagonal grids coloured according to the order of priority generated. In addition, those consulting the map can select the taxonomic group of interest and choose a grid, for which information will be displayed on: the grid area, the spatial and temporal intensity values, the number of species recorded for that grid, the number of new species recorded in the last year and the proportion of these over the total recorded for that grid.



<iframe height="500px" width="100%" frameborder="no" src="https://bienflorencia.shinyapps.io/iNatUy_priority_map/"> </iframe>
