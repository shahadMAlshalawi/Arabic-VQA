# Datasets

This directory contains the submodules for the datasets used in the Arabic VQA project. Each dataset is hosted on Hugging Face and can be accessed directly.

## Submodules

### 1. [ok-vqa-ar-en](https://huggingface.co/datasets/MahmoodAnaam/ok-vqa-ar-en)
- **Description:** OK-VQA dataset with Arabic and English translations for Visual Question Answering tasks.
- **Usage:**
  ```python
  from datasets import load_dataset

  ok_vqa = load_dataset("MahmoodAnaam/ok-vqa-ar-en")
  print(ok_vqa)
  ```

### 2. [vqav2-ar-en](https://huggingface.co/datasets/MahmoodAnaam/vqav2-ar-en)
- **Description:** VQAv2 dataset with Arabic and English translations for Visual Question Answering tasks.
- **Usage:**
  ```python
  from datasets import load_dataset

  vqav2 = load_dataset("MahmoodAnaam/vqav2-ar-en")
  print(vqav2)
  ```

## Notes

- These datasets are added as submodules and hosted on Hugging Face.
- To update the datasets, use the following command:
  ```bash
  git submodule update --remote
  ```
- To initialize the submodules when cloning this repository:
  ```bash
  git clone --recurse-submodules <repository_url>
  ```


