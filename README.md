# Widespread Error Detection in Large Scale Continuous Integration Systems

This repository contains slides presented at the 2024 CI/CD Industry Workshop (CCIW).

If you use this method in your research, please consider citing it as:
```
@inproceedings{swierc2024widespread ,
  author    = {Swierc, Stanislaw and Lu, James and Yi, Thomas},
  title     = {Widespread Error Detection in Large Scale Continuous Integration Systems},
  year      = {2024},
  maintitle = {IEEE Conference on Software Testing, Verification and Validation (ICST)},
  booktitle = {CI/CD Industry Workshop (CCIW)},
}
```

## Dataset
To reproduce this analysis, download the dataset. It contains  5000 Json documents describing verification process of React project collected between 2023 and 2024.

- https://zenodo.org/records/11238429

## Setup
This project uses [Pipenv](https://pipenv.pypa.io/). To create a new virtual environment and install all dependencies, use the following command:

```bash
pipenv sync
```

