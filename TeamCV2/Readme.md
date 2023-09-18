
# 주제: Formula to Latex

<img width="777" alt="image" src="https://github.com/X-AI-eXtension-Artificial-Intelligence/4th-ADV-SESSION/assets/100743813/6b9801e8-26a6-4c37-a7a0-091be7549da3">

---

#### 사용 모델
[Pix2tex - LatexOCR](https://github.com/lukas-blecher/LaTeX-OCR)
  
<img width="739" alt="image" src="https://github.com/X-AI-eXtension-Artificial-Intelligence/4th-ADV-SESSION/assets/100743813/9fc02872-52be-4603-b2ef-20c01638ffd3">


<br>

[YOLO v8](https://github.com/HumanSignal/labelImg)

  
<img width="675" alt="image" src="https://github.com/X-AI-eXtension-Artificial-Intelligence/4th-ADV-SESSION/assets/100743813/7ebe9c83-3b50-4b7a-ade5-b668caea90bb">

* 사용시 해당 GitHub Clone 해서 사용해야 합니다.

---

#### 데이터
* [M2LATEX-100K (Kaggle)](https://www.kaggle.com/datasets/shahrukhkhan/im2latex100k)
  
<img width="328" alt="image" src="https://github.com/X-AI-eXtension-Artificial-Intelligence/4th-ADV-SESSION/assets/100743813/56e1f406-2666-4b60-a017-4decd0627eb4">

---

## 목차

- [1. 배경 및 목적](#배경-및-목적)
- [2. 주최/주관 & 팀원](#주최/주관-&-팀원)
- [3. 프로젝트 기간](#프로젝트-기간)
- [4. 프로젝트 소개](#프로젝트-소개)
- [5. WebUI Inference](#WebUI-Inference)
- [6. 느낀점](#느낀점)
- [7. 발표자료](#발표자료)

---

## 1. 배경 및 목적

* 논문 번역 시 수식 변환의 어려움 존재
* 기존에 존재하는 PDF to LaTex가 제대로 작동되지 않음
* WebUI를 통해 원하는 Formula를 변환해서 논문 번역 시 수월하게 사용할 수 있게끔 배포하는 것이 목적

---

## 2. 주최/주관 & 팀원

* 주최/주관: AI빅데이터융합경영학과 딥러닝 논문 분석 학회 X:AI 4기 CV2 TEAM
* 팀원: 총 4명 (황건하, 이승학, 유광열, 이서연)

---

## 3. 프로젝트 기간

*  2023.07.06 ~ 2023.09.18

---

## 4. 프로젝트 소개

* 논문 리뷰 또는 논문 번역 시 수식 변환을 쉽게 만들어주는 프로젝트

<img width="873" alt="image" src="https://github.com/X-AI-eXtension-Artificial-Intelligence/4th-ADV-SESSION/assets/100743813/3dc67f68-baab-4ad9-82d9-43f1b463965a">


### 4.1. 과정

* WebUI를 통해 원하는 논문의 Formula를 변환
    * YOLO v8을 통해 Formula Detection 진행
    * Pix2tex-LaexOCR model 활용
* 논문 속 모든 Formula를 Latex로 변환 후 csv로 반환
    * 반환된 Latex 언어 복사하여 사용

### 4.2. 기대효과

* 논문 리뷰 작성할 때 수식 입력이 편해짐
* 처음보는 수학 기호에 대한 Latex를 찾아 볼 필요가 없음
* 전체 논문 번역 시 자연스러운 번역 결과가 나올 것으로 기대

### 4.3.한계점

* 대량의 데이터를 활용하지 못함
* WebUI를 예쁘게 만들지 못함

---

## 5. WebUI Inference

(1) python main.py로 실행
<br>
(2) WebUI 흰색 영역에 PDF 형식의 논문 드래그
<br>
(3) 해당 이미지 위에서 원하는 Formula 영역을 q로 통해 지정하고 드래그
<br>
(4) 2-3초 기다리면 밑에 copy text가 나오고, 변환된 Latex 언어를 복사하여 사용

---

## 6. 느낀점

**황건하**

**이승학**

**유광열**

**이서연**

---

## 7. 발표자료









