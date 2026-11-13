# Awesome Planetary Terrain AI

Curated research papers, patents, datasets, and technical resources for **AI-enabled terrain analysis on the Moon and Mars**.

**Scope:** terrain mapping · geomorphology · DEM/DTM · surface roughness · crater detection · landform segmentation · terrain classification · traversability · hazard avoidance · landing-site assessment

> Research-paper selection is restricted to peer-reviewed journals with established standing in planetary science, remote sensing, geoscience, photogrammetry, and robotics. Patent links are provided for technical landscape research; verify legal status in the relevant patent office.

## Moon

### Research papers

| Paper | Journal | Terrain focus |
|---|---|---|
| [Lunar Global Shape and Polar Topography Derived from Kaguya-LALT Laser Altimetry](https://doi.org/10.1126/science.1164146) | *Science* (2009) | Global topography · polar relief · laser altimetry |
| [GLD100: The Near-Global Lunar 100 m Raster DTM from LROC WAC Stereo Image Data](https://doi.org/10.1029/2011JE003926) | *Journal of Geophysical Research: Planets* (2012) | Global DTM · stereo photogrammetry · topography |
| [Gullies and Landslides on the Moon: Evidence for Dry-Granular Flows](https://doi.org/10.1002/jgre.20043) | *Journal of Geophysical Research: Planets* (2013) | Gullies · landslides · crater-wall geomorphology |
| [A New Lunar Digital Elevation Model from the Lunar Orbiter Laser Altimeter and SELENE Terrain Camera](https://doi.org/10.1016/j.icarus.2015.07.039) | *Icarus* (2016) | SLDEM2015 · global DEM · LOLA/TC fusion |
| [Extracting Accurate and Precise Topography from LROC Narrow Angle Camera Stereo Observations](https://doi.org/10.1016/j.icarus.2016.05.012) | *Icarus* (2017) | NAC stereo · high-resolution DTM · photogrammetry |
| [Meter-Scale Topographic Roughness of the Moon: The Effect of Small Impact Craters](https://doi.org/10.1029/2020JE006429) | *Journal of Geophysical Research: Planets* (2021) | Roughness · slopes · impact craters · NAC DTMs |
| [Topographic Knowledge-Aware Network for Automatic Small-Scale Impact Crater Detection from Lunar Digital Elevation Models](https://doi.org/10.1016/j.jag.2024.103831) | *International Journal of Applied Earth Observation and Geoinformation* (2024) | Deep learning · crater detection · DEM |
| [Geological Evidence for Extensive Basin Ejecta as Plains Terrains in the Moon’s South Polar Region](https://doi.org/10.1038/s41467-024-50155-w) | *Nature Communications* (2024) | South Pole · plains mapping · ejecta · landing-site context |
| [Geostratigraphic Mapping of the Intrusive Valentine Domes on the Moon](https://doi.org/10.1029/2024JE008423) | *Journal of Geophysical Research: Planets* (2024) | Geomorphological mapping · domes · spectral classification |
| [LU5M812TGT: An AI-Powered Global Database of Impact Craters ≥0.4 km on the Moon](https://doi.org/10.1016/j.isprsjprs.2024.11.010) | *ISPRS Journal of Photogrammetry and Remote Sensing* (2025) | AI crater catalogue · global mapping · morphometry |
| [Geological Characteristics of Chang’E-6 Landing Area in Micro-Scale Unveiled by New Observation Data](https://doi.org/10.1038/s41467-025-59443-5) | *Nature Communications* (2025) | Chang’E-6 · high-resolution terrain · landing-area geology |
| [LUC-GRAS200: A Global Lunar Crater Catalog at Sub-Kilometer Scale—Construction, Validation and Spatial Characteristics](https://doi.org/10.1029/2025JE009551) | *Journal of Geophysical Research: Planets* (2026) | Deep learning · crater catalogue · morphometry |
| [From Lunar Terrain to Learned Representations: A Comparative Study of Crater Extraction](https://doi.org/10.1016/j.icarus.2025.116909) | *Icarus* (2026) | Representation learning · crater extraction · multi-source fusion |
| [A Dual-Branch Automatic Classification Network for Lunar Simple Crater Degradation Grades Integrating Image and Morphological Parameters](https://doi.org/10.1016/j.icarus.2025.116863) | *Icarus* (2026) | Deep learning · crater degradation · morphology |

### Patents

| Patent | Assignee / focus | Terrain keywords |
|---|---|---|
| [US20210101701A1 — Reconnaissance Rover Designed for Multiple Agile and Autonomous Landings over a Small Body or Moon](https://patents.google.com/patent/US20210101701A1/en) | Airbus Defence and Space | Lunar rover · environment sensing · trajectory update |
| [CN110826174B — Lander-to-Lunar-Surface Distance Determination Using 3D Terrain During Dynamic Landing Simulation](https://patents.google.com/patent/CN110826174B/en) | Lunar landing simulation | 3D terrain · powered descent · landing geometry |
| [US8744126B1 — Morphology-Based Hazard Detection](https://patents.google.com/patent/US8744126B1/en) | BAE Systems Space & Mission Systems | 3D surface · slope hazards · bumps · holes · safe-site map |
| [US8532328B2 — Methods and Apparatus for Planetary Navigation](https://patents.google.com/patent/US8532328B2/en) | Boeing | Surface landmarks · image geometry · planetary localization |

### Datasets, archives, and tools

| Resource | Provider | Terrain / data focus |
|---|---|---|
| [LRO Data Products](https://science.nasa.gov/mission/lro/data-products/) | NASA / PDS | LROC · LOLA · Diviner · polar and regional products |
| [LROC QuickMap](https://quickmap.lroc.asu.edu/) | NASA / Arizona State University | Lunar imagery · topography · landing-site inspection |
| [SLDEM2015 — High-Resolution Lunar Topography](https://pgda.gsfc.nasa.gov/products/54) | NASA Goddard / MIT | LOLA + Kaguya Terrain Camera · global DEM |
| [Moon Foundational Data Products](https://fdp.astrogeology.usgs.gov/fdp/moon/) | USGS Astrogeology | LOLA · SLDEM · LROC · Kaguya · lunar cartography |
| [Lunar Datasets and Services](https://pds-geosciences.wustl.edu/dataserv/moon.html) | NASA Planetary Data System | LRO · Chandrayaan · Kaguya · Apollo · LCROSS |
| [ISRO Science Data Archive](https://www.isro.gov.in/Sciencedata.html) | ISRO / ISSDC | Chandrayaan mission archives · raw and derived data |
| [SELENE / Kaguya Data Archive](https://darts.isas.jaxa.jp/planet/pdap/selene/) | JAXA / DARTS | Terrain Camera · Laser Altimeter · lunar products |
| [LU5M812TGT Crater Catalogue](https://zenodo.org/records/13990480) | ISPRS JPRS research team | AI-derived lunar impact-crater catalogue |

## Mars

### Research papers

| Paper | Journal | Terrain focus |
|---|---|---|
| [Ultrahigh Resolution Topographic Mapping of Mars with MRO HiRISE Stereo Images: Meter-Scale Slopes of Candidate Phoenix Landing Sites](https://doi.org/10.1029/2007JE003000) | *Journal of Geophysical Research: Planets* (2008) | HiRISE stereo · slopes · landing-site safety |
| [Topography of Mars from Global Mapping by HRSC High-Resolution Digital Terrain Models and Orthoimages](https://doi.org/10.1016/j.epsl.2009.11.007) | *Earth and Planetary Science Letters* (2010) | HRSC · global DTM · topographic mapping |
| [Self-Supervised Terrain Classification for Planetary Surface Exploration Rovers](https://doi.org/10.1002/rob.21408) | *Journal of Field Robotics* (2012) | Self-supervised learning · visual terrain classification · rover mobility |
| [Multi-Resolution Digital Terrain Models and Their Potential for Mars Landing Site Assessments](https://doi.org/10.1016/j.pss.2013.06.001) | *Planetary and Space Science* (2013) | Multi-resolution DTM · slope · roughness · landing-site risk |
| [Terrain Classification-Based Rover Traverse Planner with Kinematic Constraints for Mars Exploration](https://doi.org/10.1016/j.pss.2021.105371) | *Planetary and Space Science* (2021) | Deep learning · terrain classes · traversability · path planning |
| [NOAH-H, a Deep-Learning Terrain Classification System for Mars: Results for the ExoMars Rover Candidate Landing Sites](https://doi.org/10.1016/j.icarus.2021.114701) | *Icarus* (2022) | HiRISE · semantic terrain classification · ExoMars |
| [A Hybrid Attention Semantic Segmentation Network for Unstructured Terrain on Mars](https://doi.org/10.1016/j.actaastro.2022.08.002) | *Acta Astronautica* (2023) | Semantic segmentation · attention network · rover navigation |
| [Terrain Classification Using Mars Raw Images Based on Deep Learning Algorithms with Application to Wheeled Planetary Rovers](https://doi.org/10.1016/j.jterra.2023.04.002) | *Journal of Terramechanics* (2023) | Deep learning · terrain recognition · rover mobility |
| [Terrain Classification for Planetary Rovers Using Wireless In-Wheel Sensor Modules and Machine Learning](https://doi.org/10.1002/rob.70124) | *Journal of Field Robotics* (2025) | Wheel–terrain interaction · sensor fusion · ML classification |
| [MarTA-Net: A Terrain-Aware U-Net Enhanced With Convolutional Block Attention Modules for Martian Surface Segmentation](https://doi.org/10.1109/JIOT.2026.3726564) | *IEEE Internet of Things Journal* (2026) | Semantic segmentation · terrain mapping · edge inference |
| [Deep Probabilistic Traversability with Test-Time Adaptation for Uncertainty-Aware Planetary Rover Navigation](https://doi.org/10.1038/s41598-026-40109-1) | *Scientific Reports* (2026) | Traversability · uncertainty estimation · rover navigation |
| [Mapping Scalloped Terrains on Mars at the Meter Scale](https://doi.org/10.1029/2026JE009764) | *Journal of Geophysical Research: Planets* (2026) | Deep learning · CTX · periglacial landform segmentation |

### Patents

| Patent | Assignee / focus | Terrain keywords |
|---|---|---|
| [US20200293057A1 — Terrain Trafficability Assessment for Autonomous or Semi-Autonomous Rover or Vehicle](https://patents.google.com/patent/US20200293057A1/en) | Mission Control Space Services | Image classification · slope · slip prediction · hazard level |
| [US20230245444A1 — Unmanned Aerial System Autonomous Terrain Mapping and Landing Site Detection](https://patents.google.com/patent/US20230245444A1/en) | Autonomous aerial systems | 3D terrain mapping · safe landing · planetary rotorcraft applications |
| [US8744126B1 — Morphology-Based Hazard Detection](https://patents.google.com/patent/US8744126B1/en) | BAE Systems Space & Mission Systems | 3D surface · slope hazards · bumps · holes · safe-site map |
| [US8532328B2 — Methods and Apparatus for Planetary Navigation](https://patents.google.com/patent/US8532328B2/en) | Boeing | Surface landmarks · image geometry · planetary localization |

### Datasets, archives, and tools

| Resource | Provider | Terrain / data focus |
|---|---|---|
| [Mars Foundational Data Products](https://fdp.astrogeology.usgs.gov/fdp/mars/) | USGS Astrogeology | MOLA · HRSC · HiRISE · CTX · DEM inventory |
| [Mars Reconnaissance Orbiter (MRO) PDS Archive](https://pds-geosciences.wustl.edu/missions/mro/default.htm) | NASA Planetary Data System | HiRISE · CTX · CRISM · SHARAD · MRO data products |
| [HiRISE Data and Digital Terrain Models](https://www.uahirise.org/dtm/) | University of Arizona / NASA | Sub-meter imagery · stereo DTMs · local topography |
| [CTX and HiRISE Digital Elevation Models for Exploration Zones](https://doi.org/10.17189/ervc-mr85) | NASA PDS (UCLA / UT Austin) | Stereo DEMs · GeoTIFF · orthoimages · Mars exploration zones |
| [Global CTX Mosaic of Mars](https://murray-lab.caltech.edu/CTX/V01/TilePages/) | Caltech Murray Lab | 5 m/pixel global mosaic · 99.5% coverage · image seam maps |
| [AI4MARS Dataset](https://data.nasa.gov/dataset/ai4mars-a-dataset-for-terrain-aware-autonomous-driving-on-mars) | NASA JPL | Curiosity · Opportunity · Spirit · semantic segmentation labels |
| [Mars Express / HRSC Archive](https://www.cosmos.esa.int/web/psa/mars-express) | ESA Planetary Science Archive | HRSC stereo imagery · topography · orthoimages |
| [USGS Astrogeology Data and Software](https://www.usgs.gov/centers/astrogeology-science-center/science/instruments-data-and-software) | USGS | MOLA · THEMIS · MOC · cartographic tools |

---

## Citation and contribution

- Prefer the publisher DOI or official mission archive when citing or downloading a resource.
- Check dataset licences, version history, coordinate systems, spatial resolution, and label definitions before reuse.
- Contributions should include a DOI, official patent publication number, or mission/archive URL.