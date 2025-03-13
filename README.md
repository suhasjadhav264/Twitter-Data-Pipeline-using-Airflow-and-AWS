# Twitter Data Pipeline | End-to-End Data Engineering with Airflow & AWS

## 📌 Project Overview
This project demonstrates an **end-to-end data engineering pipeline** using **Apache Airflow and Python** to extract, transform, and store real-time Twitter data. The pipeline is deployed on **AWS EC2** and the final data is stored in **Amazon S3** for further analysis.

## 🚀 Key Features
- **Real-time Data Extraction:** Collects tweets using the **Twitter API**.
- **Data Transformation:** Processes and cleans data using **Python and Pandas**.
- **Workflow Orchestration:** Automates scheduling and monitoring with **Apache Airflow**.
- **Cloud Deployment:** Deploys Airflow DAGs on **AWS EC2**.
- **Data Storage:** Saves processed data in **Amazon S3**.

## 🛠️ Tools & Technologies
- **Orchestration:** Apache Airflow
- **Programming:** Python
- **Cloud Services:** AWS EC2, Amazon S3
- **Data Extraction:** Twitter API
- **Data Processing:** Pandas, JSON

## 📂 Project Structure
```
📦 Twitter-Data-Pipeline
├── 📁 dags            # Airflow DAG scripts
├── 📁 scripts         # Python scripts for data extraction and transformation
├── 📁 config         # Configuration files (API keys, AWS credentials)
├── 📄 requirements.txt # Dependencies
├── 📄 README.md       # Project documentation
└── 📄 setup.sh        # Script to set up Airflow on EC2
```

## 🔄 Workflow
1. **Extract Twitter Data:** Connect to the Twitter API and fetch real-time tweets.
2. **Transform Data:** Clean and structure the data using Python (Pandas, JSON parsing).
3. **Store Data:** Upload the processed data to Amazon S3.
4. **Schedule & Automate:** Use Apache Airflow DAGs to run the pipeline on AWS EC2.

## 📊 Data Sources
- **Twitter API:** Fetches tweets based on specific keywords or hashtags.

## 🏁 How to Run the Project
1. **Set up an AWS EC2 instance** and install Apache Airflow.
2. **Configure the Twitter API keys** in the project.
3. **Deploy the Airflow DAGs** to schedule and automate the pipeline.
4. **Verify data storage in Amazon S3** after execution.

## 📌 Future Enhancements
- Implement **real-time streaming** with Apache Kafka.
- Integrate **AWS Lambda** for serverless execution.
- Extend analytics using **AWS Glue and Athena**.

## 🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests.

## 📜 License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

