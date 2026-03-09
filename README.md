# ottf


## 1. Environment Setup
Create the reproduction environment using the following command:
```bash
conda env create -f environment.yml
```

## 2. Data Preparation
### Target Dataset
POPE (COCO split)

Put the dataset under `/your_path/data` and replace the placeholder in the code with your actual dataset path to ensure proper loading.

## 3. Usage Instructions
1. Navigate to the project directory:
```bash
cd ./OTT
```

2. Full-process inference commands (run sequentially):
```bash
# First inference script
bash run_pope.sh

# Second inference script
bash test_pope_my.sh
```

## 4. Key Notes
- This repository provides code for LLaVA-1.5 on the POPE COCO dataset

- Core logic of the proposed framework implemented in `pope_fast.py`.
- Follow the placeholders in the code to configure dataset paths and model loading parameters.

- This code draws heavily on the open-source work of PAI and VISTA, and we sincerely thank their contributions to the community.
