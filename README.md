# Image Captioning Model
- Using a pretrained CNN (DenseNet201) to extract image embedding features vector which is then input to an LSTM enables translating these features into a coherent and contextually relevant sentence. 
- Images are preprocessed and paired with their corresponding captions. Text data is tokenized.
- The CNN weights are fine-tuned, and the LSTM network learns to generate accurate captions.
- Trained on Tesla P100 GPU.

# Sample Input Data
![image](https://github.com/user-attachments/assets/d3654b25-0279-401e-a7d4-a6b9e2d7dec5)

# Training Loss
![image](https://github.com/user-attachments/assets/b4a2fb76-d543-4dcc-bb13-24f397764fd1)

# Sample Outputs
![image](https://github.com/user-attachments/assets/31e1ccb8-9893-43a0-8cee-243cf50b195e)

# Evaluation
- BLEU-1: 0.4787

# Future work
- Using different models instead of DenseNet to see how it affects the model's accuracy.
- Using a bigger dataset to improve accuracy.
- Deploying as an end-to-end web app.
