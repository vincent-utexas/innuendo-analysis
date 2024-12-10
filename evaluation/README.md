# evaluation

This folder contains our scripts to evaluate our models.
* `visualization`: script to perform decomposition to visualize embeddings
* `baselines`: script to generate models trained on frequency data (CountVectorizer)
* `l2_grad`: script to explain importance of inputs for classification by finding the gradient of the output (logits) with respect to input (input embeddings)
* `integrated_gradients`: script to explain importance of inputs for classification by finding the gradient of the output with respect to the input, integrating along a linear interpolation from the baseline (all 0 embeddings) to the actual input
* `perturbation`: script to explain importance of tokens for classification by masking tokens in a sentence and comparing changes in class probabilities
* `heatmap`: visualize explanation methods using a heatmap
