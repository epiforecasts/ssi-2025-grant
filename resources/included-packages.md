
# In epinowcast org

# epinowcast

Flexible Hierarchical Nowcasting
Summary
Tools to enable flexible and efficient hierarchical nowcasting of right-truncated epidemiological time-series using a semi-mechanistic Bayesian model with support for a range of reporting and generative processes. Nowcasting, in this context, is gaining situational awareness using currently available observations and the reporting patterns of historical observations. This can be useful when tracking the spread of infectious disease in real-time: without nowcasting, changes in trends can be obfuscated by partial reporting or their detection may be delayed due to the use of simpler methods like truncation. While the package has been designed with epidemiological applications in mind, it could be applied to any set of right-truncated time-series count data.

used widely by CDC, UKHSA etc and the core of the nowcasting/delay ecosystem. Lots of code that could be spun out as was done for the discrete delay handling for example.

# primarycensored

Planned to link backends across ecosystem for EpiNow2, epuinowcast, epidist etc. Used already in epidist and integration coming soon to EpiNow2 and epinowcast

Primary event censored distributions
Universe MIT license  GitHub contributors DOI

Summary
Provides functions for working with primary event censored distributions and ‘Stan’ implementations for use in Bayesian modeling. Primary event censored distributions are useful for modeling delayed reporting scenarios in epidemiology and other fields (Charniga et al. (2024) doi:10.48550/arXiv.2405.08841). It also provides support for arbitrary delay distributions, a range of common primary distributions, and allows for truncation and secondary event censoring to be accounted for (Park et al. (2024) doi:10.1101/2024.01.12.24301247). A subset of common distributions also have analytical solutions implemented, allowing for faster computation. In addition, it provides multiple methods for fitting primary event censored distributions to data via optional dependencies.

# baselinenowcast

Getting Started with baselinenowcast
Source: vignettes/baselinenowcast.Rmd
1 Introduction
Incomplete reporting of epidemiological data at recent times can result in case count data that is right-truncated. Right-truncated case counts can be misleading to interpret at face-value, as they will typically show a decline in the number of reported observations in the most recent time points. These are the time points where the highest proportion of the data has yet to be observed in the dataset.

The imputation of the cases that will eventually be observed up until the current time is referred to as a nowcast.

A number of methods have been developed to nowcast epidemiological case count data.

The purpose of baselinenowcast is to provide a nowcast computed directly from the most recent observations to estimate a delay distribution empirically, and apply that to the partially observed data to generate a nowcast.

Right-truncation in public health surveillance can create a misleading impression of declining trends in recent data due to reporting delays. Current nowcasting solutions often remain unused in practice due to complexity, insufficient documentation, or technical barriers, whilst methodological advances are hampered by the absence of standardised benchmarks. We propose a baseline nowcasting method and accompanying modular R package that addresses these dual needs. Our approach estimates delay distributions from historical data, generates point nowcasts through a modified multiplicative approach, and quantifies uncertainty using negative binomial distributions fitted to retrospective performance. We validated this approach against the baseline method described in the German nowcasting Hub. We then conducted a model permutation study with different configurations using the German COVID-19 data to evaluate our default approach along with a range of model variations. Finally, we applied our approach to UKHSA's norovirus surveillance data and compared performance against two alternative baseline methods and a method currently used in public health surveillance. Our baseline method improved estimates compared to unadjusted data across all datasets, with <comparable performance to the KIT baseline in the German data>. The model permutation study revealed <key findings about model configurations>. In the UKHSA norovirus data, our baseline method demonstrated <specific improvements over naive approaches> and was competitive with more complex methods when the structure of the data was accounted for using domain knowledge and our modular tooling. Our approach balances statistical rigour with interpretability, providing a practical nowcasting solution for routine surveillance and a standard benchmark for methodological research, ultimately contributing to more timely and effective public health responses.

uses processing tools from epinowcast and wants to integrate more into that ecosystem as an alternative/test bed/simple option.

# epidist

Getting started with epidist
Source: vignettes/epidist.Rmd
epidist is a toolkit for flexibly estimating epidemiological delays built on top of brms (Bayesian Regression Models using Stan). brms provides a powerful framework for Bayesian modelling with an accessible R interface to Stan. By building on brms, epidist inherits the ability to work within the broader brms ecosystem, allowing users to leverage existing tools for model diagnostics, posterior predictive checks, and model comparison while addressing the specific challenges of delay distribution estimation. See the vignette("faq") for more details on the tools available in the brms ecosystem.

