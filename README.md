# Exploratory Data Analysis of COVID-19 Data

This repository contains an exploratory data analysis (EDA) of the COVID-19 data for India from the Our World in Data project (owid-covid-data). The owid-covid-data dataset is a collection of COVID-19 statistics for countries worldwide, updated daily, and includes data on confirmed cases, deaths, testing, and vaccinations.

# EDA Process

After importing the dataset and checking for missing values, we started the exploratory data analysis process. We performed the following steps:

    Checked the data types of each column and converted the date column to datetime type.
    Plotted histograms for the numerical columns to check the distribution.
    Plotted boxplots for the numerical columns to check for outliers.
    Plotted a correlation chart to check the correlation between different columns.
    Preprocessed the data for a line chart by resampling the data on a monthly basis.
    Plotted a line chart with a trendline for the "new_cases_smoothed" column.

We also identified a few additional areas for exploratory data analysis, such as:

    Comparing the trend of COVID-19 cases and deaths in different countries.
    Analyzing the impact of vaccination on COVID-19 cases and deaths.
    Analyzing the impact of government policies on COVID-19 cases and deaths.
    
    Dataset

The dataset we used for this analysis includes COVID-19 data for India from January 2020 to September 2021. The dataset contains the following variables:

 Location variables:

    iso_code: Three-letter ISO code for the country or region
    continent: Continent of the location
    location: Name of the location (country, region, etc.)

Temporal variables:

    date: Date of the observation

COVID-19 cases and deaths variables:

    total_cases: Total confirmed cases of COVID-19
    new_cases: New confirmed cases of COVID-19
    new_cases_smoothed: New confirmed cases of COVID-19 (7-day smoothed)
    total_deaths: Total deaths attributed to COVID-19
    new_deaths: New deaths attributed to COVID-19
    new_deaths_smoothed: New deaths attributed to COVID-19 (7-day smoothed)
    total_cases_per_million: Total confirmed cases of COVID-19 per 1,000,000 population
    new_cases_per_million: New confirmed cases of COVID-19 per 1,000,000 population
    new_cases_smoothed_per_million: New confirmed cases of COVID-19 (7-day smoothed) per 1,000,000 population
    total_deaths_per_million: Total deaths attributed to COVID-19 per 1,000,000 population
    new_deaths_per_million: New deaths attributed to COVID-19 per 1,000,000 population
    new_deaths_smoothed_per_million: New deaths attributed to COVID-19 (7-day smoothed) per 1,000,000 population

Other variables:

    population: Population in 2020
    population_density: Number of people divided by land area, measured in square kilometers, most recent year available
    median_age: Median age of the population, UN projection for 2020
    aged_65_older: Share of the population that is 65 years and older, most recent year available
    aged_70_older: Share of the population that is 70 years and older in 2015
    gdp_per_capita: Gross domestic product at purchasing power parity (PPP) per capita in 2019
    cardiovasc_death_rate: Death rate from cardiovascular disease in 2017 (annual number of deaths per 100,000 people)
    diabetes_prevalence: Diabetes prevalence (% of population aged 20 to 79) in 2017
    handwashing_facilities: Share of the population with basic handwashing facilities on premises in 2017
    hospital_beds_per_thousand: Hospital beds per 1,000 people, most recent year available since 2010
    life_expectancy: Life expectancy at birth in 2019
    human_development_index: A composite index measuring average achievement in three basic dimensions of human development - a long and healthy life, knowledge, and a decent standard of living - in 2019.

Using this dataset, we performed exploratory data analysis to gain insights into COVID-19 cases and deaths in India. We first cleaned the dataset by removing unnecessary columns and missing values. We then plotted various charts to visualize the data, including bar charts for the total cases and deaths, line charts for the trend of new cases and deaths, boxplots for the distribution of numerical variables, and a correlation heatmap to identify relationships between variables. We also performed statistical tests to validate our observations.

The insights we gained from the EDA include:

    India had a high number of total COVID-19 cases and deaths compared to other countries.
    The trend of new cases and deaths was decreasing in recent months, indicating a possible decline in the pandemic.
    COVID-19 cases and deaths
