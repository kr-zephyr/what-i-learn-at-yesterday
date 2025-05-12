# github의 token을 이용해서 개인 계정을 회사 장비에서 사용하기

- 간단히는 git의 url을 계정과 token을 포함해서 지정해 주면 된다.

```
# 만약 이미 repository를 clone한 상태라면

git remote set-url origin https://{{계정명}}:{{token}}@github.com/{{계정명}}/{{repository_name.git}}
```

- 새로운 repository를 clone 받는다면 url을 위와 같이 써주면 된다.

```
# 만약 새로운 repository를 clone 한다면

git clone https://{{계정명}}:{{token}}@github.com/{{계정명}}/{{repository_name.git}}
```