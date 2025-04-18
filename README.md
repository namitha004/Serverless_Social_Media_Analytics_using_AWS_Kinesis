**Serverless Social Media Analysis using AWS Kinesis
**
This project demonstrates a real-time, serverless architecture for analyzing social media streams using AWS Kinesis, Lambda, S3, and QuickSight. It captures, processes, stores, and visualizes social media data—delivering insights end-to-end without managing servers.

🚀 Project Overview
Pipeline Components
Kinesis Data Stream – Ingests real-time social data (e.g., tweets).
AWS Lambda – Parses and processes the stream.
Sentiment Analysis Module – Performs basic sentiment scoring.
Amazon S3 – Stores processed records in JSON/CSV.
Amazon QuickSight – Builds interactive dashboards from S3 data.

Services Used
AWS Kinesis Data Streams
AWS Lambda (Python)
Amazon S3
Amazon QuickSight
AWS IAM
AWS Comprehend

🛠️ How to Use
-->Create a Kinesis Data Stream
Set up the stream to receive social or mock data.
-->Deploy Lambda Function
Write logic to process and analyze incoming data.
-->Configure Amazon S3
Store the output in a structured format (e.g., partition by timestamp).
-->Connect to QuickSight
Create a dataset using your S3 bucket and design visual dashboards.

📺 Demo Video
Watch the full walkthrough here:
https://www.youtube.com/watch?v=zic-CdxjUwQ&t=4s

🧑‍💻 Getting Started
Clone or download the repository
Deploy the stream and Lambda function
Set proper IAM roles
Connect S3 to QuickSight for analytics

📬 Contact
For queries or contributions, feel free to reach out at:
namitha.mikkilineni@gmail.com

