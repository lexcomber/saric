The code and data in this repository allo you to create the interactve webmaps described in 
Comber A, Collins AL, Haro D, Hess T, Smith A, Turner A and Zhang Y (2019). A generic approach for live prediction of agricultural runoff risk: linking parsimonious soil-water models with live weather data APIs in decision tools. *Frontiers* DOI: 10.3389/fsufs.2019.00042

There are four models: 2 catchment scale, 2 field scale, for the Wissey and Teifi catchments. 

# A generic approach for live prediction of the risk of agricultural field runoff and delivery to watercourses: linking parsimonious soil-water-connectivity models with live weather data APIs in decision tools


Alexis Comber<sup>1</sup>, Adrian L. Collins<sup>2</sup>, David Haro<sup>3</sup>,<sup>4</sup>, Tim Hess<sup>3</sup>, Yusheng Zhang<sup>2</sup>, Andrew Smith<sup>5</sup>, Andrew Turner<sup>1</sup>

<sup>1</sup>Leeds Institute for Data Analytics (LIDA) and School of Geography, University of Leeds, Leeds, LS2 9JT, UK,
<sup>2</sup>Sustainable Agriculture Sciences Department, Rothamsted Research, North Wyke, Okehampton EX20 2SB, UK
<sup>3</sup>Cranfield Water Science Institute, Cranfield University, Cranfield, MK43 0AL, UK
<sup>4</sup>Estación Experimental de Aula Dei, Spain
<sup>5</sup>School of Natural Sciences, Bangor University, Bangor, LL57 2DG, UK

* Contact: a.comber@leeds.ac.uk


# Abstract 

This paper describes the development and application of a novel and generic framework for parsimonious soil-water interaction models to predict the risk of agro-chemical runoff. The underpinning models represent two scales to predict runoff risk in fields and the delivery of mobilised pesticides to river channel networks. Parsimonious field and landscape scale runoff risk models were constructed using a number of pre-computed parameters in combination with live rainfall data. The precomputed parameters included spatially-distributed historical rainfall data to determine long term average soil water content and the sensitivity of  land use and soil type combinations to runoff. These were combined with real-time live rainfall data, freely available through open data portals and APIs, to determine runoff risk using  SCS Curve Numbers. The rainfall data was stored to provide antecedent, current and future  rainfall inputs. For the landscape scale model, the delivery risk of mobilised pesticides to the river network  included intrinsic landscape factors. The application of the framework is illustrated for two case studies at field and catchment scales, covering acid herbicide at field scale and metaldehyde at landscape scale. Web tools were developed and the outputs provide spatially and temporally explicit predictions of runoff and pesticide delivery risk at 1km2 resolution. The model parsimony reflects the driving nature of rainfall and soil saturation for runoff risk and the critical influence of both surface and drain flow connectivity for the risk of mobilised pesticide being delivered to watercourses. The novelty of this research lies in the coupling of live spatially-distributed weather data with precomputed runoff and delivery risk parameters for crop and soil types and historical rainfall trends. The generic nature of the framework supports the ability to model the runoff and field-to-channel delivery risk associated with any in-field agricultural application assuming application rate data are available.
