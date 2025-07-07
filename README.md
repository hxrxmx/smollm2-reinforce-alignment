# SmolLM2 Reinforcement Learning Alignment

Implementation of RLHF alignment for **SmolLM2-135M** using:

- **REINFORCE** w/ moving average baseline with
  - Continuous-valued Reward Model (Level 1)
  - Probabilistic Reward Model (Level 2)

## Technical Details

**SFT Model:** [SmolLM2-135M-Instruct](https://huggingface.co/HuggingFaceTB/SmolLM2-135M-Instruct)  
**Dataset:** [HelpSteer2_binarized](https://huggingface.co/datasets/juyoungml/HelpSteer2-binarized)

## References

1. [Ouyang et al.](https://arxiv.org/abs/2203.02155) - Training language models to follow instructions with human feedback  
2. [Ahmadian et al.](https://arxiv.org/abs/2310.04413) - Back to Basics: REINFORCE Style Optimization