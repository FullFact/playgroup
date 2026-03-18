# playgroup
Sharing resources for Ian Ozsvald Playgroup 

## Claims and articles

The `data` folder has some JSON/JSONL files containing claims annotated using Full Fact's AI software and some raw news articles.

### fullfact-2026-03-16-claims.json

This is a list of c.2800 individual sentences processed by Full Fact's AI pipeline. Each sentence is taken from a newspaper, radio news show or social media post, and is annotated by various models. For example, the `checkworthiness` annotation is a prediction of how signficant the claim is with respect to the user organisation (e.g. 'fullfact') and topic (e.g 'health', 'housing'). The score ranges from 1-5 (or a little over...). Other annotations include `claimer` which is the person or organisation making the claim, and `claim_type` which is one (or more) of ten fixed categories including "quantity", "personal" and "prediction". Often, quantitative claims are easier to check, whereas predictions and personal beliefs are usually not possible to check.

### fullfact-2026-03-16-checkworthy-articles.json

This is a list of c.500 articles, including the overall predicted topic of the article, the publication and date and a list of sentences.

## LLM answers to repeated questions ("benchmark") 

We ask some common LLMs the same questions every day to measure consistency, accuracy etc. Full Fact plans to develop tools to analyse this data as a way of learning (and sharing) how reliable LLMs are at answering every day questions. 

[Snapshot of results in a spreadsheet](https://docs.google.com/spreadsheets/d/1CvWclVLRhktb-VzKdZ1c2TCGLjh_Y7A6R77nbVC_3Ow/edit?gid=0#gid=0)
