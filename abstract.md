**MACAD Thesis Abstract**
# Improving BIM Interoperability for MEP Systems Using Graphs
**Krisztian Hajdu and Scott Lebow**

## Problem Statement
BIM interoperability tools are mostly focused on the exchange and storage of architectural data, where changes can be administered with a high degree of automation directly within platforms like Revit. In contrast, MEP systems (especially electrical) are often only partially modeled, with many components represented only in disconnected 2D drawings, abstract diagrams, and schedules rather than as coordinated 3D elements. This disconnect hinders change management automation and leads to fragmented workflows. 
A key challenge is maintaining the operative model, which is a consolidated, post-handover representation of current building conditions. During the operations and maintenance phase of the building lifecycle, infrastructural changes occur through refurbishments and extensions (CAPEX) and maintenance (OPEX) works. For CAPEX, relevant 3D and 2D data are extracted by the asset owner, updated by the contractor, and the as-built data is integrated back into the operative model post-project by the owner. OPEX changes are smaller in scope and manually incorporated by the same. In both cases, reliably updating MEP systems and tracking the history of changes are essential for operational accuracy, data continuity, and long-term asset management.
For large campus owner-operators, the amount of interventions to manage is high, hence the inability to manage MEP systems with the same level of integration and automation as architectural elements limits efficiency and undermines the value of BIM in ongoing operations.

## Focus Areas
- Advanced BIM Interoperability and Workflow Automation
- GraphML for BIM and building analysis

## Research Questions
- How can we improve the interoperability of BIM tools to better support the integration of MEP systems, particularly for large campus owner-operators?  
- How can we leverage Graphs to store the relationships between MEP systems and other building elements to improve data exchange and management?  
- Can we apply GraphML techniques to analyze and predict the performance of MEP systems in a BIM model, and how can this be used to inform maintenance and operations decisions?
- How can we support consistent updates and historical tracking of lifecycle changes in the operative model?

## Methodology
This research will involve a combination of literature review, case studies, and practical implementation.  We will review existing BIM interoperability tools and identify gaps in their support for MEP systems.  We will then develop a prototype tool that leverages Graphs to store and manage the relationships between MEP systems and other building elements.  Finally, we will apply GraphML techniques to analyze the performance of MEP systems in a BIM model and evaluate the effectiveness of our approach through case studies with large campus owner-operators.

We will start by building a framework for electrical systems, as these are often the least spatially constrained and can be easily represented in a Graph.  We will then extend this framework to include mechanical and plumbing systems, which are more spatially complex.

We want to build tools to filter the graphs to only include the MEP systems that are relevant to a particular task, such as maintenance or operations, or renovation planning.  This will allow us to focus on the most important elements of the MEP systems and improve the efficiency of our analysis.

We want to build tools to incorporate changes to the MEP systems into the Graphs, so that we can track changes over time and understand how they impact the overall performance of the building.  This will allow us to better manage and maintain the MEP systems, as well as plan for future upgrades or renovations.

## Expected Outcomes
- A prototype tool that improves BIM interoperability for MEP systems using Graphs, specifically targeting Revit integration
- A framework for analyzing and predicting the performance of MEP systems in a BIM model using GraphML techniques
- Demonstrated methods for managing post-handover infrastructural changes in BIM, including element extraction, reintegration, and lifecycle history tracking
- Case studies demonstrating the effectiveness of our approach in improving data exchange and management for large campus owner-operators
- Recommendations for future research and development in BIM interoperability and MEP systems integration
