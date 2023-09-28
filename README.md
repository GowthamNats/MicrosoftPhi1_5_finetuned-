---
license: other
base_model: microsoft/phi-1_5
tags:
- generated_from_trainer
model-index:
- name: phi-1_5-finetuned
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# phi-1_5-finetuned

This model is a fine-tuned version of [microsoft/phi-1_5](https://huggingface.co/microsoft/phi-1_5) on a cocktail dataset.

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.0002
- train_batch_size: 2
- eval_batch_size: 8
- seed: 42
- gradient_accumulation_steps: 2
- total_train_batch_size: 4
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: cosine
- num_epochs: 1

### Training results



### Framework versions

- Transformers 4.33.3
- Pytorch 2.0.1+cu118
- Datasets 2.14.5
- Tokenizers 0.13.3
