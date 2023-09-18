# Git

## 최초설정
커밋에 기록되는 사용자 정보
```bash
git config --global user.name <name>
git config --global user.email <email>
```

## 로컬명령어
- `git init`
    -`.git` git repository를 생성 하는 명렁어
- `git add <file name>`
    - `working directory`에서 staging area로 추가
    - 일반적으로 모든 파일, 폴더를 한번에 추가하기 위해 아래의 명령어로 작성
    - `git add .`
- `git commit -m "first commit"`
    - `staging area`에 올라간 파일들의 스냅샷을 찍어 `.git directory`에 저장
    - 일반적으로 -m 옵션을 넣어서 커밋메세지를 추가
    - `git commit -m "message"`

## 원격저장소
- `git remote`
    - 원격저장소 주소를 관리하기 위한 명령어
    - `git remote add origin <url>`

- git push
    - 원격저장소에 로컬 코드를 업로드 하기 위한 명렁어
    - `git push <remote> <branch>`