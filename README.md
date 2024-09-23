# Arjuna - Dark Web Forensic Investigation Tool

**Arjuna** is a comprehensive solution designed to investigate unauthorized data distribution on the dark web and mitigate the impact using machine learning algorithms. The tool focuses on deanonymizing uploaders of sensitive data and removing unauthorized content.

## Key Features

- **Dark Web Crawling**: Arjuna efficiently crawls hidden sites, focusing on sensitive content like Personally Identifiable Information (PII), financial, and confidential data.
- **Data Scraping**: Extracts critical data such as metadata, images, and hidden information from dark web sources.
- **Data Analysis**: Leverages machine learning models, including Natural Language Processing (NLP) for data classification and anomaly detection.
- **IP Deanonymization**: Traces and de-anonymizes IP addresses linked to unauthorized content.
- **Data Removal**: Removes illegal data from the dark web and verifies its successful deletion.
- **Report Generation**: Generates detailed reports, summarizing collected data, deanonymization results, and actions taken.

## Project Phases

1. **Data Acquisition**
   - Implement tunneling and crawling techniques.
   - Develop automated scraping bots.
   
2. **Data Analysis**
   - Classify collected data using machine learning models (e.g., BERT).
   - Employ advanced de-anonymization methods.

3. **Mitigation and Verification**
   - Remove unauthorized data and verify its removal.

## Functional Requirements

1. **Crawling**
   - Efficiently crawl dark web forums, marketplaces, and sites with CAPTCHAs.
   - Handle obfuscation techniques and support customizable crawling parameters.
   
2. **Data Extraction**
   - Extract metadata, hidden data, and support various file formats (PDF, DOCX, HTML).
   
3. **Data Analysis**
   - Utilize machine learning to analyze data patterns.
   - Visualize results for users and integrate external databases.

4. **IP Deanonymization**
   - Trace and de-anonymize IPs using geolocation and social network analysis.

5. **Data Removal**
   - Remove identified content based on predefined criteria and verify removal.

6. **Report Generation**
   - Export comprehensive reports in formats such as PDF and CSV for law enforcement.

## Non-Functional Requirements

- **Storage**: Scalable and secure storage for large datasets.
- **EC2 Instance**: Compute power to handle real-time processing, leveraging AWS EC2.
- **GPU Machine**: High-performance GPU for accelerating machine learning tasks.
- **Cloud Infrastructure**: Deployed on AWS for scalability, performance, and cost optimization.

## Legal and Ethical Considerations

- Compliance with data privacy laws (e.g., GDPR, CCPA).
- Ethical principles are followed in data collection and analysis.


