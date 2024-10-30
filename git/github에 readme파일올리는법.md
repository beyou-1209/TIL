# TIL #1 (24.10.30. WED)

## 👍 git에 README.MD 파일을 올려보자

마크다운을 이용하여 README.md 파일을 작성하였다.  
평소 svn만 사용하다보니 git을 사용하는 법에 미숙한터라, 매일 배운 내용에 대해 TIL을 커밋할 예정이다.

&nbsp;
&nbsp;
&nbsp;

### 1. git을 초기화 (Local repository 설정)

```bash
git init
```

&nbsp;
&nbsp;

### 2. README.md 파일 생성

VScode 에서 새 파일 생성

&nbsp;
&nbsp;

### 3. 변경 사항 스테이징 및 커밋

1. 변경 사항 확인

```bash
git status
```

2. 변경 사항 스테이징

```bash
git add README.MD
```

3. 커밋

```bash
git commit -m "ADD README file"
```

&nbsp;
&nbsp;

### 4. remote repository 연결

1. remote repository 추가

   github에서 생성한 repository URL 복사  
   &nbsp;

2. 터미널에서 명령어 입력

```bash
git remote add origin <repository-url>
```

&nbsp;
&nbsp;

### 5. 변경 사항 push

local commit 을 github에 push

```bash
git push -u origin master
```

- master 대신 main인 경우도 있다.

&nbsp;
&nbsp;

### 6. github repository 를 확인하여 파일이 잘 올라갔는지 확인
