## Repository Structure

```plaintext
Repo/
├── model/                    # Trained machine learning models
├── api.py                    # FastAPI application
├── README.md                 # Project documentation
```
---

## Setup Instructions

### Prerequisites
Ensure you have the following installed on your system:
- Python 3.8+
- pip (Python package installer)
- Virtual environment tool (optional but recommended)

### Installation
1. Clone this repository:
   ```bash
   git clone <repo-url>
   cd <repo-name>
   ```

2. Set up a virtual environment:
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Verify the setup:
   ```bash
   python --version
   pip list
   ```

---

## Running the Project

### Run the API
Start the FastAPI server:
```bash
uvicorn api:app --reload
```

### Step 3: Access the Swagger Documentation
Open your browser and go to:
[https://127.0.0.1:8000/docs](https://127.0.0.1:8000/docs)

This will display the interactive Swagger UI for testing the API endpoints.

---

## API Endpoints
The API provides the following endpoints:
- `/predict` - Retrieve sales predictions based on weather data.
---
