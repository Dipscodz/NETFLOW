# FlowGraph — AI-Powered Network Threat & Attack-Path Intelligence

FlowGraph is an AI-driven network security platform that transforms NetFlow/IPFIX traffic into an interactive temporal network graph for detecting anomalous behavior, identifying suspicious hosts, and analyzing potential attack paths.

Unlike traditional NetFlow dashboards that primarily visualize traffic volume and protocol statistics, FlowGraph combines **graph analytics, machine learning, behavioral anomaly detection, and temporal network analysis** to investigate how suspicious activity propagates across a network.

### Core Capabilities

* **NetFlow/IPFIX ingestion** and high-volume flow processing
* **Temporal network graph construction** from source-destination communication
* **ML-based anomaly detection** for unusual network behavior
* **Lateral movement detection** across internal hosts
* **Attack-path reconstruction** from correlated network events
* **Host and connection risk scoring**
* **Interactive network visualization**
* **Behavioral baselines** for identifying deviations from normal traffic
* **Timeline-based incident investigation**
* **Explainable security alerts** showing why a flow or host was considered suspicious

### Architecture

```text
NetFlow / IPFIX
       ↓
Flow Processing
       ↓
Feature Engineering
       ↓
Behavioral Analysis
       ↓
Graph Construction
       ↓
Anomaly Detection
       ↓
Threat Correlation
       ↓
Attack-Path Analysis
       ↓
Interactive Security Graph
```

### Research Direction

The project explores how **temporal graphs and machine learning can be combined to move network monitoring from simple traffic visualization toward automated security reasoning**.

Future work includes Graph Neural Networks, streaming graph analytics, online anomaly detection, threat-intelligence correlation, and scalable processing of millions of network flows.

### Tech Stack

**Python · FastAPI · PyTorch · PyTorch Geometric · NetworkX · PostgreSQL · Neo4j · React · Cytoscape.js**

> **From network flows to explainable attack paths.**
