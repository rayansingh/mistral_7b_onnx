# mistral_7b_onnx

Convert Mistral7b to ONNX Format

NOTE: I did not have nearly enough compute or RAM on my laptop to run this model so I created a VM instance on Google Cloud with an NVIDIA T4 GPU. 

```
optimum-cli export onnx --model mistralai/Mistral-7B-v0.1 mistral_onnx --batch_size 1
```

To view the model architecture, check out
https://netron.app

Helpful Links:

https://huggingface.co/docs/optimum/en/exporters/onnx/usage_guides/export_a_model

https://www.reddit.com/r/LocalLLaMA/comments/17k2mwq/i_dont_understand_mistral_and_context_size/
