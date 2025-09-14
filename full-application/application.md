# Summary

## Summary

Our infectious disease modelling tools are fragmented across two organisations with inconsistent interfaces, overlapping functionality, and a distributed maintenance burden, creating barriers to adoption and inefficiencies.
These tools are currently used by major public health agencies, including UKHSA, WHO, CDC, and ECDC for situational awareness of infectious diseases, as well as by multiple independent research groups.
Collectively, they have been downloaded over 100,000 times with significant community engagement and have been cited in over a 100 academic papers.

Many of these packages were developed rapidly during the COVID-19 pandemic, prioritising utility over long-term sustainability.
Users struggle to discover and apply appropriate methods, while developers face significant technical debt and duplicated maintenance efforts.
The ecosystem lacks clear governance and contribution pathways that would allow it to onboard new developers and evolve to match user needs.
Without intervention, these challenges will limit the impact and sustainability of these valuable tools.

This project will unify, harmonise, and establish sustainable governance for our ecosystem of infectious disease modelling tools.
We will systematically address the current challenges through the following key activities:

1. **Creating a unified ecosystem** with a single entry point for packages across both organisations, providing clear signposts for users and establishing a unified roadmap that ensures ongoing relevance and funding opportunities.

2. **Standardising user interfaces** by seeking user and developer feedback on the divergent approaches across packages to enable consistent, intuitive interactions.

3. **Establishing formal governance structures** for the unified ecosystem to support sustainable maintenance, facilitate decision making, and enable broader community participation.

4. **Reducing code duplication** by identifying and implementing shared components across packages, improving interoperability and creating sustainable pathways for maintenance with next-generation frameworks.

5. **Building community capacity** through improved contribution guides, onboarding materials, and infrastructure that facilitates communication across the ecosystem, plus targeted workshops for both new developers and users.

Our approach involves creating shared statistical components that can be implemented once and reused across multiple packages.
This reduces duplication of effort, improves functionality, and enables greater collaboration between developers.
We will identify opportunities for such shared components that reduce maintenance burden while improving the tools' capabilities.

Through these activities, we will provide public health agencies and researchers with a more coherent, maintainable set of tools for infectious disease modelling, enabling more effective responses to both routine surveillance and emerging threats across diverse global settings.
The project directly addresses the sustainability challenges facing these widely-used tools, ensuring they remain available and effective for supporting UK and global health security.

## UKRI areas

*Please choose the UK research councils who would normally fund the research enabled by the software to be maintained in this work.*

# Vision

## Software to be maintained

epinowcast, primarycensored, baselinenowcast, epidist, scoringutils, socialmixr, EpiNow2

## Code repository (optional) 

*If there is a public repository for the software, please enter it.*

https://github.com/epinowcast, https://github.com/epiforecasts

All packages have individual repositories within these organisations.

## Website (optional)

*If there is a website for the software, please enter it,*

https://epinowcast.org, https://epiforecasts.io

All packages have linked subsites within these organisation websites.

## Year development started

*Please enter the year that development of the software first started. If you are applying for support for multiple pieces of software, use the earliest date.*

2020

## Year of first release

*Please enter the year that the software was first released. If you are applying for support for multiple pieces of software, use the earliest date.*

2020

## Programming language

*Please enter the primary programming language(s) that your software is/are written in.*

R, Stan

# Vision

*Please describe what you are hoping to achieve with this funding,*

*Discuss both your vision and objectives for the technical development, as well as your plans to improve your software's sustainability and support EDIA considerations.*

## Vision

*Explain how your proposed work will:*

- *have a benefit and impact on research, with specific examples of research impact in the UK*
- *build the community around the software*
- *increase the adoption of the software*
- *improve the maintainability of the software*
- *advance good practice*

*300 words*

