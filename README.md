# RRID
RRID is a repository that includes the resources for the research on infectious disease. Majority of the resources focus on **Infectious Respiratory Diseases** and **Vector-borne Disease** (i.e. [Influenza](https://en.wikipedia.org/wiki/Influenza), [Mumps](https://en.wikipedia.org/wiki/Mumps), [Dengue](https://en.wikipedia.org/wiki/Influenza) and [Zika](https://en.wikipedia.org/wiki/Zika)). Resources were classified as four parts: **public datasets**, **software packages** , **famious labs**, **risk assessment** and **public codes**. 


# Resources for Infectious Disease

- [Public Datasets](#public-datasets)
- [Software Packages](#software-packages)
- [Famious Labs](#famious-lab)
- [Risk Assessment](#risk-assessment)
- [Public codes](#public-codes)
- [Contributing](#contributing)


## Public Datasets

*Combined dataset*

* [Taiwan National Infectious Disease Statistics System](https://nidss.cdc.gov.tw/en/Default.aspx): provides **weekly** datasets from the Taiwan National Infectius Disease Surveillance System. You can download the case dataset with other infromations such as gentle, country,age group with the interval at 5 years. 

* [Ministry of Health in Singapore](https://www.moh.gov.sg/content/moh_web/home/statistics/infectiousDiseasesStatistics/weekly_infectiousdiseasesbulletin.html): provides **weekly** notifiable disease including Dengue Fever, Acute Upper Respiratory Tract infections, Chickenpox and Acute Diarrhoea in **Singapore**. 

* [Australian Goverment Deaprtment of Health](http://www9.health.gov.au/cda/source/cda-index.cfm): provides **monthly** Bloodborne diseases, Gastrointestinal diseases, Other bacterial infections, Quarantinable diseases, Sexually transmissible infections, Vaccine preventable diseases, Vectorborne diseases and Zoonoses at **state level**, as well as **annual** dataset by age group and sex at **country** level.  

* [Project Tycho](http://www.tycho.pitt.edu/): currently including data from all weekly notifiable disease reports for the **United States** dating back to 1888. For the level 2 dataset, the project provides an API (detailed document is [here](http://www.tycho.pitt.edu/api_help.php)). I write some rough [codes](https://github.com/Spatial-R/IDDC) to download the dataset using R software. You can also use the codes in [lgautier/project-tycho-utilities](https://github.com/lgautier/project-tycho-utilities).

* [Morbidity and Mortality Weekly Report (MMWR)](https://wonder.cdc.gov/mmwr/mmwrmorb.asp?mmwr_year=2017&mmwr_week=06): data for selected nationally notifiable diseases reported by the 50 states, New York City, the District of Columbia, and the U.S. territories at **week** interval.

* [Department of Health in Hongkong](http://www.chp.gov.hk/en/dns_submenu/10/26.html): includes **monthly** notifiable infectious diseases, Sentinel surveillance (**weekly** number of hospital admission episodes of hand, foot and mouth disease (HFMD)) and **monthly** antibiotic resistance surveillance. 

*Dengue*

* [DengueNet](http://apps.who.int/globalatlas/default.asp):  a standard platform for sharing current surveillance data in order to detect and monitor incidence and trends of dengue and DHF.

* [Dengue in Southeast Asia](http://www.tycho.pitt.edu/dev/pnas/): **monthly** dengue surveillance data collected from eight **countries** in Southeast Asia for the period 1993-2010. These data have been integrated from various sources, as described in detail in the supplementary material of the scientific paper of this study in the paper [Region-wide synchrony and traveling waves of dengue across eight countries in Southeast Asia Supporting Information](http://www.pnas.org/content/suppl/2015/10/01/1501375112.DCSupplemental).

* [Dengue in Brazil](http://www.tycho.pitt.edu/dev/dengue_bwc/):  **weekly** number of dengue cases for cities in Brazil hosting games or football teams during the FIFA 2014 World Cup (from 2001 to 2014). These data have been used for the paper [Risk of Dengue for Tourists and Teams during the World Cup 2014 in Brazil](http://journals.plos.org/plosntds/article?id=10.1371/journal.pntd.0003063).

* [Dengue in Peru and Puerto Rico](http://dengueforecasting.noaa.gov/): this dataset was used to design an infectious disease forecasting project with the aim of galvanizing efforts to predict epidemics of dengue. Other information of those two cities including Population, Satellite Precipitation and Satellite Vegetation were in the website. 

* [DengueCasesMalaysia](https://github.com/rengaray/DengueCasesMalaysia): dengue **weekly** dataset in **Malaysia** at state level from 2011 to 2015. 

* [Dengue in Guangdong](http://gdwst.gov.cn/a/sc/jikongguanli/index-2.html): **weekly** dataset at country level. In additional, import or local information is also included.

* [Chikungunya](http://www.tycho.pitt.edu/dev/chikungunya/): **weekly** reports of Chikungunya cases and deaths provided by the Pan American Health Organization ([PAHO](http://www.paho.org/hq/index.php?option=com_topics&view=article&id=343&Itemid=40931)) and the French Agence régionale de santé (ARS) at **country** level.


*FLU*

The dataset resources for flu have been aggregated in  the [res4flu](https://github.com/caijun/res4flu) repository of [Caijun](https://github.com/caijun). Here, we just list some famious resources and then add some additional resources.

* [fuID](http://www.who.int/influenza/surveillance_monitoring/fluid/en/):  collect defined epidemiological indicators and data on seasonal and pandemic Influenza from **national**, **regional** and **global systems** at **weekly** level. 

 * [FluView](http://gis.cdc.gov/grasp/fluview/fluportaldashboard.html): national and regional level outpatient illness and viral surveillence aggregated at the [regional](https://www.hhs.gov/iea/regional/) and national levels. Package [cdcfluview](https://github.com/hrbrmstr/cdcfluview) can download the dataset with information about **age-group**. 
 
 * [ILINet](http://gis.cdc.gov/grasp/fluview/main.html): influenza-like illness (ILI) activity level indicator determined by data reported to ILINet.
 
* [FluWeb Historical Influenza Database](http://influenza.sph.unimelb.edu.au/): free access to a number of rare and valuable sources of data concerning past influenza outbreaks.

* [EMPRES Global Animal Disease Information System (EMPRES-i)](http://empres-i.fao.org/eipws3g/): provides access to the H7N9 and H5N1case dataset with geographic infromation and reporting date. 

* [Influenza activity for European](http://ecdc.europa.eu/en/healthtopics/seasonal_influenza/epidemiological_data/Pages/influenza_activity_EU_EEA_activity_maps.aspx): influenza activity surveillance for the countries in the European at **weekly** level. Period: 2009 to now

* [FluTrackers.com](https://flutrackers.com/forum/forum/china-h7n9-outbreak-tracking/143874-flutrackers-2013-17-human-case-list-of-provincial-ministry-of-health-government-confirmed-influenza-a-h7n9-cases-with-links): 2013-17 Human Case List of Provincial/Ministry of Health/Government Confirmed Influenza A(H7N9) Cases. Addtional informations such as **gentle**, **age**, **city** or **province**, and clinical condition (death or not).  

* [World Animal Health Information Database](http://www.oie.int/wahis_2/public/wahid.php/Diseaseinformation/WI): provides access to all data (including avian influenza) held within OIE's new World Animal Health Information System from 2016-02-06. Besides, you can gather the information about the follow-up report. 

*Tools*

* [DELPHI](https://github.com/cmu-delphi/delphi-epidata): contains influenza data from **FluView**, **ILINet**, **Google Flu Trends**, **Twitter Stream**, **Wikipedia Access Logs**, and Outpatient ILI from Taiwan's National Infectious Disease Statistics System at [hexchotomy region](https://en.wikipedia.org/wiki/Regions_of_Taiwan#Hexchotomy) .

* [Dengue-data-stub](https://github.com/reichlab/dengue-data-stub): download time-series for Dengue in **Thailand**, however, the package is still under development.

*Vaccination*

* [Immunization schedule for countries](http://apps.who.int/immunization_monitoring/globalsummary/diseases): immunization schedule by disease or country, which is collected by the WHO. 

## Software Packages

* [R0](https://cran.r-project.org/web/packages/R0/index.html): estimation of R0 and real-time reproduction number from epidemics.

* [EpiEstim](https://cran.r-project.org/web/packages/EpiEstim/index.html): implements a Bayesian approach for quantifying transmissibility (instantaneous and case reproduction numbers) over time during an epidemic([Cori et al. (AJE, 2013)](https://academic.oup.com/aje/article/178/9/1505/89262/A-New-Framework-and-Software-to-Estimate-Time)). Examples are [here](http://spatial-r.com/en/2015/07/R0/).

* [EpiDynamics](https://cran.r-project.org/web/packages/EpiDynamics/index.html):  implements the dynamic models written in the book : [Modeling Infectious Diseases in Humans and Animals](http://www.amazon.com/Modeling-Infectious-Diseases-Humans-Animals/dp/0691116172/). You also can found the [web introduction](http://www.modelinginfectiousdiseases.org/) to this book. 

* [EpiModel](https://cran.r-project.org/web/packages/EpiModel/index.html): mathematical modeling of infectious disease with deterministic compartmental models, stochastic agent-based models, and stochastic network models.

* [episerve](https://sourceforge.net/projects/episerve/):  web-interface aiming to make the R tools for disease outbreak analysis available to to non-specialists. It relies on **epibase** for data structure and graphics, is integrated with **Epicollect** for data collection using mobile devices, and uses **EpiEstim** for reproduction number estimation. 

* [pomp](https://cran.r-project.org/web/packages/pomp/index.html): provides facilities for implementing partially observed Markov process(POMP) models, simulating them, and fitting them to time series data by a variety of frequentist and Bayesian methods.  The website for pomp is [here](http://kingaa.github.io/pomp/). Famious but hard to use. 

* [panelPomp](https://github.com/cbreto/panelPomp): R package for statistical inference using panel (longitudinal data) POMPs (Partially Observed Markov Processes). Example is [here](http://kingaa.github.io/sbied/contacts/contacts.html): dynamic variation in sexual contact rates

* [bayessir](https://github.com/vnminin/bayessir): bayesian inference for hidden Markov Susceptible-Infected-Removed (SIR) model. Method was in the paper: Predictive modeling of cholera outbreaks in Bangladesh, Annals of Applied Statistics, 10, 575 – 595.

* [debinfer](https://github.com/pboesu/debinfer): bayesian inference for dynamical models of biological systems. Document: [Bayesian inference for dynamical models of biological systems in R](https://arxiv.org/abs/1605.00021).

* [WeibullHM](https://github.com/zhifeiyan/WeibullHM): fitting a hierarchical Bayesian Weibull hidden Markov model via a forward filtering backward sampling MCMC algorithm. Document will come soon.  

* [BDAepimodel](https://github.com/fintzij/BDAepimodel): tractable fitting of stochastic epidemic models via Bayesian data augmentation. Detailed vignette to the package as well as some examples of fit the dynamic model with bayesian aspect using the pomp package is also provided. 

* [ABSEIR](https://github.com/grantbrown/ABSEIR): spatial SEIR modeling via Approximate Bayesian Computation. Analytical techniques is more completely described in [this paper](https://github.com/grantbrown/EARNMC/blob/master/manuscript-preprint/r0Methods.pdf), as well as in his [thesis work: Application Of Heterogeneous Computing Techniques To Compartmental Spatiotemporal Epidemic Models](http://ir.uiowa.edu/etd/1554/).

* [SimInf](https://github.com/stewid/SimInf):  provides an efficient and flexible framework for data-driven stochastic disease spread modelling that integrates within-herd infection dynamics as continuous-time Markov chains and livestock movements between herds as scheduled events. [Website](http://siminf.org/).

* [IDSpatialStats](https://github.com/HopkinsIDD/IDSpatialStats): present an interpretable measure of spatial clustering, τ, which can be understood as a measure of relative risk. 

* [GI](https://github.com/davidchampredon/GI):  calculate generation interval distributions. Document: [Intrinsic and realized generation intervals in infectious-disease transmission](https://www.ncbi.nlm.nih.gov/pubmed/26674948).

* [rEDM](https://github.com/ha0ye/rEDM): empirical dynamic modeling based on attractor reconstruction. Document: [Nonlinear Tools for a Nonlinear World: Applications of Empirical Dynamic Modeling to Marine Ecosystems](https://github.com/ha0ye/phd_thesis).  This method was also used to test the threshold value for envrionmental factors on infectious disease, seeing paper([Global environmental drivers of influenza](http://www.pnas.org/content/113/46/13081.full)).

* [rAedesSim](https://github.com/alfcrisci/rAedesSim):  population mosquito modeling. 

*Climatic*

* [riem](https://mirrors.tuna.tsinghua.edu.cn/CRAN/web/packages/riem/index.html): allows to get weather data and air pollutant data from Automated Surface Observing System (ASOS) stations (**airports**) in the whole world thanks to the [Iowa Environment Mesonet website](https://mesonet.agron.iastate.edu/request/download.phtml?network=IN__ASOS). 

* [GSODR](https://mirrors.tuna.tsinghua.edu.cn/CRAN/web/packages/GSODR/index.html): global summary daily weather data in R. Provides automated downloading, parsing, cleaning, unit conversion and formatting of Global Surface Summary of the Day (GSOD) weather data from the from the USA National Climatic Data Center (NCDC). [Vignettes](https://mirrors.tuna.tsinghua.edu.cn/CRAN/web/packages/GSODR/vignettes/GSODR.html). 

* [rnoaa](https://mirrors.tuna.tsinghua.edu.cn/CRAN/web/packages/rnoaa/index.html): lient for many 'NOAA' data sources including the 'NCDC' climate '[API](https://www.ncdc.noaa.gov/cdo-web/webservices/v2)'. In addition, we have an interface for 'NOAA' sea ice data, the 'NOAA' severe weather inventory, 'NOAA' Historical Observing 'Metadata' Repository ('HOMR') data, 'NOAA' storm data via 'IBTrACS', tornado data via the 'NOAA' storm prediction center

* [rcaaqs](https://github.com/bcgov/rcaaqs):  faciliate the calculation of air quality metrics according to Canadian Ambient Air Quality Standards. 

## Risk Assessment

* [Vector-borne Disease Airport Importation Risk Tool](http://www.vbd-air.com/): using the method published in the nature journal: [The global distribution and burden of dengue](http://www.nature.com/nature/journal/v496/n7446/full/nature12060.html) and [Web-based GIS: the vector-borne disease airline importation risk (VBD-AIR) tool](http://ij-healthgeographics.biomedcentral.com/articles/10.1186/1476-072X-11-33).

* [Epigrass](http://pythonhosted.org/epigrass/index.html): pigrass is a framework for the construction and simulation of complex network epidemiology models. 

* [heemod](https://github.com/pierucci/heemod): models for health economic evaluation. Features: accounting for time-dependency, probabilistic uncertainty analysis, and deterministic sensitivity analysis. Most of the analyses presented in [Decision Modelling for Health Economic Evaluation](https://www.amazon.com/Decision-Modelling-Economic-Evaluation-Handbooks/dp/0198526628) can be performed with heemod.

* [Assessing the Impact of OCV Use on Protection and Epidemic Risk](http://iddynamics.jhsph.edu/apps/shiny/ocvtools/): This tool estimates the proportion of the population directly protected from vaccine, the number of cases prevented (direct + indirect effects), and the final number expected to be infected for a given population size and vaccine coverage (required inputs). 

## Public Codes

* [chikungunya_simulation](https://github.com/akshayjin/chikungunya_simulation): a generalized ABM which captures these interactions at a micro-scale by explicitly modeling each human and mosquito to predict the complex trajectory of the infection. The model has been integrated with GIS, census and climate data to effectively model the host and agent behavior and as a proof of concept, is also trained and validated using 2013-14 Caribbean Chikungunya epidemic data. 

* [Heterogeneity, Mixing, and the Spatial Scales of Mosquito-Borne Pathogen Transmission](https://github.com/TAlexPerkins/PlosCompBio_2013): Perkins TA, Scott TW, Le Menach A, Smith DL (2013) Heterogeneity, Mixing, and the Spatial Scales of Mosquito-Borne Pathogen Transmission. PLoS Computational Biology 9(12): e1003327. 

* [Socially structured human movement shapes dengue transmission despite the diffusive effect of mosquito dispersal](https://github.com/bcreiner/socially_structured): Reiner, R.C. Jr, Stoddard, S.T., Scott, T.W. (2014) Socially structured human movement shapes dengue transmission despite the diffusive effect of mosquito dispersal. Epidemics 6: 30-36.

* [Model-based projections of Zika virus infections in childbearing women in the Americas](https://github.com/TAlexPerkins/Zika_nmicrobiol_2016): Perkins TA, Siraj AS, Ruktanonchai CW, Kraemer MUGK, Tatem AJ. (2016) Model-based projections of Zika virus infections in childbearing women in the Americas. Nature Microbiology 1:16126.

* [A Comparative Study of Techniques for Estimation and Inference of Nonlinear Stochastic Time Series](https://github.com/dbarrows/nls-forecast): Masters thesis on nonlinear stochastic time series forecasting, including Basic particle filter, Iterated Filtering 2, S-maps and Spatiotemporal Epidemics. 

* [Controlling dengue with vaccines in Thailand](https://github.com/tjhladish/dengue):  methods was published in the [Projected Impact of Dengue Vaccination in Yucatán, Mexico](http://journals.plos.org/plosntds/article?id=10.1371/journal.pntd.0004661) and [Controlling Dengue with Vaccines in Thailand](http://journals.plos.org/plosntds/article?id=10.1371/journal.pntd.0001876) . Codes is [Here](http://www.cs.unm.edu/~dlchao/dengue/index.html).

* [Bayesian Inference for Infectious Disease Transmission Models Based on Ordinary Differential Equations](https://github.com/weidemannf/thesis_code): dissertation thesis on Bayesian parameter inference for dynamic infectious disease modelling: rotavirus in Germany. 

* [The Impact of a One- versus Two-Dose Oral Cholera Vaccine Regimen in Outbreak Settings: A Modeling Study](https://github.com/HopkinsIDD/singledose-ocv): Azman AS, Luquero FJ, Ciglenecki I, Grais RF, Sack DA, Lessler J (2015) The Impact of a One-Dose versus Two-Dose Oral Cholera Vaccine Regimen in Outbreak Settings: A Modeling Study. PLoS Med 12(8): e1001867. 

* [Household Transmission of Influenza A and B in a School-based Study of Non-Pharmaceutical Interventions](https://github.com/scottyaz/hhl-flu-pitt): Andrew S. Azman a , James H. Stark b , Benjamin M. Althouse et.al. Household Transmission of Influenza A and B in a School-based Study of Non-Pharmaceutical Interventions, Epidemics, 2013,5, 181-186.

* [Association between Severity of MERS-CoV Infection and Incubation Period](): Victor Virlogeux, Minah Park, Joseph T. Wu, Benjamin J. Cowling (2016). Association between Severity of MERS-CoV
Infection and Incubation Period. Emerging Infectious Diseases, 22(3): 526-528.

* [pomp-astic inference methods for epidemic models illustrated on German rotatvirus surveillance data](https://github.com/theresasophia/pomp-astic): calculate the mle with iterated filtering using the pomp package for what is refered to as Model StSt+ in the manuscript.

## Famious Lab

* [DELPHI](http://delphi.midas.cs.cmu.edu/): Developming the theory and practice of epidemiological forecasting. [Github](https://github.com/cmu-delphi/). Publicly Available Tools: Epidemiological time series visualizer ([EpiVis](http://delphi.midas.cs.cmu.edu/epivis/epivis.html)), API to automatically updated epidemiological data sources ([Epi-Data](https://github.com/cmu-delphi/delphi-epidata)) and Visual comparison of scored submissions to CDC's Predict the Flu Challenge([FluScores](http://delphi.midas.cs.cmu.edu/misc/fluscores/)).

* [Infectious Disease Dynamics Group at Johns Hopkins University](http://www.iddynamics.jhsph.edu/projects): run the gamut of the study of disease dynamics, from original data collection, to methodological research, to policy engagements. [Github](https://github.com/HopkinsIDD). 

* [Koelle Research Group](https://sites.duke.edu/koelle/2016/11/07/the-koelle-lab-website-has-a-new-entry/): focuses on using mathematical models and statistical approaches to better understand the ecological and evolutionary dynamics of infectious diseases.

* [Dennis L. Chao](http://www.cs.unm.edu/~dlchao/): develop computer simulation models of infectious disease outbreaks such as influenza, dengue and cholera. Open analysis codes on dengue and cholera. 
 
* [Vladimir N. Minin](http://www.stat.washington.edu/vminin/): Predictive modeling of cholera outbreaks in Bangladesh, Latent continuous time Markov chains for partially-observed multistate disease processes and Likelihood-based inference for partially observed multi-type Markov branching processes. Package:[bayessir](https://github.com/vnminin/bayessir).

* [Edward Ionides](http://dept.stat.lsa.umich.edu/~ionides/):  Time series analysis with applications to ecology, epidemiology, health economics, cell motion and neuroscience. Methodological work on inference for partially observed stochastic dynamic systems.  Tutorials and slides on time series analysis  is usefull. 
 
* [Aaron A. King](http://kinglab.eeb.lsa.umich.edu/king/software): sophisticated mathematical, computational, and statistical tools to advance theoretical ecology and evolution on infectious disease. 
 
* [CHICAS](http://chicas.lancaster-university.uk/projects/): centre for the health informatics, computing and statsistics. [Campylobacter Transmission](http://enigmaproject.org.uk/), [Inference for Vector-borne Diseases](http://chicas.lancaster-university.uk/projects/vector_borne_disease.html)[[GIthub](https://github.com/chrism0dwk?tab=repositories)], [Modelling the Evolution of Seasonal Influenza](http://chicas.lancaster-university.uk/projects/seasonal_influenza_modelling.html), 
  
* [Perkins Lab](http://perkinslab.weebly.com/): use mathematical models to answer questions about the transmission and control of infectious diseases. Our work primarily focuses on dengue, Zika, chikungunya, malaria, and other vector-borne diseases. 
  
* [seeg lab](spatial ecology and epidemiology group): spatial ecology and epidemiology group in Department of Zoology, University of Oxford. [movement](https://github.com/SEEG-Oxford/movement): analysis of movement data in disease modelling and mapping, [seegMBG](https://github.com/SEEG-Oxford/seegMBG): contain a number of miscellaneous functions to streamline model-based geostatistical analyses as applied in several SEEG projects, [seegSDM](https://github.com/SEEG-Oxford/seegSDM): Streamlined Functions for Species Distribution Modelling in the SEEG Research Group. 
 
* [SpeLL](https://github.com/lgautier/project-tycho-utilities):  concerned with baseline works on the denominator, i.e. the number of hosts, which are key spatial variables used in most epidemiological models, and we actively work on the improvement of large-scale data sets on the distribution of human and livestock populations. A second focus of active research is the spatial epidemiology of avian influenza, a major disease of poultry with a strong zoonotic potentia.
 
* [Wan Yang](http://www.columbia.edu/~wy2202/Research.html): applies mathematical modeling and Bayesian inference methods to study the transmission dynamics of infectious diseases such as influenza, Ebola, and measles. how environmental factors influence the transmission of influenza, its seasonality, and the underlying mechanisms. 
  
## Contributing

Your contributions are always welcome! If you have additional resources on infectious disease, please open an issue in [here](https://github.com/Spatial-R/RRID/issues).

## License

This work is distributed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License - [CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/legalcode).

