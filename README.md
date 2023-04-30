# Face Detection
**CSE 573 Homework 5**

#### <font color=red>You can use opencv >= 4.5.4 for this homework.</font>


**task 1 validation set**
```bash
# Face detection on validation data
python task1.py --input_path data/validation_folder/images --output ./result_task1_val.json

# Validation
python ComputeFBeta/ComputeFBeta.py --preds result_task1_val.json --groundtruth data/validation_folder/ground-truth.json
```

**task 1 test set running**

```bash
# Face detection on test data
python task1.py --input_path data/test_folder/images --output ./result_task1.json
```


The submission files  in `Coding/` should contain only  3 files, named **"task1.py"**, **"result_task1.json"**, **"result_task1_val.json"**. If not, there is something wrong with your code/filename, please go back and check.

**Notes:**

- Do NOT include `data/` , `ComputeFBeta/` or `README.md` in your submission.
- The data structure of `result_task1_val.json` is different from that of `ground-truth.json`.
