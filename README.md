## Git init

Git versiohallinnan ottaminen käyttöön työkansiossa. Git käyttäjänimen määrittäminen. Sähköpostiosoitteen määrittäminen.

    git init
    git config --global user.name "User Name"
    git config --global user.email "user.name@edu.riveria.fi"
    
## Git commit

Tiedon lisääminen Git indeksiin. Commit:n luominen indeksissä olevista tiedoista. 

    git add <filename>
    git commit -m "commit message"

## Git check

Git tilan tarkastminen. Git commit:n listaaminen. 

    git status
    git log
    git log --oneline

## Git work with branch

Git haarojen listaaminen. Uuden haaran lisääminen. Haaran tietojen yhdistäminen master päähaaraan.

    git branch
    git branch <branch_name>
    git checkout <branch_name>
    git merge <branch_name>

## Git work with remote repository

    git clone https://github.com/username/project.git
    git add <filename>
    git commit -m "commit message"
    git fetch
    git pull

    git remote add origin https://github.com/username/project.git
    git remote -v
    git push -u origin master
     