# Leveraging GraphML for Predictive Analysis of MEP Systems
**Krisztian Hajdu and Scott Lebow**

## Abstract

This project applies graph machine learning (GraphML) to analyze and predict the performance and lifecycle of Mechanical, Electrical, and Plumbing (MEP) systems in buildings. We focus on representing MEP systems as graphs to enable advanced filtering, prediction, and change tracking. A prototype tool will extract MEP data, convert it to graph formats, and support machine learning workflows for performance prediction and anomaly detection. The approach will be validated through case studies, demonstrating how graph-based methods can improve MEP system analysis and lifecycle management.

We aim to predict MEP system maintenance needs, assign risk scores and track changes over the building lifecycle. The project will start with electrical systems, since these are less spatially constrained, and have simpler relationships, before expanding to mechanical and plumbing systems. The outcomes will include a working prototype, a framework for MEP analysis using GraphML, and case studies validating the approach.

Maintence and operations decisions will be informed by predictive models, grouping MEP systems into operational clusters to streamline tasks, equipment that require similar maintenance, or are in the same physical location can be managed together. The research will provide actionable recommendations for advancing MEP system integration in BIM workflows, supporting more efficient operations and long-term asset management.

## Focus Areas
- GraphML for BIM and building analysis

## Research Questions
- How can MEP systems be effectively represented as graphs for machine learning analysis?
- What GraphML and machine learning techniques are most effective for predicting MEP system performance and detecting anomalies?
- How can graph-based methods support the tracking of changes and lifecycle management of building systems?

## Methodology
The research involves extracting MEP system data, constructing graph representations, and applying GraphML libraries (e.g., NetworkX, Neo4j) for analysis. Machine learning models (e.g., using scikit-learn, TensorFlow, PyTorch) will be developed to predict system performance and identify potential issues. The approach will be validated through case studies, focusing on the effectiveness of graph-based methods for MEP analysis and change tracking.

## Planned Technology
- **GraphML Libraries**: NetworkX, Neo4j, Graph-tool
- **Machine Learning Libraries**: Scikit-learn, TensorFlow, PyTorch
- **Visualization**: Plotly, Gravis
- **Prototype Tool**: Streamlit, Gradio, or Dash for web-based GUI

## Expected Outcomes
- A prototype tool for MEP system graph extraction and analysis
- Demonstrated application of GraphML and machine learning to building systems
- Case studies validating predictive and change tracking capabilities
- Recommendations for future research in graph-based building system analysis
