# Application name

Standardising and formalising the epinowcast ecosystem

# Project details

*Please indicate if you are expecting to apply for a Large Award of up to 2 years duration and up to £500,000 budget or a Small Award of up to 1 year duration and up to £150,000 budget. Full budget details will be required at the full proposal stage.*

Large Award: 2 years duration, up to £500,000 budget

# Proposal summary / scope of work

*0 / 500 words*
*Please provide a short summary of the work being proposed. Please note that this summary may be publicly published - do not include any confidential information.* 

Infectious disease modelling tools are essential for effective public health response, yet our current offerings are fragmented across the epinowcast and epiforecasts organisations. These tools, some developed rapidly during the COVID-19 pandemic, now face challenges of inconsistent interfaces, overlapping functionality, and distributed maintenance burden.

This project aims to harmonise packages across both organisations, creating a unified framework under the epinowcast ecosystem. We will migrate key epiforecasts packages into the epinowcast organisation, establish standardised governance, and implement common interfaces and shared components. Our focus will be on creating a sustainable infrastructure that allows for future package onboarding and integration.

Specifically, we will harmonise core epinowcast packages (epinowcast, baselinenowcast, primarycensored, epidist) with key epiforecasts packages (EpiNow2, scoringutils, socialmixr), whilst developing integration layers with Julia-based probabilistic programming tools. This work will address technical debt accumulated during rapid development, standardise interfaces between packages, and implement common backends for shared functionality like delay distribution handling.

These tools are currently used by major public health agencies including UKHSA, CDC, and ECDC, making their sustainability crucial for ongoing infectious disease surveillance and response. By unifying the ecosystem, we will provide users with simplified package discovery, consistent interfaces, clear migration paths from legacy tools, and unified documentation and support channels.

The project will create formal governance structures and community-building initiatives, including monthly developer meetings, user-centred design approaches, and improved onboarding processes for contributors. We will establish metrics to track technical improvements, user adoption, and community growth throughout the project.

This harmonisation effort will significantly benefit UK research by providing a more robust, maintainable set of tools for infectious disease modelling, enabling more effective public health response to both routine surveillance and emerging threats.

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

Our team is uniquely positioned to harmonise the epinowcast ecosystem, as we are the original creators and maintainers of both the epinowcast and epiforecasts package collections. This gives us comprehensive understanding of both ecosystems, a clear vision for unification under the epinowcast umbrella, and practical experience in migrating and harmonising related packages.

The project will be led by Sam Abbott, who has developed widely-used packages across both organisations, with installs exceeding 50,000. Sam brings extensive experience working with multiple public health agencies including UKHSA, CDC, and ECDC, and has successfully managed the transition of several tools between frameworks.

We will employ a dedicated Research Software Engineer with expertise in R package development to implement harmonisation strategies and develop shared components. This role is critical for addressing technical debt while maintaining service to existing users.

Sebastian Funk will provide strategic guidance and stakeholder management. His experience leading large-scale infectious disease modelling efforts will ensure our technical direction aligns with evolving research and public health needs.

Our team already maintains active connections with both contributor communities and institutional users spanning both package ecosystems. This positions us ideally to unify governance models, standardise development practices, and create a sustainable framework for future growth and maintenance of these essential public health tools.

# Benefit to UK research

*0 / 250 words*
*Briefly describe the expected value of the proposed work to UK research. You may wish to describe the fields of research or types of research method the software is used in, and describe the benefits to a particular community. You may also want to give examples of what research is enabled by the software.*

This project will deliver significant value to UK research by harmonising critical infectious disease modelling tools currently used by UKHSA, academic epidemiology groups, and NHS planning teams. By unifying tools across the epinowcast ecosystem, we will provide UK researchers with a simplified, more consistent toolchain that reduces learning curves and technical overhead.

UK public health agencies currently rely on these tools for nowcasting infectious diseases including COVID-19, influenza, and norovirus. The harmonised ecosystem will enable more robust outbreak response capabilities for emerging threats and facilitate research into reporting delays and biases in surveillance systems.

The project aligns with key UK research priorities around pandemic preparedness, health data science infrastructure, and methodological innovation in infectious disease modelling. By reducing duplication and inconsistencies between tools, we will enable more efficient knowledge transfer between research groups and institutions.

Examples of research enabled by this harmonised ecosystem include real-time situational awareness during outbreaks, comparative analyses across multiple diseases, seamless integration of nowcasting and forecasting, and combined modelling of reporting delays with transmission dynamics. UK researchers will benefit from standardised approaches to evaluate interventions and integrate diverse data streams, including clinical, genomic, and wastewater surveillance data.

# Landscape analysis

*0 / 250 words*
*Briefly describe the other software (either proprietary or open source) that is primarily used by the research community addressed by the work in this proposal. Summarise, to the best of your knowledge, how the software in this proposal compares to these other software in terms of user base size, usage, and maturity. Describe, if appropriate, how the other software interacts with the software in this proposal.*

The infectious disease modelling landscape features two main approaches: pipeline approaches that combine separate models, and joint modelling approaches offering more integrated but less flexible solutions. Our software spans both approaches but is currently fragmented across two GitHub organisations (epinowcast and epiforecasts), creating confusion for users.

Within our ecosystem, EpiNow2 has approximately 50,000 downloads and is widely used by health agencies, while epinowcast is emerging as the next-generation solution. The scoringutils package has become the standard for forecast evaluation across multiple international initiatives. This fragmentation across organisations with overlapping functionality creates inefficiencies and barriers to adoption.

Other open-source alternatives include EpiEstim, which offers simpler functionality but faster computation; Epidemia, which provides comprehensive features but has seen dormant development; and EpiMap, which has limited traction. Proprietary solutions exist but often lack flexibility for adaptation to new threats, have accessibility barriers for low-resource settings, and present challenges with transparency and reproducibility.

Our software uniquely bridges pipeline flexibility with joint modelling rigour, balancing methodological sophistication with user accessibility. The proposed harmonisation will create a unified ecosystem that maintains this balance while reducing redundancy and confusion. By standardising interfaces and processes, we will also facilitate easier integration with other modelling frameworks, strengthening the entire infectious disease modelling landscape.

# Measure of impact (optional)

*0 / 250 words*
*Briefly describe how you would measure the impact of the proposed work. You may have existing measures that you use, or you may propose new measures. For the Expression of Interest we are looking to understand how you would approach this, and what you think is important to measure. In the full application, you will be asked to define specific measures.*

We will measure impact across four key dimensions:

Technical improvements: We will track reduction in reported bugs, improved test coverage across packages, decreased resolution time for critical issues, and performance improvements for key operations. We will also measure the reduction in duplicated code across packages and the implementation of shared interfaces and components.

User adoption: We will monitor package downloads, GitHub stars/forks, citations in academic literature, and adoption by public health agencies. Specifically, we will track users successfully migrating from legacy to harmonised tools and reduced support requests due to inconsistencies.

Community health: We will assess the number of active contributors, geographic and institutional diversity of contributors, first-time contributor conversions, and community forum engagement. We will particularly focus on contributors spanning previously separate tools.

Governance and sustainability: We will track the establishment of a single governance structure for the entire epinowcast ecosystem, implementation of clear onboarding processes for new packages and contributors, development of a unified roadmap, and progress toward NumFocus affiliated project status.

These metrics will be collected continuously and reported quarterly throughout the project, with baseline measurements established at project initiation. This comprehensive approach will ensure we can demonstrate both technical improvements and broader ecosystem health.

