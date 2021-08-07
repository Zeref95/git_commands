# git_commands

git КОМАНДА --help

git config --global user.name "John Doe"
git config --global user.email johndoe@example.com

git
git clone URL 
    (PATH)
git init

git status
git log

git add (PATH)
    --all

git commit (flags) "COMMENT"
    -m

git push
    ветка (orign master)

git pull

git branch (NAME_BRANCH)            //создать ветку
git checkout (flags) (NAME_BRANCH)  //перейти на ветку
    -b -сразу создать ветку
    если указать хэш (первые 4 символа), то он станет HEAD
git merge (NAME_BRANCH `которую засунуть в текущую`)   //слияние веток
git rebase (NAME_BRANCH `в которую засунуть текущую`)  //слияние веток (последовательное)
    //если применить к предку, то поместит текущую в предка

^ - перемещение на 1 коммит назад
^^ - на 2 коммита
~<число> - перемещение на несколько коммитов назад
