# 28/03 Meeting Notes — Topic Brainstorming

Saturday, 28 March 2026, 9:35 AM

## Business & Consumer Intelligence

Focuses on analyzing user sentiment and behavior to provide actionable insights for companies or shoppers.

**Micro-Review Insight Tool**
| | |
|---|---|
| Goal | Extracts specific pros & cons from thousands of product reviews |
| Functions | Aspect-based sentiment analysis, feature-specific feedback aggregation |
| Models | BERT (for multi-label classification), VADER |

**Customer Complaint and Feedback Analysis System**
| | |
|---|---|
| Goal | Categorizes large volumes of unstructured customer feedback into actionable reports |
| Functions | Problem extraction, issue classification, frequency analysis |
| Models | TF-IDF + SVM, BERT, TextRank (for report summarization) |

**Restaurant Review Rating Prediction**
| | |
|---|---|
| Goal | Automatically predicts star ratings based on the text of a review |
| Functions | Sentiment trend identification, satisfaction analysis |
| Models | Naive Bayes, Logistic Regression, LSTM |

**Spam Message Detection**
| | |
|---|---|
| Goal | Classifies incoming messages as spam or legitimate |
| Functions | Text filtering, harmful content detection |
| Models | TF-IDF + Naive Bayes, BERT |

## Information Retrieval & Professional Tools

Designed to bridge the gap between complex datasets and specific user needs in professional settings.

**Job Ad Skill Extraction and Resume Matching Assistant**
| | |
|---|---|
| Goal | Matches candidates to jobs by analyzing skills in descriptions and resumes |
| Functions | NER (Named Entity Recognition) for skill extraction, similarity scoring |
| Models | Cosine Similarity, Spacy NER |

**Policy Document Question Answering System**
| | |
|---|---|
| Goal | Provides direct answers to user queries about long "Terms of Service" documents |
| Functions | Relevant content retrieval, precise answer extraction |
| Models | BM25, Sentence-BERT, Question-Answering (QA) BERT models |

## Education & Content Simplification

Focuses on increasing accessibility and efficiency for students and the general public.

**Smart Study Assistant**
| | |
|---|---|
| Goal | Converts long lecture transcripts or textbooks into summaries and flashcards |
| Functions | Key term extraction, automated summarization, Q&A generation |
| Models | T5/BART (for abstractive summary), TextRank |

**Plain-English Explainer for Government / Legal Text**
| | |
|---|---|
| Goal | Simplifies complex legal jargon into understandable language |
| Functions | Difficult sentence identification, plain-English rewriting |
| Models | Sequence-to-Sequence (Seq2Seq) models, T5 |

**Automatic Text Summarization**
| | |
|---|---|
| Goal | Reduces the size of domain-specific datasets (medical, legal, etc.) |
| Functions | Extractive and abstractive summarization |
| Models | Transformer-based summarization models |

## Linguistic Tools & Quality Assurance

Technical utilities for improving the accuracy and structure of digital text.

**Autocorrect & Grammar Checking**
| | |
|---|---|
| Goal | Identifies and fixes spelling and grammatical errors |
| Functions | Error detection, rule-based and ML-based correction |
| Models | Wagner-Fischer algorithm, RNN/LSTM, Transformers |
