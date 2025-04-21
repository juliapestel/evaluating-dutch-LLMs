# Evaluating Dutch Speakers and Large Language Models on Standard Dutch: a grammatical Challenge Set based on the *Algemene Nederlandse Spraakkunst*

We introduce a challenge set that evaluates both Large Language Models and native dutch speakers on grammatical aspects of Dutch. The challange set is based on the Algemene Nederlandse Spraakkunst (ANS) and includes 500 minimal pairs (sentences that differ minimally in grammaticality) which span across 10 syntactic phenomena. 

## Repository Contents

- Scraping code for the ANS: `evaluating-dutch-LLMs/code/scraping_ans.ipynb`
- Summary of native speaker performance on challenge set: `evaluating-dutch-LLMs/data/NSD_evaluation.csv`
- Challenge set: `evaluating-dutch-LLMs/data/challenge_set.csv`
- Summary of model performance on challenge set: `evaluating-dutch-LLMs/data/model_evaluation.csv`
- Complete information received from scraping the ANS: `evaluating-dutch-LLMs/data/scrapingANS_data.csv`
- Folder contains all raw results from the native speaker evaluation: `evaluating-dutch-LLMs/results/raw_NSD/`
- Folder contains all raw results from the model evaluation: `evaluating-dutch-LLMs/results/raw_models/`
- Recruitment message for Dutch native speakers (English): `evaluating-dutch-LLMs/supplemental_materials/evaluation_NS_LLM/EN_recruit_message.txt`
- Prompt used with ChatGPT for generation of additional minimal pairs: `evaluating-dutch-LLMs/supplemental_materials/evaluation_NS_LLM/GPT_prompt.txt`
- Recruitment message for Dutch native speakers (Dutch): `evaluating-dutch-LLMs/supplemental_materials/evaluation_NS_LLM/NE_recruit_message.txt`
- Instructions shown to participants: `evaluating-dutch-LLMs/supplemental_materials/evaluation_NS_LLM/intructions.txt`
- Folder contains figures used in paper: `evaluating-dutch-LLMs/supplemental_materials/figures/`

## Challenge Set

The challenge set csv (`evaluating-dutch-LLMs/data/challenge_set.csv`) contains all minimal pairs including their relevant information. 

- "ID": numerical indicator of phenomenon
- "subject": what type of constituent (Noun Constituent, Adjectival Constituent, Adpositional Constituent, Verb Constituent)
- "phenomenon": what type of phenomenon
- "sub_subject": the more specific subject the minimal pair was listed as on the ANS
- "Correct.sentence": the grammatically correct sentence in the minimal pair
- "Wrong.sentence": the grammatically incorrect sentence in the minimal pair
- "Label": the label of the minimal pair on the ANS (if applicable)
- "URL": the url to the webpage from which the minimal pair was extracted (if applicable)
- "Generated": how the minimal pair was generated (ANS, Manual, Chat-GPT, Manual/ANS)
