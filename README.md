
https://github.com/user-attachments/assets/6ba50a7c-0b1a-4ead-adde-d608f310264a

# Zeta Project
Zeta is divided into three repositories.

- Anyone can create LLMs using the Zeta-Tool.
- Zeta-Dataset is the publication location of datasets for the Zeta-Tool.
- Azuki-Format is the format of datasets for the Zeta-Tool.

## Official/Recognized Models
### Zeta 2
- **(Safetensor)** [Zeta-2 by DiamondGotCat](https://huggingface.co/DiamondGotCat/Zeta-2): Original Model for Customization
- **(GGUF)** [Zeta-2-GGUF by mradermacher](https://huggingface.co/mradermacher/Zeta-2-GGUF): Quantized Model ready to use (Thanks for mradermacher!)
- **(Ollama)** [Zeta-2 on Ollama by DiamondGotCat](https://ollama.com/DiamondGotCat/Zeta-2): Easy to Use with Ollama Command (`ollama run DiamondGotCat/Zeta-2:f16`)

### Zeta 1
- **(Safetensor)** [Zeta-1 by DiamondGotCat](https://huggingface.co/DiamondGotCat/Zeta-1): Original Model for Customization
- **(GGUF)** [Zeta-1-GGUF by mradermacher](https://huggingface.co/mradermacher/Zeta-1-GGUF): Quantized Model ready to use (Thanks for mradermacher!)
- **(Ollama)** [Zeta-1 on Ollama by DiamondGotCat](https://ollama.com/DiamondGotCat/Zeta-1): Easy to Use with Ollama Command (`ollama run DiamondGotCat/Zeta-1:latest`)

## Contributors
- [Sabale302](https://github.com/Sabale302) in Zeta-Tool: Thanks for sharing your ideas!
- [mradermacher](https://huggingface.co/mradermacher) in Zeta: Thanks for converting it to GGUF!

## License
It's MIT licensed.
I decided on this license because it makes it easy and free for anyone to use.

## Repos
- [Zeta-Tool](https://github.com/DiamondGotCat/Zeta-Tool): Create Your Own LLM using NLoRAT
- [Zeta-Dataset](https://github.com/DiamondGotCat/Zeta-Dataset/releases): Datasets for Zeta-Tool
- [Azuki-Format(AzukiF)](https://github.com/DiamondGotCat/Azuki-Format): Dataset Format for Zeta-Tool

(NOTE: Hinode-AI, and Azuki-AI is Marged to Zeta Project)

## What is NLoRAT?

**NLoRAT (Non-LoRA Tuning)** is a simple method of fine-tuning an existing LLM *without* using LoRA or adapters.  
You just train the model as-is, using your own dataset (e.g. in Azuki Format).  
No special tools or architecture changes are required.

If you can run the original LLM, you can also run the LLM with NLoRAT.
