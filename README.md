# Korean Document Summarization with KoBART

> **Bootcamp Mission 12** | Natural Language Processing

## 미션 소개
AI Hub 문서요약 텍스트를 활용해 한국어 문서를 요약하는 KoBART 기반 모델을 구성한 NLP 미션입니다. 데이터 전처리부터 파인튜닝과 평가까지 요약 모델 파이프라인을 다룹니다.

## 구현 목표
- 요약 데이터의 입력 문서와 요약문 구조를 이해한다.
- 사전학습 언어모델을 요약 과제에 맞게 파인튜닝한다.
- 생성 결과를 정성·정량적으로 검토한다.

## 주요 구현 내용
- 한국어 문서요약 데이터 전처리
- KoBART 기반 파인튜닝
- 생성형 요약 결과 평가

## 사용 기술
- Python
- Transformers
- KoBART
- NLP
- Jupyter Notebook

## 실행 방법
```bash
pip install -r requirements.txt
jupyter notebook notebooks/mission12.ipynb
```

> 데이터셋 또는 사전학습 모델이 외부에서 제공되는 경우, 실행 전에 노트북 또는 코드의 데이터 로드 설정을 확인해야 합니다.

## 폴더 구조
```text
notebooks/
  mission12.ipynb
README.md
requirements.txt
.gitignore
```

## 학습 내용
- 요약은 분류가 아닌 텍스트 생성 문제라는 점
- 입력 길이와 생성 파라미터가 결과 품질에 영향을 준다는 점

## 트러블슈팅 및 재현 시 참고 사항
AI Hub 데이터는 별도 접근 권한과 다운로드 절차가 필요할 수 있습니다.

## 결과 확인
전처리·학습·요약 생성 결과는 노트북에서 확인할 수 있습니다.

## 포트폴리오 관점
이 저장소는 **Natural Language Processing** 역량을 학습·실험한 결과물입니다. 구현 범위와 실행 조건은 코드 및 노트북을 기준으로 확인할 수 있습니다.