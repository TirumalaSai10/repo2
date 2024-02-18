# repo2
Dataphion Assignment
In this project, we aim to develop a robust Spark job to consume events from Apache Kafka and efficiently insert the data into Iceberg/Delta Lake tables. The tables will be designed to capture essential event attributes such as Event Name, Type, Value, Timestamp, Page Source, URL, Component ID, User ID, and Date. Leveraging Spark's capabilities, we'll then generate insightful daily, weekly, and monthly reports from the ingested data. These reports will include metrics such as the top 10 events and their respective counts for a given date, identifying returning users, determining active users, and calculating churn rates. By employing Kafka for real-time event ingestion and leveraging Iceberg/Delta Lake for efficient storage and querying, our solution ensures scalability, reliability, and performance in processing large volumes of event data for actionable insights. This end-to-end pipeline empowers businesses to make data-driven decisions swiftly and effectively.
