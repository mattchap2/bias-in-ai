# Bias in AI

## Essay

Prepare an essay on your understanding of bias and discrimination in artificial intelligence. Your essay should follow a survey-like approach based on the reading assignments.

This essay should demonstrate your point of view on the overall subject of algorithmic bias. As the author, discuss the justifications on the reasons that bias in AI–based solutions should be addressed. Also, your essay should demonstrate various ways to measure the fairness of a dataset and algorithm and discuss different ways to mitigate algorithmic bias. Moreover, also discuss what you expect to see in the fair machine learning solutions in the future.

Appropriately use citations and back your proposed discussion with relevant literature. Focus on peer-reviewed references with reasonably well–cited manuscripts.

## Implementation

Analyse a human-centric dataset and develop a fair machine learning ecosystem to detect, reduce and eventually mitigate different types of bias that exist in the final outcome of the algorithm in various ways.

### Task 1: Project Proposal
Select the project you wish to work on. Write maximum of one page project proposal describing what you intend to implement, and the reasons you believe that it suits bias in artificial intelligence.

Please describe what you’d like to do. Describe the motivation for this project, what concrete tasks you plan to do, and what the final work product of these tasks will be.

Is there a particular context you’re thinking about (e.g., hiring, advertising) as you formulate this project? If you’re planning to do an empirical project, list the dataset(s) you will use or gather.

It isn’t necessary that you do precisely what you outline above for the final project, but it should help you start thinking about your work to answer these questions. Also, please indicate what technologies you plan to use in your implementation (i.e. the programming language, packages that you use for data analysis and the implementation of AI algorithm).

### Task 2 - Data Analysis

Find a human-centric dataset which is publicly available with demographic information (age, gender, race, sexual orientation, country of origin, etc). Please follow these steps:

1. Clearly describe any “cleaning”, binning, bucketing, or discrete-to-continuous feature transformation you did in this process in the project progress section.

2. For one way of splitting the dataset into different demographic groups, write down the size of the groups, the average value for each (numeric) feature, the variance of each (numeric) feature, the mode for each categorical feature, and the three most frequent values for each categorical feature, each computed on the different demographic subgroups. If your dataset has more than 20 features, you can report this information only for 20 features. Do you observe any interesting differences between the different subgroups’ statistics?

3. If you have observed any sort of bias, please describe it and explain the reasons why this bias has happened from your point of view.

### Task 3 - Conventional Implementation

At this stage of the project, you have a biased dataset. Now, implement a conventional ML algorithm that suits the project description. For instance, if you have chosen to solve a classification problem in your project proposal, implement a classification algorithm that is widely used (and is potentially biased).

1. Describe your chosen algorithm and justification for selection in the project progress section in the project proposal document.

2. Naively split your dataset into training and testing sets by randomly sampling some of the data, for example, 70% train and 30% test. If your model has hyper–parameters that you wish to optimise, you may wish to create a separate validation dataset to optimise these, for example 70% training, 15% validation, and 15% testing.

3. Train your model and see how it generalises to the testing dataset. Explain your approach and findings.

4. Subsample a new testing dataset in an unbiased way and representative of the task, for example, you may wish to ensure gender and age diversity. Retrain your model and see how it generalises to these new testing conditions. Compare your findings with the results in 3 and explain your approach.

5. If you have observed any sort of bias, please describe it and explain the reasons why this bias has happened from your point of view.

### Task 4 - Fair Machine Learning Implementation

Implement one of the fair ML methods of mitigating bias in the scope of your selected project (if you choose only one algorithm to implement, you should justify your choice). Use the solutions that were provided in the suggested projects papers. Now, follow these steps:

1. Implement the fair ML solution used in your project (if there is more than one, implement only one).

2. Describe your proposed algorithms.

3. Now test the performance (i.e. accuracy, sensitivity or similar criteria, can be found in the research paper for your suggested project) of your trained model for the minority groups (if you have more than one, choose only one). Compare it with the performance of your model over the majority group.

4. If you have observed any reduction in algorithmic bias, describe it and use appropriate plots to demonstrate it.

5. Do you get roughly the same results as your project paper? If not, reconsider your code or justify the reasons.

6. If you have observed any sort of reduction in accuracy, please describe it from your point of view. Use proper plots and graphs where necessary.
