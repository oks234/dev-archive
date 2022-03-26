# Git 명령어 모음

## 계정, 이메일 확인, 변경

```
git config user.name
git config user.email
```

- 글로벌: `--global`, ex) `git config --global user.name`
- 로컬: `--local`

## 리모트 저장소

### 리모트 저장소 확인

```
git remote -v
```

### 리모트 저장소 `origin` 삭제

```
git remote remove origin
```

### 리모트 저장소 `origin` 추가

ssh일 경우

```
git remote add origin git@github.com:[user-id]/[repository-name].git
```

https일 경우

```
git remote add origin https://github.com/[user-id]/[repository-name].git
```
