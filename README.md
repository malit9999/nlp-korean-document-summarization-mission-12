# Bootcamp Mission 12 - KoBART 기반 한국어 문서 요약

## 1. 개요
AI Hub 문서요약 데이터를 활용해 한국어 문서 요약 모델을 파인튜닝한 미션입니다.

## 2. 목표
KoBART 계열 모델을 활용해 데이터 전처리부터 파인튜닝, 정량/정성 평가까지 수행하는 것을 목표로 했습니다.

## 3. 사용 기술
- Python
- pandas
- numpy
- matplotlib
- torch
- transformers
- datasets
- evaluate
- tqdm

## 4. 주요 기능
- 문서 요약 데이터 로드
- 텍스트 정제 및 이상치 제거
- KoBART 파인튜닝
- ROUGE 및 BERTScore 평가

## 5. 실행 방법
```bash
pip install -r requirements.txt
jupyter notebook notebooks/mission12.ipynb
```

## 6. 주요 파일
- `notebooks/mission12.ipynb`

## 7. 폴더 구조
```text
bootcamp-mission-12
  .gitignore
  notebooks/
    mission12.ipynb
  README.md
  requirements.txt
```

## 8. 학습 내용
문서 요약 태스크에서 입력 길이, 모델 선택, 평가 지표가 결과에 미치는 영향을 학습했습니다.

## 9. 트러블슈팅
미션을 진행하며 발생한 오류와 해결 과정은 노트북 또는 보고서에 정리했습니다.

## 10. 결과 화면
결과 이미지는 노트북 출력, 보고서 또는 `images/` 폴더에서 확인할 수 있습니다.

## 11. 공개 전 확인 사항
- 제출 노트북만 포함했으며, 원본 데이터와 모델 파일은 공개 범위 확인 전 포함하지 않았습니다.
