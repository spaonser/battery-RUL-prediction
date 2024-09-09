# battery-RUL-prediction
A Li-ion battery Remaining Useful life project based on De-stationary Transformer
# Install
1. pip install -r requirements.txt
2. pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu124
# Explanation
In the experiments with two datasets, there are two directories. The battery-RUL directory contains multiple models, including our model, while the battery-RUL-AE directory contains the De-Transformer model.
# Data
Before conducting the experiment, you need to copy ./dataset/ to the main directory.
# Usage
Navigate to the ./scripts directory and execute the corresponding model using a bash command, for example: bash ./scripts/NASA_script/Autocorr_Nonstationary_Transformer.sh.
