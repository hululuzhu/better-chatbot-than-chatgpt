# better-chatbot-than-chatgpt
- Brainstorm possible research/engineering candidates that could let us train better chatbots than ChatGPT/GPT4


## Tentative Agenda as of 2023/05/16

* Solid foundation pretrained models
    * [Llama](https://arxiv.org/abs/2302.13971') & [ChatGLM](https://github.com/THUDM/ChatGLM-6B/blob/main/README_en.md)
    * [MPT-7b](https://www.mosaicml.com/blog/mpt-7b) & [RedPajama](https://www.together.xyz/blog/redpajama)?
* Get close to ChatGPT by “behavioral cloning” or self-align? 
    * [Alpaca](https://github.com/tatsu-lab/stanford_alpaca)
    * [Vicuna](https://lmsys.org/blog/2023-03-30-vicuna/)
    * [Dromedary](https://arxiv.org/abs/2305.03047)
* More [sub-domain] knowledge than ChatGPT?
    * Domain specific pretraining: e.g. [codex](https://arxiv.org/abs/2107.03374), [Minerva](https://arxiv.org/abs/2206.14858)
    * Retrieval in LM training: [WebGPT](https://arxiv.org/abs/2112.09332) and [Sparrow](https://arxiv.org/abs/2209.14375)
    * [Augmented LM](https://arxiv.org/abs/2302.07842) (retrieval outside LM training)
        * E.g. [Langchain](https://python.langchain.com/en/latest/index.html), or [DPR](https://github.com/facebookresearch/DPR)
* [Weak] More aligned to human preference?
    * [Character.ai](Character.ai)
    * Tutor like [GPTutor](https://arxiv.org/abs/2305.01863)
* Longer context than GPT4?
    * [AliBi](https://arxiv.org/abs/2108.12409)
    * [HWFA](https://spaces.ac.cn/archives/9603) (chinese only, by Su Jianlin)
* Lower cost of training and inference?
    * [Multi-query attention](https://arxiv.org/abs/1911.02150)
    * [FlashAttention](https://arxiv.org/abs/2205.14135)
    * [FastTranformer](https://github.com/NVIDIA/FasterTransformer)
    * [PEFT](https://huggingface.co/blog/peft) by HuggingFace
    * [DeepSpeedChat](https://github.com/microsoft/DeepSpeedExamples/tree/master/applications/DeepSpeed-Chat)
* Better reward model and RL?
    * [InstructGPT](https://arxiv.org/abs/2203.02155)
    * [Anthropic](https://arxiv.org/abs/2204.05862)
    * [Sparrow](https://arxiv.org/abs/2209.14375)
    * [John Schulman Bekerley talk](https://www.youtube.com/watch?v=hhiLw5Q_UFg)
* More modalities than GPT4?
    * [HuggingGPT](https://arxiv.org/abs/2303.17580)
    * [MiniGPT4](https://github.com/Vision-CAIR/MiniGPT-4)

