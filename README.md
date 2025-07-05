# 악성 댓글 자동 감지 및 카테고리별 분류 프로그램 개발
사용 모델: klue/bert-base model
사용한 학습 데이터 셋: ‘Smilegate AI’에서 공개한 한국어 혐오 표현 “UnSmile” 데이터 셋(11 labels)
사용한 실험 데이터 셋: Korean HateSpeech Dataset

## 학습 결과
<img width="656" alt="image" src="https://github.com/user-attachments/assets/fb908d19-841c-487a-9c6a-854e7cdbe331" />
[6번째 모델 채택]

<img width="680" alt="image" src="https://github.com/user-attachments/assets/6650e902-b054-498e-9d2b-b10c51123276" />
[test loss, Macro F1 Score, test set prediction result]

<img width="680" alt="image" src="https://github.com/user-attachments/assets/ee99e6f5-e620-4248-a964-e02d1a874afc" />
[정답과 예측 비교]

<img width="516" alt="image" src="https://github.com/user-attachments/assets/82dee135-dbfd-4c9c-b2ee-f944ffc676d8" />
[정밀도, 재현율, f1-score]

## 실험 결과
<img width="671" alt="image" src="https://github.com/user-attachments/assets/4f8538f7-352c-4d9c-a319-5142d9858aa9" />
[예측 결과 분포]

<img width="553" alt="image" src="https://github.com/user-attachments/assets/da05b27c-6440-4ee1-88e3-976b016cbfd6" />

## 참고문헌
https://www.inews24.com/view/1444614
https://github.com/ZIZUN/korean-malicious-comments-dataset
https://github.com/kocohub/korean-hate-speech
https://github.com/smilegate-ai/korean_unsmile_dataset
https://wikidocs.net/31379
https://wikidocs.net/152922
https://wikidocs.net/166796
https://huggingface.co/klue/bert-base







