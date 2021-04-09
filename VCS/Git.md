
![img.png](img.png) <br>
`git 실수 모음`
---

### - GitHub 하위 디렉토리 클론하기 

```
mkdir 파일명

cd 파일명

git init 

git config core.sparsecheckout true

git remote add -f origin 프로젝트 깃 저장소 주소

echo 하위 디렉토리 경로/* > .git/info/sparse-checkout

git pull origin master
```

### - `git pull Already up to date` 에러
```
git fetch --all

git reset --hard origin/master
```

### - `git push "error:failed to push some refs to"` 에러
- github 파일과 현재 push 하려는 commit이 일치하지 않아서 발생




