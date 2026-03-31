# Criterion-Conditional-In-Context-Learning

## For reviewer ByDF Q3: Evaluation of Multiple Criteria
This page contains detailed results for the 3-criteria evaluation mentioned in our rebuttal. These experiments demonstrate that our framework and the MCT method are robust to finer-grained decision boundaries and exhibit strong generalization capabilities.

- Table : Evaluation of MCT under 3-criteria setting
<img width="647" height="185" alt="table1" src="https://github.com/user-attachments/assets/3ebfe2bc-1393-46d2-8dd1-ac146ec741b2" />

Compared to the baseline (Qwen2.5-VL-7B), MCT significantly improves CS across Industrial, Medical, and Surveillance domains. This confirms that the model is learning to adapt to shifted boundaries rather than memorizing fixed categories.

- Table : Cross-domain generalization of MCT under the 3-criteria setting
<img width="811" height="216" alt="table2" src="https://github.com/user-attachments/assets/f78f3b94-2b72-4b70-bbfe-3f32bf171f22" />

MCT maintains consistent improvements even in cross-domain scenarios under the 3-criteria setting. For instance, a model trained only on "Medical" still shows substantial gains when tested on "Industrial" and "Surveillance" compared to the base model.

- Table : Generalization from 3-criteria training to 2-criteria evaluation
<img width="815" height="220" alt="table3" src="https://github.com/user-attachments/assets/2339f8ff-c17c-46a9-9915-71770ff8c30e" />

The results demonstrate Dual Generalization. Not only does the model retain high performance when shifting from 3-criteria to 2-criteria decision boundaries, but it also maintains superior CS and CI scores in entirely unseen domains (Cross-domain Generalization)

## For reviewer ByDF Q4:  Reasons for Failure Prediction

<img width="837" height="583" alt="Question" src="https://github.com/user-attachments/assets/599c71b2-8593-4d47-adf2-e2fcf429677c" />

