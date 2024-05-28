## Summary
The ITSI Content Pack for AWS-Kinesis from Kinney Group is specifically designed to monitor system health related to AWS-Kinesis. It leverages Splunk ITSI to provide in-depth analysis and visualization of logs for AWS-Kinesis, ensuring critical systems are operating optimally. This content pack is an essential tool for IT professionals looking to enhance the reliability and performance of their data streaming infrastructure.

* Comprehensive Performance Monitoring: Offers detailed insights into AWS Kinesis data streams, shard management, data ingestion, and processing, enabling optimized resource utilization.
* Critical System Status Tracking: Monitors the real-time operational status of AWS Kinesis services, helping IT professionals swiftly identify and address potential issues.
* Enhanced Data Processing Efficiency: Facilitates better decision-making on data processing and system adjustments by analyzing performance trends and detecting inefficiencies across the infrastructure.

[Kinney Group ITSI Content Pack Blog](https://kinneygroup.com/blog/installing-itsi-content-packs/)

This ITSI Content Pack is open source and available for community collaboration and enhancement on [GitHub](https://www.github.com/kinneygroup).

For more information about Kinney Group's Splunk Products, visit our [website](https://kinneygroup.com/atlas)

## Details
The ITSI Content Pack for AWS-Kinesis contains service definitions and KPIs ready to import to ITSI. The KPI Thresholds and importance values are set to defaults so that they can be tuned manually for your use case. After configuration, this content pack provides a comprehensive monitoring solution for AWS Kinesis services.

[Kinney Group ITSI Content Pack Blog](https://kinneygroup.com/blog/installing-itsi-content-packs/)

For more information about Kinney Group's Splunk Products, visit our [website](https://kinneygroup.com/atlas)

### Services
AWS Kinesis monitoring encompasses several specialized services, each targeting specific aspects of data streaming performance:

1. Kinesis Data Streams
    * Description: Manages the ingestion and processing of real-time data streams.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
2. Shard Management
    * Description: Manages the shards within a Kinesis stream, including their creation, deletion, and scaling.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
3. Data Ingestion
    * Description: Handles the ingestion of data into Kinesis streams.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
4. Data Processing
    * Description: Processes the ingested data and prepares it for downstream applications.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
5. Latency Management
    * Description: Monitors and manages the end-to-end latency of data processing within Kinesis.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
6. Error Handling
    * Description: Monitors and manages errors during data ingestion and processing.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)

### KPIs
Each service utilizes specific KPIs to measure its effectiveness:

1. Kinesis Data Streams
    * Description: Manages the ingestion and processing of real-time data streams.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
2. Shard Count
    * Description: Number of active shards in the stream.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
3. Shard Read Throughput
    * Description: Read throughput per shard.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
4. Shard Write Throughput
    * Description: Write throughput per shard.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
5. Incoming Records
    * Description: Number of records being ingested into the Kinesis stream.
    * Source: [../../itsi-docs-library/aws-kinesis/files/Search_name_length.txt](../../itsi-docs-library/aws-kinesis/files/Search_name_length.txt)
6. Incoming Bytes
    * Description: Number of bytes being ingested per second.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
7. Throttled Records
    * Description: Number of records throttled during ingestion.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
8. Processed Records
    * Description: Number of records processed.
    * Source: [../../itsi-docs-library/aws-kinesis/files/Search_name_length.txt](../../itsi-docs-library/aws-kinesis/files/Search_name_length.txt)
9. Processing Latency
    * Description: Time taken to process data.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
10. Processing Errors
    * Description: Number of errors encountered during processing.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
11. End-to-End Latency
    * Description: Total time from data ingestion to processing completion.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
12. Iterator Age
    * Description: Age of the oldest record in the stream.
    * Source: [../../itsi-docs-library/aws-kinesis/files/Search_name_length.txt](../../itsi-docs-library/aws-kinesis/files/Search_name_length.txt)
13. Ingestion Errors
    * Description: Number of errors during data ingestion.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
14. Processing Errors
    * Description: Number of errors during data processing.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)
15. Throttled Requests
    * Description: Number of requests throttled due to errors.
    * Source: [../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt](../../itsi-docs-library/aws-kinesis/files/special-chars-in-key-name.txt)

### Relationships
#### Dependencies: 
Services are interconnected; for instance, Kinesis Data Streams is dependent on Shard Management, Data Ingestion, and Data Processing. Similarly, Data Processing relies on Latency Management and Error Handling to ensure timely and error-free data processing.

#### Hierarchical Structure: 
Some services form a hierarchy, such as Data Processing depending on Latency Management and Error Handling, illustrating a layered approach to performance monitoring where base metrics support broader performance indicators.

## Installation

### Installation prerequisites:

[Splunk Addon for AWS](https://splunkbase.splunk.com)

[Splunk App for Content Packs](https://splunkbase.splunk.com/app/5391)

[Splunk ITSI](https://www.splunk.com/en_us/products/it-service-intelligence.html)

## Troubleshooting

[Kinney Group ITSI Content Pack Blog](https://kinneygroup.com/blog/installing-itsi-content-packs/)

[Github and Readme](https://www.github.com/kinneygroup)

support@kinneygroup.com

## Contact

To provide feedback, visit our [Github and Readme](https://www.github.com/kinneygroup) for our content packs.

support@kinneygroup.com

For more information about Kinney Group's Splunk Products, visit our [website](https://kinneygroup.com/atlas)

## Version History

| Version | Date  | Description                |
|---------|-------|----------------------------|
| -.-.-   | -/-/- | Initial Preview Release    |

## Considerations:

[Kinney Group ITSI Content Pack Blog](https://kinneygroup.com/blog/installing-itsi-content-packs/)