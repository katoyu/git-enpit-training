1.
git clone ~~~~/git
git checkout -b (ブランチ名)
(修正)
git add -A
git commit -m “コメント”
git push origin git push origin (ブランチ名)
PRを送る（in GitHub）

2,
git fetch
git checkout (確認したいブランチ名)
(確認)
PRをmergeする（in GitHub）

3.
リリースをかく

次の作業やるときは
git checkout master
git pull