In this vignettte, we will give a quick start guide to using the epidist package. To get started we will introduce some of the key concepts in delay distribution estimation, and then simulate some data delay data from a stochastic outbreak that includes common biases. Using this simulated data we will then show how to use the epidist package to estimate a distribution using a simple model and a model that accounts for some of the common issues in delay distribution estimation. We will then compare the output of these models to the true delay distribution used to simulate the data again using epidst tools.

1 Key concepts in delay distribution estimation
In epidemiology, we often need to understand the time between key events - what we call “delays”. Think about things like:

incubation period (how long between getting infected and showing symptoms),
serial interval (time between when one person shows symptoms and when someone they infected shows symptoms), and
generation interval (time between when one person gets infected and when they infect someone else).
We can think of all these as the time between a “primary event” and a “secondary event”.

The tricky bit? Getting accurate estimates of these delays from real-world data is a challenge. The two main challenges we typically face are:

interval censoring (we often only know events happened within a time window, not the exact time), and
right truncation (we might miss observing later events if our observation period ends).
Don’t worry if these terms sound a bit technical! In Section 3, we’ll walk through what these issues look like by simulating the kind of data you might see during an outbreak. Then in Section 5, we’ll show how epidist helps you estimate delay distributions accurately by accounting for these issues.

For those interested in the technical details, epidist implements models following best practices in the field. Check out Park et al. (2024) for a methodological overview and Charniga et al. (2024) for a practical checklist designed for applied users. We also recommend the nowcasting and forecasting infectious disease dynamics course for more hands on learning.

Used by UKHSA, CDC, ECDC, and multiple research groups. Depends on primarycensored and inputs used by epinowcast and epinow2 wihin the ecosystem.

# In epiforecasts org

# scoringutils

Used by UKHSA, CDC, ECDC and multiple research groups. Integrated in the hubverse as the primary forecast scoring tool.

scoringutils: Utilities for Scoring and Assessing Predictions
Note: This documentation refers to the stable version of scoringutils. You can also view the documentation of the development version.

The scoringutils package facilitates the process of evaluating forecasts in R, using a convenient and flexible data.table-based framework. It provides broad functionality to check the input data and diagnose issues, to visualise forecasts and missing data, to transform data before scoring, to handle missing forecasts, to aggregate scores, and to visualise the results of the evaluation. The package is easily extendable, meaning that users can supply their own scoring rules or extend existing classes to handle new types of forecasts.

The package underwent a major re-write. The most comprehensive documentation for the updated package is the revised version of our original scoringutils paper.

Another good starting point are the vignettes Details on the metrics implemented and Scoring forecasts directly.

For further details on the specific issue of transforming forecasts for scoring see:

Nikos I. Bosse, Sam Abbott, Anne Cori, Edwin van Leeuwen, Johannes Bracher* and Sebastian Funk* (*: equal contribution) (2023). Scoring epidemiological forecasts on transformed scales, PLoS Comput Biol 19(8): e1011393 https://doi.org/10.1371/journal.pcbi.1011393

Installation
Install the CRAN version of this package using

install.packages("scoringutils")
Install the unstable development version from GitHub using

remotes::install_github("epiforecasts/scoringutils", dependencies = TRUE)
Quick start
Forecast types
scoringutils currently supports scoring the following forecast types:

binary: a probability for a binary (yes/no) outcome variable.
point: a forecast for a continuous or discrete outcome variable that is represented by a single number.
quantile: a probabilistic forecast for a continuous or discrete outcome variable, with the forecast distribution represented by a set of predictive quantiles.
sample: a probabilistic forecast for a continuous or discrete outcome variable, with the forecast represented by a finite set of samples drawn from the predictive distribution.
nominal categorical forecast with unordered outcome possibilities (generalisation of binary forecasts to multiple outcomes)
Input formats and input validation
The expected input format is generally a data.frame (or similar) with required columns observed, and predicted that holds the forecasts and observed values. Exact requirements depend on the forecast type. For more information, have a look at the paper, call ?as_forecast_binary, ?as_forecast_quantile etc., or have a look at the example data provided in the package (example_binary, example_point, example_quantile, example_sample_continuous, example_sample_discrete, example_nominal).

