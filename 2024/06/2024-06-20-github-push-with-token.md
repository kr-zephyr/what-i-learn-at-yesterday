# Token을 이용해 github에 push하기

회사 장비에서 git은 회사 계정에 연결되어 있다.  
아직 찾아보지는 않았지만 살짝 검색해서는 git 계정을 multiple하게 사용하는 방법을 찾지는 못했다.  
개인 계정의 repository에 push하는 경우(혹은 private repo를 다루는 경우) token을 이용해 push할 수 있다.

git push https://{{token}}@github.com/kr-zephyr/lectures.git

문제는 token을 생성할 때에만 조회할 수 있다는 것.  
따라서 token을 어딘가에 기록해 두어야 하는 문제가 있다.

방법을 찾으면 업데이트할 예정임.