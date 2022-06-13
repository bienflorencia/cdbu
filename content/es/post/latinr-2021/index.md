+++
title = "NaturalistaUY: ¿dónde hay más oportunidades de llenar vacíos de información?"
subtitle = "Presentación en la Conferencia LatinR"

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
links = [{name = "Accedé a la app de Shiny", url = "https://github.com/bienflorencia/LatinR2021/tree/main/iNatUy_priority_map"}, {name = "Presentación", url = "https://github.com/bienflorencia/LatinR2021/blob/5081c1cac28a4207a653771da89870146ab7bca3/docs/xaringan_latinR/Presentacion_NaturalistaUY.pdf"}]

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

**Este trabajo fue presentado en la Conferencia LatinR 2021**. Usando como base los datos ingresados en la plataforma iNaturalist para Uruguay (descargados el 21 de octubre de 2021), nos propusimos generar un mapa interactivo que ordene las áreas con déficit de datos de biodiversidad y nos permita resaltar aquellas en las que registros adicionales de biodiversidad podrían ser particularmente valiosos para llenar los vacíos de conocimiento. Las grillas se clasificaron como "Sin registros", "Muy alta", "Alta", "Media", "Baja" y "Muy baja" prioridad, basándose en cada grupo taxonómico. A continuación, los datos se utilizaron como base para crear una aplicación en Shiny. La app permite visualizar el mapa de Uruguay con las grillas hexagonales coloreadas según el orden de prioridad generado. Además, quienes consulten el mapa podrán seleccionar el grupo taxonómico de interés y elegir una grilla, para la cual se desplegará información sobre: el área de la grilla, los valores de intensidad espacial y temporal, la cantidad de especies registradas para esa grilla, el número de especies nuevas registradas en el último año y la proporción de éstas sobre el total registrado para esa grilla.


<iframe height="600px" width="100%" frameborder="no" src="https://bienflorencia.shinyapps.io/iNatUy_priority_map/"> </iframe>

**Grattarola, F., & Barreneche, J. M.** (2021). *Soy naturalista y quiero pasear en mi país, dónde hay más oportunidades de llenar vacíos de información?* Conferencia Latinoamericana sobre Uso de R en Investigación+ Desarrollo (LatinR 2021), Virtual.
