# Motor_Insuring_Pricing_Model

This project focuses on building a motor insurance pricing model to estimate the expected cost of claims. The project uses motor insurance data with information about vehicles, policyholders, exposure, number of claims, and claim costs. The data is first explored to understand the main patterns and differences in risk between different groups of customers.

The model uses a frequency-severity approach. A Poisson GLM is used to predict how often claims occur, while a Gamma GLM is used to predict the cost of a claim. These two predictions are then combined to calculate the expected claim cost, also known as the pure premium.

The project also compares the risk levels of different policyholders and checks how well the model performs on unseen data. It demonstrates the use of Python, data analysis, GLMs, and basic actuarial insurance pricing concepts to solve a real-world motor insurance problem.
