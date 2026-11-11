# Project Setup

## I. Run or Test Locally
Requires:
    Python
    Docker Desktop 

### 1. Create & Activate Environment  

```bash
python3.12 -m venv venv    # Pin to v3.12
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate.bat  # Windows
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Load and Run PostgreSQL Container
```bash
docker compose up -d db
```

### 4. Test Locally 
```bash
pytest
```

### 5. Run Locally 
```bash
python main.py
``` 

## II. DockerHub

DockerHub URL: https://hub.docker.com/r/nosaomoregie/601_m10no


