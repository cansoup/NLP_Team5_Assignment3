# 24/04 Meeting Notes

23 April 2026, 20:20

## Research Problem

- Minimise hallucination
- Reducing the size of input sequence

## Share Results of Research

## Which dataset will we use

## Which model will we use

- TextRank (summarise) + Bert Extracting Summariser => Encoder-Decoder Model
- Data distillation

## How we gonna compare models

## Member's Role

| Role | Description | Assigned to | Due |
|---|---|---|---|
| Data & Preprocessing | - Collect and prepare the dataset<br>- Clean raw text, handle sentence tokenisation<br>- Implement chunking strategies for long documents<br>- Create train/validation/test splits and build the tokenisation pipeline for transformer models | Alka Lama | 30/04 |
| Extractive Model | - Implement the extractive summarisation baseline<br>- Configure sentence selection parameters, run experiments on the test set, and document results with sample outputs for qualitative comparison | Jinseo Park, Cyrus Kwan | 03/05 |
| Abstractive Model | - Load and configure the pre-trained summarisation model<br>- Run baseline model and then fine-tune the model on the training set<br>- Manage generation parameters (beam search, length penalty) and save checkpoints | Cyrus Kwan, Alka Lama | 07/05 |
| Evaluation & Analysis | - Set up evaluation pipeline<br>- Produce comparison tables and visualisations across all models<br>- Conduct error analysis on failure cases | Minha Kim, Woori Lee | 10/05 |
| Presentation | - Compile findings from all members into the final report and prepare the slide deck for the group presentation | Cyrus Kwan, Minha Kim | 14/05 |
| Background Research | - Search for other model to compare with<br>- Accuracy metrics (numerical score) | Minha Kim, Woori Lee, Jinseo Park | |

## Report

| Part | Description | Assigned to | Reviewer |
|---|---|---|---|
| Abstract | | Minha Kim | |
| Introduction | Explaining the studied problem and the aim of the project | | |
| Background | Analysing challenges behind the proposed problem | Minha Kim, Woori Lee, Jinseo Park | |
| Methodology | Providing theoretical analysis of the proposed solution | Cyrus Kwan, Alka Lama, Jinseo Park | |
| Experiment Result | Explaining how the solution is implemented:<br>- The algorithm or the workflow of the code<br>- Link to a publicly accessible GitHub repo / Google Colab page containing the code<br>- Information on the data used in the project<br>- The results of the experiments | All | All |
| Conclusion | | | |
| Team Member Contribution | | All | All |
| References | | All | All |
