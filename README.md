# Joe Biden Speech Chatbot

Seonghee Lee (이승희)
Stanford 

### Features
- Language Model Interaction: Uses Llama-2-7b, a powerful language model, for generating responses.
- Document Processing: Capable of loading and processing PDF documents.
- Terminal-based Interface: Simple and interactive command-line interface for querying the model.


** This code can only be run locally. Please refer to the youtube video below to see it working with the provided problems 

Youtube Video : https://youtu.be/v8zbJo199tI

### Prerequisites
To run this script, you need the following:

Python 3.x
TensorFlow (compatible with your Python version)
Other dependencies listed in requirements.txt (if available)

### Installation
1. Clone the Repository:
git clone https://github.com/shljessie/RAG.git

2. Install Dependencies:
Navigate to the cloned directory and run:
pip install -r requirements.txt

3. Set up Environment Variables:
Ensure the HF_ACCESS_TOKEN environment variable is set with your HuggingFace token.

4. Prepare Your Documents:
Place the PDF documents you want to process in the ./documents/ directory.

python bidenbot.py

