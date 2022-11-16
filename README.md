# Finetune Huggingface t5 for text2text generation

### About T5: ###
- T5 , or Text-to-Text Transfer Transformer developed by Google, is a Transformer based architecture that uses a text-to-text approach.


### Goal: ### 
We have multiple small/simple notes in the following fashion.

Input:
- James Elliot leaving the company was a loss.
- The firm drew comfort from Shrenick Shah's experience and involvement in the strategy since its inception in 2012.

Target output:
- Elliot's departure was a loss, but we draw comfort from Shah's experience and involvement in the strategy since its 2012 inception. 

Predicted output from t5:
- Elliot's departure from the firm was a loss, and the firm drew comfort from Shah's experience and involvement in the strategy since its inception in 2012. 

 ### Implementation details: ###

- We have used a T5-based Huggingface model(https://huggingface.co/JulesBelveze/t5-small-headline-generator) to finetune on our dataset
- Dataset split into train and test
- Ran for 12 epochs

