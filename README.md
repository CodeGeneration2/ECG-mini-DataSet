# ECG–mini DataSet
  Since efficient code generation is a new branch that is opened for code generation, we curate a new dataset of efficient code generation programming problems called ECG for fine-tuning and evaluation. Accordingly, our model is fine-tuned on the ECG dataset. 
  
  The ECG draws on the APPS dataset (Hendrycks et al., 2021) and the CodeContests dataset (Li et al., 2022). We describe the dataset creation process and creative ideas in detail in Readme for DataSet folder.

  Although we developed the ECG dataset to perform efficient code generation, the ECG dataset is an exhaustive dataset that can be applied to different tasks. Therefore, we derived three datasets from this feature of the ECG dataset that can be applied to different specific code processing tasks to fill the gap of other code processing-oriented datasets.
  
Among the ECG datasets our model uses for efficient code generation, we derive three datasets from them: ECG-CG, [ECG-mini](https://github.com/CodeGeneration2/ECG-mini-DataSet), and ECG-clone. 
The specific description of [the ECG-mini dataset](https://github.com/CodeGeneration2/ECG-mini-DataSet) below.


## ECG–mini DataSet
  Since our dataset is intended to be exhaustive, many relevant descriptions will likely be annoying for some users who only use the critical data. Therefore, the ECG-mini dataset is split from the ECG, keeping only the essential data. Each amount of data has a problem text, a low-efficiency code, and a high-efficiency code.











