# ConformalLLM
## Contributors: Charlie Lu (MIT), Bhawesh Kumar (Harvard), Gauri Gupta (MIT)
Extending Conformal Prediction to LLMs 

### We will update our code soon to include additional experiments.

In this notebook, we apply conformal prediction for generating robust uncertainty estimates for classification tasks in LLMs. 
We use LLaMA model to generate the uncalibrated uncertainty on MMLU dataset questions and use naive conformal prediction procedure to
obtain prediction sets with a guarantee on coverage rate. We also experiment with voilating exchangeability condition in LLMs and assess
how that affects covergae guarantee for conformal prediction.
