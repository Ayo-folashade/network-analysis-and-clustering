# Network Traffic Analysis with IP Anonymization and Clustering

**Overview:**
- Captured network traffic using Wireshark and saved it in .pcap format.
- Extracted data using `tshark` and saved into `network_traffic.csv`.
- Loaded `network_traffic.csv` into a Pandas DataFrame (`df`).
- Anonymized IP addresses using SHA-256 hashing.
- Preprocessed data by handling missing values and normalizing features (`len` and `ip_protocol`).
- Applied DBSCAN to identify clusters and anomalies.
- Visualized clustering results using a scatter plot.

