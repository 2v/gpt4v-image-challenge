Multimodal Foundation Models Exploit Text to Make Medical Image Predictions
Thomas Buckley, B.S.1, James A. Diao, M.D., M.Phil.1,2, Pranav Rajpurkar, Ph.D.1, Adam Rodman, M.D.3, and Arjun K. Manrai, Ph.D.1*

1 Department of Biomedical Informatics, Harvard Medical School, Boston, MA
2 Department of Medicine, Brigham and Women's Hospital, Boston, MA
3 Department of Medicine, Beth Israel Deaconess Medical Center, Boston, MA

**Abstract** 

Multimodal foundation models have shown compelling but conflicting performance in medical image interpretation. However, the mechanisms by which these models integrate and prioritize different data modalities, including images and text, remain poorly understood. Here, using a diverse collection of 1014 multimodal medical cases, we evaluate the unimodal and multimodal image interpretation abilities of proprietary (GPT-4, Google’s Gemini Pro 1.0) and open-source (Llama-3.2-90B, LLaVA-Med-v1.5) multimodal foundational models with and without the use of text descriptions. Across all models, image predictions were largely driven by exploiting text, with accuracy increasing monotonically with the amount of informative text. By contrast, human performance on medical image interpretation did not improve with informative text. Exploitation of text is a double-edged sword; we show that even mild suggestions of an incorrect diagnosis in text diminishes image-based classification, reducing performance dramatically in cases the model could previously answer with images alone. Finally, we conducted a physician evaluation of model performance on long-form medical cases, finding that the provision of images either reduced or had no effect on model performance when text is already highly informative. Our results suggest that multimodal AI models may be useful in medical diagnostic reasoning but that their accuracy is largely driven, for better and worse, by their exploitation of text.

