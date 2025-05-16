# Application name

Unifying, harmonising, and establishing sustainable governance for the epinowcast/epiforecasts ecosystem of infectious disease modelling tools

# Project details

*Please indicate if you are expecting to apply for a Large Award of up to 2 years duration and up to £500,000 budget or a Small Award of up to 1 year duration and up to £150,000 budget. Full budget details will be required at the full proposal stage.*

Large Award: 2 years duration, up to £500,000 budget

# Proposal summary / scope of work

*0 / 500 words*
*Please provide a short summary of the work being proposed. Please note that this summary may be publicly published - do not include any confidential information.* 

Despite widespread usage by public health agencies and researchers, our infectious disease modelling tools are fragmented across two organisations with inconsistent interfaces, overlapping functionality, and distributed maintenance burden, creating barriers to adoption and inefficiencies. These tools, including EpiNow2, epinowcast, scoringutils, primarycensored, and epidist, are currently used by major public health agencies including UKHSA, WHO, CDC, and ECDC for situational awareness of infectious diseases, as well as by numerous research groups. Collectively they have been downloaded over 100,000 times with 200+ stars on GitHub and have been cited in over 100 academic papers.

Many of these packages were developed rapidly during the COVID-19 pandemic, prioritising immediate utility over long-term sustainability. Users now struggle to discover and apply appropriate methods, while developers face significant technical debt and duplicated maintenance efforts. The ecosystem lacks clear governance and contribution pathways that would allow it to grow beyond its current developers and evolve to match user needs. Without intervention, these challenges will continue to limit the impact and sustainability of these valuable tools.

This project will unify, harmonise, and establish sustainable governance for the epinowcast/epiforecasts ecosystem of infectious disease modelling tools. We will systematically address the current challenges through the following key activities:

1. Creating a single entry point for R packages across epinowcast and epiforecasts organisations to create a coherent ecosystem with clear signposts for users.

2. Seeking user and developer feedback on the divergent user interfaces across packages to enable standardisation.

3. Establishing formal governance structures for the unified ecosystem to support sustainable maintenance, facilitate decision making, and enable broader community participation.

4. Reducing code duplication across packages to improve interoperability and reduce technical debt.

5. Implementing shared components and common backends across packages to enable future integration with next-generation probabilistic programming frameworks such as Turing.jl and create sustainable pathways for maintenance.

6. Improving contribution guides and onboarding materials to expand our contributor pool and distribute maintenance responsibility across a wider community.

7. Creating infrastructure that facilitates communication across the ecosystem to support community-driven packages and diverse contributors.

8. Establishing a unified roadmap for the ecosystem to ensure ongoing relevance and funding opportunities.

9. Running two targeted workshops: one focused on onboarding new developers to contribute to the ecosystem, and another dedicated to training new users in effectively applying our tools for infectious disease modelling.

Through these activities, we will provide public health agencies and researchers with a more coherent, maintainable set of tools for infectious disease modelling, enabling more effective response to both routine surveillance and emerging threats across diverse global settings.

# Categories of work

- [x] Technical
- [x] Community
- [x] Documentation
- [x] Training
- [x] Governance

*Please check all categories of activities that apply to the work you are requesting funding for. Click on the help text (?) for further details of each category. Please note that these categories may be publicly published.*

# Project Team

*0 / 250 words*
*Briefly describe why your team is the appropriate one to carry out these activities. You will be asked to provide details of the Project Lead and Co-Leads on the Team Details page, along with their connection to the software.*

Our team brings expertise in developing and maintaining the tools this project seeks to harmonise. As creators and maintainers of the epinowcast and epiforecasts ecosystems, we understand both the code and communities that rely on these tools.

The project will be led by Dr. Sam Abbott, founder of the epinowcast community and developer of key packages in both organisations. With experience working with UKHSA, CDC, and ECDC, Sam has successfully translated methodological innovations into accessible tools. He has built inclusive communities through the epinowcast initiative, which includes over 50 researchers globally. His expertise in real-time epidemiological analysis and commitment to open science makes him qualified to lead this effort.

Professor Sebastian Funk will provide strategic guidance and stakeholder management. As Director of CMMID at LSHTM and a Wellcome Senior Research Fellow, Sebastian brings leadership experience and a global network of collaborators. He has led multiple open-source software projects, including socialmixr and rbi.

Our team has established contribution pathways across both ecosystems, with guides, forums, and support channels. Core tools like epinowcast and EpiNow2 each have 20+ contributors, showing our ability to convert users into community members. Combining Sam's expertise in software development and community building with Sebastian's vision, we are positioned to create a sustainable ecosystem serving current and future needs of the infectious disease modelling community.

# Benefit to UK research

*0 / 250 words*
*Briefly describe the expected value of the proposed work to UK research. You may wish to describe the fields of research or types of research method the software is used in, and describe the benefits to a particular community. You may also want to give examples of what research is enabled by the software.*

This project will deliver significant value to UK research by harmonising critical infectious disease modelling tools currently used by UKHSA, academic epidemiology groups, and other organisations. We need to address the fragmentation of infectious disease modelling tools across our organisations so that users can discover, apply, and contribute to appropriate methods without confusion.

UK public health agencies currently rely on these tools for nowcasting infectious diseases including COVID-19, influenza, and norovirus. The harmonised ecosystem will enable more robust outbreak response capabilities for emerging threats and facilitate research into reporting delays and biases in surveillance systems.

