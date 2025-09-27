# Getting Started
Follow these steps to get a local copy of the project up and running on your machine.

# Prerequisites
You need to have Python 3.7 or later installed.

# Installation
Clone the repository to your local machine:

- git clone [https://github.com/naima-shaikh/Real-Time-Sentiments-Analysis-Tool.git]

- cd Real-Time-Sentiments-Analysis-Tool

Install the required Python libraries. 
It's recommended to use a virtual environment.

pip install transformers torch gradio

# Note: 
The torch library can be large. If you prefer to use TensorFlow, you can install that instead:
-  pip install transformers tensorflow gradio.

# Usage
Run the main application script from your terminal:

python sentiments.py

(Note: You may need to rename your main script file to app.py if it is named something else).

Once the server is running, you'll see a local URL in your terminal (usually http://127.0.0.1:7860). Open this URL in your web browser.

Type or paste any text into the input box and the sentiment label (Positive or Negative) will update automatically in real time.

# Technologies Used
Python: The core programming language.

Hugging Face transformers: Provides access to the pre-trained sentiment analysis model (distilbert-base-uncased-finetuned-sst-2-english).

Gradio: Used to create the simple, interactive web interface.

PyTorch / TensorFlow: The deep learning framework used by the model.