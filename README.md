# Image_captioning
A deep learning model that generates natural language captions for images using ViT-GPT2 architecture.

A simple AI model that generates captions for images using a pre-trained "VisionEncoderDecoderModel (ViT + GPT2)" from Hugging Face.

-->Tech Stack
- Python  
- PyTorch  
- Transformers (Hugging Face)  
- Pillow (PIL)  
- Requests  

-->How It Works
1. Loads a local image or one from a URL.  
2. Uses a Vision Transformer (ViT) to extract image features.  
3. Passes features to a GPT-2 decoder to generate natural language captions.  

-->Example
Input: Image of a two polar bears  
Output: polar_bears.png

-->Model Used
(`nlpconnect/vit-gpt2-image-captioning`)(https://huggingface.co/nlpconnect/vit-gpt2-image-captioning)