This project will unify, harmonise, and establish sustainable governance for our ecosystem of infectious disease modelling tools, delivering significant value to UK research by addressing the fragmentation across organisations.
UK public health agencies currently use these tools to support outbreak response and surveillance for infectious diseases including COVID-19, influenza, and norovirus.
The harmonised ecosystem will enable more robust outbreak response capabilities for emerging threats and facilitate research into reporting delays and biases in surveillance systems.
Researchers use our tools for methodological comparison and validation.
For example, scoringutils is widely used for evaluating forecast models, EpiNow2 has been used for evaluating methods like EpiFusion (Judge et al. 2024) and viral load based approaches (Hay et al. 2021), and epinowcast has been used to evaluate methods for nowcasting (Mellor et al. 2024).
This cross-method validation is crucial for advancing epidemiological research.
Other examples of research enabled by this ecosystem include real-time situational awareness during outbreaks and robust estimation of reporting delays in surveillance systems.

The ecosystem currently lacks clear governance and contribution pathways that would allow it to onboard new developers and evolve to match user needs.
Establishing formal governance structures for the unified ecosystem will support sustainable maintenance, facilitate decision making, and enable broader community participation.
We have established some contribution pathways with guides, forums, and support channels across both ecosystems, demonstrating our capacity to scale the community further through improved governance and documentation.
By improving contribution guides and onboarding materials, we will expand our contributor pool and distribute maintenance responsibility across a wider community.

Creating a single entry point for packages across both organisations will provide clear signposts for users, while standardising user interfaces will enable consistent, intuitive interactions.
By simplifying the handling of complex surveillance data, our tools make sophisticated modelling more accessible, allowing researchers to focus more on epidemiological questions than data challenges.
The project aligns with key UK research priorities around pandemic preparedness, health data science infrastructure, and methodological innovation, enabling more efficient knowledge transfer between research groups and institutions through reduced duplication and inconsistencies.
By creating a coherent ecosystem with standardised interfaces and unified governance structures, this project will advance good practice in research software development, and help to establish methodological and technical standards.

## Objectives

*Clearly describe the aims and objectives of this work.*

*200 words*

**Overall Aim**: To harmonise critical infectious disease modelling tools currently used by UKHSA, academic groups, and organisations, addressing the fragmentation across our organisations so that users can discover, apply, and contribute to appropriate methods.

**Specific Objectives**:

1. **Create a unified ecosystem** with a single entry point for packages across both organisations, providing clear signposts for users and establishing a unified roadmap that ensures ongoing relevance.

2. **Standardise user interfaces** by seeking user and developer feedback on divergent approaches across packages to enable consistent, intuitive interactions.

3. **Establish formal governance structures** for the unified ecosystem to support sustainable maintenance, facilitate decision making, and enable broader community participation.

4. **Reduce code duplication** by identifying and implementing shared components across packages, improving interoperability and creating sustainable pathways for maintenance.

5. **Build community capacity** through improved contribution guides, onboarding materials, and infrastructure that facilitates communication across the ecosystem, plus targeted workshops for developers and users.

These objectives will enable more robust outbreak response capabilities for emerging threats and facilitate research into reporting delays and biases in surveillance systems, while making sophisticated modelling more accessible to researchers.

## Timeliness and Sustainability

*Justify why it is important that your project is funded in this round, and include:*

- *why it is important that this work is funded now, rather than at a different time*
- *what other funding sources have been investigated, and why these are not suitable*
- *how the software will be sustained and maintained after the RSMF funding ends, and how the RSMF funding will help achieve this*

*300 words*

## EDIA

*Explain how you will embed equity, diversity, inclusivity and accessibility considerations into your proposed work and the software being maintained, and how these will guide your aims, objectives, activities and outputs.*

*This can include (but is not limited to) considerations applying to your team, your community, and your software.*

Our central motivation in this project is to create more accessible and inclusive software that makes best practices in infectious disease modelling available to all researchers, regardless of background or resources.
We are committed to fostering a welcoming and inclusive environment for contributors and users alike, where diverse voices are heard, valued, and empowered to both contribute to the project and use these tools in applied outbreak analysis.

**Community Diversity and Inclusion**

The epinowcast community already includes over 50 researchers globally, demonstrating our ability to foster inclusive collaboration across diverse geographical and institutional settings.
Core tools like epinowcast and EpiNow2 each have 20+ contributors from different backgrounds, showing our success in converting users into community members.
Our onboarding initiatives aim to facilitate participation from under-represented groups, and we have successfully onboarded contributions from a wide range of individuals, irrespective of gender, ethnicity, or location.

