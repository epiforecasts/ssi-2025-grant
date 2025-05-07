
3. Proposal Purpose:
Describe the purpose of the proposal in one sentence (maximum of 200 characters including spaces).  Example: To develop a comprehensive, validated atlas of the human kidney at single-cell resolution open to the entire scientific and clinical community.
To develop robust tools for real-time infectious disease analysis and response, with a priority on developing the community around them and improving their accessibility in under-represented settings.


4. Amount Requested
Year one:
Year two:
Total all years: 
$361,711

5. Proposal Summary/Scope of Work
Provide a short summary of the work being proposed (maximum of 500 words)
The modern landscape of infectious disease research and response requires real-time analysis tools that can adapt to rapidly changing scenarios. The epinowcast.org initiative is at the forefront of this challenge, bringing together a multidisciplinary community of infectious disease modellers, epidemiologists, and software developers. Our mission is to create a comprehensive suite of tools tailored for real-time infectious disease analysis. Leading global health organisations, including the World Health Organisation (WHO) and the US and European Centres for Disease Control (CDC/ECDC) have already begun to adopt these tools. We now need to prioritise these tools’ accessibility and usability in a wide range of contexts, including their use by health agencies in low-resource settings.
Our core offering is the epinowcast R package, a sophisticated tool designed for the hierarchical nowcasting of right-truncated epidemiological time-series. Leveraging a semi-mechanistic Bayesian model, it provides insights into current disease trends by analysing available observations in the context of historical reporting patterns. This "nowcasting" approach is invaluable in real-time infectious disease tracking, as it offers clarity in situations where trend changes might be obscured by partial reporting or delayed detection. Epinowcast.org has its roots in the EpiNow2 package developed by our team, which has been downloaded over 25,000 times and is a key tool for numerous research groups and national/international health agencies.
We wish to use this opportunity to support the project as follows:
1. Enhancement of the epinowcast package: We will refine and expand the epinowcast R package to ensure its robustness and generic applicability for monitoring infectious diseases using prevalent epidemiological data sources.
2. User support: To foster wider adoption of our tools, we will expand our documentation, ensuring that users, regardless of their technical proficiency, can harness their full potential. This will be complemented by additional support for users as resources allow.
3. Tailoring for low-resource settings: Infectious diseases in low-resource settings often have the greatest impact, and also face specific analytical and accessibility challenges. We will identify stakeholders with expertise in these settings and collaboratively refine our tools to cater to these challenges.
4. Development of the epidist package: Building on recent research highlighting the significance of delay distributions in outbreak responses, we plan to develop the prototype epidist package. This tool estimates delay distributions and accounts for common biases found in infectious disease surveillance data.
5. Community engagement and expansion: At the heart of our initiative is the belief in community collaboration. We will use this grant to assist in formalising a community governance structure; onboarding, with an emphasis on integrating members from low-resource settings; and to expand our community meeting series with an additional monthly developer meeting. Furthermore, we will support the development of community packages.
We have a clear vision, a suite of cutting-edge tools, and a commitment to community collaboration. With the support of this grant, we seek to fortify the computational foundations of real-time infectious disease responses, making them more robust, accessible, and impactful.
6. Work Plan:
A description of the proposed work for which funding is being requested, including resources the applicants will provide that are not part of the requested funding. For software development-related work (e.g., engineering, product design, user research), specify how the work fits into the existing software project roadmap. For community outreach related activities (e.g., sprints, training), specify how these activities will be organized, the target audience, and expected outcomes (maximum of 750 words)
Overall roadmap:
Over the next two years, we seek to equitably expand the epinowcast community while continuing to improve our open-source software offering and maintaining legacy projects such as EpiNow2.
Specifically, we aim to prioritise accessibility in low-resource settings, strengthen the overall diversity of the contributing community, and formalise a sustainable community governance structure. 
Software improvements will focus on both robustness improvements and methodological extensions (partly funded by the Wellcome Trust 210758/Z/18/Z) and US-based deployment and validation case studies (partly funded by the US Centers for Disease Control and Prevention, CDC, CDC-RFA-FT-23-0069). We also aim to expand our current funding model from one focused on the core team to becoming more evenly spread across contributors and organisations.
Related work for this grant:
Work in this grant will focus on expanding, diversifying, and supporting the community around our current software offerings, formalising our governance structure, improving the robustness of our tools, and supporting the onboarding of community-driven software tools. We will:
1. Enhance the epinowcast Package:
Use methods for user-centred design, including stakeholder mapping and user surveys, to guide the future package development roadmap.
Refine the epinowcast R package for robustness and generic applicability.
Upgrade the user interface focusing on user-friendliness and efficiency.
2. User Support:
Develop comprehensive, user-friendly documentation for the epinowcast and epidist packages.
Provide active user support through the epinowcast forum, Github issues, and regular community meetings.
Produce case studies that help transition EpiNow2 users to becoming epinowcast users.
3. Tailor for Low-Resource Settings:
Analyse challenges in low-resource settings and adapt tools accordingly using user input, integrated into the stakeholder mapping and user research proposed above.
Ensure accessibility and effectiveness in resource-constrained environments by developing with these contexts in mind.
Focus developer resources on helping onboard users from these settings so that they can become community contributors.
4. Develop the epidist Package:
As for the epinowcast package, use methods for user-centred design, including stakeholder mapping and user surveys, to guide the future package development roadmap.
Add improved test coverage and software development infrastructure to the package.
Generalise its functionality to include other probability distributions than the currently supported lognormal distribution.
5. Community Engagement and Expansion:
Identify models for sustainable community governance, consult with community members, and adopt a formal governance structure.
Organise monthly virtual developer meetings to enhance collaboration. These meetings will aim to cover a wide range of topics of interest to the community including the design philosophy of epinowcast packages, the design philosophy of other open source software projects, R package development, stan development, Git, and GitHub skills, and unit testing.
Support the development of community packages like hashprng and coerceDt as resources allow. Aiming to onboard at least 3 throughout the grant.
Become an affiliated NumFocus project.
Use the resources from this grant to increase activity on our community site and blog. In particular, we will improve the newcomer experience on the two sites.
Expected Outcomes:
Improved, robust epinowcast and epidist R packages with user-friendly documentation and interfaces.
Expanded community engagement, including wider participation in under-represented low-resource settings.
A formal governance structure for the epinowcast community.
Experience and knowledge of formal approaches for user-centred design in constructing project road maps.
Support for the development of complementary community packages.
Increased adoption of epinowcast tools by global and local health organisations and research groups for real-time infectious disease tracking and response.
7. Milestones and Deliverables:
List expected milestones and deliverables, and their expected timeline. Be specific and include where possible any goals for metrics the software project(s) are expected to reach upon completion of the grant. Please use a third-person voice (maximum of 500 words).
First 6 Months:
epinowcast:
Version 1.0.0 release
Release to CRAN
Stakeholder map created
User survey sent out
epidist:
Prototype package refined to a version 1.0.0 release
Release to CRAN
Community development:
Begin community seminar series on software engineering
Draft proposal for community governance and draft approach for engaging with the community on this proposal
First Year:
epinowcast:
100 GitHub stars
30 code contributors
10k downloads on CRAN
User survey analysed and report shared on the epinowcast blog
Academic paper illustrating use cases of the epinowcast package and introducing the epinowcast community
epidist:
Functionality added to support multiple distributions
5k downloads on CRAN
10 code contributors
25 GitHub stars
User survey sent out
Stakeholder map created
Community development:
100 community forum members
Accepted proposal for community governance
Become a NumFocus ​​Affiliated project
Support the CRAN release of at least two community packages
18 Months:
epinowcast:
150 GitHub stars
35 code contributors
15k downloads on CRAN
Roadmap responding to user survey published on the epinowcast blog
Paper/blogpost based on user research exploring barriers and opportunities for adopting epinowcast in different settings.
epidist:
Case study for estimating delays during an outbreak published
10k downloads on CRAN
15 code contributors
40 GitHub stars
User survey analysed and posted to the epinowcast community blog
Academic paper showcasing the epidist package
Community development:
150 community forum members
Community governance setup
Organised community discussion to propose new community packages
Second year:
epinowcast:
200 GitHub stars
40 code contributors
20k downloads on CRAN
First part of user roadmap complete
epidist:
Case study for estimating time-varying delays published
15k downloads on CRAN
30 code contributors
50 GitHub stars
User roadmap published to the epinowcast blog
Community development:
150 community forum members
Community governance setup
Supported community members (i.e. independent of the core team funded on this grant)  to secure funding for work within the epinowcast community
Support the CRAN release of an additional community package.
8. Existing Support:
List active and recently completed (previous two calendar years) financial or in-kind support for the software project(s), including duration, total costs in USD, and source of funding. Include any previous funding for these software projects received from CZI, Wellcome, and/or Kavli outside of the EOSS program (maximum of 250 words).
Real-time modelling for forecasts during infectious disease outbreaks (Wellcome Trust, $2.04 million to SF) supports the development of forecasting methodology and validation and has supported the development of the EpiNow2 package and the methodology used in the epinowcast package, but does not extend to dedicated support for software development and maintenance, user engagement and community building that is at the heart of this proposal.
Center for Implementation in Outbreak Analytics and Disease Modeling: Multi-Scale Outbreak Decision-Support Tools (CDC, $1.1 million to SF) supports the implementation of nowcasting and forecasting tools across the US but no specific funding for the broader applicability of the tools we are envisioning with this proposal.
Groundwork for building the next generation of outbreak and surveillance methodology and tools (­LSHTM COVID-19 response fund, $19,000 to SA) supported the initial setup and running fees for the epinowcast community site and of the continuous integration used in the epinowcast R package.
9. Landscape Analysis
Briefly describe the other software tools (either proprietary or open source) that the audience for this proposal primarily uses. How do the software project(s) in this proposal compare to these other tools in terms of user base size, usage, and maturity? How do existing tools and the project(s) in this proposal interact? (maximum of 250 words)
1. EpiNow2: The predecessor of epinowcast.org, EpiNow2 is actively developed and has a large user base. Epinowcast seeks to build on the foundation laid by EpiNow2 and offer a toolset that is both more user-friendly for newcomers and also modular enough for advanced users. Epinowcast represents the next generation of infectious disease modelling tools.

