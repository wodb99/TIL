### 1/ 16배운 내용 정리
1. git push
   1. git remote : git과 git hub 사이를 연결해주는 역할
   2. 코드 : git remote add origin 주소복사
   3. push는 마지막으로 commit한 것만 가능 : git push origin +master

2. git pull
    1. clone과 pull의 차이 : clone은 새로운 환경에서 처음 다운로드 할때, pull은 clone 진행한 후 다운로드 할 때
    2. git pull origin +master

3. git ignore
    1. 사용 이유 : 용량 크거나 보안상의 문제 때문, 청구결제 관련된 api_key 같은 파일을 add 하지 않기 위해
                  (staging area에 올리지 않기 위해)

    2. .git ignore 파일 생성 후 안에 파일명 쓰고 저장
    3. git init -> git status로 확인하기기