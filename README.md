# assgn3_102203136
Data Representation
Models Considered: GPT-3.5, LLaMA 2, and Mistral
Decision Matrix: Stores the performance of each model across the six evaluation criteria.
Weights: Each criterion is assigned a relative importance score.

 Normalization of Data
Since the criteria have different units and scales, the script applies Min-Max Normalization to standardize values. For cost criteria (where lower is better), values are inverted.

 Weighted Normalized Decision Matrix
Each normalized value is multiplied by the corresponding weight to ensure fair comparison.

 Ideal and Negative-Ideal Solutions
Ideal Solution: The best possible value for each criterion.
Negative-Ideal Solution: The worst possible value for each criterion.
The script calculates these based on the maximum and minimum values in the weighted decision matrix.

 Distance Calculation
Using Euclidean distance, the script computes:

Distance from the Ideal Solution (S⁺)
Distance from the Negative-Ideal Solution (S⁻)

 Compute the TOPSIS Score
The final score for each model is computed as:
 
A higher score means the model is closer to the ideal solution and is ranked higher.

 Results & Visualization
The models are ranked based on their TOPSIS scores.
A bar chart visualizes the scores of each model.

 Output
The ranking of the models is printed.
The best model has the highest TOPSIS score.












