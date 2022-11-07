# How Far are We from Robust Long Abstractive Summarization? (EMNLP 2022)

[[`Paper`]](https://arxiv.org/abs/2210.16732)

#### Huan Yee Koh<sup>\*</sup>, Jiaxin Ju<sup>\*</sup>, He Zhang, Ming Liu, Shirui Pan ####

(:star2: denotes equal contribution)

## Human Annotation of Model-Generated Summaries
For now, we release the human annotation dataset **robust_long_abstractive_human_annotation_dataset.jsonl** (or **.csv**). We use this dataset for the metric comparison in section 5 of our work. 


|  **Data Field**  | **Definition** | 
| :--------: |:---- | 
|  **dataset**  | Whether the model-generated summary is from arXiv or GovReport dataset. | 
| **dataset_id** | The document ID of the dataset (IDs are from the original dataset of [arXiv](https://github.com/armancohan/long-summarization) and [GovReport](https://gov-report-data.github.io/). | 
|  **model_type**  | Model variant which generates the summary. 1K, 4K and 8K represents 1,024, 4096 and 8192 input token limit of the model. For more information, please refer to the original paper. | 
| **model_summary** | Model-generated summary | 
| **relevance** | Percentage of the reference summary’s main ideas contained in the generated summary. Higher = Better.| 
| **factual consistency** | Percentage of factually consistent sentences. Higher = Better. |


## Human Annotation of Model-Generated Factual Error Types
We are standardizing the data for detailed factual error types. Stay tuned! 



## Citation

For more information, please refer to our work: [<i>How Far are We from Robust Long Abstractive Summarization?</i>](https://arxiv.org/abs/2210.16732)

```
@article{koh2022far,
  title={How Far are We from Robust Long Abstractive Summarization?},
  author={Koh, Huan Yee and Ju, Jiaxin and Zhang, He and Liu, Ming and Pan, Shirui},
  journal={arXiv preprint arXiv:2210.16732},
  year={2022}
}
```
