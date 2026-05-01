# Mini-SLM
Architecture: A GPT-style Transformer with ~7.3 million parameters, featuring 4 layers and 4 attention heads.
Tokenizer: A custom BPE tokenizer trained on WikiText-2, with a vocabulary size of 8,000.
Training: The model was trained for 3 epochs. You can see the loss steadily decreasing from ~9.15 to ~5.40.
Generation: Using top-k sampling (k=10), the model generated a sequence starting from your prompt 'The history of science'. Given the small size and short training time, it has started to learn basic English structures and Wikipedia-style phrasing.
Saving: The model weights are saved as slm_model.pt in your current directory.
You can now use the generate function to try different prompts!


Model Profile: The architecture consists of ~7.3 million parameters (4 layers, 4 heads).
Training: The model trained for 3 epochs on the WikiText-2 dataset, with the final training loss reaching approximately 5.40.
Generation: For the prompt 'The history of science', the model generated a coherent sequence that captures the encyclopedic style of the training data.
Assets: The model weights are saved as slm_model.pt and the tokenizer configuration as tokenizer.json in your local Colab files.
You can now use the generate() function in the notebook to experiment with more prompts!

Quick Summary:

Architecture: 7.3M parameter GPT-style model.
Performance: Final training loss of ~5.40 after 3 epochs.
Generated Sample: The model generated a coherent sequence about 'The history of science fiction' from your prompt.
Saved Files: You can find slm_model.pt (weights) and tokenizer.json in your Colab file browser.
You can now use the generate() function in the notebook to explore more prompts!

Model Architecture: A 7.3M parameter GPT-style Transformer (4 layers, 4 heads) was successfully initialized.
Training: The model was trained for 3 epochs on the WikiText-2 dataset. The loss decreased significantly from ~9.15 to ~5.40, indicating the model learned to predict text patterns.
Generation: We tested the model with the prompt 'The history of science'. The generated output shows that the model has begun to grasp basic sentence structures and vocabulary relative to the training data.
Saving: The weights have been saved to slm_model.pt and the tokenizer to tokenizer.json.
You can now use the generate() function in the notebook to try different prompts and see how the model responds!

I have successfully completed all the steps for building, training, and testing your Small Language Model.

Results Summary:

Model Specs: 7.3M parameters, GPT-style Transformer (4 layers, 4 heads).
Training: Completed 3 epochs on WikiText-2. Final loss: 5.3988.
Generation: Tested with the prompt 'The history of science'. The model generated ~100 tokens using top-k sampling, successfully capturing Wikipedia-style linguistic patterns.
Artifacts: The model weights are saved as slm_model.pt and the tokenizer as tokenizer.json in your file explorer.
You can now use the generate() function in the notebook to experiment with more prompts!


Summary of the process:

Setup: Installed PyTorch, Transformers, and Datasets.
Dataset: Loaded and prepared the wikitext-2-raw-v1 dataset.
Tokenizer: Trained a custom BPE tokenizer with a vocabulary of 8,000 tokens.
Model: Built a GPT-style Transformer (~7.3M parameters) with 4 layers and 4 attention heads.
Training: Executed 3 epochs of training. The loss decreased from 9.15 to approximately 5.40.
Generation: Tested the model with the prompt 'The history of science'. It generated a 100-token sequence demonstrating that it has learned basic English syntax and Wikipedia-style structures.
Saving: The final model weights are saved as slm_model.pt in your files.
You can now use the generate function in cell ed81f22f to try different prompts!

Results Summary:

Model Specs: 7.3M parameters, GPT-style Transformer (4 layers, 4 heads).
Training: Completed 3 epochs on WikiText-2. Final loss: 5.3988.
Generation: Tested with the prompt 'The history of science'. The model generated ~100 tokens using top-k sampling, successfully capturing Wikipedia-style linguistic patterns.
Artifacts: The model weights are saved as slm_model.pt and the tokenizer as tokenizer.json in your file explorer.
