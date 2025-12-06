# nlp-neologism-verbalization
COMS 4705 Final Project

## Do Neologisms Transfer Across Language Models?
Keywords: neologism, transfer learning, model steering, self-verbalization

## Teammates:
Varun Ramamurthi, Department of Computer Science, Columbia University, vzr2104@columbia.edu


Owen Terry, Department of Computer Science, Columbia University, okt2002@columbia.edu


Sungjoon Park, Department of Computer Science, Columbia University, sp4050@columbia.edu

## Project Roadmap:

1. Train ~short on LLaMA-3-B. This will help us understand how neologism training works. 
    - Training goal is to get model to output 100 word answres given the neologism as an input
    - Need to define training regime, dataset split for test/validation, etc. 

2. Evaluate our ~short trained on LLaMA-3-B using previously unseen data.

3. Train ~short on Mistral-7B. Use same method as used for LLaMA-3-B for control. 
    - Test and get feedback on whether we need to have training methodology has to be equivalent across models for control. 
    - Let's hope to get here by Wednesay for Hewitt's OH

4. Run more interesting evals and training. 

## Links to Various Resoruces:

1. Mistral-7B:
https://huggingface.co/mistralai/Mistral-7B-v0.1

2. LLaMA-3.1-8B:
https://huggingface.co/meta-llama/Llama-3.1-8B