# NLP_Univ_Project
### Abstractive Text Summarisation: Team BLOOM 

### Bitan Biswas, Yadnesh Salvi, Praveen Kumar, and Saketh Maddineni 💪 


***Abstractive Text Summarization is the task of generating a short and concise summary that captures the salient ideas of the source text. The generated summaries potentially contain new phrases and sentences that may not appear in the source text. Given the vast set of language models and state-of-the-art technologies in the domain of NLP, we explore the wikiHow dataset and perform abstractive summarisation of the detailed texts in it. We also evaluate the summarisations based on BLEU and ROUGE scores.*** 🎯  

**WikiHow** is a new large-scale dataset using the online WikiHow (http://www.wikihow.com/) knowledge base. There are two features: - text: wikiHow answers texts. - headline: bold lines as summary. There are two separate versions: - all: consisting of the concatenation of all paragraphs as the articles and the bold lines as the reference summaries. - sep: consisting of each paragraph and its summary. The dataset has 157,252 training samples which we use in a limited fashion (wherever limited resources) for exploring the summarisation pipeline. **Homepage of the dataset:** https://github.com/mahnazkoupaee/WikiHow-Dataset

**The uniqueness of the project lies in the fact that we try to explore abstractive summarisation in a thorough fashion, making sure we use all kinds of NLP models and evaluate their performances and also compare the same. The models we use are the Vanilla LSTM-based RNN model, Vanilla GRU-based RNN model, Seq2Seq Model with Attention, and HuggingFace Transformer Google T5 model. The models are wrangled and evaluated thoroughly.**

![comarison of rouge and bleu scores (1)](https://user-images.githubusercontent.com/76226078/181808424-cbd37b32-ad58-4727-9045-66e86d94d16c.jpg)

The models in the notebooks are:
1. Abstractive Summarisation using SimpleRNN(Baseline): Model 1
2. Abstractive Summarisation using GRU Model: Model 2
3. Abstractive Summarisation using Vanilla LSTM model: Model 3
4.Abstractive Summarisation using Seq2Seq model with Attention: Model 4a
5. Abstractive Summarisation using Seq2Seq model with Word2Vec embeddings: Model 4b.
6. Abstractive Summarisation using Finetuned Google T5 small: Model 5

<img width="389" alt="Screenshot 2022-07-29 at 9 55 29 PM" src="https://user-images.githubusercontent.com/76226078/181809055-6ea18362-bd0f-48e1-88d0-6d0d96ba9ed7.png">

