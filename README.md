SAS Viya Forecasting Pipelines
=============================

## Overview
SAS Visual Forecasting, the new-generation forecasting product from SAS, includes a web-based user interface for creating and running projects that generate forecasts from historical data. It is designed to use the highly parallel and distributed architecture of SAS® Viya®, a cloud-enabled, in-memory analytics engine that is powered by SAS® Cloud Analytic Services (CAS), to effectively model and forecast time series on a large scale. SAS Visual Forecasting includes several built-in modeling strategies, which serve as ready-to-use models for generating forecasts. It also supports custom modeling nodes, where you can write and import your own code-based modeling strategies. Similar to the ready-to-use models, these custom modeling nodes can also be shared with other projects and forecasters. Forecasters can use SAS Visual Forecasting to create projects by using visual flow diagrams (called pipelines), running multiple built-in or custom models on the same data, and choosing a champion model based on the results. 

This repository provides custom pipeline and modeling nodes in SAS Visual Forecasting.

## Custom modeling nodes:
| File name  | VF version | Description |
| ------------- | ------------- | ------------- |
| Gradient Boosting Model.zip  | Viya 4  | Example of a custom code node using Gradient Boosting for time series forecasting. Details are in the SGF Paper SAS3258-2019, **Writing a Gradient Boosting Model Node for SAS® Visual Forecasting**, downloadable at [click here](https://www.sas.com/content/dam/SAS/support/en/sas-global-forum-proceedings/2019/3258-2019.pdf).|