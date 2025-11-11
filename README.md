
<img width="1920" alt="zeta_full_black" src="https://github.com/user-attachments/assets/e0cf639f-53b5-4baa-b417-cd957cb83b23" />

> [!IMPORTANT]
> I am developing various projects, and since I manage, maintain, and update all of them myself, there may be times when I can't attend to each project individually.
> For example, large-scale projects like [Zeta-LLM](https://github.com/Zeta-DGC/Zeta-LLM) are very difficult to develop.
> [PyYPSH](https://github.com/YPSH-DGC/YPSH) is also a challenging project, as it implements a custom programming language using ASTs, which is quite advanced.
> If you would like to report bugs or suggest new features for my projects, I would greatly appreciate it if you could use pull requests and make them ready to merge, if possible.
> Also, if someone else has already created an issue, I would be thankful if you could create a pull request that immediately addresses the problem, if you're able to.
> (This message is displayed in some repositories created by Nercone. Translated by GPT-4o.)

# Zeta LLM
| [Zeta Official X Account](https://x.com/Zeta_LLM/) |

Zeta is divided into three repositories.

- Anyone can create LLMs using the Zeta-Tool.
- Zeta-Dataset is the publication location of datasets for the Zeta-Tool.
- Azuki-Format is the format of datasets for the Zeta-Tool.

## Official Models [[Release Tab]](https://github.com/DiamondGotCat/Zeta/releases)

### [Zeta 4.5](https://github.com/DiamondGotCat/Zeta/releases/tag/zeta-4.5) (2025-06_01)
**(Latest)** | 464M Params | MIT License | Official GGUF Available (Quantized by mradermacher) |

### [Zeta 4](https://github.com/DiamondGotCat/Zeta/releases/tag/zeta-4) (2025-05_03)
| 464M Params | MIT License | Official GGUF Available (Quantized by mradermacher) |

### [Zeta 3](https://github.com/DiamondGotCat/Zeta/releases/tag/zeta-3) (2025-05_02)
| 464M Params | MIT License | Official GGUF Available (Quantized by mradermacher) |

### [Zeta 2](https://github.com/DiamondGotCat/Zeta/releases/tag/zeta-2) (2025-05_01)
**(Stable)** | 464M Params | MIT License | Official GGUF Available (Quantized by mradermacher) |

### [Zeta 1](https://github.com/DiamondGotCat/Zeta/releases/tag/zeta-1) (2025-04_01)
| 405M Params | MIT License | Official GGUF Available (Quantized by mradermacher) |

## Contributors
- [Sabale302](https://github.com/Sabale302) in Zeta-Tool: Thanks for sharing your ideas!
- [mradermacher](https://huggingface.co/mradermacher) in Zeta: Thanks for converting it to GGUF!

## Repos
- [Zeta-Tool](https://github.com/Zeta-LLM/Zeta-Tool): Create Your Own LLM using NLoRAT
- [Zeta-Dataset](https://github.com/Zeta-LLM/Zeta-Dataset/releases): Datasets for Zeta-Tool
- [Azuki-Format(AzukiF)](https://github.com/DiamondGotCat/Azuki-Format): Dataset Format for Zeta-Tool

(NOTE: Hinode-AI, and Azuki-AI is Marged to Zeta Project)

## What is NLoRAT?

**NLoRAT (Non-LoRA Tuning)** is a simple method of fine-tuning an existing LLM *without* using LoRA or adapters.  
You just train the model as-is, using your own dataset (e.g. in Azuki Format).  
No special tools or architecture changes are required.

If you can run the original LLM, you can also run the LLM with NLoRAT.
