# fan_project_review
 ### 프로젝트 주의사항
  - 현 Repository pull 하여 virtual environment 구성하여 사용하기(venv) 
  - flaks-request-validator 코드를 수정해야함
    - venv/Lib/site-packages/flask_request_validator/validator.py 파일
    - 95번줄 raise InvalidRequest(errors)위에 return errors 삽입
  - 특정 모듈에 의존하는 코드 작성 시 requirements.txt 파일 업데이트 필수
