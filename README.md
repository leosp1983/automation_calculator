# Automation Analytics
========================

**Objetivo**
-------------

Implantação e configuração do Grafana com dashboard do Automation Analytics

**Funções**
-------------

- [X] Cria a estrutura de diretórios do Grafana: Garante que as pastas necessárias para armazenar dashboards, datasources e plugins estejam criadas.

- [x] Valida a instalação do Grafana: Verifica se o serviço Grafana está instalado e disponível na máquina alvo.

- [x] Configura a fonte de dados Infinity: Define a data source yesoreyeram-infinity-datasource, utilizada para leitura de arquivos JSON via URL.

- [x] Provisiona a dashboard do Automation Analytics: Importa o painel com visualizações personalizadas de ROI, savings e estatísticas do Ansible Automation Platform.


**Referências**
-------------

- https://docs.ansible.com

- https://developers.redhat.com/articles/2024/08/28/monitor-ansible-automation-platform-using-prometheus-node-exporter-and-grafana?source=sso#conclusion