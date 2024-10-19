# git-practice

#### git-practice를 위한 commit 생성

echo "일부 내용" >> file1.txt
git add file1.txt
git commit -m "file1.txt에 내용 추가"

echo "Python 스크립트" >> script.py
git add script.py
git commit -m "script.py 추가"

echo "다른 파일 내용" >> file2.txt
git add file2.txt
git commit -m "file2.txt에 내용 추가"

echo "README 업데이트" >> README.md
git add README.md
git commit -m "README.md 업데이트"

git push -u origin master
