# Facebook Social Network Analysis

## Project Overview
This project applies network analysis techniques to explore the structural properties, connectivity patterns, and community behavior within a Facebook social network. Using graph theory and statistical methods, the analysis uncovers how users interact, form communities, and influence information flow across the network.

The goal of this project is to demonstrate how network analytics can be used to understand complex systems such as social platforms, collaboration networks, and digital communities.

## Dataset
- **Source:** Stanford Large Network Dataset Collection (SNAP)
- **Dataset:** Facebook Combined Ego Network
- **Network Type:** Undirected graph
- **Nodes:** 4,039 users
- **Edges:** 88,234 friendships
- **Privacy:** Fully anonymized dataset

## Tools & Technologies
- Python
- NetworkX
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Analytical Approach

### Data Preparation
- Loaded and converted the raw edge list into a graph structure.
- Validated connectivity and removed inconsistencies.
- Computed basic network statistics and graph properties.

### Network Analysis Techniques
The following network metrics and methods were applied:
- Degree distribution analysis
- Community detection (Louvain method)
- Clustering coefficient and triadic closure
- Betweenness centrality (bridge node detection)
- Degree assortativity
- Network resilience simulations (random vs targeted node removal)

## Key Insights
- The network exhibits **strong community structure**, with users forming tightly connected groups.
- Most users experience the **friendship paradox**, where their friends have more connections than they do.
- A high clustering coefficient indicates strong **triadic closure**, meaning friends of friends are likely to be connected.
- A small number of users act as **bridge nodes**, controlling a large share of information pathways.
- The network is significantly more vulnerable to **targeted removal of high-degree nodes** than to random failures.

## Business Relevance
The insights from this analysis can support:
- Community-based feature design
- User engagement and recommendation systems
- Identification of influential users
- Platform resilience and security planning
- Social structure–driven decision making

## Visualizations
The analysis includes:
- Degree distribution plots
- Community network graphs
- Centrality-based node highlighting
- Network fragmentation simulations
- Comparative visual summaries of key metrics

## Limitations
- Analysis is based on a single snapshot in time.
- Anonymized data limits contextual interpretation.
- Results may not generalize to follower-based or directed networks.

## Conclusion
This project demonstrates how network analysis can reveal hidden patterns within large social systems. By combining graph metrics with visual exploration, the analysis provides actionable insights into connectivity, influence, and structural stability in social networks.

## Files in This Repository
- `facebook_network_analysis.ipynb` – Full Python analysis and visualizations
- `report/facebook_network_analysis_report.pdf` – Detailed analytical report
- `https://snap.stanford.edu/data/ego-Facebook.html` – Link to Dataset
