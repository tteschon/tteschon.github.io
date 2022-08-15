---
title: Automation Operating Model
author: Tyler Teschon
date: 2022-08-15
category: Jekyll
layout: post
---

```yaml
toc:
    enabled: true
```

The Automation Operating Model (AOM) represents how an automation program orchestrates and executes it's intelligent automation capabilties to create and deliver value to an organization, in line with it's business model and strategic objectives.

:inbox_tray: Intake
-------------
### Opportunity Identification
Organic: business to CoE
- RPA Opportunity Form - capture consistent and relevant data for screening and preliminary assessment.
- Workshops
Inorganic: CoE to business
- Analyst interview

Process Mining - analytical technique that leverages both data mining and model based process analysis in order to discover or “mine” previously hidden insights about the current state of business processes through the analysis of their event data.

Task Mining - capture and analysis of process tasks (simple activities within a process that can be seen as a single unit of work that have a duration)

### Capture & Assessment
#### Select App Function Screening
Determine if the opportunity is best addressed by existing\other function or app and/or enhancements, not RPA (avoid using RPA as a workaround).

#### Existing Solution Screening
Is the opportunity best addressed by existing solution (enhancement)
Is the opportunity best addressed with existing automations (reusable or similar)

#### Best Solution Screening
Is there a better AI solution for this than the RPA platform?

#### Roadmap screening
is the solution/need already addressed in app roadmap?

### Detailed Analysis
- Complexity calculation & assessment
- Ideal is high-impact & low complexity for maximum value
- Gain understanding of the business process and known exceptions
- Identify and involve in the assessment the SME and any necessary peripheral teams (audit, security, compliance, etc.)
- Vet ROI basis calculations with internal teams for baseline assumption (e.g. FTE cost, hours per FTE per week, development costs)
- Reassess validity of intake form given the gathered input and update form as needed to better improve quality input.
- Identify how and where assessment results are to be stored for future reference (internally for CoE and externally for business)

### Opportunity Profiling
#### Determine process fitness
- Rule based - can the decisions made in the process be captured in a pre-defined logic? Is the exception rate either low or can be included as well in the business logic?
- Automatable/repetitive - does the process need to stay manual or is non-repetitive due to either high-exception rate or factors that cannot be integrated in business logic?
- Standard input - is the input in the process either electronic and easily readable or readable using existing capability? (e.g. OCR, ICR, etc.)
- Stable process - has the process been the same for a certain period of time and no changes are expected within the next couple months?

#### Process Complexity
- Number of screens - what number of screens with their corresponding elements need to be captured? The higher the number of screens, the higher the number of elements need to be captured and configured prior to the process automation.
- Type of applications - what applications are involved in the process? Some apps are more easily automated than others.
- Business logic scenarios
- Standard input

:triangular_ruler: Design
-------------

:wrench: Develop
-------------

:vertical_traffic_light: Test
-------------

:rocket: Deploy
-------------

:white_check_mark: Support
-------------

[1]: https://github.com/allejo/jekyll-toc
