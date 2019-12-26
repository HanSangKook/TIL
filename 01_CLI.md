## 리눅스 CLI 커맨드 라인 인터페이스

> Command Line Interface (명령형 인터페이스)

- 명령어들
  - `pwd` : 현재 내가 있는 위치를 출력 (print working directory)
  - `ls` : 현재 위체 있는 파일 내용물을 확인
    - `ls -a` : ls로 볼 수 없는 모든 폴더 보기
  - `cd` : 폴더를 변경(change directory)
  - `cd ..` : 상대적으로 현재 폴더에서 한개의 상위 폴더로 이동
  - `mkdir` 폴더명 :  새로운 폴더 생성 (make directory) ex: mkdir TIL 
  - `rm` : remove의 약자-> 파일을 삭제 (rm 파일명)
    - `rm -r 폴더명` : 폴더를 삭제
    - `rm - r .git` : 어떤 폴더에서 깃허브 관리 해제를 하고 싶으면.
  - `git init` : 깃이 특정 파일을 관리 할 수 있도록 깃에게 명령
  - `git status` :  관리 폴더에 지정한 폴더에 상태 변화를 확인 및 감지/ 새로운 파일 추가 등
- `git add 파일명.md` : 파일추가해서 사진을 찍도록 한다.
- `git commit -m "Add 파일명.md"` :  파일이름을 적어서 Add하기
  - `git log`  : 관련 내용
  - `git log --oneline`  : 로그 한줄 보기
  - `git  checkout` : 
  - `git remote add 저장소의 이름 및 주소` 
- `git push origin master`  : 오리진이라는 폴더에 내꺼 추가

### 



