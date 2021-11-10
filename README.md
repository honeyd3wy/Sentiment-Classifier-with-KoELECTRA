# 💖🤗 Sentiment Classifier (with KoELECTRA)
> _"Did you like this game? or not?"_ Steam의 게임 리뷰 텍스트를 분류하고 분석합니다.

- pre-trained model : `KoELECTRA-Base-v3`

  ![Untitled - 2021-11-09T215806 111](https://user-images.githubusercontent.com/86245237/140928677-02b90d70-ea82-4b1c-8fc0-6beebf9b4871.png)

- fine-tuning dataset : 감성 분석용 말뭉치의 `Steam 한국어 리뷰`

- pytorch 사용

  - download model : [`model.pt`](https://docs.google.com/uc?export=download&id=1oJK7P5Jo1_RyTWb4Nd9nJ2vLRSeCl0D1) (430MB)

- [Report](https://pypyai.notion.site/Report-Steam-Review-Sentiment-Classification-Analysis-1fbbf8b38a2146d9890982373baec33b) (작성 중입니다.)

## How To Use?

> ⚠️ 가상환경에서 실행하는 것을 권장합니다!

1. `model.pt`를 다운로드
2. `git clone`으로 repository 다운로드
3. 다운받은 모델 파일을 clone한 경로로 옮기기
4. `use_classifier_for_local.ipynb` 파일 실행



# Text-mining (with KoNLPy)

- `Mecab()`으로 명사 추출 후 불용어 처리

- `squarify`로 시각화




## Reference
- [huggingface/transformers](https://github.com/huggingface/transformers)
- [monologg/KoELECTRA](https://github.com/monologg/KoELECTRA)
- [감성 분석용 말뭉치](https://github.com/bab2min/corpus/tree/master/sentiment)
- [ELECTRA: PRE-TRAINING TEXT ENCODERS AS DISCRIMINATORS RATHER THAN GENERATORS](https://openreview.net/pdf?id=r1xMH1BtvB)
- [KoNLPy](https://konlpy.org/ko/latest/)
- [한국어/영어 불용어(Stopword) 제거하기 (+ 한국어 불용어 리스트)](https://mr-doosun.tistory.com/24)
