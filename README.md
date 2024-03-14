# LLMEval-Survey

## Paper Structure

* What to evaluate
    * Natural language generation 
        * Summarization
        * Dialogue
        * Translation
        * QA
        * Sentence style transfer
        * data to text
            * image caption
        * story generation
        * general generation
    * Reasoning 
        * mathematical reasoning
        * commonsense reasoning
        * logical reasoning
        * domain-specific reasoning
    * Robustness, Ethic, Bias, Trustworthiness, Factuality, toxicity 
    * Knowledge
      * Social Science
      * Natural Science and Engineering
      * Medical Applications

* How to evaluate
    * Benchmark evaluation 
        * HELM
        * Big-Bench
        * MMLU
        * TruthfulQA
        * MT-Bench
        * AlpacaEval
    * LLM evaluator
        * Prompt-based
            * score-based
            * probability-based
            * likert-style
            * pariwise
            * ensemble
            * advanced
        * tuning-based
            * probability-based
            * likert-style
            * pariwise
            * advanced
        * aspects
            * accuracy, fluency....
    * Human evaluation
        * Chatbot Arena

## LLMs for evaluation
### Prompt-based
- [Score-based] | [Multi-Dimensional Evaluation of Text Summarization with In-Context Learning](https://arxiv.org/abs/2306.01200)
- [Probability-based] | [Gptscore: Evaluate as you desire](https://arxiv.org/abs/2302.04166)
- [Factscore: Fine-grained atomic evaluation of factual precision in long form text generation](https://arxiv.org/abs/2305.14251)
- [Chateval: Towards better llm-based evaluators through multi-agent debate](https://arxiv.org/abs/2308.07201)
- [Can large language models be an alternative to human evaluations?](https://arxiv.org/abs/2305.01937)
- [Large Language Models are not Fair Evaluators](https://arxiv.org/abs/2305.17926)
- [Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena](https://arxiv.org/abs/2306.05685)
### Tuning-based
- [T5score: Discriminative fine-tuning of generative evaluation metrics](https://arxiv.org/abs/2212.05726)
- [X-Eval: Generalizable Multi-aspect Text Evaluation via Augmented Instruction Tuning with Auxiliary Evaluation Aspects](https://arxiv.org/abs/2311.08788)
- [CritiqueLLM: Scaling LLM-as-Critic for Effective and Explainable Evaluation of Large Language Model Generation](https://arxiv.org/abs/2311.18702)
- [PandaLM: An Automatic Evaluation Benchmark for LLM Instruction Tuning Optimization](https://arxiv.org/abs/2306.05087)
- [INSTRUCTSCORE: Explainable Text Generation Evaluation with Finegrained Feedback](https://arxiv.org/abs/2305.14282)
### [other reference](https://docs.google.com/document/d/1sXmIE6JUVjpVAGTpyqgeaoSIWK0tvT-I20-t7hzKnC0/edit?usp=sharing)

## Applications of LLM-evaluators
- [OpinSummEval: Revisiting Automated Evaluation for Opinion Summarization](https://arxiv.org/abs/2310.18122)
- [SummEval: Re-evaluating Summarization Evaluation](https://arxiv.org/abs/2007.12626)
- [USR: An Unsupervised and Reference Free Evaluation Metric for Dialog Generation](https://arxiv.org/abs/2005.00456)
- [StoryER: Automatic Story Evaluation via Ranking, Rating and Reasoning](https://arxiv.org/abs/2210.08459)
- [Shepherd: A Critic for Language Model Generation](https://arxiv.org/abs/2308.04592)
- [Wider and Deeper LLM Networks are Fairer LLM Evaluators](https://arxiv.org/abs/2308.01862)
- [Automatic Evaluation of Attribution by Large Language Models](https://arxiv.org/abs/2305.06311)

## Benchmark
- [Holistic Evaluation of Language Models](https://arxiv.org/abs/2211.09110)
- [Beyond the Imitation Game: Quantifying and extrapolating the capabilities of language models](https://arxiv.org/abs/2206.04615)

## Evaluating LLM's alignment 
- [Trustworthy LLMs: a Survey and Guideline for Evaluating Large Language Models' Alignment](https://arxiv.org/abs/2308.05374)
