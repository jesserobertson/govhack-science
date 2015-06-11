# Science-flavoured data sources

## Interactive online portals

Data portals can quickly give you access to a range of data sets, usually by searching through their metadata or spatially/temporally. You can download these in a number of formats. Generally the focus of these portals is on national-scale datasets.

- [**Integrated Marine Observing System**](https://imos.aodn.org.au/imos123/home) - data portal for all marine data available from universities, DSTO, CSIRO and the IMOS system itself. Treasure trove of info: includes salinity, oxygen, temperature etc for oceans, radar data, AUV stuff etc.

- [**Atlas of Living Australia**](http://ala.org.au) - contains a massive amount of biodiversity data collated by [Australian scientific communities](http://www.ala.org.au/about-the-atlas/atlas-background/atlas-partners/partner-profiles/) and [citizen scientists](http://www.ala.org.au/get-involved/citizen-science/). Tons of geospatially located species occurences, info on those species, apis for uploading data etc etc etc.

- [**AuScope Earth Data Portal**](http://portal.auscope.org) - contains a huge variety of Australia-wide geospatial and geoscientific datasets from the CSIRO, Geoscience Australia, the state Geological Surveys and several Australian universities. If you're interested in accessing the API's, a how-to for the [mine location/mineral occurrence data is here](https://twiki.auscope.org/wiki/CoreLibrary/ERMLGovHackOerview) and the [borehole data here](https://twiki.auscope.org/wiki/CoreLibrary/NVCLGovHackOverview).

- [**Terrestrial Ecosystem Research Network (TERN)**](http://portal.tern.org.au) - a wide variety of ecosystem datasets including plants, animals, ecological dynamics, fresh water and esturine ecosystems, [soils](http://portal.tern.org.au/search#!/q=%22land%20surface%22%20OR%20soil*%20OR%20erosion%20OR%20sedimen*%20OR%20land*%20OR%20topography%20OR%20%22frozen%20AND%20land%22%20OR%20%22soil%20AND%20salinity%22/p=1/tab=collection/num=10), [agriculture](http://portal.tern.org.au/search#!/q=%28agricultur*%20OR%20farm%20OR%20pastoral%20OR%20pastur*%29%20OR%20%28graz*%20OR%20crop*%20OR%20irrigation%29%20OR%20%28conserv*%20OR%20manage*%29/p=1/tab=collection/num=10), [oceans and coasts](http://portal.tern.org.au/search#!/q=%28coast*%20OR%20ocean*%29%20OR%20marine%20OR%20beach%20OR%20bathmetry%20OR%20tide*%20OR%20aqua*%20OR%20sea*%20OR%20saltwa*%20OR%20storm%20OR%20shoreline%20OR%20wave*%20OR%20salinity/p=1/tab=collection/num=10), [climate](http://portal.tern.org.au/search#!/q=climate%20OR%20%28index%20OR%20indice*%29%20OR%20anomaly%20OR%20oscillation%20OR%20pattern/p=1/tab=collection/num=10), [human-nature interaction](http://portal.tern.org.au/search#!/q=%28human*%20OR%20%22human%20impact%22%29%20OR%20survey%20OR%20boundaries%20OR%20economi*%20OR%20productio*%20OR%20behav*%20OR%20infrastructure%20OR%20%22land%20management%22%20OR%20harzard*/p=1/tab=collection/num=10) and [energy, water and gas](http://portal.tern.org.au/search#!/q=energy%20OR%20gas%20OR%20flux*%20OR%20atmospher*%20OR%20cloud%20OR%20air%20OR%20Pheno*%20OR%20radia*%20OR%20vapo*%20OR%20wind*%20OR%20precipitation%20OR%20rain/p=1/tab=collection/num=10).
 
- [**Australian Soil Resource Information System (ASRIS)**](http://www.asris.csiro.au/#) - provides access to national soils and landform maps and sample data right across Australia. There's also a [soil map iOS app](http://www.csiro.au/en/Research/AF/Areas/Sustainable-farming/Decision-support-tools/SoilMapp) that highlights the ways this data could be used.

## General data portals

These portals allow you to query a wider set of data sources than the portals above, although your result might be a lot noisier than for the domain-specific portals above. Many of these are also available in the portals above, but there's a lot of specialized local datasets that might be useful (the portals above focus on national-scale datasets).

- [**Reserch Data Australia**](https://researchdata.ands.org.au/) - the big kahuna - is an index of most of the research data that is publically available from Australian institutions. Just make sure you're mostly using government data (agencies like GA, CSIRO etc are part of government).

- [**GA's Data and Publications search**](http://www.ga.gov.au/data-pubs) - let's you search Geoscience Australia's extensive catalogue of data, publications, online tools, maps and videos. 

- [**CSIRO Data Access Portal (data.csiro.au)**](http://data.csiro.au) - provides access to data published by CSIRO across a range of disciplines (User Guide, catalog API). It gives access to CC-BY and CSIRO Data License datasets. Diverse subjects - [pulsars](https://data.csiro.au/dap/search?q=Pulsars&p=1&rpp=25&sb=RELEVANCE&dr=all&soud=on) to [viruses](https://data.csiro.au/dap/search?tn=Veterinary%20Virology), [ontologies](http://dx.doi.org/10.4225/08/537452F354E36) to [genomics](https://data.csiro.au/dap/search?q=genomics&p=1&rpp=25&sb=RELEVANCE&dr=all&soud=on), [seabed sediments](https://data.csiro.au/dap/search?q=seabed%20sediments&p=1&rpp=25&sb=RELEVANCE) to [solar radiation](https://data.csiro.au/dap/search?q=solar%20radiation&p=1&rpp=25&sb=RELEVANCE)
There is an API which can be used to access the catalog content, [see here](https://wiki.csiro.au/display/dmsdoc/Web+Services+Interface)

## Others

- [**Geoscience Australia's list of web services**](http://www.ga.gov.au/data-pubs/web-services/ga-web-services) - have an abundance of geological data, including topography, gravity, magnetics, geological maps, hydrological data and more. These are all generally behind Open Geospatial Consortium-compliant web services, so you can easily slurp then into whatever GIS software you might be using ([QGIS](http://www.qgis.org/en/site/) is an excellent free & open-source option here).

- [**WA Department of Parks and Wildlife**](http://www.dpaw.wa.gov.au/plants-and-animals/other-databases) also have a bunch of data related to threatened species and environments, obviously with a WA focus. Most of these are available through SLIP.

- [**Landsat on AWS**](http://aws.amazon.com/public-data-sets/landsat/) - This isn't an Australian Government dataset, but Govhack Perth participants will have access to $200 AWS vouchers so if you want to mash up Australian data with landsat and process it on EC2 then it might be a neat option for projects. There's more info on landsat on [NASA's website here](http://landsat.gsfc.nasa.gov/). Just be aware of the resolution limitations of Landsat - you probably can't see your house from there. 

- [**NASA NEX on AWS**](http://aws.amazon.com/nasa/nex/) - this is a bunch of Earth science datasets which are available on Amazon Web Services. In addition to Landsat, NEX includes global climate projections and analysis, and [MODIS data from NASA](http://modis.gsfc.nasa.gov/). These are also really large datasets but you might be able to do some cool mashups with subsets of these (it's pretty straightforward to just pull out what you need from the data).
