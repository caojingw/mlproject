## End to End ML Project
Goal: To gain more understanding about MLops and ways of deploying ML models. Credit to: https://github.com/krishnaik06/mlproject

### Prerequisites
- Python 3.8
- `pip install -r requirements.txt`

## How can I use it?

We're going to tackle this in 3 parts:
1. Running Flask on our local machines (Done)
2. Deploying our app to GCP App Engine (In process)
3. Converting to a Docker Image, uploading to Google Container Registry (GCR) and deploying on GCP

### 1. Getting the app running

1. Clone this repo
```
git clone https://github.com/caojingw/student_performance_prediction.git
```

2. Change into the directory
```
cd student_performance_prediction
```

3. Create and activate a virtual environment (optional)
```
pip install virtualenv
virtualenv <ENV-NAME>
source <ENV-NAME>/bin/activate
```
4. Install the required dependencies
```
pip install -r requirements.txt
```
5. Activate Flask and run `main.py`
```
Python app.py
```
**This is what you will see on your local URL:**

![image](https://github.com/caojingw/student_performance_prediction/assets/39035531/45fd2b23-200f-419e-a46b-b2616abf996f)

### 2. GCP App Engine - Coming soon

### 3. Docker Image - Coming soon
