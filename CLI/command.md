# Command

command line interface 명령어를 정리합니다.

#### pwd

현재 위치한 폴더를 출력하는 명령어입니다.

```shell
pwd
```



#### ls

list의 약자로 현재폴더에 있는 파일과 폴더를 출력하는 명령어입니다.

```shell
ls # 숨김폴더는 출력안함.
ls -a # 숨길폴더, 파일까지 모두 출력함.
```



#### cd

change directory의 약자로 폴더를 이동하는 명령어 입니다.

``` shell
cd <PATH> # 이동하고 싶은 폴더를 PATH에 입력
```



#### 생성

- `touch` : 파일을 생성
- `mkdir` : 폴더를 생성



#### vi

vim 에디터를 사용하여 편집

연습할 수 있는 사이트 [빔어드벤처](https://vim-adventures.com/)



### GIT 용어 정리

GIT 용어를 정리합니다.



#### git init

git, initialize(초기화) 하는 명령어 입니다.

```shell
git init # git initailze
```



### git status

git, 상태를 보는 명령어 입니다.

```shell
git status # git status를 보여줍니다.
```



### git add

commit 할 파일을 넣어주는 명령어 입니다.

```shell
git add <file name> # git, commit할 파일 삽입
```



### git commit 

commit하는 명령어 입니다.

```shell
git commit -m "<commit message>" # git commit -m "commit message 삽입" 
```



### git config

설정하는 명령어 입니다.

```shell
git config # 설정
```



### git diff

달라진 점을 보는 명령어 입니다.

```shell
git diff # 전에 비해 파일이 어떻게 바뀌었는지 볼 수 있는 명령어
```



### git log

기록 보는 명령어 입니다

```shell
git log # 기록보기
```



### git push

commit된 목록을 git-hub-repo에 올립니다.

```shell
git pust <name> <branch name>
```



### git clone

다른 사용자의 git project를 복사합니다.

```shell
git clone <clone github 주소> # 주소를 복사한다.
```



### git remote

remote된 저장소를 확인합니다.

```shell
git remote -v # remote 저장소 확인, -v옵션은 URL까지 출력
```



### git remote remove

remote된 저장소의 이름을 삭제합니다.

```shell
git remote -remove <remote name> # remove 옵션으로 저장소의 이름을 삭제
```

