# LLM-Batman
Applying modern techniques for testing and evaluating LLM responses in a variety of contexts. A performance rubric will be created that evaluates the accuracy, completeness, conceptual depth, originality/insight, faithfulness to source, and bias/hallucination for starters. This rubric will evolve with time.

There will also be some objective evaluation measures added (even though this is a fairly subjective, unsupervised task), such as ROUGE / BLEU / METEOR, BERTScore, other LLMs as critiquers. I will also experiment with some prompt engineering to see if these make a big difference in scores or not, utilizing principles from [the prompt engineering guide](https://www.promptingguide.ai/).

Finally, model's outputs will be generated by the HuggingFace APIs, later shifted to OpenAI Playground or something similar as needed.

# What will be tested?

- Cross-cultural philosophical synthesis

- Deep character and narrative understanding

- Ability to reason through abstract lenses

- Comparative ethical analysis

- Respect for cultural, religious, and historical context

- Handling of non-Western frameworks (Sufi, Taoist, Islamic, Confucian)


# Why do this...?
The world has had many interesting figures. These people had incredibly powerful philosophies. You find that, as you read more and more about them, you start seeing intersections in places you never imagined before. 

This repository is an examination of such things, with the lens of testing LLMs in mind, while learning something new (hopefully). The plan is to utilize as many useful benchmarks and evaluation criteria as possible. Examples, 

1. [sekfcheckgpt](https://github.com/potsawee/selfcheckgpt) and [the associated paper](https://arxiv.org/pdf/2303.08896)

2. [bigbench](https://github.com/google/BIG-bench)

3. [HELM](https://crfm.stanford.edu/helm/classic/latest/)

4. [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness)

5. [Anthropic Constituitional AI](https://arxiv.org/pdf/2212.08073)

