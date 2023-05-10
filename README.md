# FITE
This repo is the official implementation of "Face-Sensitive Image-to-Emotional-Text Cross-modal Translation for Multimodal Aspect-based Sentiment Analysis"

# Abstract
Aspect-level multimodal sentiment analysis, which aims to identify the sentiment of the target aspect from multimodal data, recently have attracted extensive attention in the community of multimedia and natural language processing. Despite the recent success in textual aspect-based sentiment analysis, existing models mainly focused on utilizing the object-level semantic information in the image but ignore explicitly using the visual emotional cues, especially the face emotions. How to distill visual emotional cues and align them with the textual content remains a key challenge to solve the problem. In this work, we introduce a face-sensitive image-to-emotional-text translation (FITE) method, which focuses on capturing visual sentiment cues through facial expressions and selectively matching and fusing with the target aspect in textual modality. To the best of our knowledge, we are the first that explicitly utilize the emotional information from images in the multimodal aspect-based sentiment analysis task. Experiment results show that our method achieves state-of-the-art results on the Twitter-2015 and Twitter-2017 datasets. The improvement demonstrates the superiority of our model in capturing aspect-level sentiment in multimodal data with facial expressions. Our code is publicly available at: https://github.com/yhit98/FITE.


## Data 
Download the Twitter-17 dataset [here](https://github.com/jefferyYu/TomBERT/tree/master/absa_data/twitter), and the Twitter-15 dataset [here](https://github.com/jefferyYu/TomBERT/tree/master/absa_data/twitter2015).
You don't need the images to run the code in the repo, but if you want to download them, there are instructions in the TomBERT repo [here](https://github.com/jefferyYu/TomBERT#download-tweet-images-and-set-up-image-path).