Through this project, we will strengthen community diversity by improving contribution guides and onboarding materials specifically designed to support individuals from diverse backgrounds, particularly those who are under-represented or from low-resource settings.
The planned workshops for developers and users will actively seek to include participants from diverse institutions and career stages, with particular attention to supporting early-career researchers and those from under-represented groups.

**Software Accessibility**

By using entirely open-source, publicly available, and free-of-cost platforms such as GitHub and R, we ensure opportunities within our software development processes are available to anyone.
Our approach of simplifying the handling of complex surveillance data makes sophisticated modelling more accessible, allowing researchers to focus on epidemiological questions rather than technical barriers.
The standardised interfaces and improved documentation resulting from this harmonisation project will reduce technical barriers to adoption, particularly benefiting researchers with limited computational resources or training.

**Inclusive Development Practices**

Both team members actively promote inclusive research cultures.
Sam has created an environment through the epinowcast community that nurtures early-career researchers through organising seminars, maintaining discussion forums, and coordinating collaborative development.
Sebastian has led development of openly accessible training courses used by researchers worldwide for self-study, demonstrating commitment to removing educational barriers.

Our approach focuses on providing meaningful opportunities for growth with structured support tailored to individual needs and career stages.
We are committed to continuously assessing and improving our EDIA efforts, guided by feedback from our community members and ensuring our unified governance structures embed these principles from inception.

# Approach

*Explain what work you have planned, and how you will manage this. Cover both the technical as well as project management areas.*

**Planned work**
- *where applicable: summary of any previous work and how this will be built upon and progressed*
- *where applicable: a clear and transparent methodology*
- *effective and appropriate activities to achieve your objectives*
- *which team members are responsible for each activity and task*
- *expected outputs for each task and how they relate to each other*
- *a timeline with a feasible workplan*
- *strategy to maximise translation of outputs into outcomes and impacts*

**Management**
- *how the work will be managed and progress monitored and evaluated*
- *how the current software project governance and infrastructure will contribute to the success of the work*
- *what risks to delivery were identified and how they will be managed*

*2000 words*

*Add a Gantt chart to show the timings of activities*

# Capability to deliver

## Relevant Experience

Our team created and maintains the tools this project seeks to harmonise, giving us unique understanding of both the code and communities that rely on these tools.

Dr. Sam Abbott will lead the project at 100% FTE.
As founder of the epinowcast community and developer of key packages across both organisations, Sam has translated methodological innovations into accessible tools used by UKHSA, CDC, and ECDC.
His track record includes leading development of EpiNow2 (downloaded over 50,000 times), creating the epinowcast ecosystem, and developing primarycensored as a shared component that exemplifies our unification approach.
Sam has successfully managed the transition of research software from pandemic-driven rapid development to sustainable long-term maintenance, directly addressing the challenges this project seeks to resolve.

Professor Sebastian Funk will provide strategic guidance at a fractional FTE.
As Director of CMMID at LSHTM and a Wellcome Senior Research Fellow, Sebastian brings leadership experience and public health networks essential for achieving our objectives.
He has led multiple open-source software projects, including socialmixr and rbi, demonstrating his ability to guide complex software ecosystems to maturity.

## Balance of Skills and Expertise

Our team composition directly maps to the five categories of work: technical, community, documentation, training, and governance.
Sam brings expertise in R package development, Stan modelling, and software architecture, while our planned senior research software engineer will provide specialised technical implementation skills.
Sebastian's networks in public health and infectious disease modelling provide access to user communities whose needs will drive our harmonisation efforts.

We have established contribution pathways with guides, forums, and support channels across both ecosystems.
Core tools like epinowcast and EpiNow2 each have 20+ contributors, showing our ability to convert users into community members.
This demonstrates our capacity to scale the community further through improved governance and documentation.

## Leadership and Management Skills

Sam's leadership capabilities are demonstrated through successful management of the epinowcast ecosystem, coordinating development across multiple packages.
He has built the epinowcast community to include over 50 researchers globally, demonstrating his ability to foster inclusive collaboration.

