# 2020120013_AIPrograming_week11
# 성적 관리 프로그램 (load_scores)

## 1. 무엇을 하나요 (What)
성적 CSV 파일을 읽어 0~100 사이의 유효한 정수 점수 목록(`kept`)과 형식이 잘못되어 건너뛴 줄 기록(`skipped`)을 분리해 반환하는 프로그램입니다.

## 2. 왜 만들었나요 (Why)
실제 성적 CSV 파일에는 빈 줄, 결석 같은 문자열 점수, 0~100 범위를 벗어난 점수, 쉼표가 포함된 이름, 동명이인 등이 섞여 있어 단순 파싱으로는 프로그램이 중단되거나 데이터가 누락되기 때문입니다.

## 3. 어떻게 쓰나요 (How)
Python 3 환경에서 별도 외부 라이브러리 설치 없이 바로 실행할 수 있습니다.

## 4. 테스트 방법
pip install pytest pytest-cov 
pytest -v 
pytest --cov=load_scores --cov-report=term-missing

## 5. 파일 구성
load_scores.py, test_load_scores.py, README, LICENSE

## 6. 만든 사람
이름: 김민섭, 학번: 2020120013, ai활용: README.md 문서 구조 정리
