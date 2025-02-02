# Transformers-Tutorials

Hi there!

This repository contains demos I made with the [Transformers library](https://github.com/huggingface/transformers) by 🤗 HuggingFace.

NOTE: if you are not familiar with HuggingFace and/or Transformers, I highly recommend to check out our [free course](https://huggingface.co/course/chapter1), which introduces you to several Transformer architectures (such as BERT, GPT-2, T5, BART, etc.), as well as an overview of the HuggingFace libraries, including [Transformers](https://github.com/huggingface/transformers), [Tokenizers](https://github.com/huggingface/tokenizers), [Datasets](https://github.com/huggingface/datasets), [Accelerate](https://github.com/huggingface/accelerate) and the [hub](https://huggingface.co/).

Currently, it contains the following demos:
* BERT ([paper](https://arxiv.org/abs/1810.04805)): 
  - fine-tuning `BertForTokenClassification` on a named entity recognition (NER) dataset. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/BERT/Custom_Named_Entity_Recognition_with_BERT_only_first_wordpiece.ipynb)
* LayoutLM ([paper](https://arxiv.org/abs/1912.13318)): 
  - fine-tuning `LayoutLMForTokenClassification` on the [FUNSD](https://guillaumejaume.github.io/FUNSD/) dataset [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/LayoutLM/Fine_tuning_LayoutLMForTokenClassification_on_FUNSD.ipynb)
  - fine-tuning `LayoutLMForSequenceClassification` on the [RVL-CDIP](https://www.cs.cmu.edu/~aharley/rvl-cdip/) dataset [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/LayoutLM/Fine_tuning_LayoutLMForSequenceClassification_on_RVL_CDIP.ipynb)
  - adding image embeddings to LayoutLM during fine-tuning on the [FUNSD](https://guillaumejaume.github.io/FUNSD/) dataset [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/LayoutLM/Add_image_embeddings_to_LayoutLM.ipynb)
* TAPAS ([paper](https://arxiv.org/abs/2004.02349)):  
  - fine-tuning `TapasForQuestionAnswering` on the Microsoft [Sequential Question Answering (SQA)](https://www.microsoft.com/en-us/download/details.aspx?id=54253) dataset [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/TAPAS/Fine_tuning_TapasForQuestionAnswering_on_SQA.ipynb)
  - evaluating `TapasForSequenceClassification` on the [Table Fact Checking (TabFact)](https://tabfact.github.io/) dataset [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/TAPAS/Evaluating_TAPAS_on_the_Tabfact_test_set.ipynb)
* Vision Transformer ([paper](https://arxiv.org/abs/2010.11929)):
  - performing inference with `ViTForImageClassification` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/VisionTransformer/Quick_demo_of_HuggingFace_version_of_Vision_Transformer_inference.ipynb)
  - fine-tuning `ViTForImageClassification` on [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) using PyTorch Lightning [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/VisionTransformer/Fine_tuning_the_Vision_Transformer_on_CIFAR_10_with_PyTorch_Lightning.ipynb)
  - fine-tuning `ViTForImageClassification` on [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) using the 🤗 Trainer [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/VisionTransformer/Fine_tuning_the_Vision_Transformer_on_CIFAR_10_with_the_%F0%9F%A4%97_Trainer.ipynb)
* LUKE ([paper](https://arxiv.org/abs/2010.01057)):
  - fine-tuning `LukeForEntityPairClassification` on a custom relation extraction dataset using PyTorch Lightning [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/LUKE/Supervised_relation_extraction_with_LukeForEntityPairClassification.ipynb)
* DETR ([paper](https://arxiv.org/abs/2005.12872)):
  - performing inference with `DetrForObjectDetection` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/DETR/DETR_minimal_example_(with_DetrFeatureExtractor).ipynb)
  - fine-tuning `DetrForObjectDetection` on a custom object detection dataset [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/DETR/Fine_tuning_DetrForObjectDetection_on_custom_dataset_(balloon).ipynb)
  - evaluating `DetrForObjectDetection` on the COCO detection 2017 validation set [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/DETR/Evaluating_DETR_on_COCO_validation_2017.ipynb)
  - performing inference with `DetrForSegmentation` [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/DETR/DETR_panoptic_segmentation_minimal_example_(with_DetrFeatureExtractor).ipynb)
  - fine-tuning `DetrForSegmentation` on COCO panoptic 2017 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/DETR/Fine_tuning_DetrForSegmentation_on_custom_dataset_end_to_end_approach.ipynb)
* T5 ([paper](https://arxiv.org/abs/1910.10683)):
  - fine-tuning `T5ForConditionalGeneration` on a Dutch summarization dataset on TPU using HuggingFace Accelerate [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/tree/master/T5)
  - fine-tuning `T5ForConditionalGeneration` (CodeT5) for Ruby code summarization using PyTorch Lightning [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/T5/Fine_tune_CodeT5_for_generating_docstrings_from_Ruby_code.ipynb)
* LayoutLMv2 ([paper](https://arxiv.org/abs/2012.14740)):
  - fine-tuning `LayoutLMv2ForSequenceClassification` on RVL-CDIP [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/LayoutLMv2/RVL-CDIP/Fine_tuning_LayoutLMv2ForSequenceClassification_on_RVL_CDIP.ipynb)
  - fine-tuning `LayoutLMv2ForTokenClassification` on FUNSD [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/LayoutLMv2/FUNSD/Fine_tuning_LayoutLMv2ForTokenClassification_on_FUNSD.ipynb)
  - fine-tuning `LayoutLMv2ForTokenClassification` on FUNSD using the 🤗 Trainer [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/LayoutLMv2/FUNSD/Fine_tuning_LayoutLMv2ForTokenClassification_on_FUNSD_using_HuggingFace_Trainer.ipynb)
  - performing inference with `LayoutLMv2ForTokenClassification` on FUNSD [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/LayoutLMv2/FUNSD/Inference_with_LayoutLMv2ForTokenClassification.ipynb)
  - true inference with `LayoutLMv2ForTokenClassification` (when no labels are available) + Gradio demo [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/LayoutLMv2/FUNSD/True_inference_with_LayoutLMv2ForTokenClassification_%2B_Gradio_demo.ipynb)
  - fine-tuning `LayoutLMv2ForTokenClassification` on CORD [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/LayoutLMv2/CORD/Fine_tuning_LayoutLMv2ForTokenClassification_on_CORD.ipynb)
  - fine-tuning `LayoutLMv2ForQuestionAnswering` on DOCVQA [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/LayoutLMv2/DocVQA/Fine_tuning_LayoutLMv2ForQuestionAnswering_on_DocVQA.ipynb)
* CANINE ([paper](https://arxiv.org/abs/2103.06874)):
  - fine-tuning `CanineForSequenceClassification` on IMDb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/NielsRogge/Transformers-Tutorials/blob/master/CANINE/Fine_tune_CANINE_on_IMDb_(movie_review_binary_classification).ipynb)
* GPT-J-6B ([repository](https://github.com/kingoflolz/mesh-transformer-jax)):
  - performing inference with `GPTJForCausalLM` to illustrate few-shot learning and code generation [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NielsRogge/Transformers-Tutorials/blob/master/GPT-J-6B/Inference_with_GPT_J_6B.ipynb)

... more to come! 🤗 

If you have any questions regarding these demos, feel free to open an issue on this repository.

Btw, I was also the main contributor to add the following algorithms to the library:
- TAbular PArSing (TAPAS) by Google AI
- Vision Transformer (ViT) by Google AI
- Data-efficient Image Transformers (DeiT) by Facebook AI
- LUKE by Studio Ousia
- DEtection TRansformers (DETR) by Facebook AI
- CANINE by Google AI
- BEiT by Microsoft Research 
- LayoutLMv2 (and LayoutXLM) by Microsoft Research 

All of them were an incredible learning experience. I can recommend anyone to contribute an AI algorithm to the library!
