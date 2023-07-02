### Aim
This project will be explaining efficiency of pre trained models and transfer learning for text generation saving high computational power and training time.


This project aims to train a text generation model using GPT-2 (Generative Pre-trained Transformer 2) or any other pre trained model to generate coherent and contextually relevant text. In this project, Movie script data will be used for transfer learning. Pretrained model will be fine tuned for the obtained dataset. Different hyperparameters will be used to optimize the model.

### Exploration
Different kind of optmizers and different values of learning rate wil be used to fine tune the pre-trained model and effectiveness of each will be explained.

### Dataset
[Dataset Link](https://github.com/formcept/whiteboard/tree/master/nbviewer/notebooks/data/harrypotter)

### Methodology
1. Data Collection: Gather a large text corpus suitable for the desired application, such as Harry Potter scripts, books, articles, or any other relevant dataset.

2. Preprocessing: Clean and preprocess the text data by removing unnecessary characters, punctuation, and special symbols. Tokenize the text into individual words or subword units for model input.

3. Model Selection: Choose the GPT-2 model as the base model for text generation. GPT-2 is a state-of-the-art transformer-based model known for its language generation capabilities.

4. Fine-tuning: Fine-tune the pre-trained GPT-2 model on the collected dataset. This involves training the model on the specific text corpus to adapt it to the desired context or style. Adjust the hyperparameters, such as learning rate, batch size, and number of training epochs, to optimize the fine-tuning process.

5. Text Generation: Once the model is fine-tuned, generate text samples by providing a starting prompt or seed text.

6. Evaluation: Evaluate the quality and coherence of the generated text by manually reviewing the samples.

7. Report: Document and present the project findings, including the dataset used, preprocessing steps, fine-tuning process, and generated text samples. Include visualizations, graphs, and analysis to support the project's key takeaways and insights.
