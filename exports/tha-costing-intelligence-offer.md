# **Proposal: Data Pipeline & Costing Intelligence**

Client: Thomas Hillig Architects  
Date: 22nd June 2026

## **Client story**

THA's costing problem spans fragmented historical data, industry standards, local factors, THA labour, carbon impact, and contractor dependencies.

## **Problem**

Too slow to do costing, they depend on externals every time. It is a complex process generally and what they get back in the end is incomplete. This creates a risk of poorly costed or incompletely costed projects for clients. Costing elements often depend on contractors and other third parties who are also slow.

## **Why XYZ?**

This is a complex costing and data problem with domain-specific knowledge spread across systems, documents, and paper records. The hard part is understanding which data can be trusted, how estimates should be traced, where automation helps, and where human review stays in control. A generic or optimistic methodology would create risk. The phased methodology below gives THA a practical way to test the main assumptions before larger commitments are made.

## **Working hypothesis**

We can make meaningful improvements by combining AI with THA's own data as an alternative to slow and expensive third-party services or manual effort. There is deep value in creating a structured knowledge base that can support faster, more transparent, and more reusable costing work.

## **High-Level Solution Overview**

The core of the likely solution path is a THA costing intelligence knowledge base. This will bring together the most useful available data: existing spreadsheets, project documents, historical cost information, Projo exports, external cost-estimation examples, internal labour assumptions, contractor inputs, and carbon / CO2 logic where relevant.

The key information in historical costings for past projects includes materials and amounts used, DIN categorizations, labour, etc. Additionally, it provides references for regional variations. This all feeds into the costing equation for new projects together with updated cost for materials and labour. The key umbrella for structuring this data will likely center around DIN 276 and related categorizations used in projects. 

This knowledge base can support practical tools and AI workflows tailored to THA needs. Including decision support, cost-estimation assistance, scenario comparison for design alternatives, costing document generation, internal overhead calculations, and carbon scoring. 

The overarching goal is to reduce costing cycle time in early stages of the project, make impact of assumptions and design alternatives more transparent, while leveraging THA's historical knowledge and expertise, and reduce dependence on external costing specialists/agencies where the work can be handled internally with confidence.

The system should not be treated as a fully automatic black box. Costing is commercially sensitive and can be highly project-specific, so the workflows need clear guardrails. These should define which data sources are trusted, how estimates are generated, how confidence and assumptions are shown, when human review is required, and where hand-offs happen inside THA's existing process.

The solution combines AI-supported automation with structured review points. This allows THA to move faster while keeping control over quality, accountability, and professional judgment.

Building out the knowledge base, workflows, guardrails, and supporting tools is a process of iterative refinement and development. This is something that the THA team will have to be actively involved in on an ongoing basis.

## **Phase Overview (Executed sprint style)**

1\. **Startup**: Start phase, full understanding, discovery, workshop, job shadowing

2\. **De-risking / experimentation**: De-risking and vertical slice, testing approaches, major learnings, first knowledge base with limited test data

3\. **Prototyping & Testing**: First testable solution, with demos and workshop, second knowledge base with extended/enriched data

4\. **Early validation / pilot project**: Pilot and calibration, third knowledge base with extensive data, pending decisions on how much historical data to digitalise

5\. **Wider validation / rollout**: Broader rollout, workflow integration and workshop, iterative knowledge-base improvements ongoing from here

6\. **Robustness & Full Adoption**: Stress test, edge cases, iterative refinement, polish, knowledge-base data pipeline

7\. **Expansion**: Ongoing support and improvement, executing on stretch goals, increasing scope, for example realtime design-based costing

## **Detailed phase descriptions**

### **1\. Startup**

Description: Current state analysis by starting the project properly with a focused discovery workshop, job shadowing, and structured information gathering with Markus and the relevant THA team members. Build a full understanding of the current costing workflow, data sources, pain points, decision points, existing spreadsheets, Projo export options, cost-specialist process, internal labour assumptions, carbon / CO2 requirements, and what sample material is available.

Output: data source and data types audit, gap analysis, priority use cases, success criteria, full high-level business goals, risk analysis and a clearer scope for the de-risking phase.

Goal: information gathering; agree the priority workflow, usable sample data, and success criteria for de-risking spike.

### **2\. De-risking / experimentation**

Description: Run the de-risking and vertical-slice phase using limited representative test data. Validate assumptions. Test different approaches for ingestion, extraction, mapping, estimate ranges, source traceability, labour-cost assumptions, carbon / CO2 logic, and where human review is still needed. 

Goal: prove whether THA's real data can support traceable costing estimation before committing to a larger build and further project costs. Identify a feasible MVP for the next phase that delivers value.

Output: first knowledge base with limited test data, working prototype slice, findings, performance accuracy/limitations insights, recommended data model and approach, recommended architecture, and decision on whether to proceed. Also make a recommendation for tools and solution providers.

### **3\. Prototyping & Testing** 

