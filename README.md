# Machine Learning Engineer Advent Calendar

Advent, the 4th Century Christian tradition celebrating and preparing the four weeks before Christmas inspired the modern creation of retail [Advent calendars](https://www.npr.org/2022/12/11/1141855237/advent-calendar-history-evolution) (printed and gift-based) in the 19th Century. Virtual Advent calendars are the latest progression of the Advent calendar where individuals and families can create their own virtual  countdown of Christmas or any event. In this mold, I created the Machine Learning (ML) Engineer Advent Calendar as a 25-day series of hands-on Jupyter notebooks to demonstrate core ML engineering skills in realistic workflows for individuals looking to develop the ML engineering abilities. Each week focuses on a different aspect of ML engineering, using [Kaggle](https://www.kaggle.com/), public, and synthetic datasets. Additionally, we end each week with a Thursday Docker lab so you can package and reproduce analysis before deploying in the cloud or using an Amazon Web Services (AWS) cloud service in the Friday lab.

## Calendar Goals

- Delve into data engineering, feature engineering, model building, MLOps, responsible Machine Learning, and more
- Create reproducbile Machine Learning pipelines
    - ETL, data checks, logging, Docker-based containerization, deployment
- Leverage AWS services: SageMaker, S3, Data Wrangler, and more

## Weekly Structure

| Week | Theme |
|------|--------|
| 1 | Data Foundations |
| 2 | Machine Learning Fundamentals |
| 3 | Deep Learning & Transformers |
| 4 | Software Engineering for ML |
| 5 | MLOps & Deployments |
| 6 | Responsible Machine Learning |

## Getting Started

1. Clone the repository:
```bash
git clone git@github.com:kpolimis/machine_learning_advent_calendar.git
cd machine_learning_advent_calendar
````

2. Create a Python environment:

```bash
conda env create -f environment.yml
conda activate ml-advent
```

3. Launch Jupyter Lab:

```bash
jupyter lab
```

## Project Directory

```
machine_learning_advent_calendar/
├── aws/
├── azure/
├── datasets/
├── models/
├── notebooks/
├── scripts/
├── Dockerfile.base
├── Dockerfile.api
├── docker-compose.yml
├── environment.yml
└── README.md
```
