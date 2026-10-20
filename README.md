# 🍊 오렌지 실습 시뮬레이터

고등학교 **인공지능 기초** 교과서의 *오렌지 활용 활동 3·4*를 설치 없이 웹 브라우저에서 실습하고 복습할 수 있는 시뮬레이터입니다.

👉 **바로 실행: https://cs196083.github.io/orange-practice-simulator/**

## 구성

| 메뉴 | 내용 |
|---|---|
| 🐧 활동 3 펭귄 | 펭귄 데이터로 종류 분류 (File → Preprocess → Data Table → Scatter Plot / Data Sampler → kNN·Logistic Regression → Test and Score) |
| 🫁 활동 4 폐 이미지 | 흉부 X-ray 이미지 분류 (Import Images → Image Viewer / Image Embedding → Random Forest·kNN·Neural Network → Test and Score → Confusion Matrix, Predictions) |
| 🧪 자유 실습 | 모든 위젯을 자유롭게 연결 |
| 📖 위젯 학습 자료 | 위젯 15종의 입력·출력·주요 설정·활동에서의 쓰임, 핵심 개념(결측치, 교차검증, 평가 지표, 이미지 임베딩, Learner와 Model), kNN 체험 |
| 📝 복습 퀴즈 | 객관식 16문항 + 워크플로 순서 맞히기 2문항 (해설 포함) |

## 특징

- 위젯을 끌어다 놓고, 점선(포트)을 끌어 연결하고, 더블 클릭으로 설정 창을 여는 **Orange와 비슷한 조작**
- 오른쪽 **미션 패널**이 교과서 단계를 자동으로 확인하고, 힌트와 결과 해석 문제를 제시
- kNN, 로지스틱 회귀, 랜덤 포레스트, 신경망을 **브라우저 안에서 실제로 학습·평가** (AUC, CA, F1, Precision, Recall, 혼동행렬)
- 교과서의 역량 평가 기준으로 스스로 점검하는 **평가하기**
- 작업 내용은 브라우저에 자동 저장, 휴대폰·태블릿에서도 사용 가능
- 교사용 **정답 워크플로** 버튼

## 데이터 안내

- 펭귄 데이터: Palmer Penguins (Gorman et al., 2014, CC0). 캐글 `penguins_size.csv`와 같은 형식
- 폐 X-ray 이미지: 캐글 *Covid-19 Image Dataset*의 구성(Covid / Normal / Viral Pneumonia, 훈련 250장·테스트 66장)을 흉내 내어 **컴퓨터가 그린 가상의 이미지**입니다. 실제 의료 영상이 아닙니다.
- Image Embedding은 실제 Orange(Inception v3, 2048개 특징)를 단순화하여 16개 특징으로 시뮬레이션합니다.

이 시뮬레이터는 학습용으로 Orange Data Mining의 화면과 동작을 단순화해 재현한 것이며, Orange 공식 프로그램이 아닙니다.
