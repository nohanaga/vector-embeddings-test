# vector-embeddings-test
戦国時代 Wikipedia データセットを使用して OpenAI  Embeddings モデルの性質を比較します。

## 準備
1. [単語リストの作成](./prep_word_list.ipynb)
2. [Embeddings の生成](./prep_openai_busho.ipynb)


## Tools
- [コサイン類似度比較](./similarity_busho.ipynb)
- [コサイン類似度 MRL 比較](./similarity_busho_MRL.ipynb)

## Acknowledgment
This repository was created based on the analysis in English by [pamelafox](pamelafox/vector-embeddings-demos). Thank you.

https://github.com/pamelafox/vector-embeddings-demos

And Japanese stop word list is [here](https://github.com/watson-developer-cloud/doc-tutorial-downloads/blob/fe85b14d6facd97af413f1c2caf2860f8f757707/discovery-data/custom_stopwords_ja.json#L4).
