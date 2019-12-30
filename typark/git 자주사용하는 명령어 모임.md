# GIT 명령어 모음

1. git 사용자 이름/이메일 설정
  - 사용자 설정
    - git config user.name "User Name"
  - 이메일 설정
    - git config user.email "User Email(git Email)"
  - 적용 확인
    - git config --list
  - 옵션
    - 전역으로 할경우 config 다음에 --global 옵션을 추가하면 된다.

2. 저장소 복제하기
  - git clone "GIT 주소"

3. 기본적인 사용법
  - 파일 추가
     - git add <파일명, 폴더>
  - 로컬 레포에 저장
     - git commit -m "커밋 메시지" 