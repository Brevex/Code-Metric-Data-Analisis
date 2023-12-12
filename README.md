<h1 align = "center"> US Used Cars Data Analysis </h1><br>

<h2> &#128269; About the project </h2><br>

<p>This data analysis aims to catalog and filter different algorithms into a complexity metric. An initial dataframe with the scores 
was filtered to better understand how efficient each algorithm in the database can be. The final dataframe with the filtered data 
classifies the algorithms into 3 labels: Risk by Cyclomatic Complexity, Fan-in and Fan-out Complexity and Maintainability Score.</p><br>

<h2> &#128246; Classification Criteria </h2><br>

<div align="center">
	
| Type of Complexity            | Equation                                                    | Evaluation Criteria                                         | 
|:-----------------------------:|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| Fan-in and Fan-out            | $C = wmc \cdot (Fin \cdot Fout)^2$                          | $0=(<= 100), 1=(101-1000), 2=(> 1000)$                      |
| Maintainability Score         | $MS = loopQty + comparisonsQty + numbersQty + variablesQty$ | $0=(<= 65), 1=(66-85), 2=(> 85)$                            |
| Risk by Cyclomatic Complexity | $wmc$                                                       | $0=(<= 10), 1=(11-20), 2=(21-50), 3=(> 50)$                 |

</div>

<h2> &#128302; Technologies Used </h2><br>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py" />
  </a>
</p>

<br><h2> &#128202; Analysis Result </h2><br>

<details>
	<summary>Importance score for each variable</summary><br>
	<p>The variable importance score in the context of the random forest algorithm indicates the importance of each
	feature (variable) in predicting the target variable, which, in this case, is the price of the car. In other words, a variable 
	is considered important if removing it from the model results in worse predictions. The importance of the variable is calculated 
	for all trees in the forest and then the average is taken 5.</p><br>
	<img src="https://github.com/Brevex/US-Used-Cars-Data-Analysis/blob/54f75e2de4f55d668ba495bef7ac14ec4011e24b/readme%20images/feature%20importance.png">
</details>

<details>
	<summary>Average horsepower by engine cylinders</summary><br>
	<p>Data analysis showing the average horse power value of each engine model in the dataset</p><br>
	<img src="https://github.com/Brevex/US-Used-Cars-Data-Analysis/blob/54f75e2de4f55d668ba495bef7ac14ec4011e24b/readme%20images/horse%20power.png">
</details>

<details>
	<summary>Average horsepower score per engine</summary><br>
	<p>Machine learning model that attempts to establish a relationship between the engine model and the amount of power. The 
	model uses a random forest tree process to assign a score to each model.</p><br>
	<img src="https://github.com/Brevex/US-Used-Cars-Data-Analysis/blob/54f75e2de4f55d668ba495bef7ac14ec4011e24b/readme%20images/engines%20score.png">
</details>

<details>
	<summary>Price prediction</summary><br>
	<p>The scatterplot shows the result of a machine learning model that tries to predict the price of cars. As shown in the graph, only 
	a minority of the values deviate from those predicted by the prediction model, showing a good frequency of hits with approximate values.</p><br>
	<img src="https://github.com/Brevex/US-Used-Cars-Data-Analysis/blob/54f75e2de4f55d668ba495bef7ac14ec4011e24b/readme%20images/price%20prediction.png">
</details>


<br><h3 align = "center"> - By <a href = "https://www.linkedin.com/in/breno-barbosa-de-oliveira-810866275/" target = "_blank">Breno</a> - </h3>
