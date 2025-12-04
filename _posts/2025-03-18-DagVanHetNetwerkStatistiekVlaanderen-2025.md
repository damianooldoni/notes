---
title: Dag van het netwerk - Statistiek Vlaanderen
background:
  img: /assets/backgrounds/statistiek2025.jpg
  by: [Deng Xiang](https://unsplash.com/@dengxiangs)
author: Damiano Oldoni
tags: [data, data sharing, open data, 2025, Belgium, Brussels, Flemish Authority, statistics]
toc: true
comments: false
published: true
---

## General

- [Website](https://www.vlaanderen.be/statistiek-vlaanderen/netwerkdag-statistiek-vlaanderen-over-datadeling-op-18-maart-2025)
- Program: See Website
- Organizer: [Statistics Flanders](https://www.vlaanderen.be/en/statistics-flanders)
- Host: [Government of Flanders](https://www.vlaanderen.be/en)
- Founder: [Government of Flanders](https://www.vlaanderen.be/en)
- Date: 18/03/2025

## Workshop 4: Privately held data as source for public statistics

### Use of Strava-data for public statistics

Presenter: [Jasper Truyens](jasper.truyens@sport-vlaanderen) ([Sport Vlaanderen](https://www.sport.vlaanderen/))

2018: routes online. Only downloads data. Flemish Ardennes: highest number of downloads. However, not enough accurate data.

During Covid: implementing ecovisio counters with realtime data (every 15min).
Costs: 6k euro for 3 year for each counter.

From 2020 to 2022: strong decrease. But 2020 was a special year: due to the covide related lockdowns, a lot of people spent more time than usual outside and sport a lot more than the years after.

But what before 2020? But how to compare with pre-covid years? 

From 2022 access to Strava data. Data are anonymized. Data are free of use for Sport Vlaanderen, but they cannot be published.

409OOO users in Flanders in 2024
9800000 bikeactivities in 2024
16000000 walking/run activities in 2024.
Users: only 10% women

The Strava data are important to answer the key question: how many counters do we, Sport Vlaanderen, still have to install to have better statistical representation?

UK's Office for National Staistics built a prediction model to know the use of English natural areas by 

This was the basis of an official collaboration between VSA and Sport Vlaanderen.

The ground truth is the Ecovisio MTB counters (25 counters in Sport Vlaanderen)
Strava data: correlation Strava.Ecovisio
Other data:
- Demographic data
- Meto data
- OpenStreetMap for Point of Interest

The Random Forest Model was the best prediciont model. And the "total trip count" of Strava had the most prediction value

Performance: accuracy is bad in Oudenaarde (more hills and cobbles = higher #road cyclists but lower #MBTers), Roeselare and Lokeren. Very low MTB count values is the main reason for low accuracy.

Some other aspects influencing the performance: kids have no Strava account. Some places are very crowded due to camps for children.

Other aspects to further study:
- the relation with gravel
- What's the factor of the success of a MTB route?
- use of a route is not equal to point counting

Challenges 2025:
- Prediction model further develop for "die-hard" MBTers cycling out of the routes
- Systematic analysis 
- Structural collaboration with 


### Working towards a business-centered vision on data collection

Presenter: [Anita Vaasen-Otten](mailto:amvj.vaasen-otten@cbs.nl) ([Centraal Bureau voor de Statistiek](https://www.cbs.nl/))

What about:
- economy
- society

how does [Centraal Bureau voor de Statistiek](https://www.cbs.nl/) (CBS) get the data?
- Existing public registries: belastingsdienst, KVK, UWV, Kadaster
- Other data sources: scan dta of supermarkets and info about energy consumption of energy leveranciers
- Self collected data via questionnaries to companies and people

Companies are central in the project "Realisatie Bedrijven Centraal".

Results in 2024:
- Referente GrootboekSchema (RGS) coupled with questionaire directly from company accountancy. In this way companies return their data in the same format every year and without extra preprocessing.
- Shorter questionnaire production statistics: reduction of 75%
- Companies portal live
- Number of hotspots (companies): < half than before
- Handhaving intensified

What in 2025?
- 3 improved quesitonnaires (shorter and simplified)
- Better align the request with definitions and breakdowns that companies recognize
- Internal: set up variable database as  basis for further optimize of the 


Path 1: automatization
Path 2:  voor companies
Path 3: Improved experience of delivering data


### Large Case Unit of the National Bank of Belgium: collaboration with multinationals to improve the quality of the macro-economic statistics

Presenter: Yannick Rombauts ([National Bank of Belgium](https://www.nbb.be/en))

The macroeconimic statistics at NBB are calculated in the same way in other EU coutries. It makes statistics comparable.

The most important of the macro-economic statistics is the [gross domestic product](https://en.wikipedia.org/wiki/Gross_domestic_product) (GDP), i.e. the monetary vamue of all goods produced and services provided by economic agents of a country.

GDP of Belgium in 2023: € 519.8 bn.

Sources for calculating GDP:
- annual accounts
- VAT, NSSO, customs
surveys, e.g. for intra-EU external trade

Motto is: Lowest possible admin burden for companies!

Statistical confidentiality aobut the used data.

The [Large Cases Unit](https://www.nbb.be/nl/statistieken/large-cases-unit) was establisehd in 2021. It's a specialized and centalized unit with 7 team members.

Goal: improve quality, consistency and coherency of the data and produced statistics.

14 Multinational Enterprises (MNEs) in portfolio. Selection based on a Complexity Index and ad-hoc demands. No geographic distribution is taken into account.

Methodology can be seen as a four step procedure.

1. Profiling: list of entities of the MNE group within the EU
2. Qualitative analyses
3. Quantitative analyses 
4. Integration possible corrections


Ultimate goal:
- provide full economicpicture of the MNE
- detect inconsistencies which could have an impact to the GDP calculation

In the latter case, compare info with other information sources: VAT declarations, prodcom, etc.

Try to receive additional information:
- additioan details from annual accouts
- additioan details from VAT declaration
- Global production models

List of MNE is not public for confidentiality reasons.


## Workshop 3: Data sharing with general users


{:.alert .alert-warning}
The notes of this workshop are not complete: I had to leave after the first talk.

### The Social Study: data availability

Presenter: [Bart Meuleman](mailto:bart.meuleman@kuleuven.be) (KULeuven)

[The Social Study](https://thesocialstudy.be/): a scientific panel to measure citizen beliefs. Co-owned by all Belgian universities.

Surveys are still relevant source of data. Not the only one, but still relevant for life situation and behavior of citizens.

However:
- there is a negative survey climate. Too many surveys?
- Versnippering  an surveys
- new ways of data collection and data koppeling via technologival innovations

Future of surveys is in combination with other data sources.

The Social Study (TSS)?
A research infrastructure which gives possibilities to collect and couple and share efficient survey data of high quality.

Pool of > 5000 panel members: every 6 weeks invited for a short survey
Interdisciplinair
All surveys can be coupled
All collected survey data (after embargo) are avialable for the research community (not commercial)

Panel composition:
- people older tahn 16 years
- living in Belgium, not necessarily with Belgian nationality
- private households

Based on random sampking from Royal register.

A lot of investement in recruitement. Face-to-face strategies and push-to-web strategy combination.

One year long recruitment

Random sampling: 17752.
Participation to recruitment interview: 6933 (39%)
Joining the panel: 5845 (32%)

Less women than men.
Young people are more willing to join than older people.

Core Study questionnaires: core information about all panelists. Economic situation, wellbeing, health, work, education, social and cultural capital, religion and etnicity, political preferences, ...

Data sharing: Scientific Use Files via archive [Social Sciences and Digital Humanities Archive](https://www.sodha.be/) (SODHA).

Commissioned questionnaires: ordered by external teams

Immediately shared with the 
After 1 year embargo are also these data shared via SODHA.

Example of commissioned questionnaires: local elections, political polarization, green transition

There is an agreement with VSA voor one yearly commissioned questionnaire. In 2024: opvattingen ove rBrussel - pe. In 2025: Nature and Sport.

Coupling with administrative data: work in progress in collaboration with STATBEL.

Not via SUFs in archive of course as TSS is not owner of these data.

Biggest challenges about data sharing is avoiding of indirect identification of panel members. Consensus about data linking.

There are also costs about the maintenance of the infrastructure.
