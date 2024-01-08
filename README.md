# CQSUMDP

### EMNLP 2023 Findings Paper: [Can Large Language Models Fix Data Annotation Errors? An Empirical Study Using Debatepedia for Query-Focused Text Summarization](https://aclanthology.org/2023.findings-emnlp.686/)

The dataset is available here: https://drive.google.com/drive/folders/172qZJDwzQK0wbB_vqEd9EA7U8vuYPfYp?usp=sharing

The dataset is formatted in a way such that the baseline experiments using HuggingFace's summarization models could be quickly run, with the "text" column represents the combination of the input "query" and the "document", and the "summary" column indicates the gold reference summary. 

The original query and the re-annotated queries are also added in the file. There is a "Type" column that contains the information on whether the LLM has classified the query as relevant/irrevalent.

If the query is considered as "relevant", then the LLM classified type is "yes"; otherwise "no".   

