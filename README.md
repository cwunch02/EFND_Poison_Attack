# EFND_Poison_Attack

This is a poisoning attack for the [Explainable Fake News Detection with Large Language Model via Defense Among Competing Wisdom](https://doi.org/10.1145/3589334.3645471) by Wang et al.

## To use
Simply put the `RAWFC_poisoned` directory into the `datasets` directory in the EFND main directory. Then simply replace the `dataset.py`, `step2_explanation_generation.py`, and `step3_final.py` in the `source` directory.

Following this, simply run the commands as found on the [Github](https://github.com/wangbo9719/L-Defense_EFND?tab=readme-ov-file) for the project. Replace the first and second commands `--dataset_name RAWFC` with `--dataset_name RAWFC_poisoned` to start the training and top-k evidences.

After this, simply follow the commands until the end of training and testing.
