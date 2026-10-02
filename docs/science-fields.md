# Find your field in eeeearth

Each module has a primary field so researchers and contributors can find the right project. A second field names a useful specialization. These labels describe the module's subject; they do not certify that every feature implements a published scientific model. The [Earth systems guide](earth-systems/README.md) shows current and planned behavior.

| Module | Common field | Research field and focus |
| --- | --- | --- |
| [eeeearth](https://github.com/eeeearth/eeeearth) | Earth systems | Earth system science and ecological modeling; joins local scene processes. |
| [treeeees](https://github.com/eeeearth/treeeees) | Plants | Plant biology (botany) and plant functional ecology; plant form and species traits. |
| [beeees](https://github.com/eeeearth/beeees) | Animals | Zoology and animal behavior (ethology); species traits and seasonal actions. |
| [breeeeze](https://github.com/eeeearth/breeeeze) | Weather | Atmospheric science, especially meteorology and climatology; local weather and regional profiles. |
| [seeeeds](https://github.com/eeeearth/seeeeds) | Ecosystems | Population and community ecology; habitat suitability, food webs and population state. |
| [tweeeets](https://github.com/eeeearth/tweeeets) | Nature sounds | Bioacoustics and soundscape ecology; animal calls and weather sound. |
| [speeeecies](https://github.com/eeeearth/speeeecies) | Species records | Biodiversity informatics and taxonomy; contributor records, source attribution and validation. |
| [deeeecomp](https://github.com/eeeearth/deeeecomp) | Living soil | Soil science, soil ecology and biogeochemistry; soil state, decay and nutrient cycling. |
| [fungeeee](https://github.com/eeeearth/fungeeee) | Fungi | Mycology and fungal ecology; fungal records and root-associated networks. |
| [licheeeens](https://github.com/eeeearth/licheeeens) | Lichens | Lichenology; planned lichen records and traits. |
| Bryophytes (module pending) | Mosses and liverworts | Bryology; planned separate records and traits. |
| [geeeeo](https://github.com/eeeearth/geeeeo) | Rocks and landforms | Geology and geomorphology; rocks, bedrock and soil parent material. |
| [streeeam](https://github.com/eeeearth/streeeam) | Live broadcast | Science communication and broadcast engineering; delivers the scene and commentary. |

The public `weeee` repository has no stated scientific scope yet, so it has no field label.

## Places to start

These are field entry points, chosen because their professional societies, research centers or data programs provide definitions and working examples. They are orientation resources, rather than endorsements or claims about the code.

| Field | Starting points |
| --- | --- |
| Earth system science and ecology | [NASA Earth System Science Research](https://science.nasa.gov/earth-science/research/), [Ecological Society of America](https://esa.org/about/) |
| Plant biology | [American Society of Plant Biologists](https://aspb.org/about/), [Smithsonian Botany research](https://naturalhistory.si.edu/research/botany/research) |
| Animal behavior | [Animal Behavior Society](https://www.animalbehaviorsociety.org/web/about-mission.php), its [teaching introduction](https://www.animalbehaviorsociety.org/web-final-download/Committees/ABSEducation/laboratory-exercises-in-animal-behavior/laboratory-exercises-in-animal-behavior-introduction.html) |
| Weather and climate | [American Meteorological Society glossary](https://glossary.ametsoc.org/) |
| Species records | [GBIF biodiversity data guide](https://docs.gbif.org/guide-publishing-survey-data/en/), [Smithsonian natural history collections](https://collections.nmnh.si.edu/) |
| Bioacoustics | [Cornell Center for Conservation Bioacoustics](https://www.birds.cornell.edu/ccb/) |
| Soil and nutrients | [Soil Science Society of America](https://www.soils.org/about-society), [USDA soil profile guide](https://www.nrcs.usda.gov/resources/education-and-teaching-materials/a-soil-profile) |
| Fungi | [British Mycological Society](https://www.britmycolsoc.org.uk/about.html) |
| Lichens and bryophytes | [British Lichen Society](https://britishlichensociety.org.uk/the-society/introduction), [British Bryological Society](https://www.britishbryologicalsociety.org.uk/the-society/) |
| Rocks and landforms | [Geological Society of America](https://www.geosociety.org/), [USGS soil formation overview](https://www.usgs.gov/publications/soil-formation-chapter-6) |
| Science communication | [AGU Sharing Science](https://www.agu.org/Learn) |

For broader reading, [*Principles of Terrestrial Ecosystem Ecology*](https://link.springer.com/book/10.1007/978-1-4419-9504-9) connects climate, geology, soils, plants and ecosystem processes. [*Ecology: From Individuals to Ecosystems*](https://bcs.wiley.com/he-bcs/Books?action=index&bcsId=12185&itemId=1119279356) covers populations and communities. [*Introduction to Fungi*](https://www.cambridge.org/core/books/introduction-to-fungi/B3BC3E8F4017DBE4C804BDE80DE77B23) introduces fungal biology and ecology.

## Agreed scope direction: lichens, bryophytes and soil crusts

The original `licheeeens` plan groups lichens, mosses, liverworts and biological soil crusts. Lichens belong to lichenology; mosses and liverworts belong to bryology. A biological soil crust is a community that can also contain cyanobacteria, algae and fungi, according to [USGS biocrust research](https://www.usgs.gov/centers/southwest-biological-science-center/science/biological-soil-crust-biocrust-science?field_partner_type_target_id=141710&page=4).

**Approved direction:** `licheeeens` owns lichen species and lichen-specific traits. Bryophytes have a separate planned module; its name and implementation remain open. `seeeeds` owns biocrust as a community relationship, while `deeeecomp` owns its soil effects. This is a scope decision, with implementation work still to follow. `geeeeo` supplies parent material and rock context to `deeeecomp`, which owns living soil state.
