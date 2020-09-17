# Bidirectional Adversarial Networks for microscopic Image Synthesis (BANIS)

### Author: Jun Zhuang, Dali Wang

### Files:
"Data" files is used to store preprocessed dataset \
"preproc.py" is used for preprocessing \
"utils.py" contains utilized functions \
"banis_model.py" is the model architecture \
"main.py" is the main function

### Dataset:
C. elegans microscopy images

### Executions:
1. Preprocess the dataset and get the pkl files.
2. Run main function for training or synthesize the images \
python [script_name] -num_epochs -warmup_step -is_trainable \
  e.g. python main.py 40000 17000 true (for training)
