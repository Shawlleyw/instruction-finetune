# Instruction Finetune with ColossalAI

A LLM finetune script with ColossalAI framework.

This script takes advantage of QLoRA.


## Data Format

The data format aligns with alpaca dataset.

## Usage

```shell
usage: Instruction Finetune [-h] [--model MODEL] [--epoch EPOCH]
                            [--memory-track] [--batch BATCH_SIZE] --data
                            DATA_PATH [--tokens MAX_TOKENS]
                            [--plugin {torch_ddp,gemini,low_level_zero}]

Fine-tune LLM models in colossal-AI framework through QLoRA

optional arguments:
  -h, --help            show this help message and exit
  --model MODEL
  --epoch EPOCH
  --memory-track
  --batch BATCH_SIZE    specify batch size
  --data DATA_PATH      specify data path
  --tokens MAX_TOKENS   specify max tokens
  --plugin {torch_ddp,gemini,low_level_zero}
                        specify a plugin
```
