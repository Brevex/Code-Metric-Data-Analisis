<h1 align = "center"> US Used Cars Data Analysis </h1><br>

<h2> &#128269; About the project </h2><br>

<p>This data analysis aims to catalog and filter different algorithms into a complexity metric. An initial dataframe with the scores 
was filtered to better understand how efficient each algorithm in the database can be. The final dataframe with the filtered data 
classifies the algorithms into 3 labels: Risk by Cyclomatic Complexity, Fan-in and Fan-out Complexity and Maintainability Score.</p><br>

<h2> &#128200; Classification Criteria </h2><br>

| Type of Complexity            | Equation                                                    |
|:-----------------------------:|:-----------------------------------------------------------:|
| Fan-in and Fan-out            | $C = wmc \cdot (Fin \cdot Fout)^2$                          |
| Maintainability Score         | $MS = loopQty + comparisonsQty + numbersQty + variablesQty$ |
| Risk by Cyclomatic Complexity | $wmc$                                                       |

| Type of Complexity            | Evaluation Criteria                                         | 
|:-----------------------------:|:-----------------------------------------------------------:|
| Fan-in and Fan-out            | $0=(<= 100), 1=(101-1000), 2=(> 1000)$                      |
| Maintainability Score         | $0=(<= 65), 1=(66-85), 2=(> 85)$                            |
| Risk by Cyclomatic Complexity | $0=(<= 10), 1=(11-20), 2=(21-50), 3=(> 50)$                 |

| Evaluation value   | Risk by Cyclomatic Complexity | Fan-in and Fan-out Complexity | Maintainability Score |
|:------------------:|:-----------------------------:|:-----------------------------:|:---------------------:|
| 0                  | Low                           | Good                          | Good                  |
| 1                  | Moderate                      | Moderate                      | Moderate              |
| 2                  | High                          | High                          | Bad                   |
| 3                  | Very High                     | (N/A)                         | (N/A)                 |

<br>
<h2> &#128302; Technologies Used </h2><br>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py" />
  </a>
</p>

<br><h2> &#128202; Analysis Result </h2><br>

<div align="center">
  <img src="https://github.com/Brevex/Code-Metric-Data-Analisis/blob/84451405bfd9952321e6ecb98d76beded072cad5/readme%20images/chart.png">
</div>

<br><h3 align = "center"> - By <a href = "https://www.linkedin.com/in/breno-barbosa-de-oliveira-810866275/" target = "_blank">Breno</a> - </h3>
