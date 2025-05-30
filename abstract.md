**MACAD Thesis Abstract**
# Improving BIM Interoperability for MEP Systems Using Graphs
**Krisztian Hadju and Scott Lebow**

## Problem Statement
BIM interoperability tools are mostly focused on the exchange and storage of architectural data, often neglecting the integration of MEP (Mechanical, Electrical, and Plumbing) systems.  This results in robust data exchange for architectural elements but leaves structural and MEP systems underrepresented.  For large campus owner-operators, this can lead to inefficiencies in managing and maintaining their facilities.  

For example, it is easy to determine if a door exists in both a BIM model and a real-world building, but it is much more difficult to determine if a piece of MEP equipment exists in both places.  This can lead to costly errors in maintenance and operations, as well as difficulties in planning for future upgrades or renovations.

## Focus Areas
- Advanced BIM Interoperability and Workflow Automation
- GraphML for BIM and building analysis

## Research Questions
- How can we improve the interoperability of BIM tools to better support the integration of MEP systems, particularly for large campus owner-operators?  
- How can we leverage Graphs to store the relationships between MEP systems and other building elements to improve data exchange and management?  
- Can we apply GraphML techniques to analyze and predict the performance of MEP systems in a BIM model, and how can this be used to inform maintenance and operations decisions?

## Methodology
This research will involve a combination of literature review, case studies, and practical implementation.  We will review existing BIM interoperability tools and identify gaps in their support for MEP systems.  We will then develop a prototype tool that leverages Graphs to store and manage the relationships between MEP systems and other building elements.  Finally, we will apply GraphML techniques to analyze the performance of MEP systems in a BIM model and evaluate the effectiveness of our approach through case studies with large campus owner-operators.

We will start by building a framework for electrical systems, as these are often the least spatially constrained and can be easily represented in a Graph.  We will then extend this framework to include mechanical and plumbing systems, which are more spatially complex.

We want to build tools to filter the graphs to only include the MEP systems that are relevant to a particular task, such as maintenance or operations, or renovation planning.  This will allow us to focus on the most important elements of the MEP systems and improve the efficiency of our analysis.

We want to build tools to incorporate changes to the MEP systems into the Graphs, so that we can track changes over time and understand how they impact the overall performance of the building.  This will allow us to better manage and maintain the MEP systems, as well as plan for future upgrades or renovations.

## Expected Outcomes
- A prototype tool that improves BIM interoperability for MEP systems using Graphs, specifically targeting Revit integration
- A framework for analyzing and predicting the performance of MEP systems in a BIM model using GraphML techniques
- Case studies demonstrating the effectiveness of our approach in improving data exchange and management for large campus owner-operators
- Recommendations for future research and development in BIM interoperability and MEP systems integration