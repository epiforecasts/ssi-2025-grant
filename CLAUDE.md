# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains grant application materials for the Software Sustainability Institute's Research Software Maintenance Fund (RSMF) 2025. The fund provides £4.8 million to support existing research software maintenance, focusing on reducing technical debt and improving sustainability.

### Key Software Packages

This application covers an ecosystem of epidemiological modelling R packages:

**epinowcast org:**
- `epinowcast`: Flexible Hierarchical Nowcasting - widely used by CDC, UKHSA for real-time epidemic nowcasting
- `primarycensored`: Backend for primary event censored distributions, linking across the ecosystem (EpiNow2, epinowcast, epidist)
- `baselinenowcast`: Baseline nowcasting method providing simple, interpretable nowcasting solutions
- `epidist`: Toolkit for epidemiological delay distribution estimation built on brms/Stan

**epiforecasts org:**
- `scoringutils`: Utilities for scoring and assessing predictions - integrated in hubverse as primary forecast scoring tool
- `socialmixr`: R package for deriving social mixing matrices from survey data
- `epinow2`: Most widely used package (~50k downloads) for estimating time-varying reproduction numbers

## Repository Structure

```
.
├── application/           # Original application materials
│   ├── application.md     # Original application form
│   ├── 10-key-sentences.md
│   └── contributors/      # Contributor statements
├── full-application/      # Full application form
│   └── application.md     # Formatted full application
├── past-applications/     # Previous grant applications for reference
├── resources/            # Application guidance and supporting materials
│   ├── call-summary.md   # RSMF call details
│   ├── application-details.md  # Detailed application requirements
│   ├── included-packages.md    # Package descriptions and ecosystem overview
│   └── coapplicants/     # Co-applicant details
└── README.md            # Project timeline and status
```

## Application Context

- **Fund**: Research Software Maintenance Fund (RSMF) 2025
- **Award Type**: Large Award (up to £500k for two years)
- **Focus Areas**: Technical debt reduction, community building, documentation, training, governance
- **Timeline**: Round 1 Expression of Interest deadline was 30 May 2025
- **Target**: Support existing research software used beyond creator organisations with demonstrable UK research impact

## Working with Application Materials

### Formatting Guidelines
- Guidance text should be in italics
- Use proper markdown lists for structured information
- One sentence per line in markdown documents
- Max 80 characters per line
- No trailing whitespace

### Key Application Sections
1. **Summary** (500 words) - suitable for policymakers, public, research communities
2. **Vision** - research impact, community building, adoption, maintainability
3. **Objectives** (200 words) - clear aims and objectives
4. **Approach** (2000 words) - planned work, management, Gantt chart required
5. **Capability** (1000 words) - team experience and skills evidence
6. **Resources** (1000 words) - budget justification

### Budget Categories
- Staff costs (developers, RSEs, community managers)
- Community engagement (hackathons, sprints, outreach)  
- Infrastructure (cloud computing, CI services)
- Cross-project coordination

## Git Workflow

- Main branch: `main`
- Never push directly to main without explicit request
- Use descriptive commit messages following existing style
- Include Claude Code attribution in commits when making automated changes

## File Management

- Prefer editing existing files over creating new ones
- Don't create documentation files unless explicitly requested
- Follow UK English spelling throughout
- Use `@placeholder` for missing references in markdown