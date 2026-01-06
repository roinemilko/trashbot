# trashbot
A computer vision model to classify waste into 6 categories based on recyclability. Data from [kaggle](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification).
<img width="595" height="624" alt="image" src="https://github.com/user-attachments/assets/2b6cec48-12ee-498f-9075-3e6b0057e3e4" />

## Method
Transfer learning with the resnet 50 -architecture trained on Imagenet v1 weights. Image preprocessing etc. detailed in the notebook.
## Further improvements / todo
- More detailed validation (e.g. per -class F1 score and one vs. rest ROC curve) is required
- Since training only takes $\sim$ 10-15 minutes, hyperparameter tuning with regression could improve results
- Data from different sources should be incorporated to better correspond to real-world scenarios
- "biowaste" -class missing
