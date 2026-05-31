# Fraud-Anomaly-Detection-System
Leveraging Machine Learning and Graph Analytics to Detect Financial Irregularities and Operational Risk

Overview

Organizations operating large-scale healthcare and patient support programs process millions of transactions involving patients, healthcare providers, distributors, financial assistance programs, and third-party vendors. As these ecosystems grow, traditional rule-based monitoring systems often struggle to identify sophisticated fraud schemes, hidden relationships, and emerging risk patterns.
To strengthen governance, compliance, and operational integrity, I designed and developed a cloud-native Fraud & Anomaly Detection Platform on AWS that combined Machine Learning, Graph Analytics, and Real-Time Risk Monitoring to proactively identify suspicious activities, financial irregularities, and hidden fraud networks.
The solution integrated data from multiple operational systems and utilized advanced anomaly detection, graph-based relationship analysis, and predictive risk scoring to support compliance teams, auditors, and business stakeholders in detecting and investigating high-risk activities.
________________________________________
Business Challenge

The organization managed a complex healthcare support ecosystem involving:
•	Patient enrollment activities
•	Financial assistance programs
•	Hospital interactions
•	Distributor transactions
•	Drug delivery operations
•	Vendor engagements
•	Payment and reimbursement processes
•	Program eligibility assessments

Traditional monitoring systems relied heavily on predefined business rules and manual audits, creating several challenges:

•	Fraud patterns continuously evolved beyond static rules
•	Hidden relationships between entities were difficult to identify
•	Large transaction volumes made manual investigation inefficient
•	Risk indicators were scattered across multiple systems
•	Compliance teams lacked proactive risk visibility
The business required an intelligent system capable of identifying both known fraud patterns and previously unseen anomalies.
________________________________________
Solution

I developed a multi-layered Fraud Intelligence Platform on AWS that combined supervised and unsupervised machine learning techniques with graph-based relationship analysis.
The solution continuously analyzed operational transactions, financial records, patient activities, distributor interactions, and program participation data to identify suspicious behavior patterns and generate risk alerts.
The platform enabled investigators to move from reactive audits to proactive fraud detection and risk prevention.
________________________________________
Data Sources

The fraud detection ecosystem integrated data from multiple enterprise systems:

Patient Operations

•	Enrollment history
•	Program participation records
•	Treatment activity
•	Case management interactions

Financial Operations

•	Assistance program utilization
•	Payment transactions
•	Reimbursement requests
•	Financial assessments

Provider Network

•	Hospitals
•	Clinics
•	Healthcare providers

Distribution Network

•	Drug distributors
•	Shipment records
•	Delivery confirmations

Compliance Systems

•	Audit findings
•	Investigation reports
•	Governance controls
________________________________________
AWS Architecture

The platform was built using a scalable AWS-based architecture.
Data Ingestion Layer
Data was ingested from enterprise systems through:
•	Amazon S3
•	AWS Glue
•	Amazon RDS
•	Event-driven data pipelines
________________________________________
Data Processing Layer

Large-scale datasets were processed using:
•	AWS Glue ETL Jobs
•	Amazon EMR
•	Apache Spark
Data quality checks, feature engineering, and aggregation pipelines were implemented to prepare data for fraud analysis.
________________________________________
Machine Learning Layer

Models were developed and deployed using:
•	Amazon SageMaker
•	Python
•	Scikit-Learn
•	XGBoost
•	Graph Analytics Frameworks
________________________________________
Monitoring & Visualization

Fraud alerts and risk scores were surfaced through:
•	Amazon QuickSight
•	Risk Monitoring Dashboards
•	Investigation Workbenches
________________________________________
Machine Learning Framework

The fraud detection strategy utilized multiple complementary approaches.
________________________________________
1. Supervised Fraud Detection
   
Historical fraud investigations and confirmed suspicious activities were used to train predictive models.
XGBoost Models
XGBoost was implemented to:
•	Predict fraud likelihood
•	Identify high-risk transactions
•	Prioritize investigations
•	Generate fraud risk scores
Key features included:
•	Financial behavior patterns
•	Transaction frequency
•	Program utilization metrics
•	Historical investigation outcomes
•	Provider interaction trends
The model provided interpretable risk scores to support compliance investigations.
________________________________________
2. Unsupervised Anomaly Detection
   
