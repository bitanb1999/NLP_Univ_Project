# NLP_Univ_Project
### Abstractive Text Summarisation: Team BLOOM 

### Bitan Biswas, Yadnesh Salvi, Praveen Kumar, and Saketh Maddineni 💪 


***Abstractive Text Summarization is the task of generating a short and concise summary that captures the salient ideas of the source text. The generated summaries potentially contain new phrases and sentences that may not appear in the source text. Given the vast set of language models and state-of-the-art technologies in the domain of NLP, we explore the wikiHow dataset and perform abstractive summarisation of the detailed texts in it. We also evaluate the summarisations based on BLEU and ROUGE scores.*** 🎯  

**WikiHow** is a new large-scale dataset using the online WikiHow (http://www.wikihow.com/) knowledge base. There are two features: - text: wikiHow answers texts. - headline: bold lines as summary. There are two separate versions: - all: consisting of the concatenation of all paragraphs as the articles and the bold lines as the reference summaries. - sep: consisting of each paragraph and its summary. The dataset has 157,252 training samples which we use in a limited fashion (wherever limited resources) for exploring the summarisation pipeline. **Homepage of the dataset:** https://github.com/mahnazkoupaee/WikiHow-Dataset

**The uniqueness of the project lies in the fact that we try to explore abstractive summarisation in a thorough fashion, making sure we use all kinds of NLP models and evaluate their performances and also compare the same. The models we use are the Vanilla LSTM-based RNN model, Vanilla GRU-based RNN model, Seq2Seq Model with Attention, and HuggingFace Transformer Google T5 model. The models are wrangled and evaluated thoroughly.**

