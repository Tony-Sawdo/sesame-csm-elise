# Sesame CSM Elise

This model is a fine-tuned version of [sesame/csm-1b](https://huggingface.co/sesame/csm-1b) using the [Elise dataset](https://huggingface.co/datasets/MrDragonFox/Elise).

The model can be found here: [keanteng/sesame-csm-elise](https://huggingface.co/keanteng/sesame-csm-elise)

## Model Details
- **Base Model**: sesame/csm-1b
- **Training Data**: MrDragonFox/Elise dataset
- **Fine-tuning Approach**: Voice cloning through conditional speech generation
- **Voice Characteristics**: [Describe voice qualities]
- **Training Parameters**: 
  - Learning Rate: 2e-5
  - Epochs: 3
  - Batch Size: 1 with gradient accumulation steps of 4
- **GPUs Used**: 1x NVIDIA A100 40GB

## Samples

Samples can be listened after downloading, you can find them [here](https://huggingface.co/keanteng/sesame-csm-elise/tree/main/inference).


## Using This Repo

Load the repo:

```bash
git clone https://github.com/keanteng/sesame-csm-elise/blob/main/requirements.txt
```

Install the requirements:

```bash
pip install -r requirements.txt
```