2. EpiEstim: Developed over a decade ago, it attracts a significant user base, especially those newer to the field. EpiEstim has methodological limitations due to its design as a pure R package and its use of conjugate priors to enable inference. It offers a more basic feature set, which epinowcast encompasses, but can return results very quickly. Performance between the two becomes closely matched when comparing similar functionalities but the more advanced features epinowcast offers in dealing with the intricacies of outbreak data are crucial in many real-world settings.

3. Epidemia: An extension of the rstanarm package, Epidemia provides a comprehensive feature set for modelling infectious disease dynamics by integrating multiple data sources. It has seen some use, but its development has been dormant for the past two years.

4. EpiMap: Integrates population flows to model transmission across areas, EpiMap has limited traction with no significant user base and has seen no ongoing development.

Many infectious disease modellers build their tools, commonly using the stan probabilistic programming language. Epinowcast supports this practice by ensuring our tools are modular stan code. This allows users to enhance their work, bridging the gap between standardized tools and custom solutions.
10. Value to Biomedical Users
Described the expected value of the proposed work to the biomedical research community (maximum of 250 words)
Infectious disease modelling, as showcased during the COVID-19 pandemic, has become an indispensable tool for interpreting data, assessing interventions, and predicting disease dynamics. The epinowcast.org initiative and associated suite of software tools, building upon the success of the EpiNow2 R package, aims to address a critical gap in preparedness. Historically, tools for infectious disease modelling have often been developed rapidly in response to an outbreak and abandoned afterwards. This reactive and unsystematic approach can lead to delays in effective responses. Our project seeks to proactively equip public health institutions with robust, state-of-the-art tools that implement appropriate statistical methodology and can handle diverse types of data typically collected during infectious disease outbreaks. By providing these tools, we aim to bolster the community's capacity to respond swiftly and effectively to future infectious disease outbreaks, ensuring that they are not just reacting to crises but are well-prepared in advance.

