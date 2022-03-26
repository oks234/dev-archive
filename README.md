# dev-archive
Development resource archive

# Git 명령어 모음

## 계정, 이메일 확인, 변경

```
git config user.name
git config user.email
```

- 글로벌: `--global`, ex) `git config --global user.name`
- 로컬: `--local`

# Mac Command Line으로 파일, 폴더 삭제

## 하나의 파일 삭제

```
rm myfile.txt
```

## 여러 개의 파일 삭제

```
rm myfile.txt yourfile.png .env
```

## 정말 지울 것인지 한번 더 확인.

```
rm -i myfile.txt
```

'y' 혹은 'yes'를 입력하여야 진행.

## 폴더 삭제

```
rmdir myFolder
```

안에 다른 폴더나 파일이 있으면 삭제할 수 없음.

## 폴더 강제 삭제

```
rmdir -R myFolder
```

걱정된다면, i flag

```
rmdir -iR myFolder
```

## 출처

['명령 줄'로 파일·폴더 삭제하는 것이 더 효율적인 이유와 방법 - ITWorld Korea](https://www.itworld.co.kr/news/162320)
