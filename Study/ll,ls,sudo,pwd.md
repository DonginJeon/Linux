# ls
- 현재 디렉토리의 목록을 출력하는 기능
- -a : 숨겨진 파일, 디렉토리를 포함하여 출력
- -l : 현재 디렉토리의 목록을 상세하게 출력 (=ll)
- ls --sort=time : 파일 시간 순으로 정렬
- ls -l --sort=time


# ll
- ls -l의 줄임말
- ubuntu에서는 그냥 사용가능
```
alias # 등록되어 있는 alias 정보 조회 가능
alias [option] [name]='[value]'
alias ll='ls -l --color=auto' # ll 이라는 명령어에 ls -l --color=auto를 등록한다는 의미.
```

# sudo
- sudo: superuser do (이후에는 subtitude user do로 변경) 의 줄임말. 로그아웃 하지 않고 다른 사용자의 권한을 빌려 shell을 사용할 수 있게 함
- -i : 로그인 사용자를 대상 사용자로 실행함과 동시에 명령어도 사용할 수 있음
- -s : 대상 사용자로 shell을 실행

```
sudo vs su

sudo # parameter 계정의 권한을 빌림. 
sudo -i # parameter 계정으로 아예 로그인. 보통 parameter 계정 없이 사용하기 때문에 root 로그인과 동일. 
sudo -s # parameter 계정으로 전환. working directory는 바뀌지 않기 때문에 로그인이라고 볼 수는 없음.
su # parameter 계정으로 전환. 보통 parameter 없이 사용하기 때문에 su root와 동일. 
su - # parameter 계정으로 전환 + parameter 계정의 환경변수 적용.
```