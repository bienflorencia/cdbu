+++
# Project title.
title = "Vertebrates"

# Date this page was created.
date = 2019-04-23T00:00:00

# Project summary to display on homepage.
summary = "A comprehensive database of tetrapod species occurrence records native from Uruguay."

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["databases"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/biodiversidata"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "Photo by [**Daniel Hernández**](../../authors/danielh/)"
  
  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

# A comprehensive database of tetrapod species occurrence records native from Uruguay.  

We hace created a comprehensive database of tetrapod occurrence records native from Uruguay, with the latest taxonomic updates and georeferencing of the collection locations. The dataset provides primary biodiversity data on extant Amphibia, Reptilia, Aves and Mammalia species recorded in Uruguay. The total number of records in the dataset is 69,390, including 680 species (51 amphibians, 444 birds, 117 mammals and 68 reptiles). This is the largest and most geographically and taxonomically comprehensive database of Uruguayan tetrapod species available to date, and it represents the first open repository for the country.


{{% alert note %}}
**This work is currently under peer-review. We hope to have it available soon.**  
{{% /alert %}}


The data fields that are being collected include the following terms:


| **Column label** | **Column description** |
|----------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| occurrenceID | An identifier for the Occurrence (as opposed to a particular digital record of the occurrence), constructed from a combination of identifiers in the record that will most closely make the occurrenceID globally unique. |
| scientificName | The full scientific name with genus and specific epithet |
| vernacularName | Common or vernacular name in Uruguay (in Spanish) |
| kingdom | The full scientific name of the kingdom in which the taxon is classified |
| phylum | The full scientific name of the phylum or division in which the taxon is classified |
| class | The full scientific name of the class in which the taxon is classified |
| order | The full scientific name of the order in which the taxon is classified |
| family | The full scientific name of the family in which the taxon is classified |
| countryCode | The standard code for the country in which the Location occurs |
| stateProvince | The name of the next smaller administrative region than country (department) in which the Location occurs |
| verbatimLocality | The original textual description of the place |
| decimalLatitude | The geographic latitude (in decimal degrees) |
| decimalLongitude | The geographic longitude (in decimal degrees) |
| georeferenceSources | A list of maps, gazetteers, or other resources used to georeference the Location |
| georeferencedBy | A person, group, or organization who determined the georeference (spatial representation) for the Location. |
| eventDate | The date when the event was recorded. Format: dd-mm-yyyy |
| year | The four-digit year in which the Event occurred. Format: yyyy |
| month | The ordinal month in which the Event occurred. Format: mm |
| day | The integer day of the month on which the Event occurred. Format: dd |
| basisOfRecord | The specific nature of the data record (HUMAN_OBSERVATION, PRESERVED_SPECIMEN, MACHINE_OBSERVATION, UNKNOWN) |
| institutionCode | The name (or acronym) in use by the institution having custody of the object(s) or information referred to in the record |
| collectionCode | The name or acronym identifying the collection or data set from which the record was derived |
| catalogNumber | An identifier (preferably unique) for the record within the data set or collection |
| recordedBy | A list (concatenated and separated) of names of people, groups, or organizations responsible for recording the original Occurrence |
| recordNumber | An identifier given to the Occurrence at the time it was recorded. Often serves as a link between field notes and an Occurrence record, such as a specimen collector's number. |
| identifiedBy | A list (concatenated and separated) of names of people, groups, or organizations who assigned the Taxon to the subject |
| iucnStatus | IUCN red list category of the taxon at the Global level |
| associatedReferences | A list (concatenated and separated) of identifiers (publication, bibliographic reference, global unique identifier, URI) of literature associated with the Occurrence |
