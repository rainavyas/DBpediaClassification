# Objective
Train a Transformer based architecture on the classifying the [DBpedia](https://huggingface.co/datasets/dbpedia_14) dataset into one of fourteen classes.

# Dependencies

## Install using PyPI

`pip install datasets`
`pip install torch`
`pip install transformers`

# Train

# Training

Fork the repository (and clone).

Run the _train.py_ scripts with desired arguments in your terminal. For example, to train an ELECTRA-based classifier:

`python ./train.py my_model.th electra --B=8 --lr=0.00001 --epochs=2`


Note that the training script finetunes pre-trained architectures.
