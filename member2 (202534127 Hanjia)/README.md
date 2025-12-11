# Food recommendation program 

이 프로젝트는 사용자의 입력 문장을 기반으로 요청 조건에 맞는 음식 메뉴를 추천합니다.
---

## 사용 패키지 및 버전

- Python 3.8 이상 권장
- Transformers (Huggingface tokenizer 사용)

> 아래 명령어를 통해 필요한 패키지를 한 번에 설치할 수 있습니다:

```bash
pip install -r requirements.txt

## 필수 데이터 파일: menu_db.csv

- 메뉴 데이터베이스
  - menu_db.csv 파일은 각각의 음식이 어떤 키워드 속성을 가지고 있는지 저장되어 있습니다.
  - 프로그램은 menu_db.csv 파일을 읽어 JSON처럼 다루며, 각각의 음식이 어떤 키워드 속성을 가지고 있는지 비교가능한 상태로 저장됩니다.

## 실행 구조

- 조건 필터링

    - 사용자가 입력한 키워드가 음식 항목의 속성과 일치하는지 확인하고 매칭됩니다.

- 추천된 메뉴를 출력합니다.

- 반복 입력 처리
    - "종료" 혹은 "exit" 입력 시 프로그램이 종료됩니다.
  

- 실행 결과 예시
   <img width="2135" height="1132" alt="스크린샷 2025-12-11 212458" src="https://github.com/user-attachments/assets/487876b1-e0ba-4571-b4d9-62e76235d2d7" />



```
