### Implementacion de Grafana + CAdvisor + Prometheus + node_exporter



## Grafana
Permite presentar por medio de graficos y dashboard las metricas de los agentes de Prometheus, node_exporter, Cadvisor entre otros
- [Documentacion Grafana](https://grafana.com/docs/grafana/latest/setup-grafana/installation/docker/)

## Prometheus
Prometheus se encarga de recopilar y almacenar métricas de rendimiento
- [Documentacion Prometheus](https://prometheus.io/docs/prometheus/latest/installation/)

## Cadvisor
cAdvisor (Container Advisor) proporciona a los usuarios de contenedores una comprensión del uso de recursos y las características de rendimiento de sus contenedores en ejecución. Es un demonio en ejecución que recopila, agrega, procesa y exporta información sobre los contenedores en ejecución. Específicamente, para cada contenedor, mantiene parámetros de aislamiento de recursos, uso histórico de recursos, histogramas de uso histórico completo de recursos y estadísticas de red. Estos datos se exportan por contenedor y a nivel de máquina.
- [Documentacion Cadvisor](https://github.com/google/cadvisor)

## node_exporter

Exportador Prometheus para métricas de hardware y sistema operativo expuestas por kernels *NIX, escrito en Go con recolectores de métricas conectables.
- [Documentacion Cadvisor](https://github.com/prometheus/node_exporter)