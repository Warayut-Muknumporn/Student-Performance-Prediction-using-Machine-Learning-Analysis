# Student-Performance-Prediction-using-Machine-Learning-Analysis
In this dissertation, the project is based on machine learning algorithms
which are convenient for predicting student performance. One challenge of the research is dealing with the enormous amount of information in MOOCs. This research focuses on using educational data mining (EDM) to develop for the benefit of students and find the algorithm to predict student performance to predict the grade early and help students in terms of decision making.

# Implementation

The dataset for this research has been provided by Open University Learning Analytics dataset. This data set is generated from collecting educational information through MOOCs. The publicly accessible dataset comprises student demographics, the modules they study, the semester they begin, their academic performance measured by their marks on assignments and examinations, and their interactions with virtual learning environments (VLE). The task predicts which students will fail or withdraw and pass the module. The dataset is a little disorganised, with multiple missing values and discrepancies across tables. The first section of the work has a complete list of cleaning procedures. Numerous discrepancies are brought to light and corrected, or recommendations are offered on how to do so in future work. Some feature engineering is carried out with proposals for additional features that might benefit this project. Several classification and regression methods also forecast the academic progress of students.

# Frame the problem

the data's nature should create regression and classification problems to predict student performance: failure, withdrawal, and pass from module presentation. The aforementioned is challenging in light of the data limitations, considering the incompleteness of data. The Assessment Results table is incomplete; the final test results for all students are absent for all but one module. This implies that the whole table with scores as a response variable for regression may provide less reliable findings due to incomplete information. Thus, it is conceivable for a student to pass their assignments yet fail the final test, resulting in a failing grade for the module as a whole. A second concern is that score, and the final result is the same in the Student Information table. Therefore, projecting the possibility of someone failing based on the fact that they received a final grade of less than 40% is not a prediction. Moreover, it would be fascinating to determine if it is feasible to identify students who are in danger of dropping out or failing without knowing their real academic achievement. Considering these factors, the following is the plan: 

• Regression problem: combine all data, delete the final result column from the Student Information table, and use the scores as the target.

• Classification Problem: combine all tables except for Assessment Results and utilise the target field from the Student Information database.

# Exploratory data analysis

![3](https://github.com/Warayut-Muknumporn/Student-Performance-Prediction-using-Machine-Learning-Analysis/assets/116235617/aeebedd0-674c-4cca-b71f-bf9039249d43)
![249](https://github.com/Warayut-Muknumporn/Student-Performance-Prediction-using-Machine-Learning-Analysis/assets/116235617/37db574a-c448-4a10-ae56-fbab486c6de4)
![5](https://github.com/Warayut-Muknumporn/Student-Performance-Prediction-using-Machine-Learning-Analysis/assets/116235617/2bc96bec-4916-4ea5-af66-4cd18798c378)
![4](https://github.com/Warayut-Muknumporn/Student-Performance-Prediction-using-Machine-Learning-Analysis/assets/116235617/7cc847ad-4f54-4255-bb5d-ab56d60b83bf)


# Modeling

![222](https://github.com/Warayut-Muknumporn/Student-Performance-Prediction-using-Machine-Learning-Analysis/assets/116235617/b3811a8e-37ab-42b6-87f9-a50f540ea9f1)
![111](https://github.com/Warayut-Muknumporn/Student-Performance-Prediction-using-Machine-Learning-Analysis/assets/116235617/3ec1449e-13a8-44a6-a472-663129e9a87d)
![2](https://github.com/Warayut-Muknumporn/Student-Performance-Prediction-using-Machine-Learning-Analysis/assets/116235617/607ae68d-04bf-459d-9d13-17ac00277958)
![1](https://github.com/Warayut-Muknumporn/Student-Performance-Prediction-using-Machine-Learning-Analysis/assets/116235617/313d4b39-f2dd-4a6a-919a-181069d456d6)


