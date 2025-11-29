# My SageMaker Template

Use this repository to instantiate new repositories for use in Amazon SageMaker projects. 

## Structure

The template has the following structure, which is recommended for all data scientists.

```
├── README.md          <- The top-level README for developers using this project.
├── data               <- Store any interim or processed data here temporarily
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
││
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks
│
├── scripts            <- Python files
```