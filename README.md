# Chinkara Open Question Answering Dataset

This is a dataset based on [Dolly 15k](https://huggingface.co/datasets/databricks/databricks-dolly-15k) dataset. We've only taken *open_qa* parts of those instructions and then created our new dataset. This dataset can be used in your projects using `datasets` library and it's also accessible on [HuggingFace](https://huggingface.co/datasets/MaralGPT/chinkara_open_qa).

## Goal

The goal of creating this dataset was to train our model [Chinkara](https://github.com/prp-e/chinkara) on it and test the outcome compared to the old Guanaco one.

## Structure

The dataset follows the following structure: 

```
### Human: INSTRUCTION
### Assistan: RESPONSE
``` 

This structure was pretty much used in every other _Guanaco_ style dataset out there and seemed to be the best structure for an LLM which is going to be trained with QLORA method.

## Why Dolly?

Dolly 15k is a good choice since it is _human generated_ and it reduces the risk on hallucinations. Also the other advantage of this dataset is that it is _available only in English_. Being mono-lingual can be beneficial when the model is small and quantized.

## Further procedures

For now, there is no further study, action or procedure to be done on this particular project.