Description: Build the first testable solution around the highest-value use case using the recommended architecture from the previous phase. Run demos and a workshop with THA to review the workflow, assumptions, interface, and usefulness of the outputs. Extend and enrich the data beyond the first experiment set.

Goal: give THA a limited but credible solution that can be tested on selected costing scenarios.

Output: first testable internal solution for limited scope, improved knowledge base with extended/enriched data, demo materials, workshop feedback, and a prioritized list of fixes or improvements. 

### **4\. Early validation / pilot project** 

Description: Run a pilot and calibration phase on real or near-real costing work. Compare outputs against historical estimates (if included), external cost-specialist outputs, and THA's own expert judgment. 

Goal: Validate quality against real examples and decide what is ready for broader use. Decide how much historical data should be digitised and how much additional data is worth bringing into the system. 

Output: improved and extended knowledge base, validated use cases, quality thresholds, known limitations, and a practical rollout & improvement roadmap. Digitisation plan and preparation for any information that is deemed essential to the knowledge base, assuming this step is needed.

### **5\. Wider validation / rollout**

Description: Broaden the rollout and integrate the workflow with more of the THA team, project types, and recurring costing needs. Run a feedback workshop to review adoption, gaps, and operational fit. From this phase onward, knowledge-base improvements should become part of an iterative and ongoing feedback loop.

Goal: turn the validated workflow into a broader operating solution across more projects, data sources, and recurring costing needs and usable decision support. 

Output: broader operating solution, expanded user feedback, workflow-integration plan, improved knowledge base, and clearer requirements for robustness and widespread internal adoption. Inclusion of the fully digitalised knowledge base, again, if needed.

## **6\. Robustness & Full Adoption**

Description: Stress tests the solution against edge cases, messy inputs, unusual project types, missing data, conflicting assumptions, and higher-risk estimates. Refine the data pipeline, QA process, permissions, audit trail, reporting, and operational polish. Full team training workshops as needed. 

Goal: make the solution reliable enough for regular operational use beyond controlled pilot scenarios. 

Output: improved knowledge-base data pipeline, stress-test results, edge-case handling, stronger QA process, refined calculation assumptions, and more robust production behaviour. Full team adoption.

## **Expansion**

Description: Continue support and improvement while executing on stretch goals and increasing scope. This could include more data sources, deeper Projo or other integrations, richer carbon scoring, contractor-input workflows, additional reporting, and later ambitious features such as realtime design-based costing and distributing the solution directly to contractors and providers or otherwise upgrading their dataflows. 

Goal: keep the solution improving as THA's needs and feedback from the team grow and turn validated stretch goals into practical new capabilities. 

Output: ongoing maintenance, QA, data updates, new feature releases, expanded knowledge base, and roadmap execution.

## **Phase Scheduling**

Time estimates per phase, based on current understanding. The later phases may need to be adjusted after each phase based learnings and agreed scope changes. Additionally, we may adjust the ambition level of the project.

1\. Startup Phase: 2 weeks

2\. De-risking / Experimentation Phase: 3 weeks  
\------------------------------------

3\. Prototyping & Testing  Phase: 6 weeks

4\.  Early validation / pilot project  Phase: 6 weeks  
\------------------------------------

5\. Wider validation / rollout Phase: 8 weeks

6\. Robustness & Full Adoption Phase: 6 weeks

\------------------------------------

Expansion Phase: Ongoing

## **Phase Costing**

**Simple per-phase cost estimate**

Based on the current understanding, costs are according to estimated phase complexity and duration.

1\. Startup Phase: EUR 20k

2\. De-risking / Experimentation Phase: EUR 20k

3\. Prototyping & Testing Phase: EUR 35k

4\. Early validation / pilot project  Phase: EUR 45k

5\. Wider validation / rollout Phase: EUR 65k

6\. Robustness & Full Adoption Phase: EUR 45k

Expansion Phase: ongoing, costed separately as support or later scope extension.

## **Billing Caveats** 

\* Estimates are based on the currently available information, should significant changes arise that increase or decrease the scope of any phase, revised costing or offers will be updated accordingly.

\* Billing cadence, invoices will normally be issued immediately following the completion of each phase.

\* Payment will be made within 14 days of the issue date of any given invoice. 

\* Larger phases will be 50% invoiced up front, when the sum or effort time exceeds 40K or 2 months respectively. 

\* Additionally required effort is billed at 2K per day.

\* FORMATION can guarantee post-project support and follow-up availability through a monthly retainer, payable in advance based on the reserved support requirement per month at the agreed day rate. Outside of that model availability cannot be guaranteed.

\* Assumption is that the operational costs of running the solution (such as LLM tokens, hosting etc) are covered directly by THA as internal expenses.

\* THA will directly cover any costs associated with digitisation of paper or other records deemed necessary by the client for the fullest possible knowledge base.

Yours sincerely,

Ian Hannigan  
Managing Director  
FORMATION GmbH  
XYZ is a division of FORMATION  
formationxyz.com
