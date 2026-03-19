# AI Foundational Labs

Hands-on ML security labs covering the four core adversarial attack types. No setup required — runs entirely in your browser.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aimlsec/ai-foundational-labs/main)

> **One click to start:** Binder builds a live JupyterLab environment with all notebooks and datasets ready. First load takes ~3–5 minutes; subsequent loads are faster.

---

## Labs

| Notebook | Topic | Open |
|----------|-------|------|
| START_HERE.ipynb | Orientation & setup check | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aimlsec/ai-foundational-labs/main?filepath=START_HERE.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aimlsec/ai-foundational-labs/blob/main/START_HERE.ipynb) |
| Lab1_Evasion_Attack.ipynb | Craft inputs that fool a trained classifier | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aimlsec/ai-foundational-labs/main?filepath=Lab1_Evasion_Attack.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aimlsec/ai-foundational-labs/blob/main/Lab1_Evasion_Attack.ipynb) |
| Lab2_Poisoning_Attack.ipynb | Corrupt training data to backdoor a model | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aimlsec/ai-foundational-labs/main?filepath=Lab2_Poisoning_Attack.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aimlsec/ai-foundational-labs/blob/main/Lab2_Poisoning_Attack.ipynb) |
| Lab3_Inference_Attack.ipynb | Infer membership from model outputs | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aimlsec/ai-foundational-labs/main?filepath=Lab3_Inference_Attack.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aimlsec/ai-foundational-labs/blob/main/Lab3_Inference_Attack.ipynb) |
| Lab4_Extraction_Attack.ipynb | Steal a model by querying its API | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/aimlsec/ai-foundational-labs/main?filepath=Lab4_Extraction_Attack.ipynb) [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aimlsec/ai-foundational-labs/blob/main/Lab4_Extraction_Attack.ipynb) |

---

## Datasets

Datasets are **auto-downloaded** when the environment starts — no manual steps needed.

- **SMSSpamCollection** — UCI SMS Spam Collection (Lab 1, Lab 2)
- **nursery.data** — UCI Nursery dataset (Lab 3, Lab 4)

---

## Dependencies

`numpy` · `pandas` · `matplotlib` · `seaborn` · `scikit-learn` · `adversarial-robustness-toolbox`

No PyTorch or GPU required.
