This project focuses on detecting anomalies in a manufacturing process using an unsupervised Graph Neural Network (GNN) model. The approach involves transforming tabular machine operation data into a graph-based representation to capture complex relationships between variables such as machine statuses, worker interactions, and operational conditions. By leveraging GNNs, the model can effectively detect irregular patterns and deviations that indicate potential anomalies.

Key Objectives:
✅ Convert Tabular Data into a Graph

Represent machines, workers, and operational states as nodes and edges.
Establish relationships based on machine-worker interactions and transitions.
✅ Train an Unsupervised GNN for Anomaly Detection

Use self-supervised learning to train the model without explicit anomaly labels.
Identify unexpected patterns in the manufacturing workflow.
✅ Leverage Machine-Worker Interactions & Operational Status

Detect unusual worker distributions and machine failures.
Exclude anomalies caused by temporary machine redirections (e.g., products sent to Machine 3 instead of Machine 1).
✅ Visualize Relationships & Anomalies

Heatmaps to show feature correlations.
Graph-based visualizations to highlight machine interactions.
Anomaly scatter plots to pinpoint unusual behaviors.
Technologies Used:
🔹 Python (Pandas, NumPy, NetworkX, PyTorch-Geometric)
🔹 Graph Neural Networks (GNNs) for anomaly detection
🔹 Matplotlib & Seaborn for visualization

Expected Outcomes:
📌 A graph-based representation of the manufacturing process.
📌 A trained unsupervised GNN model that detects operational anomalies.
📌 Informative visualizations for insights into machine-worker interactions.
📌 Improved anomaly detection accuracy while minimizing false positives.

This project helps manufacturers detect inefficiencies, prevent failures, and optimize operations using advanced AI-driven anomaly detection techniques. 
