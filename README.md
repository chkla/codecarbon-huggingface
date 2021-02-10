# Testing CodeCarbon 💨 with Huggingface 🤗

In this notebook, I played around with the new [CodeCarbon](https://codecarbon.io/) 💨 package integrated into [Comet](https://www.comet.ml/) ☄️ using [Huggingface](https://huggingface.co/) 🤗 to show a fine-tuned language model's carbon footprint.

In 2019 the paper ["Energy and Policy Considerations for Deep Learning in NLP"](https://arxiv.org/pdf/1906.02243.pdf) popped up, discussing machine learning models' carbon footprint. Giving this as a portion of food for thought, the community starts thinking about the long-term effects and consequences.

The [CodeCarbon](https://codecarbon.io/) 💨 project is a software package to track the carbon footprint. This package is already integrated into [Comet](https://www.comet.ml/) ☄️ , a tool to analyze and track your models (similar to [wandb](https://wandb.ai/)).

To exemplify the use of CodeCarbon 💨, I used a part of code from [this](https://colab.research.google.com/github/huggingface/notebooks/blob/master/examples/text_classification.ipynb#scrollTo=uNx5pyRlIrJh) HuggingFace' notebook to define a simple task for fine-tuning a language model (if you want, you can try out any other task).

_Note: The current integration in HuggingFace seems to be a bit buggy in logging the experiments in the right format to get a carbon score._
