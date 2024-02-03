# Topsis on Text Summarization Models
In this assignment we had to apply topsis to find the best pre-trained model for Text-Summarization

The dataset was taken from hugging face

# For every text summarization model, I have selected four parameters, which are:

1. Factual correctness: 
With reference to the human-written summary, the produced summary's correctness in capturing the substance of the original discourse is measured. Better factual information representation is indicated by higher factual correctness.

2.Fluency: 
Fluency gauges the resulting summary's comprehensibility and readability. Summaries with higher fluency sound smoother and more authentic.
 
3. Content Coverage: 
This metric evaluates how well the produced synopsis incorporates significant details from the conversation. More content coverage denotes more thorough covering of pertinent data.

4. Semantic Coherence: 
Semantic coherence gauges how effectively the summary that is produced preserves the original dialogue's logical flow and coherence. Improved coherence and flow are indicated by higher semantic coherence.

## The pretrained models that I have used are:
### 1.sshleifer/distilbart-cnn-12-6
### 2.google/pegasus-large
### 3.facebook/bart-large-cnn
### 4.allenai/led-large-16384-arxiv
### 5.t5-large

#### Usage
```Topsis evaluation_results.csv "1,1,1,1" "+,+,+,+" final_result.csv```
The result with topsis was stored in [final_result.csv](https://github.com/SATYAJEETBEDI/Topsis2-Satyajeet-102117170/blob/main/final_result.csv)

A graph was plotted of each model and its topsis score which is 
<img width="877" alt="Topsis_Graph" src="https://raw.githubusercontent.com/SATYAJEETBEDI/Topsis2-Satyajeet-102117170/main/Topsis_Graph.png">
