# Current Topics: Temporal Reasoning

Within the scope of this paper we investigate the performance of the `roberta`
model on the novel task of **temporal reasoning**. Furthermore, we explore different
strategies of boosting baseline performance and compare fine-tuning methods to
modern prompt engineering methods.

## Datasets
- Raw Dataset
- Cleaned Dataset
- Cleaned Dataset + $x\%$ generated samples
- Parsed Dataset
- ...

## Methods
- Extending small dataset with generated samples
- Using parameter efficient training methods ([adapters](Adapters/README.md))
- Using special pretrained models
- ...

## Results

| Model     | Dataset         | Accuracy* | Notes    |
|-----------|-----------------|-----------|----------|
| `roberta` | Raw Dataset     |           | Baseline |
| `roberta` | Cleaned Dataset |           | Baseline |
| ...       |                 |           |          |


\* Accuracy using 5-Fold Cross Validation

## Procedure
For each _new_ idea, create a new subfolder and milestone.
Inside the folder add a README file describing, what you are doing and why. 
(As well as other relevant files).

Others can make suggestions such as "make sure to test with
dataset X" by adding issues to specific milestones.
Make sure the main README is updated.
Enter results in the results table and link to your README in the subfolder.
