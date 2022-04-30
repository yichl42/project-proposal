# Final Project Proposal

Please complete your proposal following the outline below.

## Project title

> Give your project a concise, interesting title that summarizes the entirety of your project. (Your title can change on subsequent deliverables.)

### Authors

> Names of your team members and contact information (email addresses).

Haochen Hu (haochh3@uw.edu), Eason Lin, Shammu Meyyappan (shammu53@uw.edu)

### Date
4/29/2022
Winter 2022

## Abstract

> No more than three sentences that summarize your project. Focus on the very most important aspects. For example: (1) "Our main question is .... This question is important because .... To address the question, we will ...." (2) "We are concerned with ..., because .... To address this concern, we plan to ...." (3) "Consider that .... This is important because .... Accordingly, we plan to ...."

Our main question is the relationship between outbreak and reduction over time.

We are concerned with several outbreaks of covid and the pattern of reduction of covid after outbreaks.

Considering that covid is widespread and harms people's health, this is important because analyzing and understanding the reasons and patterns of outbreaks can help people learn more about covid.
Accordingly, we plan to record the data and analyze it, and we hope that we can help the government make decisions.


## Keywords

> 3-5 keywords that summarize your project.
(e.g., "Keywords: human physiology; bicycle exercise; Gen Z; times-series data")

Pandemic, Coronavirus, Covid-19, Health, Time-series data

## Proposal

1. Introduction  

> Briefly introduce your project.  Include 3-5 research questions. What motivates the questions? Why are they important? (at least 200 words)

1. When are the top 3 days with the most new cases?

2. After the first covid breakout, when do daily new cases start to reduce?

3. Is the time between outbreaks related to seasons?

4. Is the time used to reduce the covid cases related to the country?

5. Is the relationship between the number of new people per day and the number of deaths per day proportional?

We want to do research on the relationship between the covid outbreaks and seasons, so we need to record the time of each breakout, and we need to analyze the time of breakout, and relate it to seasons.

Without considering the policy, we would like to know whether the decrease in the number of new people per day is related to seasonal changes or climate, so besides recording the time of outbreaks, we also record the time of reduction at the same time. We want to know if the death is related to time or the daily new cases.

Other than this, we need to consider the different situation of each individual countries, so besides analyzing the seasons we need to consider the relationship between the outbreaks and the locations of countries in order to help people to learn more about covid and help the government to make decisions.

2. Related Work  

> Describe your topic and related work in this space. You must include 3 citations to related work (URLs to similar work, high quality articles from the popular press, research papers, etc. ) Please use a standard citation style of your choice. (at least 200 words)

3. The Dataset
> Where did you find the data? Please include a link to the data source
> Who collected the data?
> How was the data collected or generated?
> Why was the data collected?
> How many observations (rows) are in your data?
> How many features (columns) are in the data?
> What, if any, ethical questions or questions of power do you need to consider when working with this data?
> What are possible limitations or problems with this data? (at least 200 words)

We found [our data](https://www.kaggle.com/datasets/josephassaker/covid19-global-dataset) through a search on Kaggle, a public database where users can view and upload data sets. The data was scraped by Joseph Assaker, an artificial intelligence engineer from Lebanon, on March 17, 2022 from [Worldometer](https://www.worldometers.info/coronavirus/), a trusted live-tracker of coronavirus data through official government reports. The data was collected in an attempt to more easily monitor and predict future trends regarding COVID-19, both on a worldwide scale and within specific countries.

> "As for the reason for me building this dataset, it's because I couldn't get my hands on an easily digestible and up-to-date dataset of Covid-19, so, I decided to build my own using Python and web scraping techniques... Going through this data, Kagglers can visualize various trends in their own country, or compare several countries." - Joseph Assaker

The data contains 7 columns tracking the date, country, cumulative total cases, daily new cases, active cases, cumulative total deaths, and daily new deaths, respectively. It contains 170,917 rows, each representing one of the 762 days from February 15, 2020, (when 223 of the 225 countries represented in this data began tracking COVID-19 statistics) up to March 17, 2022 (when the data was last scraped). Two exceptions to this are China, which began tracking its data from January 22, 2020, and Palau, which only began tracking on August 25, 2021. Ethically, we must consider how the ramifications of the COVID-19 pandemic extend far beyond some statistical observations, and the lives lost to it can never truly be represented by a single column in a data set. Inconsistent or inaccurate reporting of COVID-19 cases and deaths are the two biggest potential limitations of this data, as different countries may have different requirements for listing something as a case of or death caused by COVID-19. Additionally, certain countries or governments may also be manipulating their own reports to appear more or less successful in their responses to the pandemic for political or financial gain.

4. Implications

> Assuming you answer your research questions, briefly describe the expected or possible implications for technologists, designers, and policymakers. (at least 150 words)

5. Limitations & Challenges
>What challenges or limitations might you need to address with your project idea more broadly? Briefly discuss. (at least 150 words)

Acknowledgements
> Is there anyone you would like to thank? A librarian who helped you with your research? A Teaching Assistant? A friend who helped you find your data? Say thank you in this section.
