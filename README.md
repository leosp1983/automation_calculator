# Automation Analytics
========================

**Objective**
-------------

Deployment and configuration of Grafana with an Automation Analytics dashboard.

**Functions**
-------------

- [X] Creates the Grafana directory structure: Ensures that the necessary folders to store dashboards, datasources, and plugins are created.

- [x] Validates Grafana installation: Checks if the Grafana service is installed and available on the target machine.

- [x] Configures the Infinity data source: Sets up the yesoreyeram-infinity-datasource, used to read JSON files from a URL.

- [x] Provisions the Automation Analytics dashboard: Imports a panel with customized visualizations for ROI, savings, and statistics from Ansible Automation Platform.


**References**
-------------

- https://docs.ansible.com

- https://developers.redhat.com/articles/2024/08/28/monitor-ansible-automation-platform-using-prometheus-node-exporter-and-grafana?source=sso#conclusion