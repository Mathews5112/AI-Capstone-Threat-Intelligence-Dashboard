# 🛡️ AI-Capstone-Threat-Intel

A threat intelligence automation and visualization project that collects cybersecurity threat data from multiple sources, stores it in Airtable, enriches it with IOCs, CVEs, summaries, and relevance scores, then displays the results in a Streamlit dashboard for security triage and analysis.

## 📌 Project Overview

This dashboard acts as a lightweight **Security Operations Center-style threat intelligence console**. It is designed to help security analysts quickly review and prioritize threat intelligence from public cybersecurity feeds. Instead of manually checking different sources, this project uses automated n8n workflows to collect, normalize, enrich, and score threat data before sending it into Airtable. The Streamlit dashboard then provides a clean interface for viewing recent threats, CVEs, indicators of compromise, severity levels, and recommended actions. Its goal is not just to display raw data, but to transform raw threat information into **actionable intelligence**.

Raw threat feeds can be difficult to use because they often contain duplicate records, long descriptions, unstructured text, and mixed indicators. This dashboard solves that problem by organizing the data into categories such as severity, source, attack type, relevance score, affected software, CVEs, and IOCs.

This makes the dashboard useful for:

- Cybersecurity research
- Threat intelligence analysis
- Vulnerability monitoring
- IOC investigation
- Incident response preparation
- Security operations prioritization

This project demonstrates how automation, AI-assisted analysis, and structured threat intelligence can improve the speed and quality of cybersecurity triage.