Sebastian provides strategic leadership through directing a major research centre with over 40 academic staff and coordinating international collaborations.
His experience managing large, multi-institutional projects provides oversight skills necessary for delivery across our technical and community objectives.

## Contributing to Good Practice

We have established open development practices across both organisations, including transparent contribution guidelines, and code review processes.
Sam has contributed to good practice through developing methodologies for sustainable research software development, including community building and technical debt management.
Sebastian has contributed through policy development and advocacy for research software sustainability within the research community.

## Approach to Developing Others

Our approach focuses on providing meaningful opportunities for growth with structured support tailored to individual needs and career stages.
Sam has supervised multiple researchers through formal supervision, including co-supervising Katherine Sherratt's PhD on collaborative modelling and serving on Nikos Bosse's PhD advisory board for forecast scoring software development.
He has created an environment through the epinowcast community that nurtures early-career researchers, including organising seminars, maintaining discussion forums, and coordinating collaborative development.

Sebastian has extensive experience developing others through supervision of PhD students and early-career researchers at LSHTM.
He has led development of openly accessible training courses on model fitting and nowcasting infectious disease dynamics, used by researchers worldwide for self-study.
Both team members actively promote inclusive research cultures.

The planned workshops in this project - one for onboarding developers and another for training users - will allow us to reach broader audiences.

# Project partners

*Upload a single PDF containing all Project Partner Letters of Support.*

*Each individual Letter of Support should be no more than two A4 pages, provided on headed paper, dated within six months of the application submission date and signed by the named contact (or appropriate responsible party).*

*A well written project partner letter of support will confirm the organisation's commitment to the proposed project and should identify:*

- *the value, relevance and possible benefits of the proposed work to the partner*
- *the period of support, the full nature of the collaboration or support*
- *how the partner will provide added value*

*Project partner contributions whether in cash (direct) or in kind (indirect), must be explained in detail in the project partner letter of support. A value must be put on in-kind contributions:*

# Resources

## Justification of resources

*Justify the application's more costly resources, in particular:*

- *any staff costs*
- *significant costs related to collaboration or community engagement*
- *any consumables beyond typical requirements*
- *infrastructure costs*
- *all resources that have been costed as 'Exceptions'*

*You do not need to justify Estates and Indirect costs.*

*We are not looking for a detailed breakdown of each cost, but want you to demonstrate how the resources you are applying for are comprehensive, appropriate and justified, and represent the optimal use of resources to achieve the intended outcomes.*

*1000 words*

Dr Sam Abbott will lead the project at 100% FTE.
As founder of the epinowcast community and developer of key packages across both organisations, Sam has unique understanding of both the technical architecture and user communities.
Full-time commitment is essential for coordinating harmonisation across seven packages in two organisations while building governance structures and community capacity.

Professor Sebastian Funk will provide strategic guidance at fractional FTE.
As Director of the CMMID at LSHTM, Sebastian brings leadership experience and public health networks essential for stakeholder engagement and ensuring alignment with research community needs.

The team will include a senior research software engineer who will implement technical aspects of unification, interface standardisation, and code deduplication.
This role is necessary because harmonising complex R packages with Stan backends requires specialist expertise in software architecture and statistical computing frameworks.

The project includes two targeted workshops: one for onboarding new developers and another for training users.
These workshops represent necessary investments in building sustainable contributor communities and ensuring effective adoption of the harmonised ecosystem.
Workshop costs cover venue, materials, and facilitation expenses for bringing together developers and users to establish contribution pathways and transfer knowledge about the unified tools.

## Total funding requested

## Directly incurred - staff 

## Directly incurred - Travel and Subsistence

## Directly incurred - Other

## Directly allocated - Staff

## Directly allocated - Estates

## Directly allocated - Other

## Indirects

## Exceptions

## Budget

*The lead organisation's consolidated budget in a standard FEC costing format.*

## Signoff

### Evidence of lead organisation approval

*You must provide evidence that the appropriate person at the lead organisation has given approval for this application to be submitted, that the budget is accurate, and that all participating organisations have agreed to the submission. This could be in the form of an email from your head of department or similar, or research office, or confirmation of approval in your research grants system.*
