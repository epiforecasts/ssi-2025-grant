## Current and recent research funding (including Wellcome grants) (1000 words)


LSHTM COVID-19 Response Fund (2023). Groundwork for building the next generation of outbreak and surveillance methodology and tools. £15,000. Project lead - received all funds. 100% on research 01/03/2023-01/03/2024

## Describe how the currently active grants listed above relate to this application. If you hold grants related to the topic of this application, explain how these differ and confirm there is no overlap in funding. (200 words)

I hold no currently active grants related to this work. My previous grant helped prototype the epinowcast package. There is no overlap in funding between this application and any of my previous grants.

## What percentage of your research time will you spend on this project?
100

## How have you contributed to the generation of knowledge? (1000 words)

My work develops and implements methodological approaches that translate statistical principles into accessible, reliable tools for infectious disease modelling and outbreak response. My work has bridged the gap between theoretical approaches and practical applications by creating software tools that have been widely adopted by public health agencies and researchers.

During the COVID-19 pandemic, I led the development of EpiNow2, an R package for real-time estimation of time-varying epidemiological parameters. This package has been used extensively by researchers and public health agencies. This methodology formed a part of the UK's early pandemic response through analysis presented to SAGE and SPI-M-O, for which I received the SPI-M-O Award for Modelling and Data Support.

Building on this experience, I have developed methodological improvements addressing challenges faced during outbreak response. This includes methods for nowcasting right-truncated case counts, joint modelling of transmission dynamics and reporting delays, and estimating delay distributions. To support these methods, I led the development of analytical solutions to common primary censored delay distributions and integrated this into a wider ecosystem of tools and methods.

A theme of my work has been developing joint models for novel data sources in real-time settings. This includes working with Cycle threshold values from over 3 million COVID-19 cases in England, revealing patterns in viral load dynamics across different demographic and epidemiological factors. I co-developed a joint modelling approach that combined PCR and antibody data from the ONS Community Infection Survey to estimate incidence, growth rates, and reproduction numbers. I have also worked on combining within-host SARS-CoV-2 viral kinetics with information on past exposures, which identified intrinsic differences between Omicron and Delta variants. These differences would not have been detectable using either data source alone.

During my time consulting at the US CDC's Center for Forecasting and Outbreak Analytics, I contributed to projects focused on integrating multiple datasets, improving forecasting, and enhancing situational awareness for outbreak response. This work involved helping to develop methods to synthesise data streams to provide more robust insights. As part of these efforts, I led the development of EpiAware, a prototype open-source composable modelling approach that emerged from the need to rapidly integrate and analyse heterogeneous surveillance data whilst being able to readily adapt the model structure. This project, which forms the conceptual foundation for this grant application, demonstrates how a generative process-focused approach can enhance epidemiological modelling while supporting more effective data integration for improved situational awareness.

Peer-reviewed

Charniga, K., Park, S. W., ..., Abbott, S. Best Practices for Estimating and Reporting Epidemiological Delay Distributions of Infectious Diseases. PLOS Computational Biology 20(10): e1012520 (2024).

Established best practices for estimating and reporting delay distributions in infectious disease epidemiology, addressing key challenges in real-time analysis. As last author, I managed this collaborative effort.

Abbott*, S., Russell*, T. W., Townsley*, H., ..., Kucharski, A. J. Combined analyses of within-host SARS-CoV-2 viral kinetics and information on past exposures to the virus in a human cohort identifies intrinsic differences of Omicron and Delta variants. PLoS Biology 22(1): e3002463 (2024). * equal contribution

Jointly fitted viral kinetic data and incubation period data. As co-first author, I led development of the modeling framework integrating these different data types. This work exemplifies principles of composable modeling and limitations of current approaches.

Lison, A., Abbott, S., Huisman, J.S., Stadler, T. Generative Bayesian modeling to nowcast the effective reproduction number from line list data with missing symptom onset dates. PLOS Computational Biology. 20(4):e1012021 (2024).

Contributed to methodology development and implementation of this joint model integrating right-truncation and transmission dynamics, producing more robust estimates during key outbreak phases and demonstrating advantages over pipeline approaches.

Overton, C. E., Abbott, S., Christie, R., Cumming, F., Day, J., Jones, O., Paton, R., Turner, C., Ward, T. Nowcasting the 2022 mpox outbreak in England. PLOS Computational Biology. 19(9):e1011463 (2023).

