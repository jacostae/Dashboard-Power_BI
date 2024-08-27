# Dashboards en Power BI

A continuación, se explica brevemente la funcionalidad de los dashboards encontrados en este repositorio:

## 1. Seguimiento Recaudo

Este dashboard realiza el seguimiento al recaudo de los vehículos de una empresa de transporte, que cuenta con diferentes unidades estratégicas de negocio.

### Página _General_
Se observa el recaudo registrado por unidad estratégica de negocio y su proyección de recaudo (realizada en DAX, dependiendo de los días faltantes del mes y su recaudo promedio diario):
![Recaudo_1](https://github.com/user-attachments/assets/25135b5b-7144-4993-8610-f7f05bac935d)

### Página _Recaudo por vehículo_
Se observa el recaudo por vehículo, teniendo en cuenta que cada tipo de vehículo tiene valores de recaudo meta, los cuales se van recalculando a medida que pasan los días. De esta manera, se obtiene un semáforo que indica cuáles están en el rango óptimo de recaudo, cuáles superan la meta de recaudo y cuáles están por debajo de esta:
![Recaudo_3](https://github.com/user-attachments/assets/c1f436eb-9544-4809-b538-8e69cd70202c)

### Página _Recaudo diario_
Se observa el recaudo diario de los vehículos, así como el top 10 de los vehículos con mayor recaudo:
![Recaudo_2](https://github.com/user-attachments/assets/b32352d7-05f3-48dd-95f2-b4c72e0da6a8)


## 2. Operación dedicada
Este dashboard muestra la posición actual del vehículo, la cantidad de kilómetros recorridos en el mes y las horas de conducción diaria de cada vehículo. Esta información se obtiene de la API de Geotab:
![S1](https://github.com/user-attachments/assets/12fde662-20b6-4d03-a2e1-a5afb18f8223)

## 3. ETA
Este dashboard muestra la posición actual del vehículo (información de la API de Geotab), el destino (información del viaje obtenida de un archivo alojado en SharePoint) y el tiempo estimado de llegada (obtenido mediante una consulta a la API de Google Maps, utilizando la ubicación actual y el destino):
![ETA](https://github.com/user-attachments/assets/85cb8b80-ab7b-436d-99ee-d353d8db7bdd)

