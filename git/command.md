## git command

> 기본 명령어를 정리합니다.

![Git concepts for newcomers — Part 2: Git repository, working tree and  staging area | by Sébastien Dubois. | ITNEXT](https://miro.medium.com/max/1204/1*zpvd5fjZAFGsVAEsvMGKxA.png)

##### init

`.git 폴더를 생성해주는 명령어. 처음 한번만 실행합니다.`



##### add

 working directory에 있는 파일을 staging area에 올리는 명령어



- 기본 사용법
  - file name에 .을 입력하면 모든 파일, 폴더를 한번에 올림

```bash
git add <file name>
```



##### commit

staging area에 있는 파일들을 하나의 commit으로 저장하는 명령어



- 기본 사용법
  - -m : 커밋 메시지를 작성하기 위한 옵션



```bash
git commit -m "message"
```



### remote

원격저장소를 관리하기 위한 명령어



- add : 원격저장소를 추가



```bash
git remote add <remote name> <URL>
```



##### push

로컬에 저장되어 있는 커밋들을 원격저장소에 업로드 하는 명령어



- 기본 사용법

```bash
git push origin master
```



##### status

git 의 현재상태를 확인하는 명령어



- 기본 명령어

```bash
git status
```

