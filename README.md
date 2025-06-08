# Apache Airflow Setup with Docker on Windows

## Prerequisites
Before proceeding, ensure you have the following installed:
- **Docker Desktop** - [Download here](https://www.docker.com/products/docker-desktop/)
- **Visual Studio Code** - [Download here](https://code.visualstudio.com/)
- **Git** (if you plan to version control your project) - [Download here](https://git-scm.com/)

## Setup Instructions

### 1. Create Airflow Directory
Navigate to your desired location on your PC and create a folder named `Airflow`:
```powershell
mkdir Airflow
  mkdir Airflow

cd Airflow
mkdir dags logs plugins

```

### 2. Download the airflow compose file
- **Docker Compose File** - [https://airflow.apache.org/docs/apache-airflow/3.0.1/docker-compose.yaml]
- Save it inside the same folder inside the Airflow folder.

### 3. Run Aiflow
- open terminal inside Vs-code and browse to the Airflow folder.
```powershell
docker-compose up airflow-init
docker-compose up
```

### 4. Airflow on browser
- Once the containers are up and running, Open Airflow on browser default location: localhost:8080
- The default userid - airflow, and password - airflow
