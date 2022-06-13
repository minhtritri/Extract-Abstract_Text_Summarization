# Extract-Abstract_Text_Summarization
Research on text summarization with multiple extract and abstract models
## Dataset
We use on VNDS dataset, in there half to do this problem for training, val and testing model Seq2seq(abstraction) but we used full for extraction model.

## In the direction of Extraction , we use clustering machine learning model like KMean, Hierarchical , TextRank
Result: 
| Model  | Rouge 1 | Rouge 2 | Rouge L|
| ------------- | ------------- | ------------- | ------------- |
| KMean  | 0.51  | 0.20 | 0.3 |
| Hierarchical  | 0.51 | 0.19 | 0.3 |
| Text Rank | 0.45 | 0.44 | 0.37 |
| KL* | 0.51 | 0.19 | 0.26 |
| Sumbasic* | 0.52 | 0.19 | 0.26 |

(*) is result of paper author dataset
## In the direction of Abstraction , we use Sequence to Sequence(seq2seq) model in Deep Learing 

Result: 
| Model  | Rouge 1 | Rouge 2 | Rouge L|
| ------------- | ------------- | ------------- | ------------- |
| seq2seq  | 0.47  | 0.11 | 0.28 |