Demonstrated how nowcasting approaches can be rapidly adapted to emerging outbreaks. I advised on methodology and implementation, supporting operational use by UKHSA during the mpox response.

Preprints

Park, S. W., ..., Abbott, S. Estimating epidemiological delay distributions for infectious diseases. medRxiv 2024.01.12.24301247 (2024).

Provides a framework for estimating epidemiological delay distributions, addressing challenges such as truncation, interval censoring, and dynamical biases. As senior author, I coordinated this collaborative effort and contributed to methodological development.

Abbott, S., Funk, S. Estimating epidemiological quantities from repeated cross-sectional prevalence measurements. medRxiv 2022.03.29.22273101 (2022).

A novel approach to jointly modelling PCR and antibody prevalence data from ONS Community Infection Survey to estimate incidence, growth rates, and reproduction numbers. I co-developed methodology and analysis, showcasing integration of multiple data streams for robust epidemiological insights.

Software

Abbott S, Hellewell J, ..., Funk S (2024). EpiNow2: Estimate Real-Time Case Counts and Time-Varying Epidemiological Parameters. R package version 1.7.1, https://epiforecasts.io/EpiNow2/

A range of public health organisations and research groups widely use this toolkit. I led the development and was the maintainer for 4 years. It showcases our ability to translate our work into meaningful tooling.

Abbott S, Lison A, Funk S, Pearson C, Gruson H, Guenther F, DeWitt M (2024). epinowcast: Flexible Hierarchical Nowcasting. doi:10.5281/zenodo.5637165.

Similarly widely used, this toolkit showcases my move towards collaborative community co-creation as it is part of the wider epinowcast organisation and was developed with multiple contributors.

Howes A, Park SW, Abbott S (2024). epidist: Estimate epidemiological delay distributions with brms. https://doi.org/10.5281/zenodo.14213017

This package puts into practice recommendations for estimating delays in a flexible Bayesian regression framework. I led developmemnt and managed contributions from multiple collaborators.

Abbott S, Brand S, Pearson C, Funk S, Charniga K (2024). primarycensored: Primary event censored distributions. https://doi.org/10.5281/zenodo.13632839

This package provides analytical and numerical solutions for censored and truncated delay distributions, a key component in epidemiological models. I led the development, creating a reusable model component. This tool exemplifies the modular approach of our application by providing well-defined, self-contained functionality that can be combined with other model components. However, it also showcases the limitations of this approach when using the currently widely used R and Stan ecosystems due to only being able to support function passing and depends on metaprogamming.

## How have you contributed to the development of others?

My approach to developing others focuses on providing meaningful opportunities for growth while offering structured support tailored to individual needs and career stages.

I have contributed to the academic development of several researchers through formal supervision. As co-supervisor for Katherine Sherratt's PhD by publication (2023-24) on collaborative modelling efforts to support policy in epidemic outbreaks, I provided methodological guidance and mentoring. I also served on the advisory board for Nikos Boss's PhD (2020-24) on evaluating crowd forecasts and development of forecast scoring software, bringing expertise in both forecasting methodology and software development. Additionally, I co-supervised Ryan Tao's Masters dissertation (2021) evaluating the impact of different surveillance data reporting cadences on the performance of nowcasting models.

As the founder and organiser of the epinowcast community, I have created an environment that nurtures the development of early-career researchers interested in epidemic modelling. This includes organising a regular seminar series, maintaining an active discussion forum, and coordinating collaborative software development. Many participants have subsequently developed their own R packages and methodological approaches. Others have gone on to use the methodology and tools in outbreak responses at international organisations.

During my time at the US CDC's Center for Forecasting and Outbreak Analytics, I provided mentorship and project management support to researchers at various career stages. This included guiding junior staff in developing conceptual understanding of real-time analysis approaches for COVID-19 data, helping more senior analysts translate complex methodological frameworks into public health practice, and supporting branch and team leads in managing research projects and developing their teams.

## How have you contributed to the wider research community? 

I have actively contributed to building and supporting the epidemiological modelling community through both technical contributions and community-building initiatives.

I founded and currently lead the epinowcast community, which provides resources, discussion forums, and a monthly seminar series focused on methods for real-time epidemiological analysis. This community now includes over 50 researchers and public health practitioners globally, supporting knowledge exchange between academic methodologists and frontline analysts. A focus of this group is on providing a space for technical conversations and soliciting feedback in an inclusive environment.

