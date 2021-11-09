# 💖🤗 Sentiment Classifier (with KoELECTRA)
> _"Did you like this game? or not?"_ Steam의 게임 리뷰 텍스트를 분류하고 분석합니다.

- pre-trained model : `KoELECTRA-Base-v3`

  ![Untitled - 2021-11-09T215806 111](https://user-images.githubusercontent.com/86245237/140928677-02b90d70-ea82-4b1c-8fc0-6beebf9b4871.png)

- fine-tuning dataset : 감성 분석용 말뭉치의 `Steam 한국어 리뷰`

- download model : [`model.pt`](https://docs.google.com/uc?export=download&id=1oJK7P5Jo1_RyTWb4Nd9nJ2vLRSeCl0D1) (430MB)

## Reference
- [huggingface/transformers](https://github.com/huggingface/transformers)
- [monologg/KoELECTRA](https://github.com/monologg/KoELECTRA)
- [감성 분석용 말뭉치](https://github.com/bab2min/corpus/tree/master/sentiment)
- [ELECTRA: PRE-TRAINING TEXT ENCODERS AS DISCRIMINATORS RATHER THAN GENERATORS](https://openreview.net/pdf?id=r1xMH1BtvB)
