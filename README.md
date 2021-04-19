# Kokoa Clone

BEM(Block Element Modifier)

- 좀 더 쉽게 CSS 코드를 읽게하는 방식, 일반적으로 ID대신 Class를 사용

// Reference: http://lea.verou.me/2011/10/easily-keep-gh-pages-in-sync-with-master/

$ git add .
$ git status // to see what changes are going to be commited
$ git commit -m 'Some descriptive commit message'
$ git push origin master

$ git checkout gh-pages // go to the gh-pages branch
$ git rebase master // bring gh-pages up to date with master
$ git push origin gh-pages // commit the changes
$ git checkout master // return to the master branch