Because many fraud scenarios had no historical labels, unsupervised learning techniques were introduced to identify unusual behavior.
Isolation Forest
Isolation Forest models were used to detect:
•	Abnormal financial claims
•	Unusual transaction volumes
•	Unexpected utilization patterns
•	Rare operational activities
This approach helped uncover emerging fraud schemes that had not previously been observed.
________________________________________
3. Graph-Based Fraud Detection
   
One of the most powerful components of the solution was relationship-based fraud analysis.
The business ecosystem was modeled as a graph where:
Nodes:
•	Patients
•	Hospitals
•	Providers
•	Distributors
•	Financial programs
Edges:
•	Drug deliveries
•	Financial transactions
•	Referrals
•	Program participation
•	Provider interactions
This structure enabled the identification of hidden fraud networks that traditional tabular models could not detect.
________________________________________
Graph Neural Network (GNN) Analysis

Graph-based learning techniques were applied to:
•	Detect collusive behavior
•	Identify fraud rings
•	Discover suspicious entity clusters
•	Measure influence and connectivity patterns
•	Surface hidden relationships
The graph model significantly improved detection of coordinated fraud activities involving multiple entities.
________________________________________
Risk Scoring Framework

A unified risk score was generated by combining:
•	XGBoost fraud probability
•	Isolation Forest anomaly score
•	Graph-based risk indicators
•	Business rule violations
•	Historical investigation outcomes
This composite scoring approach provided investigators with a prioritized list of high-risk cases.
________________________________________
Key Capabilities
Real-Time Fraud Detection
Automatically identified suspicious activities as new transactions entered the system.
________________________________________
Fraud Ring Discovery
Detected interconnected groups of entities exhibiting coordinated suspicious behavior.
________________________________________
Anomaly Monitoring
Identified unusual activities without requiring prior fraud labels.
________________________________________
Explainable Risk Intelligence
Provided interpretable explanations supporting each fraud alert.
________________________________________
Investigator Workbench

Enabled compliance teams to:
•	Explore entity relationships
•	Review evidence
•	Analyze transaction histories
•	Investigate risk drivers
________________________________________
Challenges Solved

Hidden Relationships
Fraud schemes often involved multiple connected entities.
Solution:
Implemented graph analytics and network-based learning techniques.
________________________________________
Limited Fraud Labels
Many fraud cases had never been observed before.
Solution:
Combined supervised and unsupervised learning approaches.
________________________________________
Large Data Volumes
Millions of records required scalable processing.
Solution:
Built distributed processing pipelines using AWS services.
________________________________________
High False Positive Rates
Traditional rule-based systems generated excessive alerts.
Solution:
Introduced machine learning-based risk scoring and model-driven prioritization.
________________________________________
Business Impact

The platform significantly improved the organization's fraud detection and governance capabilities by:
•	Increasing fraud detection accuracy
•	Reducing false-positive investigations
•	Accelerating case resolution times
•	Identifying previously unknown fraud patterns
•	Enhancing compliance monitoring
•	Strengthening governance controls
•	Improving operational transparency
The solution transformed fraud detection from a reactive audit process into a proactive, AI-driven risk intelligence capability.
________________________________________
My Contribution

As a Senior Data Scientist, I led the end-to-end development of the Fraud & Anomaly Detection Platform, including:
•	Fraud risk assessment and business discovery
•	Feature engineering and data modeling
•	Graph network design
•	Machine learning model development
•	Isolation Forest implementation
•	XGBoost optimization
•	Risk scoring framework creation
•	AWS architecture design
•	Model deployment on Amazon SageMaker
•	Dashboard development and stakeholder engagement
The project successfully combined machine learning, graph analytics, and cloud-native AWS services to create a scalable enterprise fraud intelligence solution capable of detecting both known and emerging fraud risks.
