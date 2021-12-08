# DX Metrics Grafana Dashboards

This repository contains Grafana Dashboards in `json` format that can be [imported directly into Grafana](https://grafana.com/docs/grafana/latest/dashboards/export-import/#import-dashboard). The dashboards are created or customized to be compatible with the metrics exposed by [HCL Digital Experience](https://www.hcltechsw.com/dx).

## Introduction: DX Monitoring

> The Digital Experience 9.5 Helm deployment supports monitoring the deployment activity with advanced metrics and visualization, by exposing standards-based Prometheus-compatible metrics. Prometheus metrics components can scrape the metrics of most of the DX 9.5 container applications. The collected data is queried from Prometheus and are visualized in operations dashboard solutions, such as Grafana.  
>  
> (see [HCL Digital Experience Documentation](https://help.hcltechsw.com/digital-experience/9.5/containerization/monitor_helm_deployment_metrics.html))

## Contents of this repository

* [`dx-dashboards`](./dx-dashboards/README.md) - This folder contains DX dashboards that cover features specific to the DX applications. The dashboards are created and updated by the HCL DX team.
