# Learning to Few-Shot Learn Across Diverse Natural Language Classification Tasks

This repository contains datasets used for evaluating few-shot performance introduced in the following paper. Please cite the paper if you use these datasets:


[Paper](https://arxiv.org/abs/1911.03863)
```
@inproceedings{bansal2020,
    title = "Learning to Few-Shot Learn Across Diverse Natural Language Classification Tasks",
    author = "Bansal, Trapit  and Jha, Rishikesh  and McCallum, Andrew",
    booktitle = "Proceedings of the 28th International Conference on Computational Linguistics (COLING)",
    year = "2020",
}
```

## Data
Data is available in two formats: JSON and tf_record  
Data is organized into a folder for each task.  
Each task contains 10 sampled datasets for training for each k-shot.  
Training file for i-th sample and k-th shot is named task_train_i_k, and the test data is in file task_eval.  
  
  
## Code
Code and trained models for this work are published in the following repository:
[MetaNLP](https://github.com/iesl/metanlp)

Please refer to the ReadMe there for instructions on using the model.