Before scoring, input data needs to be validated and transformed into a forecast object using one of the as_forecast_<type>() functions.

# socialmixr

Introduction to socialmixr
Sebastian Funk
2025-05-01
Source: vignettes/socialmixr.Rmd
socialmixr is an R package to derive social mixing matrices from survey data. These are particularly useful for age-structured infectious disease models. For background on age-specific mixing matrices and what data inform them, see, for example, the paper on POLYMOD by (Mossong et al. 2008).

Usage
At the heart of the socialmixr package is the contact_matrix() function. This extracts a contact matrix from survey data. You can use the R help to find out about usage of the contact_matrix() function, including a list of examples:

?contact_matrix
The POLYMOD data are included with the package and can be loaded using

data(polymod)
An example use would be

contact_matrix(polymod, countries = "United Kingdom", age.limits = c(0, 1, 5, 15))

This generates a contact matrix from the UK part of the POLYMOD study, with age groups 0-1, 1-5, 5-15 and 15+ years. It contains the mean number of contacts that each member of an age group (row) has reported with members of the same or another age group (column).

Surveys
The key argument to the contact_matrix() function is the survey that it supposed to use. The socialmixr package includes the POLYMOD survey, which will be used if not survey is specified. It also provides access to all surveys in the Social contact data community on Zenodo. The available surveys can be listed (if an internet connection is available) with

list_surveys()
A survey can be downloaded using the get_survey() command. This will get the relevant data of a survey given its Zenodo DOI (as returned by list_surveys()). All other relevant commands in the socialmixr package accept a DOI, but if a survey is to be used repeatedly it is worth downloading it and storing it locally to avoid the need for a network connection and speed up processing.

peru_survey <- get_survey("https://doi.org/10.5281/zenodo.1095664")
saveRDS(peru_survey, "peru.rds")
This way, the peru data set can be loaded in the future without the need for an internet connection using

peru_survey <- readRDS("peru.rds")
Some surveys may contain data from multiple countries. To check this, use the survey_countries function

survey_countries(polymod)

By default, socialmixr uses the POLYMOD survey. A reference for any given survey can be obtained using get_citation(), e.g.

get_citation(polymod)
#> Mossong J, Hens N, Jit M, Beutels P, Auranen K, Mikolajczyk R, Massari
#> M, Salmaso S, Tomba GS, Wallinga J, Heijne J, Sadkowska-Todys M,
#> Rosinska M, Edmunds WJ (2017). "POLYMOD social contact data."
#> doi:10.5281/zenodo.1157934 <https://doi.org/10.5281/zenodo.1157934>,
#> Version 1.1.

Bootstrapping
To get an idea of uncertainty of the contact matrices, a bootstrap can be used using the sample.participants argument of contact_matrix(). If this argument is set to TRUE, participants are sampled (with replacement, to get the same number of participants of the original study) every time the contact_matrix() function is called, and thus a different matrix returned every time. From these matrices, derived quantities can be obtained, for example the mean:

Demography
Obtaining symmetric contact matrices, splitting out their components (see below) and age-specific participant weights require information about the underlying demographic composition of the survey population. This can be passed to contact_matrix() as the survey.pop argument, a data.frame with two columns, lower.age.limit (denoting the lower end of the age groups) and population (denoting the number of people in each age group). If no survey.pop is not given, contact_matrix() will try to obtain the age structure of the population (as per the countries argument) from the World Population Prospects of the United Nations, using estimates from the year that closest matches the year in which the contact survey was conducted.

If demographic information is used, this is returned by contact_matrix() as the demography field in the results list. It is possible to enforce or prevent the function to return demography data by using the return.demography option.

# epinow2

EpiNow2: Estimate real-time case counts and time-varying epidemiological parameters
Lifecycle: maturing R-CMD-check codecov 

MIT license GitHub contributors universe GitHub commits DOI

Summary
EpiNow2 estimates the time-varying reproduction number, growth rate, and doubling time using a range of open-source tools (Abbott et al.), and current best practices (Gostic et al.). It aims to help users avoid some of the limitations of naive implementations in a framework that is informed by community feedback and is actively supported.

Forecasting is also supported for the time-varying reproduction number, infections, and reported cases using the same generative process approach as used for estimation.

Most used. Developed at beginning of pandemic. near 50k downloads. Epinowcast intended to replace but filling different niches. No shared backend but could be primarycensored and example of doing this.