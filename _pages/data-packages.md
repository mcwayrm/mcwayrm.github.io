---
layout: archive
title: "Data and Packages"
permalink: /data-packages/
author_profile: true
---
This page provides the publically avaliable datasets that I have created. Feel free to use them at your disposal, but if you would please cite your sources. A citation is provided for each dataframe. Note that some of the data listed below is not created by myself soley. Rather, some are datasets to which I have contributed towards. For these, please acknowledge all parties involved in the development of these datasets. For dataframes used in replicating my previous work, please refer to my [research page](/research/) where I try to provide access to the replication code and data for published work.

Additionally, this page houses statistical packages I have created. None are perfect, so feel free to email me feedback as well as feel free to log an issue on the source code housed on my [GitHub page](https://github.com/mcwayrm).

<!--Include Title, Data updated, Version, Quick description, link to sources to create dataframe, link to access dataframe, Codebook or Metadata as neccessary, suggested citation -->

<!-- Should work to link the data to https://datadryad.org/stash so that I can get citations on the data -->

Dataframes
------

1\. *Cruise Ship Characteristics Information*

  > This dataframe provides a crosssection of the characteristics of cruise ship vessels currently in operation. This covers 525 vessels as the beginning of 2020. This information was collected by combining information from [Wikidepida](https://en.wikipedia.org/wiki/List_of_cruise_ships) and [Vessel Finder](https://www.vesselfinder.com/vessels). The primary application of this data is for cruise tourism or cruise ship activity.
  >  
  > 
  > McWay, Ryan. (2020). *Cruise Ship Characteristics Information*. Version 1. https://github.com/mcwayrm/data_cruise_ship_info/blob/main/cruise_ship_info.csv. Extracted: [Date of Extraction]. \
  > **Keywords:** `Cruise Ships` `Cruise Tourism` `Crew` `Passengers`
  * **[Dataset](https://github.com/mcwayrm/data_cruise_ship_info/blob/main/cruise_ship_info.csv)**
  * **[Codebook](https://github.com/mcwayrm/data_cruise_ship_info/blob/main/cruise_ship_info_metadata.pdf)** 
  * **[DOI](https://www.researchgate.net/deref/http%3A%2F%2Fdx.doi.org%2F10.13140%2FRG.2.2.13528.52488?_sg%5B0%5D=uTNiTKN0BKIHPsJdpiUN-6H4OlVyI97IsaI9c6JNMl5SjGjo1jDz3CbCdXAcxx3LJWcKw4z19ENvi-gnJwg_skpplg.w4v3T6walsSH0crhAPVrTV1T4PFkG9HxCE2hkz6HWro9TDOYsa-73PVpjYqwClg3lV2m_B2xBoSuDBhCx79G4w):** 10.13140/RG.2.2.13528.52488
  * **Last Updated:** Oct. 14th 2020 
  
2\. *Global Ports*

  > This dataframe provides a crosssection of the characteristics of port cities currently in operation. This covers 5,644 port cities globally as of 2020. This information was collected by combining information from [Wikidepida](https://en.wikipedia.org/wiki/List_of_cruise_ships), [Natrual Earth](https://www.naturalearthdata.com/downloads/10m-cultural-vectors/ports/) and [Central Intelligence Agency](https://www.cia.gov/library/publications/the-world-factbook/fields/388.html). The primary application of this data is for analyses that involve port level attributes.
  >  
  > 
  > McWay, Ryan. (2021). *Global Ports*. Version 1. https://github.com/mcwayrm/data_port_cities/blob/main/global_ports.dta. Extracted: [Date of Extraction]. \
  > **Keywords:** `Port Cities` `Terminals`
  * **[Dataset](https://github.com/mcwayrm/data_port_cities/blob/main/global_ports.dta)**
  * **[Codebook](https://github.com/mcwayrm/data_port_cities/blob/main/global_ports_metadata.pdf)** 
  * **[DOI](https://www.researchgate.net/publication/348607255_Global_Ports_Metadata):** 10.13140/RG.2.2.17074.43208
  * **Last Updated:** Jan. 19th 2021 
  
<!--
3. *Cruise Ships Activity at Port*

  > This dataframe estimates cruise ship activity by matching cruise ship GPS locations to port city geocodes within a 15 KM radius. The panel covers XX ports in XX countries globally from 2009 - 2019. Port Geocodes are a combination of ... three main sources... geocoded through [Google Geocoding API](https://developers.google.com/maps/documentation/geocoding/overview). Cruise ship GPS acitvity was estimated through [Sail WX's](https://www.sailwx.info/shiptrack/) metadata.
  > 
  >
  > McWay, Ryan. (2020). *Cruise Ship Activity at Port*. Version 1. [URL]. Extracted: [Date of Extraction]. \
  > **Keywords:** `Ports` `Cruise Ships` `Global` `AIS`
  * **[Dataset]()**
  * **[Codebook]()** 
  * **Last Updated:** 
  
-->

<!--
4. *Tornado Activity at the Metropolitian Statistical Area in the United States*
 
  > Combination of NOAA National Weather Service tornado information and MSA geographic polygons. Aggregated to the annunal level, estimates the tornado activity for all 6 categories at the MSA level from 1950 to 2018. This is useful for studying tornado impacts at the MSA level
  >  
  >
  > Citation: include Jesse Antilla-Hughes
  > **Keywords:** `Tornadoes` `MSA` `Natural Disaster` `United States`
  * **[Dataset]()**
  * **[Codebook]()** 
  * **Last Updated:**
  
  -->
 
<!--
*Forca a Comunidade e Crincas (FCC)*
 
  > This is the publically avaliable dataset for the "Strengthing Communities and Children" (FCC) dataset conducted by [Dean Yang](https://sites.lsa.umich.edu/deanyang/) and his team starting in 2016 to present. As a member of his team, starting in 2020, I helped develop parts of this publically avaliable dataset. It monitors an RCT of HIV testing and various humanitrian aid related programs in Mozambique following the evaluation of the U.S.'s [PEPFAR](https://www.hiv.gov/federal-response/pepfar-global-aids/pepfar) program to address HIV/AIDS in Sub-Saharran Africa. Additionally, it measures the impacts of Cyclone Idai and Covid-19's impact on affected study areas.
  >  
  >
  > Citation
  > **Keywords:** `FCC` `HIV/AIDS` `Cyclone Idai` `Covid-19` `Mozambique`
  * **[Dataset](fordschool.umich.edu/mozambique-research)**
  * **[Codebook]()** 
  * **Last Updated:**
  

*Earnings Management for European Firms*
  Talk with Paolo about highlighting this
  >  and the data concerning board features, including the information regarding remuneration, was manually collected from the Annual Report of Corporate Governance published by the Spanish Stock Exchange Commission
  
  -->
  
  


<!--
Statistical Packages
------
-->

<!-- 
*leebounds2*
  > Stata package for lee bounds
  > 
  >
  > Citataion
  > **Keywords:** `Lee Bounds` `Continous Variable` `STATA`
  * **[Documentation]**
  * **[Slides]**
  * **[Source Code]**
  * **Last Updated:** 



*boundbutunbroken*
  > R package for lee bounds, manski bounds, oster bounds 
  > 
  >
  > Citation
  > **Keywords:** `Lee Bounds` `Manski Bounds` `Oster Bounds` `R`
  * **[Documentation]**
  * **[Slides]**
  * **[Source Code]**
  * **Last Updated:** 
  

-->
 
