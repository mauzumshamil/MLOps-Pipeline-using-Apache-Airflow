# MLOps-Pipeline-using-Apache-Airflow

## Author
**Mauzum Shamil**  
*Data Scientist | Machine Learning Enthusiast | Problem Solver*  

GitHub: [github.com/mauzumshamil](https://github.com/mauzumshamil)  
LinkedIn: [linkedin.com/in/mauzum-shamil](http://linkedin.com/in/mauzum-shamil)  
Portfolio: [linktr.ee/mauzum_shamil](https://linktr.ee/mauzum_shamil)

---

## Project Overview

This project demonstrates how to build an **MLOps pipeline** using **Apache Airflow**. The pipeline ensures smooth and efficient workflows by automating tasks such as data preprocessing, model training, and deployment using **DAGs** (Directed Acyclic Graphs). The goal is to streamline machine learning processes while enhancing efficiency, scalability, and reproducibility.

## Why Use Apache Airflow for MLOps?
Apache Airflow:

Automates repetitive tasks like data preprocessing, model training, and deployment.
Enhances efficiency by eliminating manual interventions.
Ensures scalability and reproducibility of workflows, making it easier to maintain and scale ML pipelines.

# MLOps Pipeline using Airflow

## Getting Started

### Clone the repository:
```bash
git clone https://github.com/mauzumshamil/mlops-pipeline-using-airflow.git
cd mlops-pipeline-using-airflow
```

### Install dependencies:
```bash
pip install -r requirements.txt
```

### Initialize Airflow:
```bash
airflow db init
```

### Start the webserver and scheduler:
```bash
airflow webserver --port 8080
airflow scheduler
```

Access the UI and monitor your pipelines at [http://localhost:8080](http://localhost:8080).

## Future Improvements
- Add monitoring tools like Prometheus and Grafana for real-time analytics.
- Implement CI/CD pipelines for automated deployment.
- Extend the pipeline to support model retraining and A/B testing.

## Conclusion
This project highlights the integration of Apache Airflow into an MLOps pipeline to improve automation, scalability, and efficiency. Feel free to fork, explore, and adapt it to suit your own ML workflows.
