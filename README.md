# **Cycloplegic_SER_model**

## Introduction
This cycloplegic spherical equivalent refraction（SER） prediction model is constructed using a stacking ensemble model based on non-cycloplegic SER and ocular biometric parameters (AL, CR, ACD, AL/CR, ACD/AL, AL×age, AL×CR, AL×ACD). The prediction model is used to improve the efficiency of ophthalmic diagnosis and treatment and to expand the coverage of population screening.

## Prerequisities & Installation

Create environment with conda
```bash
conda create -n C_SER_model python==3.9
conda activate C_SER_model
```

Install dependencies for finetuning
```bash
git clone https://github.com/NBeye-research/Cycloplegic_SER_model.git
cd Cycloplegic_SER_model
pip install -r requirements.txt
```

[Data example](data/data_700_example.csv)

**Please feel free to contact us for any questions or comments: Dan Li, E-mail: ldan@cdutcm.edu.cn or Yangyang Wang, E-mail: youngwang666@hotmail.com.**
