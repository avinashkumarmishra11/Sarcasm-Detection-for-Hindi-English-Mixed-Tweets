# Sarcasm Detection for Hindi-English Mixed Tweets
### A Sarcasm Project by Avinash Kumar Mishra

## Abstract 
In social-media platforms such as Twitter, Facebook, and Reddit, people prefer to use code-mixed
language such as Spanish-English, Hindi-English to express their opinions. In this paper, we
describe different models we used, using the external dataset to train embeddings, ensembling
methods for Sentimix, and OffensEval tasks. The use of pre-trained embeddings usually helps in
multiple tasks such as sentence classification, and machine translation. In this experiment, we have
used our trained code-mixed embeddings and twitter pre-trained embeddings to SemEval tasks.
We evaluate our models on macro F1-score, precision, accuracy, and recall on the datasets. We
intend to show that hyper-parameter tuning and data pre-processing steps help a lot in improving
the scores. In our experiments, we are able to achieve 0.886 F1-Macro on OffenEval Greek
language subtask post-evaluation, whereas the highest is 0.852 during the Evaluation Period.

### File Structure
This repository contains two folders Sentimix and OffensEval. Sentimix folder contains Jupyter and corresponding Python files of Spanglish and Hinglish. OffensEval Folder contains code files of OffensEval English Task 1,2,3 and Turkish, Arabic, Danish and Greek languages.

### External libraries
Sklearn, Numpy, Pandas, Tensorflow, Keras, Beautiful Soup <br />
Run below commands before running files (Pip):<br />
!pip install focal-loss <br />
!pip install keras-tcn==2.8.3 <br />
!pip install keras-multi-head <br />
!pip install keras_metrics <br />
!pip install tqdm <br />
!pip install keras-self-attention <br />

### References
https://github.com/SilentFlame/Named-Entity-Recognition/blob/master/Twitterdata/processedTweets.csv <br />
https://arxiv.org/pdf/1805.11869.pdf <br />
http://ceur-ws.org/Vol-2111/paper5.pdf <br />
https://github.com/sahilswami96/SarcasmDetection_CodeMixed/blob/master/Dataset/Sarcasm_tweets.txt <br />
https://github.com/sahilswami96/SarcasmDetection_CodeMixed/blob/master/Classification_system/build_feature_vector.py <br />
https://www.aclweb.org/anthology/C18-1247.pdf how emotional are you <br />
https://arxiv.org/pdf/1905.12516.pdf multiple datasets <br />
