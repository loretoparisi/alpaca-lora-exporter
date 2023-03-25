# alpaca-lora-exporter
Export alpaca-lora to Torch checkpoint and HuggingFace

## Alpaca-LoRA Checkpoint export
You can use the script `export_hf_checkpoint.py` from the original Alpaca-LoRa repo to export the checkpoint to the HuggingFace format
or use the script `export_state_dict_checkpoint.py` to export the checkpoint to the PyTorch format.

## Usage
```
git clone https://github.com/loretoparisi/alpaca-lora-exporter.git
cd alpaca-lora-exporter/
pip install -r requirements.txt
python export_state_dict_checkpoint.py
```
