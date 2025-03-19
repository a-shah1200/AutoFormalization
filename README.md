This repo explores the use of LLM for Autoformalization (For reference please look at this paper https://arxiv.org/abs/2205.12615). 
The current best performance by LLM to convert mathematical statements to formal language (Isabelle) seems to be have BLEU scores of  57.13 for algebra and 43.33 for number theory. So on average of about 50. 
We tested the Autoformalization using GPT 4o-mini and on combined we got results of 40 BLEU when tested on Mini-F2F datset which has combination of algebra and number theory. 
Result seem to be a bit less as compared to best, which is on codex. Codex is LLM by OpenAI which is specificaly designed for tasks like coding. So its affinity to formal language tasks makes it a prime candidate as compared to a general purpose LLM like GPT 40-mini