Outside of a response, our project aims to provide a workbench for researchers that enables them to evaluate model adaptations within our framework and then, if they are shown to perform well, to contribute them back so that others can build on them. This kind of collaborative iterative development based on benchmarks and standardised models has been harnessed in other fields, such as machine learning, to make rapid progress but has been largely absent from infectious disease modelling.

e. Open Source Software Projects
Number of software projects are involved in your proposal (maximum of five):
Epinowcast 
Epidist

11. Category
Choose the two categories that best describe the software project(s) audience.

Infectious diseases, Machine learning and data analysis (GP is machine learning innit)


12. Diversity, Equity, and Inclusion Statement:
Advancing DEI is a core value for this program, and we are requesting information on your efforts in this area. Describe any efforts the software project(s) named in this proposal have undertaken to increase diversity, equity, and inclusion with respect to their contributors and audience. Please see examples from applications funded in previous cycles (maximum of 250 words) 
Our central motivation in this project is to create fully accessible and inclusive software that makes best practices in the field encouraged for all and open to anyone. In our software projects, including epinowcast and epidist, we are committed to fostering a welcoming and inclusive environment for contributors and users alike. 
We make efforts to create a community where diverse voices are heard, valued, and empowered to both contribute to the project and use these tools in applied outbreak analysis. Community organisers actively seek to support individuals from diverse backgrounds, particularly those who are under-represented or from low-resource settings, within the community. Our onboarding initiatives aim to facilitate participation from under-represented groups, and we have successfully onboarded contributions from a wide range of individuals, irrespective of gender, ethnicity, or location. By using entirely open-source, publicly available, and free-of-cost platforms such as Github and R, we ensure opportunities within our software development processes are available to anyone. 
We are committed to continuously assessing and improving our DEI efforts, and we are consistently guided by feedback from our community members.
