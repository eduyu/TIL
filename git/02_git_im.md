# Git Intermediate

git의 중급 과정



## .gitignore

git이 관리하길 원치 않는 파일/폴더들을 정리한 파일

한개의 repo 당 한개(이상)의 `.gitignore` 파일 필요

https://gitignore.io (https://www.toptal.com/developers/gitignore)

로 접속하여 원하는 내용을 적고, `.gitignore` 파일에 복사-붙여넣기



## Local Branching

브랜치를 만들게(따게)되면, 현재 브랜치의 모든 상황을 복사하여, 평행세계를 만든다.

### create branch

```
# 브랜치 생성
$ git branch <new-branch-name>

# 브랜치 목록 확인
$ git branch

# 브랜치 이동
$ git switch <branch-name>
```



### 작업



### merge (두개의 브랜치를 병합)

#### 1. Fast Forwarding (꽃길)

```
(master)
$ git branch aaa
$ git switch aaa

(aaa)
$ 

# ... 수정 수정 ...

(aaa)
$ git add .
$ git commit -m 'aaa1'
$ git switch master

(master)
$ git merge aaa
```

#### 2. Conflict - Auto merge (충돌 & 자동 병합)



#### 3. Conflict - Manual merge (충돌 & 수동 병합)





## Remote Branching



## 협업 Collaborating

