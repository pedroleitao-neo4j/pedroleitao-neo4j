# Pedro's Neo4j Assets

Pedro's enterprise implementation patterns for Neo4j. This hub features a curated selection of industry-specific assets, spanning Cybersecurity, Finance, and AI. Each repository represents an accelerated solution focused on the strategic integration of Graph Technology and Large Language Models (LLMs) or Machine Learning to drive data-driven decision-making.

## Table of Contents

- [Industry Use Cases](#industry-use-cases)
- [AI Resources & Experiments](#ai-use-cases--experiments)

## Industry Use Cases

### 🛡️ Cybersecurity & Risk Management

These repositories demonstrate how graph technology identifies hidden risks and structural vulnerabilities that relational databases often miss.

* **[VPEM (Vulnerability Prioritization & Exposure Management)](https://github.com/pedroleitao-neo4j/cyber-vpem):** A foundational graph model for cybersecurity. It maps the relationship between assets, vulnerabilities, and business criticality to prioritize patching where it matters most.
* **[Attack Path Analysis (APA)](https://github.com/pedroleitao-neo4j/cyber-apa):** Building on the VPEM model, this project implements graph traversal algorithms to simulate how an attacker might move laterally through a network, identifying "choke points" for proactive defense.
* **[Software Supply Chain Security (SBOM)](https://github.com/pedroleitao-neo4j/cyber-sbom):** An implementation of Software Bill of Materials in a graph. It allows for instant impact analysis when a specific library version (like Log4j) is flagged, tracing its usage across the entire enterprise software ecosystem.

### 💰 Financial Services & Fraud

Leveraging Graph Data Science (GDS) to uncover patterns in complex transactional and market data.

* **[Financial Asset Correlator](https://github.com/pedroleitao-neo4j/neo4j-stocks-correlator):** Uses graph algorithms and machine learning to predict correlations between stocks. By treating market movements as a network, it identifies systemic risks and diversification opportunities that traditional time-series analysis might overlook.
* **[Customer Churn Detection](https://www.google.com/search?q=https://github.com/pedroleitao-neo4j/customer-churn-gds):** A predictive model using **Neo4j Graph Data Science**. Instead of looking at customer behavior in isolation, this project uses community detection and centrality scores to see how "social" or "connected" influence affects customer retention.

## AI Use Cases & Experiments

- [Named Entity Recognition (NER) with Neo4j and encoder models](https://github.com/pedroleitao-neo4j/ner-econ-research) for economic research and policy evaluation.

- Clean Knowledge Graphs [with a Judge Model](https://github.com/pedroleitao-neo4j/canonicalizer) for LLM based Knowledge Graph construction, where facts matters most.