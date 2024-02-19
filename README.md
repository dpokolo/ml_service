# ML Service
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) 

 ML Service with HTTP API and Streamlit UI served in two separate Docker containers.

 The model is a simple Logistic Regression iris classifier. You can replace it with model of your choice.

 # Usage""

 Run the project with the following command:

 ```
  docker compose up --build
```
You can also add `-d` flag to run in detached mode.

Once up and running, open this [link](http://localhost:8501/) in your browser to access Streamlit UI and [this link](http://localhost:8000/docs) to access OpenAPI docs page.
