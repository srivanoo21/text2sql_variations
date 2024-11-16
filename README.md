# text2sql_variations
different variations of text2sql

LORA:
Incorporating the LoRA (Low-Rank Adaptation) configuration during model loading does not directly reduce the size of the model in terms of storage, but it does reduce the number of trainable parameters, leading to a significant reduction in memory usage and computational resources during training and inference.

QLORA:
Here we are fine-tuning a pre-trained Llama-3.2-1B model for text-to-SQL tasks using LoRA (Low-Rank Adaptation), enabling efficient adaptation with quantization to reduce model size and improve inference speed applying specific quantization parameters (like 4-bit or 8-bit) to optimize performance.
 
Unsloth:
While quantization reduces model size by lowering the precision of the weights (e.g., from 32-bit to 8-bit or lower), Unsloth focuses on improving efficiency by restructuring the way attention heads are used during inference, which can reduce latency but does not alter the actual model size.



