# Paper

(additional support to train the models, in addition to the more general code to recreate the actual tables).

## Model Training

We use the standard HuggingFace library to train the model. 

To train the model, we basically edited the HuggingFace code provided [here](https://github.com/NielsRogge/Transformers-Tutorials/blob/master/BERT/Fine_tuning_BERT_(and_friends)_for_multi_label_text_classification.ipynb). We apply minimal edits to this code (e.g., we need to use our own dataset, first by loading it from a CSV file and then we cast it to an HugginFace dataset). We then just use DeBERTa-large (v3) as a base model. The hyper-parameters that we use are those that are found after the hyper-param search are available in the paper.

Happy to provide more details on this if needed!

