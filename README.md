# Lyrics_GPT
Lyrics Generator trained on  B.U.G Mafia, Mihai Eminescu, Bacovia, Tudor Arghezi, Nichita Stanescu, Lucian Blaga Lyrics

The process of building a lyrics generator using a GPT (Generative Pre-trained Transformer) model. 
It starts by checking if a GPU is available and then imports the required libraries. 
Next, it retrieves a dataset containing lyrics from Romanian hip-hop band B.U.G. Mafia, poems by Eminescu, and Bacovia from a GitHub repository. 
The data is inspected and preprocessed by removing unwanted characters and replacing specific words.

After preprocessing, the code defines a custom Transformer architecture using TensorFlow. 
It includes classes for Multi-Head Attention, FeedForwardNetwork, and TransformerBlock. 
The TransformerBlock is used to build the main model. 
The model is compiled and trained using a custom loss function and a data generator. 
The training history and model summary are displayed.

Finally, the trained model is saved in two formats: as a TensorFlow SavedModel and as a checkpoint. 
The code also includes a function to generate lyrics based on a seed text and the trained model. 
The function takes a seed text, the number of words to generate, the model, and other parameters as input, and outputs the generated lyrics.
