# Comparative Study of Explainability Methods for Legal Outcome Prediction
### This is the repository for the paper "Comparative Study of Explainability Methods for Legal Outcome Prediction"

#### Authors: Ieva Raminta Staliūnaitė, Josef Valvoda, Ken Satoh

The code is adapted from Jacovi et al. 2021 https://github.com/allenai/contrastive-explanations
Ravfogel et al. 2022 https://github.com/shauli-ravfogel/rlace-icml
and Valvoda et al. 2023 https://github.com/valvoda/Negative-Precedent-in-Legal-Outcome-Prediction

The data from Haberal et al. 2023 https://github.com/trusthlt/mining-legal-arguments
and Mumford et al. 2023 https://github.com/jamumford/ECHR_Article6_ADM_Ascribe
should be saved in mining-legal-arguments and ECHR_Article6_ADM_Ascribe
The ECtHR data should be saved in data/ecthr following Valvoda et al. 

# Integrated Gradients

python3 interpret.py

# Contrastive Explanations

notebooks/ecthr-highlight-featurerank.ipynb

# Concept Erasure

sh rlace-icml/exp/finetune.sh
sh rlace-icml/exp/run_legal_concepts.sh
sh rlace-icml/exp/run_rlace.sh
python3 rlace-icml/exp/analysis.py