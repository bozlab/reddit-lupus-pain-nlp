## 🎯Goal
Apply an unsupervised approach (BERTopic) for thematic analysis of pain mentions. Compare/contrast these with our LLM biopsychosocial pain dimensions. This can show us if we’re comprehensive in our approach or if there are others that we aren’t catching—like other dimensions of pain

- pain_vocabulary_lupus_reddit.xlsx : contains our pain vocabulary lexicon used to identify Reddit r/Lupus and r/LupusSupport posts related to pain. Categorized by coauthors based on lupus-specific pain categories
- Topic Modeling: Code available in /one-sentence/ folder, with details on hyperparameters and topic representation by example documents provided in Topic modeling details.docx
- LLM Information Extraction: Code available in the /LLM structured information extraction/ folder, to be run sequentially (1, 2, 3 as prepended to file names)
- LLM evaluation reliability calculation code: the analysis used to determine interrater reliability for LLM evaluation is the R Markdown file, llm_lupus_evaluation_reliability_code.Rmd 
