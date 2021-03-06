# ๐๐ค Sentiment Classifier (with KoELECTRA)
> _"Did you like this game? or not?"_ Steam์ ๊ฒ์ ๋ฆฌ๋ทฐ ํ์คํธ๋ฅผ ๋ถ๋ฅํ๊ณ  ๋ถ์ํฉ๋๋ค.

- pre-trained model : `KoELECTRA-Base-v3`

  ![Untitled - 2021-11-09T215806 111](https://user-images.githubusercontent.com/86245237/140928677-02b90d70-ea82-4b1c-8fc0-6beebf9b4871.png)

- fine-tuning dataset : ๊ฐ์ฑ ๋ถ์์ฉ ๋ง๋ญ์น์ `Steam ํ๊ตญ์ด ๋ฆฌ๋ทฐ`

- pytorch ์ฌ์ฉ

  - download model : [`model.pt`](https://docs.google.com/uc?export=download&id=1oJK7P5Jo1_RyTWb4Nd9nJ2vLRSeCl0D1) (430MB)

- [๐ฎ Report: Steam Review Sentiment Classification & Analysis](https://pypyai.notion.site/Report-Steam-Review-Sentiment-Classification-Analysis-1fbbf8b38a2146d9890982373baec33b)

## How To Use?

> โ ๏ธ ํฐ๋ฏธ๋์ bash, ์คํ ํ๋ก๊ทธ๋จ์ Visual Studio Code ๊ธฐ์ค์๋๋ค. Conda ๊ฐ์ ํ๊ฒฝ์ ๋ง๋ค์ด์ ์คํํ์๋ ๊ฒ์ ๊ถ์ฅํฉ๋๋ค.

1. `$ git clone https://github.com/honeyd3wy/Sentiment-Classifier-with-KoELECTRA.git`์ผ๋ก repository ๋ค์ด๋ก๋

2. `$ cd Sentiment-Classifier-with-KoELECTRA/`๋ก ๊ฒฝ๋ก ์ด๋

3. `$ pip install -r requirements.txt`๋ก ๋ผ์ด๋ธ๋ฌ๋ฆฌ ์ค์น

4. ์์์ `model.pt`๋ฅผ ๋ค์ด๋ก๋

5. ๋ค์ด๋ฐ์ ๋ชจ๋ธ ํ์ผ์ cloneํ ๊ฒฝ๋ก๋ก ์ฎ๊ธฐ๊ธฐ

6. `use_classifier_for_local.ipynb` ํ์ผ ์คํ ํ ์ฌ์ฉํ์๋ฉด ๋ฉ๋๋ค!

    - ๊ธ์  ํ์คํธ๋ `LABEL_1`, ๋ถ์  ํ์คํธ๋ `LABEL_0`์ผ๋ก ๋ถ๋ฅ
    - 'score'๋ ํด๋น class๋ก ๋ถ๋ฅ๋  ํ๋ฅ 



# Text-mining (with KoNLPy)

- `Mecab()`์ผ๋ก ๋ช์ฌ ์ถ์ถ ํ ๋ถ์ฉ์ด ์ฒ๋ฆฌ

- `squarify`๋ก ์๊ฐํ




## Reference
- [huggingface/transformers](https://github.com/huggingface/transformers)
- [monologg/KoELECTRA](https://github.com/monologg/KoELECTRA)
- [๊ฐ์ฑ ๋ถ์์ฉ ๋ง๋ญ์น](https://github.com/bab2min/corpus/tree/master/sentiment)
- [ELECTRA: PRE-TRAINING TEXT ENCODERS AS DISCRIMINATORS RATHER THAN GENERATORS](https://openreview.net/pdf?id=r1xMH1BtvB)
- [KoNLPy](https://konlpy.org/ko/latest/)
- [ํ๊ตญ์ด/์์ด ๋ถ์ฉ์ด(Stopword) ์ ๊ฑฐํ๊ธฐ (+ ํ๊ตญ์ด ๋ถ์ฉ์ด ๋ฆฌ์คํธ)](https://mr-doosun.tistory.com/24)
- [๊ผผ๊ผผํ๊ณ  ์ดํดํ๊ธฐ ์ฌ์ด ELECTRA ๋ผ๋ฌธ ๋ฆฌ๋ทฐ](https://blog.pingpong.us/electra-review/)
