# Visor de calidad del agua en Colombia
### Alvaro Villamizar


https://github.com/AlvaroVillamizar/Visor-de-Calidad-del-agua/assets/43424429/47b0d3ff-67ff-427f-baaf-d360ae493355


Enlace al reporte: https://app.powerbi.com/reportEmbed?reportId=7dcb6a0a-3b44-4085-a4f4-475b97cde28f

Para este proyecto se desarrollaron tres tableros de visualización utilizando el software de Power BI, destinados a optimizar la gestión de infraestructuras críticas en el ámbito municipal.

El primer tablero, denominado “IRCA urbano - rural” se enfoca en el Índice de Riesgo de Calidad del Agua (IRCA), proporcionando una representación gráfica y detallada de los niveles de riesgo en diferentes regiones. Mediante mapas de calor se categoriza cada municipio en función de su clasificación y valor IRCA. En esta visualización se ha aplicado una codificación que utiliza valores específicos y colores para representar las distintas categorías según la calidad del agua en cada municipio, clasificados de acuerdo a la información de la siguiente tabla.

| Clasificación IRCA (%) | Nivel de Riesgo         | Color (Hex) |
|------------------------|-------------------------|-------------|
| 80.1 - 100             | Inviable sanitariamente | d64550      |
| 35.1 - 80              | Alto                    | e66c37      |
| 14.1 - 35              | Medio                   | d9b300      |
| 5.1 - 14               | Bajo                    | 38bb00      |
| 0 - 5                  | Sin riesgo              | 118dff      |
| S.D.                   | Sin dato                | 808080      |



El segundo tablero aborda las redes de alcantarillado y acueducto. Esta visualización presenta un enfoque detallado sobre las características de la calidad del agua, con un mapa de colores de las municipalidades de Colombia, el cual clasifica cada característica según su nivel de aceptabilidad siendo azul: Aceptable, rojo: No aceptable, gris: sin dato. Adicionalmente se cuenta con un gráfico de torta dedicado a la distribución de cada una de las características del agua, y finalmente en la parte superior se encuenta un menú de características para modificar el mapa de colores a través de varias características, (Color aparente, Coliformes, Cloro residual, Turbiedad, pH y E-Coli).

<figure class="image">
<p align="center">
<img src="https://github.com/AlvaroVillamizar/Visor-de-Calidad-del-agua/blob/main/Images/Menú_IRCA.png" width="auto" height="auto">
**Figura 1.** Menú de características.

Finalmente, el tablero denominado “Población Vs Muestras” se presenta un mapa de colores, un gráfico de torta y una tabla informativa. El propósito principal de esta subsección es evaluar la suficiencia de muestras de IRCA disponibles para cada municipio. Los municipios se clasifican en las categorías de "Cumple" o "No cumple" según la cantidad de muestras disponibles. Para esta categorización, se sigue el siguiente criterio

| Población atendida por persona prestadora por municipio | Número mínimo de muestras al año |
|---------------------------------------------------------|----------------------------------|
| Menores o igual a 2.500                                 | 17                               |
| 2.501 - 10.000                                          | 41                               |
| 10.001 - 20.000                                         | 182                              |
| 20.001 - 100.000                                        | 365                              |
| 100.001 - 500.000                                       | 365                              |
| 500.001 - 800.000                                       | 1095                             |
| 800.001 - 1.000.000                                     | 1460                             |
| 1.000.001 - 1.250.000                                   | 1825                             |
| 1.250.001 - 2.000.000                                   | 2190                             |
| 2.000.001 - 4.000.000                                   | 2555                             |
| Mayor a 4.000.000                                       | 2555                             |
