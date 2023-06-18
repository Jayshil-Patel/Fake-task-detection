# Fake-task-detection

In this project, I successfully implemented a solution for detecting fake tasks in a Mobile CrowdSensing (MCS) dataset. The goal was to develop a machine learning model that can accurately distinguish between legitimate and illegitimate tasks based on various task attributes.

To begin, I utilized the Mobile CrowdSensing Dataset, which contains information such as task location (latitude and longitude), day, hour, duration, battery requirement, coverage, and task legitimacy. The dataset consisted of a total of 14,484 tasks, including 12,587 legitimate tasks and 1,897 fake tasks.

The project followed a structured presentation format, and I adhered to the given guidelines to ensure a comprehensive and engaging presentation. The presentation consisted of several key slides, each addressing different aspects of the project.

The first slide provided an overview of the problem at hand, accompanied by a conceptual figure illustrating the end-to-end data flow. This figure showcased the complexity of the task and provided valuable insights into the problem.

Next, I presented an overview of the dataset through exploratory data analysis (EDA) on a dedicated slide. This included numerical information about the dataset, along with an input-output relationship depicted through a machine learning model diagram.

To give a clear understanding of the project's implementation process, I included a general flowchart on a separate slide. The flowchart depicted each step involved in the solution, using different colors to highlight different parts of the methodology.

In order to understand the nature of the problem and set a baseline performance, I applied various machine learning methods to the dataset. These methods included K-Nearest Neighbors (KNN), Logistic Regression, Support Vector Machines (SVM), Decision Tree Classifier, and Naive Bayes Classifier. The confusion matrix and accuracy scores for each method were plotted on a bar chart to establish the baseline.

For the first improvement strategy, I explored dimensionality reduction techniques and feature selection methods. I applied Principal Component Analysis (PCA) and Autoencoder for dimensionality reduction, comparing their performance against the baseline accuracy. Additionally, I selected two feature selection techniques from wrapper, filter, and embedded types and compared their accuracy performances with the best dimensionality reduction results. The highest test accuracy was used to update the dataset for subsequent analysis.

To further enhance the performance, I introduced additional machine learning models such as Random Forest, Ensemble techniques, and other suitable algorithms. Their performance was compared to the first improvement through confusion matrices, and if the new results surpassed the first improvement, they were considered the second improvement; otherwise, the first improvement was retained.

In order to fine-tune the parameters and achieve even better performance, I conducted parameter tuning on two specific parameters. By varying the parameter values and evaluating the accuracy, I identified the optimal values that led to the highest performance. Each parameter's performance was plotted separately, and if a higher accuracy was achieved than the second improvement, it was considered the third improvement.

In conclusion, this project successfully addressed the challenge of fake task detection in Mobile CrowdSensing. Through a comprehensive analysis, I demonstrated the effectiveness of various machine learning techniques, dimensionality reduction, feature selection, and parameter tuning in improving the accuracy of the detection model. The insights gained from this project can contribute to the development of robust fraud detection systems in the Mobile CrowdSensing domain.

