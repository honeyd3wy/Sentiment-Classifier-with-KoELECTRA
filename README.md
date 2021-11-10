# 💖🤗 Sentiment Classifier (with KoELECTRA)
> _"Did you like this game? or not?"_ Steam의 게임 리뷰 텍스트를 분류하고 분석합니다.

- pre-trained model : `KoELECTRA-Base-v3`

  ![Untitled - 2021-11-09T215806 111](https://user-images.githubusercontent.com/86245237/140928677-02b90d70-ea82-4b1c-8fc0-6beebf9b4871.png)

- fine-tuning dataset : 감성 분석용 말뭉치의 `Steam 한국어 리뷰`

- pytorch 사용

  - download model : [`model.pt`](https://docs.google.com/uc?export=download&id=1oJK7P5Jo1_RyTWb4Nd9nJ2vLRSeCl0D1) (430MB)

### Text-mining (with KoNLPy)

- `Mecab()`으로 명사 추출 후 불용어 처리

- `squarify`로 시각화


## Reference
- [huggingface/transformers](https://github.com/huggingface/transformers)
- [monologg/KoELECTRA](https://github.com/monologg/KoELECTRA)
- [감성 분석용 말뭉치](https://github.com/bab2min/corpus/tree/master/sentiment)
- [ELECTRA: PRE-TRAINING TEXT ENCODERS AS DISCRIMINATORS RATHER THAN GENERATORS](https://openreview.net/pdf?id=r1xMH1BtvB)
- [KoNLPy](https://konlpy.org/ko/latest/)
- [한국어/영어 불용어(Stopword) 제거하기 (+ 한국어 불용어 리스트)](https://mr-doosun.tistory.com/24)
