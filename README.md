# Finetune-Longformer

Above is my code of finetuning a BERT-based model (Longformer) for Sequence Classification Task. I did finetune it on 200k+ training examples from the COLIEE dataset(2024).
Pipeline: Create Dataset -> Create Dataloader -> Customize original model (by adding a FFN on top of Longformer architecture) -> Configuring training params -> Training..