I have organised and contributed to multiple workshops on infectious disease modelling, including the "Nowcasting and Forecasting Infectious Disease Dynamics" course at the European summer school in infectious disease modelling. In 2024, I taught sessions on evaluating infectious disease forecasts at IDM Thailand, and in 2023 I organised the LSHTM COVID-19 Reflections event bringing together modellers to discuss lessons learned from the pandemic response. All of these courses have open source materials that are freely available online and used by public health agencies and researchers for self-study.

Throughout multiple outbreaks, I have provided technical assistance to public health agencies globally. During the COVID-19 pandemic, I made significant contributions to SPI-M/SAGE by providing weekly estimates of the reproduction number, short-term forecasts, and multiple ad-hoc reports. For the mpox outbreak in 2022, I provided consultancy support to both CDC and UKHSA. I also supported SACEMA in South Africa with their Omicron response (2021-2024), including a two-week academic visit in 2022 to provide in-person technical assistance.

My software tools are now widely used in public health, with adoption by WHO, ECDC, CDC, MSF, RKI, and UKHSA among others. I maintain these packages, regularly addressing issues, making improvements, and providing guidance to users. This maintenance work, often overlooked academically, is crucial for ensuring methodological advances remain accessible and usable.

## Describe how your research contributes to the strategic aims of your organisation. (300 words)

My research directly contributes to LSHTM's mission of improving health and health equity
worldwide through excellence in public and global health research and education.
LSHTM's mission further aims to ensure that research is widely available in a responsible and secure way, while embracing
innovations in data science and technology.

My work in real-time infectious disease modelling is aligned with these strategic priorities. Specifically, my focus on creating open-source, accessible tools aligns with LSHTM's objective to enhance the availability of tools for all. Our approach not only advances LSHTM's commitment to open science but also fosters equitable and sustainable research
partnerships globally.

By developing rigorous methodologies and practical tools for real-time infectious disease modelling, my research embodies LSHTM's commitment to innovation and impact. These tools, now widely used by public health institutions, exemplify our goal of translating knowledge into policy and practice.

Finally, my work and the work proposed here contributes to LSHTM's vision of a more healthy, sustainable, and
equitable world. By providing tools that enable rapid response to infectious disease outbreaks,
we support health equity and global preparedness.

## Describe your approach to developing and supporting a positive and inclusive research culture, including examples from previous and current groups.

I prioritise open, reproducible research practices across all my work. This includes publishing analysis code alongside manuscripts, developing thoroughly documented open-source software, and sharing educational materials freely. With the epinowcast community, I established norms for code review, collaborative development, and public discussion of methodological challenges. These practices lower barriers to participation and enable researchers at all career stages to learn, contribute, and build upon existing work.

I actively work to make technical methodological approaches accessible to researchers with diverse backgrounds. This includes creating multiple entry points to complex methods through tiered documentation (from beginner to advanced), developing user-friendly interfaces to statistical methods, and providing regular opportunities for skill development through workshops and seminars.

I approach research as a collaborative endeavour where diverse perspectives strengthen outcomes. In developing the epinowcast community, I facilitated regular collaborative sessions that integrated input from a range of perspectives. This collaborative approach ensured the resulting methodology addressed real-world needs while maintaining statistical rigour.

## Your organisation will give you and the staff employed on your grant a minimum of 10 days a year to do training and continuing professional development. Explain how you will use this time.

I will use professional development time to strengthen technical skills directly relevant to the proposed project while also building capacity for effective leadership and collaboration in an interdisciplinary team.

Given my role focusing on infrastructure development and core modules for composable modelling, I will dedicate time to deepening my expertise in Julia programming language features essential for building robust, efficient modelling frameworks. This includes participating in workshops on Julia's type system, metaprogramming capabilities, and performance optimisation techniques, as well as studying successful package ecosystems like Flux.jl and SciML that serve as architectural models for our work.

I will engage with the broader probabilistic programming community through participation in relevant conferences and workshops to ensure our approach incorporates state-of-the-art developments in the field and establishes meaningful connections with related projects.

To strengthen my leadership capabilities, I will participate in LSHTM's research leadership programme, focusing particularly on skills for managing interdisciplinary teams and fostering inclusive collaboration across technical domains. This will be crucial for effectively coordinating work across the infrastructure, core modules, and scientific applications work packages.

I will also dedicate time to pedagogical training focused on effectively communicating complex technical concepts to diverse audiences. This will support our community building and training objectives, ensuring the tools we develop can be effectively adopted by both technical and non-technical users.