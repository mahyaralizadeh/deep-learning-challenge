
# Report
# Overview of Analysis:
Explain the purpose of this analysis.

The purpose of this analysis is to create a tool for the nonprofit foundation, Alphabet Soup, that can help it select applicants for funding with the best chance of success in their ventures.
# Data Preprocessing

What variable(s) are the target(s) for your model?

The target for this model is X, or all of the columns in the new_application_df, excluding the "IS_SUCCESSFUL" column.
What variable(s) are the features for your model?

The feature for this model is the y, or the "IS_SUCCESSFUL" column in the new_application_df.
What variable(s) should be removed from the input data because they are neither targets nor features?

. The ID columns should be removed.

# Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
A sequential model with 3 layers (First Hidden, Second Hidden, and Output layer), 'relu' actvation functions for each, and 477 parameters were created.

Were you able to achieve the target model performance?

The first attept came closer to 72% which was under the desired 75%.

The second attempt ,I achieved 79% which was 4% over the target.
