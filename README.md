# Grad-Seminar26-Notes

A collection of reading notes and seminar presentations from the 2026 Graduate Seminar.

## 📚 What I Learned in 2026

| Topic | Notes |
|-------|-------|
| RoFormer: Rotary Position Embedding (RoPE) | [View Notes](https://github.com/ChengruiHan/Grad-Seminar26-Notes/blob/main/RoPE.pdf) |
| Scaling Laws: From Training to Inference | [View Notes](https://github.com/ChengruiHan/Grad-Seminar26-Notes/blob/main/Scaling%20Laws.pdf) |
| DETR Series for Object Detection | [View Notes](https://github.com/ChengruiHan/Grad-Seminar26-Notes/blob/main/DETR%20%E7%B3%BB%E5%88%97%E7%9B%AE%E6%A0%87%E6%A3%80%E6%B5%8B%E6%96%B9%E6%B3%95.pdf) |
| Is Harness All You Need? | [View Notes](https://github.com/ChengruiHan/Grad-Seminar26-Notes/blob/main/Harness.pdf) |

## Summaries

- **RoFormer / Rotary Position Embedding (RoPE)**: Derives how rotary encodings inject absolute position while making attention scores depend on relative position. Covers the high-dimensional construction, efficient implementation, long-distance decay, and context-length extrapolation.
- **Scaling Laws: From Training to Inference**: Connects power-law scaling for language-model training (Kaplan), compute-optimal model/data allocation (Chinchilla), and inference-time compute scaling. Compares how to allocate a fixed compute budget across training and reasoning.
- **DETR Series for Object Detection**: Traces the move from anchor/proposal-based detection to end-to-end set prediction with DETR, then to DINO's improved query initialization and denoising training, and Grounding DINO's open-vocabulary detection through text-conditioned categories.
- **Is Harness All You Need?**: Reviews agent harness mechanisms from frameworks such as LangChain and LangGraph to Claude Code, including action loops, tool execution, planning, context, and persistent memory. Concludes with how harness design shapes agent interaction and Agentic RL, and how to evaluate task quality alongside resource cost.
