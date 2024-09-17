# LLMtokenizer-miniBPE

* We don't deal with character level encoding in huge LLM's and instead we deal with chunk level encoding.And one way
* to do this is by using algorithms such as Byte-Pair-Encoding to construct our encoding.
* Following this paper for implementation—https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf
* Language Models are Unsupervised Multitask Learners(GPT-2 Paper)

* Why tokenize?
  * LLM's cant spell word's
  * LLM's worse at non-English languages
  * LLM's bad at simple arithmetic
  * Why did LLM's have more than necessary trouble coding in python?

* GPT tokenizer - Tiktokenizer - https://tiktokenizer.vercel.app/