Academic researchers use our tools extensively for methodological comparison and validation. For example, scoringutils is widely used for evaluating forecast models, EpiNow2 has been used for evaluating methods like EpiFusion (Judge 2024) and viral load based approaches (Hay et al 2021), and epinowcast has been used to evaluate methods for nowcasting (Mellor 2024). This cross-method validation is crucial for advancing epidemiological research.

Aside from method validation, examples of research enabled by this ecosystem include real-time situational awareness during outbreaks and robust estimation of reporting delays in surveillance systems. By simplifying the handling of complex surveillance data, our tools make sophisticated modelling more accessible, allowing researchers to focus more on epidemiological questions rather than data challenges.

The project aligns with key UK research priorities around pandemic preparedness, health data science infrastructure, and methodological innovation. By reducing duplication and inconsistencies between tools, we will enable more efficient knowledge transfer between research groups and institutions.


# Landscape analysis

*0 / 250 words*
*Briefly describe the other software (either proprietary or open source) that is primarily used by the research community addressed by the work in this proposal. Summarise, to the best of your knowledge, how the software in this proposal compares to these other software in terms of user base size, usage, and maturity. Describe, if appropriate, how the other software interacts with the software in this proposal.*

The infectious disease modelling landscape features two main approaches: pipeline approaches that combine separate models, and joint modelling approaches offering more integrated but less flexible solutions. Our software spans both approaches but is currently fragmented across two GitHub organisations (epinowcast and epiforecasts), creating confusion for users.

Within our ecosystem, EpiNow2 has approximately 50,000 downloads and is widely used by health agencies, while epinowcast is emerging as the next-generation solution. The scoringutils package has become the standard for forecast evaluation across multiple international initiatives. This fragmentation across organisations with overlapping functionality creates inefficiencies and barriers to adoption.

All our packages have progressed beyond the prototype stage. EpiNow2, scoringutils, primarycensored, and socialmixr are available on CRAN with stable releases, all past version 1.0 and with 3-5+ years of active development. Epinowcast and epidist, though not on CRAN due to a cmdstanr dependence, have had multiple stable releases and are past version 1.0. All packages have multiple contributors (5+ for smaller packages, 20+ for core tools like epinowcast and EpiNow2).

For real-time estimation tools, EpiEstim attracts a significant user base, especially those newer to the field. It offers simpler functionality but faster computation, with methodological limitations due to its design as a pure R package and use of conjugate priors. Epidemia provides comprehensive features for modelling infectious disease dynamics by integrating multiple data sources but has seen dormant development for the past two years. EpiMap integrates population flows to model transmission across areas but has limited traction with no significant user base.

For delay distribution estimation tools, [PLACEHOLDER: comparison with other delay estimation packages]

For contact matrix tools, [PLACEHOLDER: comparison with other contact matrix packages]

For forecast evaluation tools, [PLACEHOLDER: comparison with other scoring/evaluation packages]

In the broader ecosystem, our work complements initiatives like Epiverse-TRACE, which focuses on implementing existing outbreak analysis methods in R for non-expert users. While Epiverse focuses on accessibility for non-experts, our approach prioritises methodological innovation and integration for advanced users while maintaining accessibility. [PLACEHOLDER: further comparison with Epiverse and other ecosystems]

Our software uniquely bridges pipeline flexibility with joint modelling rigour, balancing methodological sophistication with user accessibility. All packages are MIT licensed, making them fully open source and accessible for both research and commercial applications. The proposed harmonisation will create a unified ecosystem that maintains this balance while reducing redundancy and confusion.

# Measure of impact (optional)

*0 / 250 words*
*Briefly describe how you would measure the impact of the proposed work. You may have existing measures that you use, or you may propose new measures. For the Expression of Interest we are looking to understand how you would approach this, and what you think is important to measure. In the full application, you will be asked to define specific measures.*

We will measure impact across four key dimensions:

Technical improvements: We will track reduction in reported bugs, improved test coverage across packages, decreased resolution time for critical issues, and performance improvements for key operations. We will also measure the reduction in duplicated code across packages and the implementation of shared interfaces and components.

User adoption: We will monitor package downloads, GitHub stars/forks, citations in academic literature, and adoption by public health agencies. Specifically, we will track users successfully migrating from legacy to harmonised tools and reduced support requests due to inconsistencies.

Community health: We will assess the number of active contributors, geographic and institutional diversity of contributors, first-time contributor conversions, and community forum engagement. We will particularly focus on contributors spanning previously separate tools.

Governance and sustainability: We will track the establishment of a single governance structure for the entire epinowcast ecosystem, implementation of clear onboarding processes for new packages and contributors, and development of a unified roadmap. Post-funding sustainability will be ensured by significantly decreasing the maintenance burden through standardised interfaces and reduced technical debt, empowering contributors through improved governance, and continuing our established practice of integrating ongoing research with software development to ensure relevance and funding opportunities. By expanding our user base through improved discoverability and documentation, we'll also create a broader pool of potential contributors and institutional stakeholders with interest in maintaining these critical public health tools.

These metrics will be collected continuously and reported quarterly throughout the project, with baseline measurements established at project initiation. This comprehensive approach will ensure we can demonstrate both technical improvements and broader ecosystem health.

